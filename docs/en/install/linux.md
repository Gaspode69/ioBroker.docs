---
title: Linux
lastChanged: 23.10.2022
translatedFrom: de
translatedWarning: If you want to edit this document please delete "translatedFrom" field, elsewise this document will be translated automatically again
editLink: https://github.com/ioBroker/ioBroker.docs/edit/master/docs/en/install/linux.md
hash: 2xmu9mKiW1SUwp64fE7C7to9UpCt4bn7nFN/0dAXYfk=
---
# IoBroker installation under Linux & on a Raspberry Pi
ioBroker is installed using a script that carries out the necessary installation steps and reloads any software packages that may be required.

## Check requirements
Before installing, please check whether the system meets all the necessary [Installation requirements](./#de/documentation/install/requirements.md).

## Important points to note
- NO installation of ioBroker as **root** user! Executing the installation script **must** be done as a normal user,

The system will also be administered by this user in the future. The `normale` user should not be called `iobroker`, it should be the user created during the basic installation.

- Required hardware: Raspberry Pi with Raspberry OS or any other hardware with a common Linux. However, Debian, Ubuntu or one of the distributions based on them is recommended
- Beginners should start with Debian / Raspberry Pi OS / Armbian without an additional virtualization layer such as Docker or Proxmox, as with each additional layer additional administrative effort and possible sources of problems are added
- Install your operating system as a server variant without a desktop
  - ioBroker works as a server 24/7 and is administered via terminal programs such as Putty, Powershell or similar. A desktop environment consumes unnecessary resources and increases the potential for errors
- Hardware Raspberry Pi: It is important to use a good power supply. With a weak power supply (e.g. cell phone power supplies)

Stability problems are to be expected

## Raspberry Pi
Instructions for installing ioBroker on a Raspberry Pi: https://forum.iobroker.net/topic/51869/installation-auf-raspi-einfacher-gehen-s-nicht

## Linux
* Install the desired current base operating system (Debian, Ubuntu, etc.) depending on the hardware used.

  Help and instructions for the respective versions are available on the relevant support pages, YouTube, etc.

* Perform a system update via the console and depending on the OS used with ``sudo apt update && sudo apt full-upgrade``.

* ioBroker with the command ``curl -sLf https://iobroker.net/install.sh | bash -`` install.

  The installation script is executed. Depending on the hardware, the installation may take some time.

  Should be ``curl`` fehlen, kann das Paket einfach nachinstalliert werden: ``sudo apt install curl``.

  The installation takes place in 4 steps which can be seen in the console:

  ``Installing prerequisites (1/4)``

  ``Creating ioBroker user and directory (2/4)``

  ``Installing ioBroker (3/4)``

  ``Finalizing installation (4/4)``

  At the end there is the message

  ``ioBroker was installed successfully``

  ``Open http://localhost:8081 in a browser and start configuring!``

ioBroker can now be accessed via the specified IP in the web browser ``http://<IP-Adresse>:8081`` and set up.

# IoBroker installation under Docker
## Check requirements
Before installing, please check whether the system meets all the necessary [Installation requirements](./#de/documentation/install/requirements.md).

## Installation
On this page you can find the official documentation to install ioBroker on Docker: https://docs.buanet.de/de/iobroker-docker-image/