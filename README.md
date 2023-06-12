# Plex Stack

**Goal:** A fully automated server that runs Plex. With the use of the all the components in this stack you will have a machine that will ingress torrents using Prowlarr to manage indexes, Sonarr & Radarr to send requested Movies/TV to qBitTorrent, and Plex to stream the media. File Browser will be used to easily manage files within Linux Distros. Mullvad is a VPN that helps keep your torrenting private, any VPN will do.

**Guide** 

- 🟢 Strongly Suggest
- 🟡 Solid Option
- 🔴 Would Advise Against

## Components 

- Plex 
- Sonarr
- Radarr
- Prowlarr
- Readarr
- File Browser
- qBitTorrent
- Mullvad

# Server Operating System (OS)

You can run this stack on most operating systems. Now, should you? I would highly suggest not running this stack on your main PC that you use every day. It might sound convenient, but it will heavily impact the performance of most normal computers purely from the increased amount of processing for all the downloads that could be ongoing. 

## Operating System Options:

- 🟢 Ubuntu Server or any Linux Distro - need to be familiar with linux, most NAS solutions run a version of a linux distro.
- 🟢 Windows Server - whatever is current and you can get your hands on.
- 🟡 Windows 10/11 - low technical skill users.
- 🟡 MacOS - I could see a Mac Mini being strong here.
- 🔴 Kubernetes Cluster - Only do this if you want the experience, I have heard of headaches from this.
- 🔴 Your Daily Driver 

# Hardware

2GB of RAM is typically more than sufficient and some installs (particularly Linux-based installs) can often happily run with even less.

The most basic thing to remember is that the more Plex apps you have playing content at the same time, the more CPU power you’ll need. Generally speaking, if you have two Plex apps requiring transcoded content at the same time, that will require about twice the CPU processing power compared to if there was only one app playing content.

[Plex CPU Article](https://support.plex.tv/articles/201774043-what-kind-of-cpu-do-i-need-for-my-server/) 

[Plex RAM Article](https://support.plex.tv/articles/200375666-plex-media-server-requirements/#:~:text=In%20general%2C%20Plex%20Media%20Server,other%20things%20on%20the%20computer.)

## Basic minimum suggestions:

- **No transcoding:** Intel “Atom” 1.2GHz (NAS devices based on ARM processors should also be capable of at least one stream with no transcoding)
- **Single 720p transcode:** Intel Core i3 3.0 GHz
- **Single 1080p transcode:** Intel Core i5 3.0GHz
- **Single 4K transcode:** Intel Core i7 3.2GHz
- If you’ll need to support more than one simultaneous transcode, you’ll need a more powerful processor.

## Hardware Options:
- 🟢 Old Tower Computer - if you have a leftover computer laying around this is usually the perfect use for them.
- 🟡 NAS - These can get pricey but they are purpose built to hold lots of data and they come with a CPU & RAM to get you started right away.
  - [Expensive but strong NAS](https://www.amazon.com/QNAP-TVS-672XT-Thunderbolt-10GbE-Slots/dp/B07JNLNHD1)
  - [More Affordable Option](https://www.amazon.com/TERRAMASTER-F2-223-2Bay-NAS-Storage/dp/B0BF4SWHQN/ref=sr_1_2?ascsubtag=wp-us-1367106051858228500-20&geniuslink=true&keywords=TerraMaster+F2-221+NAS&qid=1686596688&sr=8-2&ufe=app_do%3Aamzn1.fos.c3015c4a-46bb-44b9-81a4-dc28e6d374b3)
  - [Another Affordable Option](https://www.amazon.com/Asustor-AS5202T-Inspired-Attached-Dual-Core/dp/B07PW9DV56?tag=pcguide-best-nas-for-plex-20)
- 🟡 Mac Mini - Would easily be powerful enough but has no built in drive support so would need external drives.
- 🟡 DIY Build - Use [PC Part Picker](https://pcpartpicker.com/) and look around at builds or make your own.
- 🟡 Prebuilt Server - Could probably get your hands on a ~$500 prebuilt that has everything you need, probably just need more drives.
  - [Lenovo Tower Servers](https://www.lenovo.com/us/en/c/servers-storage/servers/towers/?orgRef=https%253A%252F%252Fwww.google.com%252F)
  - [Dell Poweredge](https://www.dell.com/en-us/shop/dell-poweredge-servers/sr/servers/tower?appliedRefinements=35986)
- 🔴 High End PC - Don't waste your gaming PC resources on this stack, it is way overkill.

# Plex

Work In Progress

# Sonarr

Work In Progress

# Arr Software Suite

Work In Progress

# File Browser

Work In Progress

# qBitTorrent

Work In Progress

# Mullvad

Work In Progress
