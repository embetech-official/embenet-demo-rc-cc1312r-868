# embeNET Demo for RC-CC1312R-868 modules

## What's inside ?

This repository contains an exemplary project demonstrating the use of embeNET Suite on [RC-CC1312R-868](https://www.radiocontrolli.com/cc1312-module-868) modules. 
The project is designed for the [Code Composer Studio](https://www.ti.com/tool/CCSTUDIO). 

The [RC-CC1312R-868](https://www.radiocontrolli.com/cc1312-module-868) module is sub-GHz multichannel radio transceiver module based on CC1312R chip from Texas Instruments.
In this demo we will assume that the module is connected to the [SmartRF06 board](https://www.ti.com/tool/SMARTRF06EBK) from Texas Instruments via the [RC-CC1312R-868-EV](https://radiocontrolli.eu/RC-CC1312R-868-EV-p262768046) adapter that can be ordered from RadioControlli.

## What's included ?

The demo includes the following components of the embeNET Suite:
- The embeNET Node library in demo mode, providing IPv6 wireless mesh networking connectivity
- A port of the embeNET Node for the CC1312R1 chip
- embeNET Node Management Service (ENMS) providing telemetry services
- MQTT-SN client

## What are the demo version limitations ?

The demo *can only be used for evaluation purposes* (see LICENSE.txt for details).
The demo is limited to 10 nodes only (including root node).

## Single node

For the purpose of this demo a single network node will consist of:
- [SmartRF06 board](https://www.ti.com/tool/SMARTRF06EBK)
- [RC-CC1312R-868-EV](https://radiocontrolli.eu/RC-CC1312R-868-EV-p262768046) adapter
- [RC-CC1312R-868](https://www.radiocontrolli.com/cc1312-module-868) module

## What you'll need to run the demo

- PC with Windows
- One node that will act as the root node in the network
- At least one more (and up to 9) nodes that will act as the network nodes
- Code Composer Studio, available for download from [the official Texas Instrumets site](https://www.ti.com/tool/CCSTUDIO)
- [embeNET demo package for RC-CC1312R-868](https://github.com/embetech-official/embenet-demo-rc-cc1312r-868/releases)

Optionally, to play with the MQTT-SN demo service you'll need:
- MQTT For Small Things (SN) written in Java, available for download from [github](https://github.com/simon622/mqtt-sn)
- MQTT Client Toolbox, available for download from [the official MQTTX page](https://mqttx.app)

Optionally, to easily interact with the custom UDP service you'll need
- [UDP - Sender/Reciever app from Microsoft Store](https://www.microsoft.com/store/apps/9nblggh52bt0)

## How to start?

Read the ['Getting started with embeNET demo for RC-CC1312R-868 module from RadioControlli using SmartRF06 board'](https://embe.tech/docs/?q=doxyview/Getting%20started%20with%20RC-CC1312R-868/index.html) tutorial.