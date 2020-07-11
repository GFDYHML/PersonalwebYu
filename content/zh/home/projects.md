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
  url = ""
  certificate_url = ""
  date_start = "2018-09-01"
  date_end = "2019-02-01"
  description = "通过配置Jenkins脚本和本地的Batch及C#文件来实现了自动泊车ECU的自动持续测试。即集成测试可以通过Jenkins平台远程启动并可设置执行周期。使用多个脚本来分别实现：自动从服务器同步最新的基于超声波传感器的自动泊车软件，调用winIDEA实现软件的自动写入，在CANoe中调用相应集成测试用例并自动启动测试。测试完成后Jenkins会自动发送带有测试报告的电子邮件到开发者信箱中以便及时获知测试结果。"

[[item]]
  organization = "Hochschule Coburg"
  organization_url = "https://www.hs-coburg.de/"
  title = "三维重建"
  url = ""
  certificate_url = ""
  date_start = "2017-10-01"
  date_end = "2018-02-01"
  description = "建立一个平台来比较几种3D重建方法：结构化光投影，轮廓形状，多视图立体和激光线扫描。并且通过MATLAB实现了基于双摄像头的三维重建：使摄像头同时拍摄同一物体，利用有具体尺寸的棋盘格对相机进行标定后即可重建出其它物体的三维影像与点云图。"
  
[[item]]
  organization = "University of Shanghai for Science and Technology"
  organization_url = "http://en.usst.edu.cn/"
  title = "同步检测泵浦光斑与样品表面微结构的装置"
  url = "https://patents.google.com/patent/CN103257141A/ru"
  certificate_url = ""
  date_start = "2013-10-01"
  date_end = "2015-10-21"
  description = "该系统采用易于调节的简单结构，主要由多个透镜与反射镜，分束片，衰减片，光阑，二维步进电机，CCD以及光垃圾桶制成。通过调整分束片和光垃圾的桶位置来实现同时监测泵浦光束和样品表面的微观结构功能。（上海市创新项目，导师：彭滟副教授）"

+++
