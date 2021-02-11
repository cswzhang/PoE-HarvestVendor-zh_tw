# Its BETA there will be issues and lackign features :)
 - Download https://github.com/esge/PoE-HarvestVendor/releases/tag/0.2.1
 - Requires AHK 1.1.33.02 
   - not that it wont work on older, but there was a bug where it would say that a piece of code is unreachable in a switch/case and you will get a warning popup everytime you launch it
 
# PoE-HarvestVendor
  - Convert your Horticrafting station crafts into a post, almost in a smart way
  - Using ahk to call capture2text OCR tool on selected screen region
  - then parsing the text
  - it works as long as OCR doesnt do stupid stuff

# Description

<img src="examples/Description.png">

- Recommended area to select
<img src="examples/snapshotArea.png">
 
- example output message
```
WTS Ritual Softcore 
  1x Remove Influence lv83 - 100c
  2x Remove Speed lv83 - 2ex
```


# 3rd Party stuff
  - http://capture2text.sourceforge.net/ for OCR
  - https://github.com/cocobelgica/AutoHotkey-JSON jxon function embeded in the main file

# Install
  - get the above mentioned OCR tool (tested on version 4.6.2)
  - get the .ahk file
  - put them in the same Folder  
  <img src="examples/folder.png">  

# Use
  - open horticrafting station
  - open harvestVendor (TDB for now ctrl+shift+q)
  - click Add crafts
  - select the area with text (the left side icons mess up OCR)
    - you can include Levels if you wish
  - stuff gets loaded into the GUI fields, add prices, sort out OCR mess if any, click Create Posting
  - now you have a message ready in clipboard
  
 
# FAQ
 **Q. A craft i have in horticrafting station is not showing up in the result**  
 A. I arbitrarily decided its not worth to list that one, if you want it listed, contact me or open an issue. [List of ignored crafts](https://github.com/esge/PoE-HarvestVendor/wiki/Crafts-that-are-being-ignored)
