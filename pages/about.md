---
layout: page
title: About
description: contact
keywords: Keke Hu, 胡可可
comments: true
menu: About
permalink: /about/
---

Life is hard!


## 联系

* GitHub：[@Keke](https://github.com/artificialintelligencecn)
* 知乎: [@Keke](https://www.zhihu.com/people/zhengweilong)


## Skill Keywords

#### Software Engineer Keywords
<div class="btn-inline">
    {% for keyword in site.skill_software_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>

#### Mobile Developer Keywords
<div class="btn-inline">
    {% for keyword in site.skill_mobile_app_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>

#### Windows Developer Keywords
<div class="btn-inline">
    {% for keyword in site.skill_windows_keywords %}
    <button class="btn btn-outline" type="button">{{ keyword }}</button>
    {% endfor %}
</div>
