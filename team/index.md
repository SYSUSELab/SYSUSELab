---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

本页介绍了中山大学智能化软件研发小组的核心成员。我们的成员共同致力于探索大型语言模型与软件工程的前沿交叉领域。欢迎您在此页面了解我们的研究团队。

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}
我们的团队在陆续开展一些有意思的团建活动...
{% include section.html %}



{% capture content %}

{% include figure.html image="images/团建1.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
