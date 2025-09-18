---
---

# SYSUSELab's Website

中山大学智能化软件研发实验室（加入一些介绍比较好）

{% include section.html %}

## Highlights

{% capture text %}

需要讲讲研究亮点，左侧找个研究代表。

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

TrustedGPT 是一个专注于大模型可信性评测的平台，旨在评估大模型在通用领域以及垂直领域的可信能力。 平台支持包括 ChatGPT、Qwen、智谱AI 和 Gemini 等主流大模型，通过多维度评测体系，从可靠性、安全性、公平性等方面进行全面评估。 通过不断更新的评测数据和标准，TrustedGPT 致力于推动生成式人工智能技术的安全、可靠应用。

{%
  include button.html
  link="projects"
  text="浏览我们的项目🔗"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/trustedgpt.png"
  link="projects"
  title="TrustedGPT"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

介绍我们的团队，左侧需要一张合照

{%
  include button.html
  link="team"
  text="结识我们的团队"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="我们的团队"
  text=text
%}
