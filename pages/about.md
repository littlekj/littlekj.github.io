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


$$
\begin{cases}
{\lambda}e^{-\lambda{x}} & x\ge 0 \\ 0 & x<0 
\end{cases}
$$
