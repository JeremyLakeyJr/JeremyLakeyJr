<div align="center">

```
     ██╗███████╗██████╗ ███████╗███╗   ███╗██╗   ██╗    ██╗      █████╗ ██╗  ██╗███████╗██╗   ██╗
     ██║██╔════╝██╔══██╗██╔════╝████╗ ████║╚██╗ ██╔╝    ██║     ██╔══██╗██║ ██╔╝██╔════╝╚██╗ ██╔╝
     ██║█████╗  ██████╔╝█████╗  ██╔████╔██║ ╚████╔╝     ██║     ███████║█████╔╝ █████╗   ╚████╔╝
██   ██║██╔══╝  ██╔══██╗██╔══╝  ██║╚██╔╝██║  ╚██╔╝      ██║     ██╔══██║██╔═██╗ ██╔══╝    ╚██╔╝
╚█████╔╝███████╗██║  ██║███████╗██║ ╚═╝ ██║   ██║       ███████╗██║  ██║██║  ██╗███████╗   ██║
 ╚════╝ ╚══════╝╚═╝  ╚═╝╚══════╝╚═╝     ╚═╝   ╚═╝       ╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝╚══════╝   ╚═╝
```

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=VT323&size=28&duration=2400&pause=900&color=00FF41&background=0D0D0D00&center=true&vCenter=true&width=720&height=48&lines=%3E+boot+sequence+complete;%3E+ESP32-S3+%2B+LoRa+%2B+sub-GHz+%2B+KiCad;%3E+mesh+radios+%7C+hardware+%7C+android+%7C+OSINT;%3E+if+it+has+a+radio%2C+I+want+to+talk+to+it;%3E+build+it.+print+it.+flash+it.+mesh+it." alt="typing" /></a>

<img src="https://img.shields.io/badge/ESP32--S3-0D0D0D?style=for-the-badge&logo=espressif&logoColor=00FF41" />
<img src="https://img.shields.io/badge/KiCad-0D0D0D?style=for-the-badge&logo=kicad&logoColor=00FF41" />
<img src="https://img.shields.io/badge/OpenSCAD-0D0D0D?style=for-the-badge&logo=openscad&logoColor=00FF41" />
<img src="https://img.shields.io/badge/Meshtastic-0D0D0D?style=for-the-badge&logo=lora&logoColor=00FF41" />
<img src="https://img.shields.io/badge/Python-0D0D0D?style=for-the-badge&logo=python&logoColor=00FF41" />
<img src="https://img.shields.io/badge/Kotlin-0D0D0D?style=for-the-badge&logo=kotlin&logoColor=00FF41" />
<img src="https://img.shields.io/badge/C%2B%2B-0D0D0D?style=for-the-badge&logo=cplusplus&logoColor=00FF41" />
<img src="https://img.shields.io/badge/TypeScript-0D0D0D?style=for-the-badge&logo=typescript&logoColor=00FF41" />
<img src="https://img.shields.io/badge/Raspberry_Pi-0D0D0D?style=for-the-badge&logo=raspberrypi&logoColor=00FF41" />
<img src="https://img.shields.io/badge/Linux-0D0D0D?style=for-the-badge&logo=linux&logoColor=00FF41" />

</div>

```console
jeremy@owasso-1:~$ whoami
hardware hacker / mesh radio tinkerer / android dev / OSINT builder
Owasso, Oklahoma

jeremy@owasso-1:~$ cat /etc/motd
I build pocket radios, print the cases for them, write the firmware that
runs on them, and the Android apps that talk to them. If it has an antenna,
a USB port, or a potentiometer, it is fair game.

jeremy@owasso-1:~$ ls ~/projects | wc -l
36
```

<br/>

## `~/projects/mesh-and-radio`

> LoRa, BLE, Reticulum. Off-grid comms that fit in a pocket.

