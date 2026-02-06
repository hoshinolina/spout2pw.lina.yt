---
title: 'What is this?'
weight: 1
---

Spout2PW is an extension for Proton/Wine that bridges [Spout2](https://spout.zeal.co/) video streams into [PipeWire](https://pipewire.org/) video streams.

Spout2 is an app-to-app video streaming technology for Windows, and PipeWire is a general audio/video streaming framework for Linux. When you run a Windows app with Spout2 support under Proton/Wine, Spout2PW takes its Spout2 streams out from the "virtual Windows world" and seamlessly converts them to PipeWire streams in the "native Linux world".

Then, you can use [OBS-PWVideo](https://github.com/hoshinolina/obs-pwvideo) to add them as a source directly in the Linux version of OBS.

Spout2PW works with apps launched from Steam, or using [umu-launcher](https://github.com/Open-Wine-Components/umu-launcher).
