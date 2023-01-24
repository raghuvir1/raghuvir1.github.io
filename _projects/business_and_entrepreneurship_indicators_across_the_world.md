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
&nbsp;  
&nbsp;  
This project visualizes trends business and entrepreneurship metrics from the Global Entrepreneurship Consortium. The dataset used for this project contains business indicators from 115 countries from 2001 to 2021. The dataset contains columns like ‘Established Business Ownership’, Entrepreneurial intentions’, ‘Total early-stage Entrepreneurial Activity (TEA)’, ‘Fear of failure rate *’, ‘Motivational Index’. The following interactive plots draw light on global trends in business and entrepreneurship.  &nbsp;  
&nbsp;  

I created all the visualizations from scratch using Python, and Altair within a Jupyter notebook. The dataset contains 1000 rows and 19 columns, out of which, 17 were numeric indicator columns.  Using the elements you can toggle between regions like Africa, Asia, Europe, North America, and Asia (including Oceania) to view global patterns. A good place to begin the analysis, is to compare global trends in average business ownership.  &nbsp;  
&nbsp;  

North America had the highest average business ownership rates in 2021 while Africa had the lowest (and most sporadic). You can also see the decline in North American business ownership rates after the 2008 recession. The next plot is of the maximum business ownership in the Americas to highlight peaks of business ownership. This plot allows a user to compare differences between countries in both North and South American continents. The Fear of Failure vs Entrepreneurial intentions plot also shows that most regions with a high fear of failure rate have lower entrepreneurial intentions. Having high Established Business Ownership Rates has a positive relationship with Total early-stage Entrepreneurial Activity. Most regions with high established business ownership and early-stage start-up activity also have higher values for their ‘perceived capabilities’. The last plot shows that when regions give a ‘high status to successful entrepreneurs’ regions are more likely to consider ‘entrepreneurship as a good choice’.  &nbsp;  

&nbsp;  

### Average Business Ownership Per Region
&nbsp;
<vegachart schema-url="{{ site.baseurl }}/assets/json/line_plot_mean_bus_own_per_region.json" style="width: 100%"></vegachart>  
&nbsp;
### Max Business Ownership in the Americas
&nbsp;  
<vegachart schema-url="{{ site.baseurl }}/assets/json/max_business_ownership_americas.json" style="width: 100%"></vegachart>
&nbsp;
### Fear of Failure vs Entrepreneurial intentions
&nbsp;  
<vegachart schema-url="{{ site.baseurl }}/assets/json/fof_vs_entre_inten.json" style="width: 100%"></vegachart>
&nbsp;
### Total early-stage Entrepreneurial Activity (TEA) vs Established Business Ownership
&nbsp;  
<vegachart schema-url="{{ site.baseurl }}/assets/json/scatter2.json" style="width: 100%"></vegachart>
&nbsp;
### Entrepreneurship as a Good Career Choice vs High Status to Successful Entrepreneurs
&nbsp;  
<vegachart schema-url="{{ site.baseurl }}/assets/json/scatter_early_stage_vs_estb_business.json" style="width: 100%"></vegachart>
&nbsp;  


<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://github.com/raghuvir1/raghuvir1.github.io/tree/main/data_files/data_viz_fall_2022" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/raghuvir1/raghuvir1.github.io/blob/main/python_notebooks/reddy_raghuvir_fall_2022_data_viz_final.ipynb" text="The Analysis" %}
</div>

