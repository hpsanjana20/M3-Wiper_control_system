# Project Report

It sends out a beam of infrared light that, when water droplets are on the windshield, is reflected back at different angles. This tells the system to activate the wipers, as well as adjust wiper speed and frequency based on the intensity of the precipitation combined with the vehicle's speed.

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



# Test Cases

|Test_ID|Description|Status of switch|Actual O/P|Exp O/P|Type of Test|
|:--:|:--:|:--:|:--:|:--:|:--:|
|TST_1|Ignition key at ACC|User button is pressed and held for 2 sec|Red LED is ON|Red LED is ON|Requirements based|
|TST_2|Wiper ON|User button is pressed|Blue, Green and Orange LED is ON|Blue, Green and Orange LED is ON|Requirements based|
|TST_3|Wiper OFF|User button is pressed|Blue, Green and Orange LED is OFF|Blue, Green and Orange LED is OFF|Requirements based|
|TST_4|Ignition key at ACC|User button is pressed and held for 2 sec|Red LED is OFF|Red LED is OFF|Requirements based|

# Architecture

* Block Diagram

![Block Diagram](https://github.com/hpsanjana20/M3-Wiper_control_system/blob/main/2_Design/block_diagram_wiper.png)

* Flowchart

![Flowchart](https://github.com/hpsanjana20/M3-Wiper_control_system/blob/main/2_Design/flowchart_wiper.png)

# SWOT Analysis

![SWOT ANALYSIS](https://github.com/hpsanjana20/M3-Wiper_control_system/blob/main/6_Output/others/swot%20analysis%20wiper.png)


