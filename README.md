# README

![alt text](https://raw.githubusercontent.com/silicator/SDRFunk/master/docs/favicon.png "Logo SDRFunk")

## SDRFunk HAM-Radio Receiver Extention 1.1.6_0a 

by silicator a.k.a. wiesel

**Early Experimental!**

based on Google Radio-Receiver 1.1.5_0

Chrome Extension Scripts by Jacobo Tarrio from 30. Juni 2016

[Radio-Receiver](https://chrome.google.com/webstore/detail/radio-receiver/miieomcelenidlleokajkghmifldohpo)

[Git-Link](https://github.com/google/radioreceiver) user: jtarrio

under Apache License v2.0 

___

### Infos:

Receive and listen to FM and AM radio broadcasts on your browser using an *RTL-SDR* (RTL2832U-chip) USB digital TV tuner.

This application does FM and AM demodulation in the browser and can capture the radio signals as *.wav

*This version was improved with adjustable styles, window-sizes and better permission controls

*Supports most compatible R820T & *T2* tuner chip now  (maybe some E4000!?) !! (incl. full PID & VID-list)

See [Compatibility-List](docs/pidvids.txt)

Features:
* Scanner
* Recorder
* Free-tuning mode for short wave, air band, marine band, etc.
* Supported modes: Wideband FM, Narrowband FM, AM, SSB.
* Some Frequencies requires an up/down-converter for shifting!

___

### Preparations:

get this program via: 

`git clone https://github.com/silicator/SDRFunk`

or download the ZIP-File from the Release-Site

___

### Build & Install:

For building just use the extention-packer the extention manager. 

a) Install it via Chrome Extension-Site (proved)

b) Unzip the the Package first and copy it into the extention-folder of chrome

Path: C:\Users\YOURUSERNAME\AppData\Local\Google\Chrome\User Data\Default\Extensions\hppnkhafjpaidmcihkjgkhbeoienblkf\1.1.6_0\

for previous original Version use ID: miieomcelenidlleokajkghmifldohpo\1.1.5_0\

c) Use the 1.1.6.pem and *.crx installer from the package

d) or via Extension-Manager (in Experimental-Mode) and load the ZIP-File and activate it

(unsecure warning because its not directly from google store)

Permissions: Can be managed in the Details

You can use _locals if you want, just remove the x in foldername.

Javascript must be activated in your browser!

___

### Usage:

run with admin/root permissions:

Use '. dot' as decimal-comma separator! 

Radio works with *.wav-file with 16-bit PCM @ 48000 [Hz] mono & stereo / 1-12.000 [MHz] range. (maybe 0.001 later)

- Tip: You could use just a copper wire for 2 m/70 cm-band or other lambda(1/4)-antennas (17.5cm/6.9in for PMR)

or any other antenna-configuration you like to use if you're an advanced amateur-radio-operator.

You can use an LNA for improving signal-strength or Bias-T (12V vertical or 18 V horizontal) setup for satellites @ 10-12 GHz.

___

### Warnings:

- Use (original) power supply ~5 V/500 mA via miniUSB 2.0

- Antenna should be grounded if possible

- You should use tested Antennas! 

- You can try to smooth the signal out with a 1:X-balloon if using long HF antenna

- Dummy-load: 0.5-100 W @ 50 Ohm "cement" or similar with cooling-ribs with fan for testing

___

### Disclaimer:

- Private Project! Work in Progress (WIP)

- I'm not a professional so **NO guarantees or warranty** for any damage or similar!!

- Usage at your **own risk** !!

- Check laws of your country first! Some Frequencies are prohibited or need a Ham-License!


*Help / Testers /Push-Pull-Requests /IssueReports and Feedback always appreciated!*

*Thank you and have fun!* 73 :)

___

### Links:

[GitPage](https://silicator.github.io/SDRFunk/)

[Readme Guideline](README.md)

[Google Radio Receiver Forum Group](https://groups.google.com/forum/#!forum/radioreceiver)

[Contribution Guideline](docs/CONTRIBUTING.md)

[Code of Conduct Guideline](docs/CODE_OF_CONDUCT.md)

[Copying Guideline](docs/COPYING.md)

[License Guideline](LICENSE.md) under Open-Source APL v2.0

This is not legal advice. 

Would appreciate beeing named in the Source
