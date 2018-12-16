---
layout: default
title: Chart
parent: Using
nav_order: 2
---

# chart 

Load funnel chart module 

- **author** - Dharma
  Chart components is using Highcharts api and vue components
  Following charts are supported
  1)Line
  2)Bar
  3)Bubble
  4)Pie
  5)Funnel
  ref: https://github.com/highcharts/highcharts-vue 

## props 

- `url` ***String*** (*optional*) 

  Fetch json data form url
  excepting json data as following
  [{"name": "Year 1800","data": [107, 31, 635, 203, 2]},{"name": "Year 1900","data": [133, 156, 947, 408, 6]}] 

- `title` ***String*** (*required*) 

- `type` ***String*** (*required*) 

  type of chart to display
  accepts
  line,bar,bubble,pie,funnel 

- `data` ***String*** (*optional*) 

  If in case url is not available
  then data will be considered
  sample data:
  [{"name": "Year 1800","data": [107, 31, 635, 203, 2]},{"name": "Year 1900","data": [133, 156, 947, 408, 6]}] 

- `config` ***Object*** (*optional*) `default: [object Object]` 

  Fetch extra addons for highcharts by using config
  extra addons like legend,tootltip,xaxis,yaxis
  x-axis and y-axis categories, 

## data 

- `chartOptions` 

  Chart options 

**initial value:** `[object Object]` 

## methods 

- `getDataFromUrl(url)` 

- `getHighCartData(data, type)` 

