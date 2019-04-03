# README

![alt text](https://github.com/silicator/SDRFunk/blob/master/docs/favicon.png "Logo SDRFunk")

## SDRFunk HAM-Radio Receiver Extension 1.1.6_0 experimental

by silicator a.k.a. Wiesel

**Early Experimental!**

based on Google Radio-Receiver 1.1.5_0 (for Chrome =< 70)

Chrome Extension Scripts by Jacobo Tarrio from 30. Juni 2016

Chrome Store [Radio-Receiver](https://chrome.google.com/webstore/detail/radio-receiver/miieomcelenidlleokajkghmifldohpo)

[Git-Link](https://github.com/google/radioreceiver) user: jtarrio

under Apache License v2.0 

Tested with Chrome v73.0.3683.86 official x64-bit (Browserversion >= 71)

___

### Infos:

Receive and listen to FM, AM, SSB radio broadcasts on your browser using an *RTL-SDR* (RTL2832U-chip) USB digital TV tuner.

This application does FM, AM, SSB demodulation in the browser and can capture the radio signals as .wav

* This version was improved with adjustable styles, window-sizes and better permission controls

* Supports most compatible R820T & T2 tuner chips now (maybe some E4000!?)

See PIDs & VIDs & Names in the [Compatibility-List](docs/compatibility-list.csv) (43 Devices incl. Generic now)

Features:

* Scanner

* Recorder (.wav)

* Free-tuning mode

* Supported modes: W-FM, N-FM, AM, SSB

* Some Frequencies require an up/down-converter for shifting!

___

### Preparations:

get this program via: 

`git clone https://github.com/silicator/SDRFunk`

or download the ZIP-File from the Release-Site (all included)

___

### Build & Install:

For building just use the extension-packer the extension manager. 

a) Install it via Chrome Extension-Site (proved)

for previous original Version use APP-ID: `miieomcelenidlleokajkghmifldohpo\`

b) Use the extention_1.1.6_0.crx (.pem for key) installer from the package

c) Unzip the extension and load it via Extension-Manager 'chrome://extensions' (in Experimental-Mode)

Path: `C:\Users\YOURUSERNAME\AppData\Local\Google\Chrome\User Data\Default\Extensions\APP-ID\1.1.6_0\`

(unsecure warning because it's not directly from Google Store)


Permissions: Can be managed in the App-Details or in manifest

You can use _locals if you want to, just remove the x in folder name (english/german).

JavaScript must be activated in your browser!

___

### Usage:

Run with admin/root permissions:

You can open the App via 'chrome://apps' and create a desktop shortlink via mouse right-click"

Use '. dot' as decimal-comma separator! 

Radio works with .wav-file with 16-bit PCM @ 48000 [Hz] mono & stereo / 1 [kHz] - 12.000 [MHz] range.

- Tip: You could use just a copper wire for 2m/70 cm-band or other lambda(1/4)-antennas (17.5 cm/6.9" in for PMR)

or any other antenna-configuration you like to use if you're an advanced amateur-radio-operator.

- You can use an LNA (USB 5V or external) for improving signal-strength 

- Bias-T (12V vertical or 18 V horizontal on LNB as PLL-type) for satellites @ 10-12 [GHz].

- I use the [NooElec NESDR SMART](https://www.nooelec.com/store/sdr/sdr-receivers/nesdr/nesdr-smart-sdr.html) with an LNA  

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

- Check laws of your country first! Some Frequencies are prohibited/illegal or need a Ham-License!

- Listening / Spying & Decoding frequencies/channels encrypted without permission  is illegal!

*Help / Testers / Push-Pull-Requests / Issue-Reports and Feedback always appreciated!*

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

Would appreciate beeing named in the Source.
