# Edina Public Schools Chromebook Enrollment Scripts

## Go-Box Scripts
The gobox_scripts folder contains various custom Go-Box enrollment scripts (.gct) to use with the GoBox Chrome enrollment hardware solution. Simply download the desired script from the gobox folder and upload it to the Go-Box device. Be sure to read the documentation at the top of each script file to ensure the chromebook is on the right screen and that the environment is correctly setup.

### powerwash_ethernet_setup.gct
The purpose of this script is to take a Chromebook that has just been powerwashed and to automate the the setup and testing process. The Chromebook will start on the "Welcome" screen displayed after a powerwash, and then the Chromebook will end with several webpages open with hardware testing websites ready to be started.

### v87_enroll_ethernet_phase_1.gct / v87_enroll_ethernet_phase_2.gct
The purpose of these two scripts is to take an unenrolled Chromebook and automate the enrollment and testing process. The reason there is two scripts is that during the enrollment process, there is a screen for entering the asset ID and location, something that cannot be feasibly automated using simulated keyboards (such as the Go-Box or a Rubber Ducky) due to each Chromebook having its own unique asset ID. Therefore, the first script ends when it gets to the asset ID screen. **The asset ID will have to be manually typed, and the person typing it will NOT proceed to the next screen.** Once the asset ID is entered, the second script will be enabled on the Go-Box, then the USB will have to be replugged in to start the second script. 

### v87_enroll_ethernet_skip_asset.gct
The purpose of this script is to take an unenrolled Chromebook and automate the entire enrollment and testing process. **This script differs from the previous enrollment script because it will skip over the screen where the asset ID and location would be entered.** The asset ID and/or location will have to be manually assigned after the enrollment process via administration tools such as Google Control Panel (GCP). The success of this script relies on the accuracy of the recorded the serial number and asset ID during the unboxing and inventorying process.
