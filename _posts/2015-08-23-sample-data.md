---
layout: post
title: "Sample Data"
date: 2015-08-23 03:32:44
image: '/assets/img/'
description: 'A sample API JSON structure'
tags:
- api 
- json
- endpoint 
categories:
- api 
- json
- endpoint
twitter_text: 'A sample API JSON structure'
---

Our APIs help the US government provide open data for US and international businesses.

Here is some sample data from ITA's Market Research Library API:

{% highlight ruby %}
{
"total":2174,
"offset":0,
"sources_used":[
{
"source":"ITA",
"source_last_updated":"2015-08-23T00:13:29+00:00",
"last_imported":"2015-08-23T19:13:13+00:00"
}
],
"results":[
{
"id":"14265600",
"countries":[
"MA"
],
"description":"Opportunities for U.S. firms to provide products and services to Morocco, under the Millennium Challenge Compact.",
"expiration_date":"2013-12-31",
"industries":{
"original":[
"Agribusiness",
"Automotive \u0026 Ground Transportation",
"Construction, Building \u0026 Heavy Equipment",
"Energy \u0026 Mining",
"Environmental Technologies",
"Industrial Equipment \u0026 Supplies",
"Marine Industries",
"Services"
],
"mapped":[
"Agribusiness",
"Automotive",
"Construction",
"Energy",
"Environmental Technology",
"Industrial Materials",
"Marine Technology",
"Business and Professional Services"
]
},
"report_type":"Market Research Report",
"title":"$ 700 Million Millennium Challenge Compact Procurement for Morocco",
"url":"http://mr.export.gov/docs/x_8442820.pdf"
},
{% endhighlight %}

Check out all our [Trade APIs](http://developer.trade.gov/) and documentation on how to integrate in your project.

[jekyll-gh]: https://github.com/mojombo/jekyll
[jekyll]:    http://jekyllrb.com