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


其概率质量函数为： $f(x) = p^x(1-p)^{1-x} =$

$X \sim B(n,p)$ 。



$\phi{_\bar X}(t)=E(e^{it \bar X})=E(e^{it\frac{1}{n}\sum_{i=1}^{n}X_i})$

 $\phi{_\bar X}(t)=E\begin{bmatrix}\prod_{i=1}^{n}{e^{i{\frac{t}{n}X_i}}}\end{bmatrix}$

 $\phi{\bar X}(t)=\prod{i=1}^{n}E\begin{bmatrix}{e^{i{\frac{t}{n}X_i}}}\end{bmatrix}$

 $E\begin{bmatrix}{e^{i{\frac{t}{n}X_i}}}\end{bmatrix}$
---
$$\begin{flalign} & f(x)=\frac{1}{\sqrt{2\pi}}e^{-\frac{x^2}{2}} & \end{flalign}$$

$$ln{\begin{bmatrix} {\phi{_X}(\frac{t}{n})} \end{bmatrix}}^n=nln\begin{bmatrix} 1+i\frac{t}{n}\mu-\frac{1}{2}(\frac{t}{n})^2\sigma^2 \end{bmatrix} \approx n(i\frac{t}{n}\mu-\frac{1}{2}(\frac{t}{n})^2\sigma^2) = it\mu-\frac{t^2}{2n}\sigma^2$$

$${\Large {\begin{bmatrix} 1-p+p(1+t+\frac{t^2}{2}) \end{bmatrix}}^n \approx {\begin{bmatrix} 1+\frac{pt^2}{2} \end{bmatrix}}^n}$$

---
$\phi_{\bar X}(t)=E(e^{it \bar X})=E(e^{it\frac{1}{n}\sum_{i=1}^{n}X_i})$

$\phi{_\bar X}(t)=E{\begin{bmatrix}\prod_{i=1}^{n}{e^{i{\frac{t}{n}X_i}}}\end{bmatrix}}$

$\prod_{}^{}$ 

\prod{i=1}^{n}{e^{i{\frac{t}{n}X_i}}}

$\phi{\bar X}(t)=E{\begin{bmatrix}\end{bmatrix}}$

$E{\begin{bmatrix} test \end{bmatrix}}$

