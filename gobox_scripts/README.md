### powerwash_ethernet_setup.gct
The purpose of this script is to take a Chromebook that has just been powerwashed and to automate the the setup and testing process. The Chromebook will start on the "Welcome" screen displayed after a powerwash, and then the Chromebook will end with several webpages open with hardware testing websites ready to be started.

### powerwash_wifi_setup.gct
The purpose of this script is to take a Chromebook that has just been powerwashed and to set it up and bring up the testing websites. This scripts uses WIFI rather than ethernet. The Chromebook will start on the "Welcome" screen displayed after a powerwash, and then the Chromebook will end with serveral webpages open with hardware testing websites ready to be started.

### v87_enroll_ethernet_skip_asset.gct
The purpose of this script is to take an unenrolled Chromebook and automate the entire enrollment and testing process. **This script differs from the previous enrollment script because it will skip over the screen where the asset ID and location would be entered.** The asset ID and/or location will have to be manually assigned after the enrollment process via administration tools such as Google Control Panel (GCP). The success of this script relies on the accuracy of the recorded the serial number and asset ID during the unboxing and inventorying process. **This script does not work on Chromebooks on v90**

### deprovision_enroll_wifi_skip_asset.gct
The purpose of this script is to take a deprovisioned Chromebook (e.g. returned from a repair shop) and automate the entire enrollment and testing process. **This script requires that the Chromebook's wireless MAC must already be approved to be on Edina-Devices.** The asset ID and/or location fields will be submitted as is, so any changes will have to be done after the enrollment process via administration tools such as Google Control Panel (GCP).