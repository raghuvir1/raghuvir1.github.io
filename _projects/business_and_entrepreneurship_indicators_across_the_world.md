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


This project visualizes trends business and entrepreneurship metrics from the Global Entrepreneurship Consortium. The dataset used for this project contains business indicators from 115 countries from 2001 to 2021. The dataset contains columns like ‘Established Business Ownership’, Entrepreneurial intentions’, ‘Total early-stage Entrepreneurial Activity (TEA)’, ‘Fear of failure rate *’, ‘Motivational Index’. The following interactive plots draw light on global trends in business and entrepreneurship. 

A good place to begin the analysis, is to compare global trends in average business ownership. Using the elements you can toggle between regions like Africa, Asia, Europe, North America, and Asia (including Oceania) to view global patterns. 

North America had the highest average business ownership rates in 2021 while Africa had the lowest (and most sporadic). You can also see the decline in North American business ownership rates after the 2008 recession. The next plot is of the maximum business ownership in the Americas to highlight peaks of business ownership. This plot allows a user to compare differences between countries in both North and South American continents. The Fear of Failure vs Entrepreneurial intentions plot also shows that most regions with a high fear of failure rate have lower entrepreneurial intentions. Having high Established Business Ownership Rates has a positive relationship with Total early-stage Entrepreneurial Activity. Most regions with high established business ownership and early-stage start-up activity also have higher values for their ‘perceived capabilities’. The last plot shows that when regions give a ‘high status to successful entrepreneurs’ regions are more likely to consider ‘entrepreneurship as a good choice’. 

### Average Business Ownership Per Region


<vegachart schema-url="{{ site.baseurl }}/assets/json/line_plot_mean_bus_own_per_region.json" style="width: 100%"></vegachart>


### Max Business Ownership in the Americas


<vegachart schema-url="{{ site.baseurl }}/assets/json/max_business_ownership_americas.json" style="width: 100%"></vegachart>


### Fear of Failure vs Entrepreneurial intentions


<vegachart schema-url="{{ site.baseurl }}/assets/json/fof_vs_entre_inten.json" style="width: 100%"></vegachart>


### Total early-stage Entrepreneurial Activity (TEA) vs Established Business Ownership


<vegachart schema-url="{{ site.baseurl }}/assets/json/scatter2.json" style="width: 100%"></vegachart>


### Entrepreneurship as a Good Career Choice vs High Status to Successful Entrepreneurs


<vegachart schema-url="{{ site.baseurl }}/assets/json/scatter_early_stage_vs_estb_business.json" style="width: 100%"></vegachart>


Source for all visualizations: Me

<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://github.com/raghuvir1/raghuvir1.github.io/tree/main/data_files/data_viz_fall_2022" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/UIUC-iSchool-DataViz/is445_oauoag_fall2022/blob/main/week11/inClass_week11.ipynb" text="The Analysis" %}
</div>

