# The Mad Noodle Keypads Gen2
 Support and documentation for the Generation 2 of The Mad Noodle Keypads
 
![Mad Noodle Keypads](https://static.wixstatic.com/media/59d0ff_da03b7404ab9489395109a39dca177d5~mv2.png)


 Fully updated second generation Mad Noodle Keypad, Source `keyboard` folder for QMK firmware, Compiled Default Firmware, and Documentaion  
 Use the included keymaps as template to create your own! 


**For FULL detailed instructions on how to create, modify, and compile QMK firmware Please visit https://docs.qmk.fm/**


## Instructions


#### Installing current Mad Noodle keyboard folder to QMK firmware

1. Vist [QMK's Github](https://github.com/qmk/qmk_firmware) and clone download current release
2. Place the enitre `qmk_firmware` in the directory you plan on working out of
3. Copy the entire `Mad Noodle Keypads Gen2/QMK Source Code/themadnoodle` folder to `qmk_firmware/keyboards` directory of the QMK firmware folder you just downloaded

Then your good to go! <br>
Modify your keymaps to your desired layout and follow the instructions on https://docs.qmk.fm/ to compile your new firmware

Make using: `make themadnoodle/<keyboard>:<keymap>` <br>
Example: `make themadnoodle/ncc1701kbv2:default`
 
 See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. 
Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

If you are having issues feel free to contact jesse@madnoodleprototypes.com or visit our website at https://www.madnoodleprototypes.com/
