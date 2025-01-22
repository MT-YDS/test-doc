---
title: 2.1 Building Bootable Media
date: 2024-10-06T18:17:00+09:00
draft: false
weight: 10
---

## Kakip OS Bootable Media Creation Procedure

We provide Linux-based software optimized for Kakip so that users can start development smoothly. This section shows the procedure for obtaining the basic software package (OS and device drivers) that comes with Kakip and creating bootable media.

### What you need

* A computer that can download the OS image and write to a microSD card (any OS)

### Downloading the Kakip OS image

Please obtain the kakip OS image from the link below. (Zip File size: approx. 3GB)

[kakip_os_image_v5 (2024.10.01)](https://www.kakip.ai/software/)

### Extracting to microSD card

There are several tools for extracting img files to media, but here we will show you how to use balena's "Etcher". Download Etcher from the following website and install it in each environment.

![EtcherDownload](images/balena_web.png)

[Download Etcher here](https://etcher.balena.io/)

#### Selecting an img file

Launch the downloaded and installed Etcher.

![EtcherWrite](images/etcher02.png)

From "Flash From File", select the img file you just downloaded.

#### Selecting the target media

![EtcherWrite](images/etcher03.png)

![EtcherWrite](images/etcher04.png)

Select the img file you downloaded earlier from "Select Target".

#### Extracting the image

![EtcherWrite](images/etcher05.png)

Press the "Flash" button to begin extracting the image.

![EtcherWrite](images/etcher06.png)

After extraction, a validation process will be performed to check.

![EtcherWrite](images/etcher07.png)

When the message "Flash Completed!" appears, the process is complete. Unmount and remove the media.

### Inserting the media into Kakip

![EtcherWrite](images/microSD.jpg)

Insert the SD card you have written to into the microSD card slot on the back of the Kakpi.
