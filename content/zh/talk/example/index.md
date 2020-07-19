---
title: 学习笔记
# event: 
# event_url: 

# location: Source Themes HQ
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

summary: 简述算法中有序度与逆序度的概念，并阐述关于插入排序中移动次数与逆序度的关系。
abstract: 简述算法中有序度与逆序度的概念，并阐述关于插入排序中移动次数与逆序度的关系。

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2020-07-20T13:00:00Z"
# date_end: "2020-07-20T15:00:00Z"
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: "2020-07-20T00:00:00Z"

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: '图源: [**GerdAltmann**](https://pixabay.com/zh/photos/algorithm-images-by-machine-learn-3859537/)'
  focal_point: Right

links:
- icon: linkedin
  icon_pack: fab
  name: 领英文章链接
  url: https://www.linkedin.com/pulse/algorithm-insertion-sort-yu-zhong/?trackingId=KmWt0RnwTaCmGRlGowB4rg%3D%3D
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []

# Enable math on this page?
math: true
---


## 为什么算法中插入排序的移动次数等于逆序度？

### 概念：
**有序度**：数组中具有有序关系的元素对的数量。
**完全有序度**：完全有序数组的有序度。
**逆序度**：数组中具有无序关系的元素对的数量。

$$\mathbf N_{逆序度} = \mathbf{N}_{完全有序度} - \mathbf{N}_{有序度}$$

### 示例：

假设我们现在要对于数组从小到大进行排序。

那么对于未完全排序的数组，例如 **4，5，6，3，2，1**，它的有序对是**4，5**，**4，6** 和**5，6**。 因此，上述数组**有序度**为**3**。

并假设另一个数组**1、2、3、4、5、6**。它具有15个有序对，并且该数组的**有序度**为**15**。此数组包含与第一个数组一样的数字，并且它是严格按照从小到大排序的，因此我们也可以称之为**满序数组**，并且这个数组的有序度**15**也是第一个数组的**完全有序度**。 因此，第一个数组的**逆序度**为**12**。

对于包含**n**个元素的完全有序数组，完全有序度为:

$$\frac{ n \left (n - 1 \right )}{2}$$

因此，对于数组**4,5,6,3,2,1**而言：

插入排序（移动次数）：

**3,4,5,6,2,1**（3）

**2,3,4,5,6,1**（4）

**1,2,3,4,5,6**（5）

数组**3,4,5,6,2,1**是通过插入排序从数组**4,5,6,3,2,1**中获得的，因此增加了3个有序对：**3,4**，**3,5**和**3,6**。 在此期间，移动次数为3，即元素3移动了3次。

现在回到问题所在，排序期间的每一步移动都将加一个有序度，即有序度+1。 因此，插入排序的移动次数等于完全有序度减去有序度，即逆序度。

它同样也可以在冒泡排序上实现。 无论是插入排序还是冒泡排序，平均时间复杂度均为$$O\left (n ^ 2 \right )$$。
