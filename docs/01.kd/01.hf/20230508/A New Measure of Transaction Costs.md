---
title: A New Measure of Transaction Costs
date: 2023-08-07 16:29:35
permalink: /pages/7578f2/
categories:
  - kd
  - hft
  - 20230508
tags:
  - 
---
# Overview
文章提出了一种新的计算交易成本的方法。在传统的计算交易成本的方法中，只考虑了交易的经纪费和交易成交价差，但作者认为这种方法忽略了其他重要的因素，比如成交量、交易时段和交易所的深度等。因此，作者提出了一种新的计算交易成本的方法，称为Effective Spread，它考虑了所有这些因素，并将其纳入计算。

Effective Spread是一个综合指标，包括了交易的成交价差和成交量、交易时段和交易所的深度等因素。作者通过对一系列美国股票的数据进行分析，证明了Effective Spread可以更准确地反映交易成本的实际情况，尤其是在低流动性市场和高波动性市场中。此外，Effective Spread还可以帮助投资者更好地理解市场的深度和流动性，提高投资决策的准确性。

总之，这篇文章提出了一种新的计算交易成本的方法，有效地纳入了多个因素，能够更准确地反映交易成本的实际情况，并帮助投资者更好地理解市场的深度和流动性。

## Statistic Logic
Effective Spread是一种新的交易成本指标，其主要特点是综合考虑了成交价差、成交量、交易时段和交易所深度等多个因素，能够更准确地反映交易的实际成本。

具体来说，Effective Spread的计算公式如下：

Effective Spread = 2 * (weighted average of execution prices - midpoint price)

其中，execution prices指的是买卖方的实际成交价，midpoint price指的是买卖盘的中间价，即买卖价的平均值。weighted average指的是按照成交量加权平均计算。

Effective Spread的计算方法与传统的Spread（即成交价差）有些类似，但是Effective Spread还考虑了成交量、交易时段和交易所深度等因素，因此更准确地反映了交易的实际成本。

举例来说，如果一个股票的买入价为10美元，卖出价为10.10美元，但是实际成交的买入价为10.02美元，卖出价为10.08美元，成交量为1000股，那么Effective Spread的计算如下：

成交价差：10.10 - 10 = 0.10美元
midpoint price：(10.10 + 10) / 2 = 10.05美元
weighted average of execution prices：(10.02 * 1000 + 10.08 * 1000) / 2000 = 10.05美元
Effective Spread：2 * (10.05 - 10.05) = 0
从上面的例子可以看出，Effective Spread的计算结果为0，说明这笔交易的实际成本非常低。而传统的Spread只考虑了买卖价之间的差异，无法反映交易成本的实际情况。

Effective Spread的优点在于，它可以帮助投资者更好地理解交易的实际成本，尤其是在低流动性市场和高波动性市场中。在这些市场中，传统的Spread可能会被高估，而Effective Spread可以更准确地反映实际情况。此外，Effective Spread还可以帮助投资者更好地了解市场的深度和流动性，提高投资决策的准确性。