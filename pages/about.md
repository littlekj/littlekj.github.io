---
layout: page
title: About
description: 积攒一点点能量
keywords: 清风拂33, littlekj
comments: true
menu: 关于
permalink: /about/
---

积攒一点点能量。

向着光亮的方向。

## 联系

<ul>
{% for website in site.data.social %}
<li>{{website.sitename }}：<a href="{{ website.url }}" target="_blank">@{{ website.name }}</a></li>
{% endfor %}
{% if site.url contains 'ink-quill.org' %}
<li>
微信公众号：<br />
<img style="height:192px;width:192px;border:1px solid lightgrey;" src="{{ site.url }}/assets/images/qrcode.jpg" alt="请显示我吖" />
</li>
{% endif %}
</ul>


## Skill Keywords

{% for skill in site.data.skills %}
### {{ skill.name }}
<div class="btn-inline">
{% for keyword in skill.keywords %}
<button class="btn btn-outline" type="button">{{ keyword }}</button>
{% endfor %}
</div>
{% endfor %}

例如有一个数据集 $[2, 4, 6, 8, 10]$ ，计算归一化步骤如下：

1. 计算均值 $\mu$： $\mu = \frac{2+4+6+8+10}{5} = 6​$
2. 计算标准差 $\sigma$ ：

	- 先计算方差：方差 = $\frac{(2−6)^2+(4−6)^2+(6−6)^2+(8−6)^2+(10−6)^2​}{5} = 8$
	- 然后取平方根得到标准差： $\sigma = \sqrt{8} ​≈ 2.83$
3. 应用零均值归一化公式：

	- 对数据点 $2$ 进行归一化： $x_i' = \frac {2 - 6} {2.83} ≈ −1.41$
	-  对数据点 $4$ 进行归一化： $x_i' = \frac {4 - 6} {2.83} ≈ −0.71$
	- 其他数据点也同样处理。
---
假设每个随机变量 $X_i$ 的方差是 $\sigma^2$，即 $Var(X_i)=\sigma^2$。
- 均值 $\bar X$ 的方差可以表示为： $Var(\bar X)=Var(\frac{1}{n}\sum_{i=1}^{n}X_i)$
- 由于 $X_i$ 是独立的，可以使用方差的加法性质。方差的计算公式为： $Var(\frac{1}{n}\sum_{i=1}^{n}X_i)=\frac{1}{n^2}\sum_{i=1}^{n}Var(X_i)=\frac{1}{n^2}\cdot n \cdot \sigma^2=\frac{\sigma^2}{n}$
