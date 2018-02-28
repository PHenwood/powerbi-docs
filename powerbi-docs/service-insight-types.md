---
title: Types of Insights supported by Power BI
description: Quick Insights and View insights with Power BI.
services: powerbi
documentationcenter: ''
author: mihart
manager: kfile
backup: ''
editor: ''
tags: ''
qualityfocus: no
qualitydate: ''

ms.service: powerbi
ms.devlang: NA
ms.topic: article
ms.tgt_pltfrm: NA
ms.workload: powerbi
ms.date: 12/20/2017
ms.author: mihart

LocalizationGroup: Dashboards
---
# Types of insights supported by Power BI
## How does Insights work?
Power BI quickly searches different subsets of your dataset while applying a set of sophisticated algorithms to discover potentially-interesting insights. Power BI scans as much of a dataset as possible in an allotted amount of time.

You can run insights against a dataset or dashboard tile.   

## What types of insights can we find?
These are some of the algorithms we use:

## Category outliers (top/bottom)
Highlights cases where, for a measure in the model, one or two members of a dimension have much larger values than other members of the dimension.  

![](media/service-insight-types/pbi_auto_insight_types_category_outliers.png)

## Change points in a time series
Highlights when there are significant changes in trends in a time series of data.

![](media/service-insight-types/pbi_auto_insight_types_changepoint.png)

## Correlation
Detects cases where multiple measures show a correlation between each other when plotted against a dimension in the dataset.

![](media/service-insight-types/pbi_auto_insight_types_correlation.png)

## Low Variance
Detects cases where data points are not far from the mean.

![](media/service-insight-types/power-bi-low-variance.png)

## Majority (Major factors)
Finds cases where a majority of a total value can be attributed to a single factor when broken down by another dimension.  

![](media/service-insight-types/pbi_auto_insight_types_majority.png)

## Overall trends in time series
Detects upward or downward trends in time series data.

![](media/service-insight-types/pbi_auto_insight_types_trend.png)

## Seasonality in time series
Finds periodic patterns in time series data, such as weekly, monthly, or yearly seasonality.

![](media/service-insight-types/pbi_auto_insight_types_seasonality_new.png)

## Steady share
Highlights cases where there is a parent-child correlation between the share of a child value in relation to the overall value of the parent across a continuous variable.

![](media/service-insight-types/pbi_auto_insight_types_steadyshare.png)

## Time series outliers
For data across a time series, detects when there are specific dates or times with values significantly different than the other date/time values.

![](media/service-insight-types/pbi_auto_insight_types_time_series_outliers.png)

## Next steps
[Power BI insights](service-insights.md)

If you own a dataset, [optimize it for insights](service-insights-optimize.md)

More questions? [Try the Power BI Community](http://community.powerbi.com/)
