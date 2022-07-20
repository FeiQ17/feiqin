---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

The theme in my Ph.D. Dissertation can be summarized as competitive strategies in food retail sector. The first two chapters of my Ph.D. dissertation examines the profitability of price discrimination (PD) schemes under different information environments by combining nonlinear pricing theory with machine learning (ML) techniques. Theoretical PD models typically exogenously impose consumer segments using assumptions that may or may not be reasonable for specific applications. Given advances in computing power, ML methods can now replace exogenous assumptions in forming consumer clusters that can proxy different consumer segments, making theoretical models more applicable in practice.

The specific question we explore is how informationally robust price discrimination techniques are. Using Nielsen scanner data, we construct full information including consumers’ demographics and purchase history, and limited information including only demographics. We then apply K-Means clustering, which is part of the unsupervised learning methods, to segment the market. The basic idea is that consumers that are similar are assigned to a group, whereas consumers that are dissimilar are assigned to different groups. Segmenting consumers with common traits helps firms target each group in a relevant and effective way. After constructing the sample by selecting households in Nielsen Consumer scanner data, we estimate the consumer demand for yogurt products using full and limited consumer information. Applying demand estimation results to PD schemes, we show that using more information helps increase the store’s profit under second-degree PD, but does not affect the profit under third-degree PD.

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}
