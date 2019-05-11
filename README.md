# ElasticSearchExample #

## Project ##

This project is a sample for [Elasticsearch] with .NET. The application parses the [Quality Controlled Local Climatological Data (QCLCD)] 
from March 2015 and bulk inserts it into a Elasticsearch instance. It doesn't deal with Clustering and only inserts on a single node.

I have used [Kibana] to create some visualizations and [TinyCsvParser] to parse the CSV data.

## Article ##

This source code is released with a blog post over at:

* [https://bytefish.de/blog/elasticsearch_net/](https://bytefish.de/blog/elasticsearch_net/)

The example was based on Elasticsearch 2, but the example is available for:

* Elasticsearch 2
* Elasticsearch 6
* Elasticsearch 7

Please see the Releases at: 

* [https://github.com/bytefish/ElasticSearchExperiment/releases](https://github.com/bytefish/ElasticSearchExperiment/releases)


## Dataset ##

The data is the [Quality Controlled Local Climatological Data (QCLCD)]: 

> Quality Controlled Local Climatological Data (QCLCD) consist of hourly, daily, and monthly summaries for approximately 
> 1,600 U.S. locations. Daily Summary forms are not available for all stations. Data are available beginning January 1, 2005 
> and continue to the present. Please note, there may be a 48-hour lag in the availability of the most recent data.

The data is available at:

* [http://www.ncdc.noaa.gov/orders/qclcd/](http://www.ncdc.noaa.gov/orders/qclcd/)

## Result ##

<a href="https://raw.githubusercontent.com/bytefish/ElasticSearchExperiment/master/ElasticSearchExample/img/screenshot2.jpg">
	<img src="https://raw.githubusercontent.com/bytefish/ElasticSearchExperiment/master/ElasticSearchExample/img/screenshot2.jpg" width="50%" height="50%" alt="Kibana Visualization of the Average Temperature" />
</a>

[TinyCsvParser]: https://github.com/bytefish/TinyCsvParser/
[Elasticsearch]: https://www.elastic.co/products/elasticsearch
[Kibana]: https://www.elastic.co/products/kibana
[Quality Controlled Local Climatological Data (QCLCD)]: https://www.ncdc.noaa.gov/data-access/land-based-station-data/land-based-datasets/quality-controlled-local-climatological-data-qclcd