| repo | what it is | stack |
|:--|:--|:--|
| [**mesh-phone**](https://github.com/JeremyLakeyJr/mesh-phone) | **OWASSO-1**: DIY ESP32-S3 handset. Sub-GHz (CC1101) + LoRa (SX1262) dual radio, LTE, NFC/RFID, GPS, trackball, keypad. Full KiCad PCB + OpenSCAD case. | `KiCad` `Python` `C++` `OpenSCAD` |
| [**meshchat**](https://github.com/JeremyLakeyJr/meshchat) | Hybrid Meshtastic + BitChat firmware for ESP32 LoRa boards. Multi-hop flood-routed mesh + encrypted BLE chat + MQTT bridge. Heltec V2/V3, T-Deck. | `C++` `C` |
| [**meshtastic-sliding-phone**](https://github.com/JeremyLakeyJr/meshtastic-sliding-phone) | Nokia N900-style slider enclosure for Heltec V4 + CardKB. Magnetic detents, printed rails. | `OpenSCAD` `Python` |
| [**altoids-mesh**](https://github.com/JeremyLakeyJr/altoids-mesh) | Parametric Altoids-tin enclosure housing a complete Meshtastic node. | `OpenSCAD` |
| [**rns-proxy**](https://github.com/JeremyLakeyJr/rns-proxy) `fork` | SOCKS5 tunnels over the Reticulum Network Stack. | `Rust` |
| [**bitchat**](https://github.com/JeremyLakeyJr/bitchat) `fork` | Bluetooth mesh chat, IRC vibes. | `Swift` |

## `~/projects/android`

> Kotlin. Dark neon. DedSec energy.

| repo | what it is | stack |
|:--|:--|:--|
| [**watch-dogs-launcher**](https://github.com/JeremyLakeyJr/watch-dogs-launcher) ★ | DedSec Launcher: Watch Dogs 2 hacktivist aesthetic as a full Android launcher. | `Kotlin` |
| [**watchdogs-map**](https://github.com/JeremyLakeyJr/watchdogs-map) | Google Maps rebuilt as a Watch Dogs 2 neon minimap. OSM tiles, custom markers, Spotify control. | `Kotlin` |
| [**Lanbulab**](https://github.com/JeremyLakeyJr/Lanbulab) | Bambu Lab printers on LAN-only mode. Discovery, slicing, MakerWorld, send-to-print. | `Kotlin` |
| [**librediet**](https://github.com/JeremyLakeyJr/librediet) | Privacy-first meal tracker. Barcode scan, voice input, Open Food Facts, Material 3. | `Kotlin` |
| [**Urbex-Finder**](https://github.com/JeremyLakeyJr/Urbex-Finder) | Find abandoned buildings near you. | `TypeScript` |

## `~/projects/recon-and-privacy`

> Know what is out there. Leave nothing behind.

| repo | what it is | stack |
|:--|:--|:--|
| [**the-lakeinator**](https://github.com/JeremyLakeyJr/the-lakeinator) ★ | All-in-one OSINT platform. Passive recon, DNS/cert intel, 2D/3D link-analysis graphs, JSON export. | `TypeScript` `Python` |
| [**android-recon**](https://github.com/JeremyLakeyJr/android-recon) | Android device reconnaissance toolkit. | `Python` `Shell` |
| [**Anon-Framework**](https://github.com/JeremyLakeyJr/Anon-Framework) | Framework to stay anonymous on all devices. | `Python` |
| [**cmd-chat**](https://github.com/JeremyLakeyJr/cmd-chat) `fork` | P2P encrypted terminal chat. No servers, no logs, RAM only. | `Python` |

## `~/projects/controllers-and-consoles`

> Old consoles, new controllers, a Pi Zero in between.

| repo | what it is | stack |
|:--|:--|:--|
| [**Pizero-to-X360**](https://github.com/JeremyLakeyJr/Pizero-to-X360) | Pi Zero as a USB adapter: modern Xbox One/Series pad in, genuine wired 360 controller out. Full input map incl. 8-bit analog triggers. | `Python` `C` |
| [**rpi-zero-bt-xinput-adapter**](https://github.com/JeremyLakeyJr/rpi-zero-bt-xinput-adapter) | 8BitDo-style Bluetooth to USB XInput adapter. Up to 4 controllers, <10 ms. | `Python` |
| [**xbox360-controller-sticks**](https://github.com/JeremyLakeyJr/xbox360-controller-sticks) | Printable replacement 360 analog sticks, matched to the OEM profile. | `OpenSCAD` |

## `~/projects/ai-agents-and-misc`

| repo | what it is | stack |
|:--|:--|:--|
| [**mcp-server**](https://github.com/JeremyLakeyJr/mcp-server) | FastMCP server with research, workspace, and self-extending skill tools. | `Python` |
| [**swarm-ui**](https://github.com/JeremyLakeyJr/swarm-ui) | Ollama + Autogen + Home Assistant in one web UI. | `Python` `JS` |
| [**smart-mirror**](https://github.com/JeremyLakeyJr/smart-mirror) | Node smart mirror: camera, face-api.js recognition, TTS, voice commands. | `JavaScript` |
| [**stremio-vr**](https://github.com/JeremyLakeyJr/stremio-vr) | Multiplayer VR cinema for Meta Quest built on Stremio. | `TypeScript` |
| [**scissor-skate**](https://github.com/JeremyLakeyJr/scissor-skate) | Collapsible skateboard where the pantograph *is* the deck. | `OpenSCAD` |
| [**mockshot-roullete**](https://github.com/JeremyLakeyJr/mockshot-roullete) | 3D Buckshot Roulette, PvE + PvP over Socket.io. | `Three.js` |

<br/>

<div align="center">

```console
jeremy@owasso-1:~$ ./stats --theme=crt
```

<img src="https://github-readme-stats.vercel.app/api?username=JeremyLakeyJr&show_icons=true&hide_border=true&bg_color=0D0D0D&title_color=00FF41&text_color=00FF41&icon_color=FFB000&ring_color=00FF41&include_all_commits=true&count_private=true" height="165" alt="stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=JeremyLakeyJr&layout=compact&hide_border=true&bg_color=0D0D0D&title_color=00FF41&text_color=00FF41&langs_count=8&hide=css,html,shell,makefile,cmake" height="165" alt="langs" />

<img src="https://github-readme-streak-stats.herokuapp.com?user=JeremyLakeyJr&theme=dark&hide_border=true&background=0D0D0D&ring=00FF41&fire=FFB000&currStreakLabel=00FF41&sideLabels=00FF41&currStreakNum=FFB000&sideNums=FFB000&dates=4A7A4A" alt="streak" />

<img src="https://raw.githubusercontent.com/JeremyLakeyJr/JeremyLakeyJr/output/github-snake-dark.svg" alt="snake" />

```console
jeremy@owasso-1:~$ cat ~/.contact
github   : @JeremyLakeyJr
youtube  : youtube.com/@jeremylakey
location : Owasso, OK

jeremy@owasso-1:~$ _
```

<img src="https://komarev.com/ghpvc/?username=JeremyLakeyJr&style=for-the-badge&color=00FF41&label=VISITORS&labelColor=0D0D0D" alt="visitors" />

</div>
