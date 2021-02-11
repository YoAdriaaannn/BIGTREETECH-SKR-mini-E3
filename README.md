# The YoAdriaaannn edit of the imfamous Marlin running on the BigTreeTech SKR Mini E3 ****WIP!!!!!****
If you so happen to have a printer just like mine, this edit will work for you. If you do not, you may wish to visit the official BigTreeTech Repo and fork your own copy. 

This fork will work for most Ender 3 and clones. Or basically any 3 axis 3d printer with a build volume of 235mm x 235mm x250. It is edited to have the following features:

* LED lights that change with temprature while preheating.
* BL Touch or clone for Z homing
* BTT TFT 3.5 E3 V3
* Dual Z
* Dual Z alignment

# BIGTREETECH SKR Mini E3 V1.x and V2.x

BIGTREETECH SKR Mini E3 V1.x and V2.x mainboards are ultra-quiet, low-power, high-quality 3D printing machine controller boards from BIQU.

These and other SRK mmainboard/motherboard for 3D-printers are produced by the 3D printing team of Shenzhen Bigtree Technology Co., Ltd. 

The first BIGTREETECH SKR Mini E3 V1.x 32-bit control boards with integrated TMC stepper-drivers was initially specially designed to be a drop-in replacement upgrade board for the Ender 3 printers by Creality, making replacing the original 8-bit mainboard/motherboard hardware used by the very popular Ender-3 3D-printer quick and easy for most users. Software updates have since released also added compatibility for other 3D-printers with a single Z-axis stepping-motor, including support for CR-10, CR-10 Mini, Ender 3 Pro from Creality.

BIGTREETECH SKR Mini E3 V2.x has added additional hardware improvements and enhancements based on community feedback. Among other things, these improvements and enhancements with SKR Mini E3 V2.x include two Z-axis interface ports, and SKR Mini E3 V2.x is today, in addition to the 3D-printers already support by the V1.x boards, also compatible with CR-10S, CR-10 S4, CR-10 S5, Ender 5, Ender 5 Pro, and Ender 5 Plus from Creality.

Pre-tested Marlin Firmware configuration example files for these 3D-printers with stock is available in an upstream repository here:

- https://github.com/MarlinFirmware/Configurations/

Note: If your motherboard version is BTT SKR Mini E3 V1.x, please check the correct BIGTREETECH-SKR-mini-E3 V1.x documents which are located respectively in both the firmware directory and hardware directory with that version. For reference, you can read about main differences between SKR Mini E3 V1.0 and SKR Mini E3 V1.2 in the ["notement" document for BTT SKR MINI E3 V1.2](https://github.com/bigtreetech/BIGTREETECH-SKR-mini-E3/blob/master/hardware/BTT%20SKR%20MINI%20E3%20V1.2/The%20Notement%20of%20BTT%20SKR%20MINI%20E3%20V1.2.pdf).

Note! After refreshing the new firmware, please always restore defaults first and then store settings, the new coordinates used for levelling will take effect, LCD option path: Configuration-> Restore defaults, Configuration-> Store settings.

Disclaimer! Marlin firmware needs to be configured aND CUSTOMIZED by the customer themselves, the reason for this is that BIQU / BIGTREETECH does not know the specific hardware configuration of each individual customer and can therefore not support individual configuration of special firmware specific to each customer. BIQU customer service will however if contacted provide configuration suggestions if details on your specific hardware setup are described. Other than e-mailing to <support@bigtree-tech.com> it is recommended to also use the BigTreeTech Facebook group and BigTreeTech Subreddit (Reddit community) channels for support, as well as posting bug-reports and feature-request as "issues" on @bigtreetech GitHub repository for BIGTREETECH-SKR-mini-E3:

- https://github.com/bigtreetech/BIGTREETECH-SKR-mini-E3/issues
- https://www.facebook.com/groups/505736576548648
- https://www.reddit.com/r/BIGTREETECH/
 
 ## History
 
 - 18-21th of May - Added BTT SKR Mini E3 v2.0 motherboard firmware and related open source materials.
