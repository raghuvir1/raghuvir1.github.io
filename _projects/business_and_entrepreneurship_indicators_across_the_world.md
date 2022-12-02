---
name: Global Business & Entrepreneurial Indicators 
tools: [Python, HTML, vega-lite, Jekyll]
image: assets/pngs/GEM.png
description: Visualizing trends and behaviors of business & entrepreneurship indicators.
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---
# Global Business & Entrepreneurial Behaviors


## Max Business Ownership in the Americas

<vegachart schema-url="{{ site.baseurl }}/assets/json/max_business_ownership_americas.json" style="width: 100%"></vegachart>

## Average Business Ownership Per Region

<vegachart schema-url="{{ site.baseurl }}/assets/json/line_plot_mean_bus_own_per_region.json" style="width: 100%"></vegachart>

## Fear of Failure vs Entrepreneurial intentions

<vegachart schema-url="{{ site.baseurl }}/assets/json/fof_vs_entre_inten.json" style="width: 100%"></vegachart>

## Total early-stage Entrepreneurial Activity (TEA) vs Established Business Ownership

<vegachart schema-url="{{ site.baseurl }}/assets/json/scatter2.json" style="width: 100%"></vegachart>


## Entrepreneurship as a Good Career Choice vs High Status to Successful Entrepreneurs

<vegachart schema-url="{{ site.baseurl }}/assets/json/scatter_early_stage_vs_estb_business.json" style="width: 100%"></vegachart>


<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://github.com/raghuvir1/raghuvir1.github.io/tree/main/data_files/data_viz_fall_2022" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/UIUC-iSchool-DataViz/is445_oauoag_fall2022/blob/main/week11/inClass_week11.ipynb" text="The Analysis" %}
</div>

