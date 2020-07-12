---
title: "汽车软件开发中的持续测试方法"
authors:
- admin
date: "2019-02-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: 通过配置Jenkins脚本和本地的Batch及C#文件来实现了自动泊车ECU的自动持续测试。即集成测试可以通过Jenkins平台远程启动并可设置执行周期。使用多个脚本来分别实现：自动从服务器同步最新的基于超声波传感器的自动泊车软件，调用winIDEA实现软件的自动写入，在CANoe中调用相应集成测试用例并自动启动测试。测试完成后Jenkins会自动发送带有测试报告的电子邮件到开发者信箱中以便及时获知测试结果。

# Summary. An optional shortened abstract.
summary: 通过配置Jenkins脚本和本地的Batch及C#文件来实现了自动泊车ECU的自动持续测试。即集成测试可以通过Jenkins平台远程启动并可设置执行周期。使用多个脚本来分别实现：自动从服务器同步最新的基于超声波传感器的自动泊车软件，调用winIDEA实现软件的自动写入，在CANoe中调用相应集成测试用例并自动启动测试。测试完成后Jenkins会自动发送带有测试报告的电子邮件到开发者信箱中以便及时获知测试结果。

tags:
- Source Themes
featured: false

links:
- name: 公司主页
  url: https://www.bosch.de/unser-unternehmen/bosch-in-deutschland/leonberg/
url_pdf: files/project-jenkins.pdf
url_code: '#'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
