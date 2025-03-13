Welcome to the Longhorn Days README file!
This document is provided to help you with your .iso installation or the transformation pack installation.

-> .ISO Installation
- If you're installing this on VMware, set the VMWare compatibility to 6.5/7. 
- Make sure to install drivers
- Enter this code to disable time sync:

tools.syncTime = "FALSE"
time.synchronize.continue = "FALSE"
time.synchronize.restore = "FALSE"
time.synchronize.resume.disk = "FALSE"
time.synchronize.shrink = "FALSE"
time.synchronize.tools.startup = "FALSE"
time.synchronize.tools.enable = "FALSE"
time.synchronize.resume.host = "FALSE"

-> Transformation Pack Installation
- Recommended builds to install the Longhorn Days Transformation pack are from 4000 to 4093.
- You can technically install the transformation pack on 37xx builds, but most features won't work.
