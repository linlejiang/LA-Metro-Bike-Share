This project creates a service monitoring dashboard, visualizing the usage patterns of bikes and stations varied by granularity across quarters from 2016Q3 to 2020Q2, with the LA Metro Bike Share service providers as end-users. The goal of this project is to help end-users make informed decisions regarding station planning and bike deployment.

## demo
- Demo Website: [Link](http://pdms.usc.edu/dsci-554-projects/project-love554)
- Demo Video: [YouTube Link](https://www.youtube.com/watch?v=R-OWenNrUKA)

## Table of Visualizations
| Page name | Chart description | Libraries used | labels |
| :--- | :--- | :--- | :--- |
|region|d3map| d3, topojson   | map|
|region|region statistics multi-line chart|d3|responsive, interactive, animated|
|region|Heatmap of station popularity for each quarter|mapbox-gl, d3|mapbox|
|station|Top 10 popular station of each quarter (bar chart)|d3|responsive, interactive, animated|
|station|Bottom 10 popular station of each quarter (bar chart)|d3|responsive, interactive, animated|
|station|slippy map|leaflet, d3|mapbox|
|station|trip duration distribution (histogram)|d3|responsive, interactive, animated|
|station|related staion trip times (donut chart)|d3|responsive, interactive, animated, layout|
|station|busy time distribution (line chart)|d3|responsive, interactive, animated|

## Project setup
```
npm ci
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```
