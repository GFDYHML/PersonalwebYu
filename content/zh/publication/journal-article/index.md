---
title: "三维重建技术"
authors:
- admin
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2018-02-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
# publication: "*Journal of Source Themes, 1*(1)"
# publication_short: ""
publication: ""
publication_short: ""

abstract: 计算三维空间中的物体的位置信息，从而重建、识别出物体是计算机视觉中的一项基本的任务。物体点在空间中的三维位置是通过摄像机的成像模型和物体图像坐标共同决定的，物体点三维位置计算是利用摄像机的内外参数和标记点在图像中的对应位置，来计算出标记点在三维空间中的实际位置。利用有具体尺寸的棋盘格对相机进行标定，可得到棋盘上角点图像像素坐标，将图像坐标输入到函数cvCalibrateCamera2()中，可以计算出摄像机内参数矩阵、畸变系数、旋转矩阵和平移向量，即是为了获得摄像机的内外参数。本项目通过极线约束性质得出对应坐标系之间的关系。由于摄像机有五个未知的内参数，而只有两个约束方程，因此至少需要大于等于三幅图像时，才能线性的求出唯一解，即标定出了这些内外参数。得到的这些内外参数可用于以后处理图像，比如旋转矩阵和平移向量可用来计算物体实际坐标位置，内参数矩阵和畸变系数可用来对图像进行矫正。之后对于矫正好的图像进行立体匹配：匹配两个不同的摄像机视图，即找出同一个世界物体点在左右成像平面上的坐标位置。此时便成求出该点的视差值和该世界物体点的深度值。通过输入成对的左右图像，来获取视差图与点云图。

# Summary. An optional shortened abstract.
summary: 比较了几种3D重建方法：结构化光投影，轮廓形状，多视图立体和激光线扫描。并且通过MATLAB实现了基于双摄像头的三维重建：使摄像头同时拍摄同一物体，利用有具体尺寸的棋盘格对相机进行标定后即可重建出其它物体的三维影像与点云图。

tags:
- 双面视觉
- 三维重建
featured: false

links:
- name: PPT
  url: files/project-3D-PPT.pdf
url_pdf: files/project-3D.pdf
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
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

<!-- {{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/). -->
