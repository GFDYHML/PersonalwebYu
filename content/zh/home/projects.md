+++
# Accomplishments widget.
widget = "accomplishments"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 50  # Order that this section will appear.

title = "项目经历"
subtitle = ""

# Date format
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Accomplishments.
#   Add/remove as many `[[item]]` blocks below as you like.
#   `title`, `organization` and `date_start` are the required parameters.
#   Leave other parameters empty if not required.
#   Begin/end multi-line descriptions with 3 quotes `"""`.

[[item]]
  organization = "罗伯特·博世有限公司"
  organization_url = "https://www.bosch.de/unser-unternehmen/bosch-in-deutschland/leonberg/"
  title = "汽车软件开发中的持续测试方法"
  url = "files/project-jenkins.pdf"
  certificate_url = "files/project-jenkins.pdf"
  date_start = "2018-09-01"
  date_end = "2019-02-01"
  description = "通过配置Jenkins脚本和本地的Batch及C#文件来实现了自动泊车ECU的自动持续测试。即集成测试可以通过Jenkins平台远程启动并可设置执行周期。使用多个脚本来分别实现：自动从服务器同步最新的基于超声波传感器的自动泊车软件，调用winIDEA实现软件的自动写入，在CANoe中调用相应集成测试用例并自动启动测试。测试完成后Jenkins会自动发送带有测试报告的电子邮件到开发者信箱中以便及时获知测试结果。"

[[item]]
  organization = "科堡应用技术大学"
  organization_url = "https://www.hs-coburg.de/"
  title = "三维重建技术"
  url = "files/project-3D.pdf"
  certificate_url = ""
  date_start = "2017-10-01"
  date_end = "2018-02-01"
  description = "比较了几种3D重建方法：结构化光投影，轮廓形状，多视图立体和激光线扫描。并且通过MATLAB实现了基于双摄像头的三维重建：使摄像头同时拍摄同一物体，利用有具体尺寸的棋盘格对相机进行标定后即可重建出其它物体的三维影像与点云图。"
  
[[item]]
  organization = "上海理工大学"
  organization_url = "http://en.usst.edu.cn/"
  title = "同步检测泵浦光斑与样品表面微结构的装置"
  url = "files/project-optical.pdf"
  certificate_url = ""
  date_start = "2013-10-01"
  date_end = "2015-10-21"
  description = "该系统采用易于调节的简单结构，主要由激光光源，隔离器，透镜，旋转底座，分束片，衰减片，CCD图像传感器，样品台，二维步进电机，三个反射镜及光垃圾桶制成。激光光源发出的激光沿水平方向依次经过隔离器、透镜、分束片聚焦样品台上，分束片下方，与激光垂直方向依次排衰减片和CCD图像传感器，经分束片反射激光垂直向上依次经过第一反射镜、第二反射镜、第三反射镜后光反射回样品背面，光垃圾桶为移动件，用于遮挡光路。通过移动光垃圾桶和调整分束片方向，实现泵浦光斑与反射及透射型样品表面微结构的监测，构成简单，容易操作。（上海市创新项目，导师：彭滟副教授）"

+++
