+++
# Accomplishments widget.
widget = "accomplishments"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 50  # Order that this section will appear.

title = "Projects"
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
  organization = "Robert Bosch GmbH"
  organization_url = "https://www.bosch.de/unser-unternehmen/bosch-in-deutschland/leonberg/"
  title = "Continuous testing method in Automotive Software Development"
  url = "files/project-jenkins.pdf"
  certificate_url = ""
  date_start = "2018-09-01"
  date_end = "2019-02-01"
  description = "Implemented a continuous test method by configuring the Jenkins pipeline.Using several batch files and C# scripts to implement automatic flash in winIDEA and automatic test in CANoe. The integration test can be launched remotely and periodicity via Jenkins. Using multiple scripts to achieve separately: automatically synchronize the latest parking-pilot software which based on ultrasonic sensors from the server, flashing softeware to ECU via winIDEA, generating the corresponding test cases in CANoe and start the test automatically. Once the test is completed, Jenkins will automatically send an email with the test report attached to the developer."

[[item]]
  organization = "Hochschule Coburg"
  organization_url = "https://www.hs-coburg.de/"
  title = "3D reconstruction techniques"
  url = "files/project-3D.pdf"
  certificate_url = ""
  date_start = "2017-10-01"
  date_end = "2018-02-01"
  description = "Build a platform to compare several 3D reconstruction methods: structured-Light projection, shape-from-Silhouette, multiview-stereo and laser-line scanning. And implemented the three-dimensional reconstruction method based on dual cameras in MATLAB: Using the checkerboard with specific dimensions to calibrate the camera and the three-dimensional images and point cloud map of other objects can be reconstruct."
  
[[item]]
  organization = "University of Shanghai for Science and Technology"
  organization_url = "http://en.usst.edu.cn/"
  title = "Device for synchronously detecting the micro structure of the light spot and the sample surface"
  url = "files/project-optical.pdf"
  certificate_url = ""
  date_start = "2013-10-01"
  date_end = "2015-10-21"
  description = "The system adopts a simple structure which is easy to adjust. It is mainly composed of a laser light source, an isolator, a lens, a rotating base, a beam splitter, an attenuator, a CCD image sensor, a sample stage, a two-dimensional stepping motor, three reflectors and a light trash production. The laser light emitted by the laser light source passes through the isolator, lens, and beam splitter in the horizontal direction to focus on the sample stage. The attenuator and the CCD image sensor are arranged in sequence in the vertical direction of the laser. After passing through the first reflecting mirror, the second reflecting mirror, and the third reflecting mirror, the light is reflected back to the back of the sample. And the light trash can is a moving part which is used to block the optical path. """By moving the light trash can and adjusting the direction of the beam splitter, the pump spot and the microstructure of the reflective and transmissive sample surface can be monitored. The structure is simple and easy to operate. (Shanghai Innovation Project, Tutor: Yan Peng)"

+++
