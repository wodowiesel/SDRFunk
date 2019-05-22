# README

![alt text](https://github.com/silicator/SDRFunk/blob/master/docs/favicon.png "Logo SDRFunk")

## SDRFunk Radio Receiver Chrome Extension 1.1.6_0 experimental

This is an enhanced version of the original extention

by silicator a.k.a. Wiesel

**Experimental !**

### Acknowledgements:

based on Google Radio Receiver 1.1.5_0 (for Chrome =< 70)

Chrome Extension Scripts by Jacobo Tarrio from 30. Juni 2016

Chrome Store [Radio-Receiver](https://chrome.google.com/webstore/detail/radio-receiver/miieomcelenidlleokajkghmifldohpo)

[Git-Link](https://github.com/google/radioreceiver) user: jtarrio under Apache License v2.0

Tested with Chrome v73.0.3683.86 official x64-bit (Browserversion >= 71)

___

### Info:

Receive and listen to FM, AM, SSB radio broadcasts on your browser using an RTL-SDR (RTL2832U-chip) USB digital TV tuner.

This application does FM, AM, SSB demodulation in the browser and can capture the radio signals as .wav

* This version was improved with adjustable styles, window-sizes and better permission controls

* Supports most compatible R820T & T2 tuner chips now (maybe some E4000!?)

See PIDs & VIDs & Names in the [Compatibility-List](docs/compatibility-list.csv) (43 Devices incl. Generic now)

Features:

* Scanner-Function

* Recorder (.wav)

* Free-Tuning mode with Steps

* Supported modes: W-FM, N-FM, AM, SSB

* Shift-Correction - Up/Down-Converter needed!

___

### Preparations:

get this program via:

`git clone https://github.com/silicator/SDRFunk`

or download the ZIP-File from the Release-Site (all included)

___

### Build & Install:

 For generating package just use the builder/packer in the extension manager of the browser.

a) Use the extention_1.1.6_0.crx (.pem for key) installer from the package

b) Unzip the extension and load it via Extension-Manager 'chrome://extensions' (in Experimental-Mode)

Path: `C:\Users\YOURUSERNAME\AppData\Local\Google\Chrome\User Data\Default\Extensions\APP-ID\1.1.6_0\`

('unsecure' warning because it's not directly from Google Store)

Permissions: Can be managed in the App-Details or in manifest

You can use _locals if you want to, just remove the x in folder name (english/german).

JavaScript must be activated in your browser!

___

### Usage:

Run with admin/root permissions:

You can open the App via 'chrome://apps' and create a desktop short link via mouse right-click"

Use '. dot' as decimal-comma separator!

Radio works with .wav-file with 16-bit PCM @ 48000 [Hz] mono & stereo / 1 [kHz] - 12.000 [MHz] range.

- Tip: You could use just a copper wire for 2m/70 cm-band or other lambda(1/4)-antennas (17.5 cm/6.9 in for PMR)

or any other antenna-configuration you like to use if you're an advanced amateur-radio-operator.

- You can use an LNA (USB 5V or external) for improving signal-strength

- Bias-T (12V vertical or 18 V horizontal on LNB as PLL-type) for satellites @ 10-12 [GHz] like Es-Hail.

- I use the [NooElec NESDR SMART](https://www.nooelec.com/store/sdr/sdr-receivers/nesdr/nesdr-smart-sdr.html) with an LNA on PMR

___

### Warnings:

- Use only (original/tested) power supplies and cables
  (I use 2x ~5 V/500 mA via USB 2.0 for the LNA & SDR & USB-Wattmeter for monitoring)

- Antenna should be grounded if possible to avoid damage

- You can try a 1:X-ballun (to reduce internal resistance) if using long HF antenna for Short Wave

- Dummy-load: 0.1-100 W @ 50 Ohm "cement" or similar with cooling-ribs with fan for testing

___

### Disclaimer:

- Private Project! Work in Progress (WIP)

- I'm not a professional so **NO guarantees or warranty** for any damage or similar!!

- Usage at your **own risk** !!

- Check laws of your country first! Some Frequencies are prohibited/illegal or need a HAM-Licenses!

- Listening / Spying & Decoding on encrypted frequencies/channels without permission is illegal!

*Help / Testers / Push-Pull-Requests / Issue- & Bug-Reports and Feedback always appreciated!*

You can use it for your projects too if you want to!

*Thank you and have fun!* 73 :)

___

### Links:

[GitPage](https://silicator.github.io/SDRFunk/)

[Google Radio Receiver Forum Group](https://groups.google.com/forum/#!forum/radioreceiver)

[Readme Guideline](README.md)

[Contribution Guideline](docs/CONTRIBUTING.md)

[Code of Conduct Guideline](docs/CODE_OF_CONDUCT.md)

[Copying Guideline](docs/COPYING.md)

[License Guideline](LICENSE.md) under Open-Source APL v2.0

I would appreciate it being named in the source.
