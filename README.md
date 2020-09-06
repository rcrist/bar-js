# bar-js
Lightweight, configurable and simple bar chart library in Javascript

[![Packagist](https://img.shields.io/packagist/l/doctrine/orm.svg)]()
[![Codacy grade](https://img.shields.io/codacy/grade/e27821fb6289410b8f58338c7e0bc686.svg)]()
[![Chrome Web Store](https://img.shields.io/chrome-web-store/stars/ogffaloegjglncjfehdfplabnoondfjo.svg)]()

## Description
bar.js is a Canvas based simple Javascript Bar Chart Library to provide a configurable, lightweight and dependency-free experience.

![](https://github.com/rcrist/bar-js/blob/master/bar.png)

## Installation
Download the 'bar.min.js' and include it in your project

```html
<script src="bar.min.js"></script>
```

## Usage
To create the bar chart, you need a block level container like a div or p.

```html
<div id="chart">This will be a bar chart!</div>
```
Then you can create the BarChart object in your JavaScript file

```js
var barChart = new BarChart(chartID, chartWidth, chartHeight, data);
```

### Parameters
- 'chartID = containerID (String)'
Defines the id of container like "chart"

- 'chartWidth (Integer)'
Defines the width of the chart like 500

- 'chartHeight (Integer)'
Defines the height of the chart like 400

- 'data (Objects Array)'
Defines the data objects. The objects should have 2 key-value pairs: Label and value. Example data:

```js
  var data = [
    {label: 'Jan', value: 123},
    {label: 'Feb', value: 11},
    {label: 'March', value: 55},
    {label: 'April', value: 893},
    {label: 'May', value: 343}
  ];
```

## License
[MIT](LICENSE.md) Copyright [Rick A. Crist](https://github.com/rcrist)
