# EBU Medias Files

This repository contains the medias files loaded into the EBU KIOSK

The main branch is directly synchronised into the totem into the /data/ebu-medias folder on every restart of the container.  The /data folder is persistant on the totem flash and won't be downloaded every time.

- Proximus.png is used by the splash screen booth , when the totem is turned on, or when a complete reboot done remotely
- Proximus_intro.mp4 is played as starting sequence of the container app.  it is played every time the container is restarted.  There is an ENV to switch on/off the sequence.
