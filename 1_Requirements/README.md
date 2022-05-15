# Description
* Wiper control system is designed using STM32F407VG as the main controller, which senses the severity of rain and helps in varying the speeds of wiper accordingly without any manual interruption.


# Features
* Offers different modes of control - low speed, medium speed and high speed
* Controls wiper action without human interruption


# Highlevel Requirements
|HLR_ID|Description|Status|
|:--:|:--:|:--:|
|HLR_1|This project ensures detection of light when water droplets falls on windshield|Implemented|
|HLR_2|This project activates the wiper|Implemented|
|HLR_3|This project adjusts wind speed and frequency based on intensity of the precipitation|Implemented|

    
# Lowlevel Requirements
|HLR_ID|LLR_ID|Description|Status|
|:--:|:--:|:--:|:--:|
|HLR_1|LLR_01|The detection is performed using user button|Implemented|
|HLR_2|LLR_01|The detection is performed using light sensor|Future|


# SWOT Analysis
![SWOT ANALYSIS](https://github.com/hpsanjana20/M3-Wiper_control_system/blob/main/6_Output/others/swot%20analysis%20wiper.png)


# 4W's & 1H
* **What**  : Windscreen wipers are necessary for maintaining sufficient view for the driver, especially in modern high-speed cars.
* **When**  : The windshield wipers remove rain and snow from the windshield, while the headlights improve visibility at night.
* **Where** : It can be incorporated in car, trucks, etc
* **Why**   : To keep the windscreen clean enough to give adequate view at all times.  
* **How**   : By using STM32F407VG microprocessor

