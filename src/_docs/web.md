---
title: Web Technologies
icon: fe fe-pie-chart
---

### Platform

Covisualiser runs on Node.JS, using the Tabler theme from codecalm.net
It is fully open source with the code available on GitHub.

### Plotly

Plotly is a powerful javascript library for processing larger sets of information, and comparing multiple sets of data with a huge range of graph types available.

### c3.js charts 

{% example html columns=2 %}
<div class="card">
	<div class="card-header">
		<h3 class="card-title">Chart name</h3>
	</div>
	<div class="card-body">
		<div id="chart-wrapper" style="height: 16rem"></div>
	</div>
</div>
{% include js-charts.html id="chart-wrapper" data='temperature' %}
{% endexample %}

### PapaParse

PapaParse is a javascript library for interpreting the csv files released by a number of the data sources, in place of an API or other formats.

### SheetJS

SheetJS provides conversion and interpreting xls/other spreadsheet formats released in place of a csv/API.

https://github.com/SheetJS/sheetjs