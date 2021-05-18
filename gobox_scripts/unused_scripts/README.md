# Unused Scripts
This folder contains various scripts that are not being used for various reasons, such as for proof of concept or archival of older scripts.

### v87_enroll_ethernet_phase_1.gct / v87_enroll_ethernet_phase_2.gct
The purpose of these two scripts is to take an unenrolled Chromebook and automate the enrollment and testing process. The reason there is two scripts is that during the enrollment process, there is a screen for entering the asset ID and location, something that cannot be feasibly automated using simulated keyboards (such as the Go-Box or a Rubber Ducky) due to each Chromebook having its own unique asset ID. Therefore, the first script ends when it gets to the asset ID screen. **The asset ID will have to be manually typed, and the person typing it will NOT proceed to the next screen.** Once the asset ID is entered, the second script will be enabled on the Go-Box, then the USB will have to be replugged in to start the second script. 
