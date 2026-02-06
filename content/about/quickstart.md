---
title: 'Quick Start'
weight: 3
---

New to Linux? Not using Flatpak? See the [detailed guide](https://github.com/hoshinolina/spout2pw/wiki) for step-by-step instructions!

### OBS/Steam Flatpak users

1. Download the latest [release](https://github.com/hoshinolina/spout2pw/releases) and extract it
1. Move/rename the **spout2pw-x.x.x** folder to **~/.var/app/com.valvesoftware.Steam/spout2pw**
1. Start Steam
1. Switch your app compatibility tool to **Proton Experimental**
1. Set the launch options to `~/spout2pw/spout2pw.sh %command%`
1. Start your app and enable Spout2 output
1. `flatpak install com.obsproject.Studio.Plugin.OBSPWVideo`
1. Start OBS and add a **PipeWire Video** source
1. Install [qpwgraph](https://flathub.org/en/apps/org.rncbc.qpwgraph)
1. Start qpwgraph and connect the source and sink nodes together
