---
title: Security Camera Materials and File Structure
date: 2025-01-19 16:14:28 -0500
categories: [Projects]
tags: [camera, comp-eng, bash, hardware, usb]     # TAG names should always be lowercase

authors: [raghav, matty]

description: This is my first post about my computer engineering final project -- a motion detected camera using the Raspberry Pi.


toc: true # turning on the table of contents
comments: false # Turning off comments on this post

media_subpath: /assets/projectFiles

image: 
    path: motion.png
    alt: Motion Logo
---

# Materials list:
- ## Hardware:
    - SD Card
    ![SD card image](/sdCard.webp)
    - Raspberry Pi
    ![Raspberry Pi 4 imgae](/raspberryPi.jpg)
    - USB Dynex 1.3 MP Webcam
    ![Dynex Webcam image](/webcam.jpg)
    - USB Keyboard
    ![USB Keyboard image](/keybaord.webp)
    - USB Mouse
    ![USB Keybaord image](/mouse.jpg)
    - Monitor
    ![Monitor image](/monitor.jpg)


- ## Software:
    - Raspbian OS (based off of Debian)
    ![Raspbian OS image](/raspbian.png)
    - Motion Program (open-source)
    [Motion Program link](https://github.com/Motion-Project/motion)

## Project layout and files on the Pi
- `/Users`{: .filepath}
    - `/etc`{: .filepath}
        - `/motion`{: .filepath}
            - `/motion.log`{: .filepath}
    - `/var`{: .filepath}
        - `/lib`{: .filepath}
            - `/motion`{: .filepath}
                - `/"VideoFileName.mp4"`{: .filepath}
    - `/tmp`{: .filepath}
        - `/motion`{: .filepath}
            - `/motion.log`{: .filepath}