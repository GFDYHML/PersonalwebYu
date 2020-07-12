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

abstract: 在过去的几年里，随着用于驾驶辅助的系统越来越复杂，软件单元测试在汽车领域的重要性急剧增加。单元测试和集成测试在汽车软件开发过程中被普遍使用，通过测试可以减少代码中的错误，提高开发阶段的效率。所有这些优势只能当整个测试流程有明确的方法可循时才可以实现。因此本论文的目的是为了验证汽车软件开发的一种持续测试方法，以及提出相应的测试测试准则和明确的流程定义，并通过配置测试平台的脚本将这一方法落实到罗伯特博世公司自动泊车部门超声波传感器组的中。
Jenkins是一款由Java编写的开源的持续集成工具，它提供了软件开发的持续集成服务。本文通过配置Jenkins脚本和本地的Batch及C#文件来实现了自动泊车ECU的自动持续测试。即集成测试可以通过Jenkins平台远程启动并可设置执行周期。使用多个脚本来分别实现：自动从服务器同步最新的基于超声波传感器的自动泊车软件，调用winIDEA实现软件的自动写入，在CANoe中调用相应集成测试用例并自动启动测试。测试完成后Jenkins会自动发送带有测试报告的电子邮件到开发者信箱中以便及时获知测试结果。本文以对持续测试的实施可行性的分析，对持续集成测试的概念的阐明，以及对持续集成测试方法的实施作为论文的成果。所有测试过程按照ISO26262标准进行定义，许多工作产品(如模板和脚本)都是在国际规范下进行和开发的。

# Summary. An optional shortened abstract.
summary: 通过配置Jenkins脚本和本地的Batch及C#文件来实现了自动泊车ECU的自动持续测试。即集成测试可以通过Jenkins平台远程启动并可设置执行周期。使用多个脚本来分别实现：自动从服务器同步最新的基于超声波传感器的自动泊车软件，调用winIDEA实现软件的自动写入，在CANoe中调用相应集成测试用例并自动启动测试。测试完成后Jenkins会自动发送带有测试报告的电子邮件到开发者信箱中以便及时获知测试结果。

tags:
- Source Themes
featured: false

links:
- name: 公司主页
  url: https://www.bosch.de/unser-unternehmen/bosch-in-deutschland/leonberg/
- name: PPT
  url: files/project-thesisPPT.pdf
url_pdf: files/project-jenkins.pdf
# url_code: '#'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: '(https://unsplash.com/photos/s9CC2SKySJM)'
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
[点击此处](files/project-jenkins.pdf) 或者标题下 *pdf* 按钮均可获取本论文的剪裁版本.
{{% /alert %}}

由于博世公司保密政策原因，仅可在此提供不含具体实现代码的剪裁版本。