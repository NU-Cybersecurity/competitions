# Cyber Competitions

A curated list of of references for high school and middle school cyber competitions.

### Contributing


### Why?

Getting started with cyber competitions can be a daunting task. We hope this collection of competitions and references will help teams get started.


### Contents

- [Competitions](#competitions)


- [Resources](#resources)
  - [Cryptography](#crypto)
  - [Forensics](#forensics-1)
  - [Operating Systems](#operating-systems)
  - [Starter Packs](#starter-packs)
  - [Steganography](#steganography-1)
  - [Tutorials](#tutorials)
  - [Wargames](#wargames)
  - [Websites](#websites)
  - [Wikis](#wikis)
  - [Writeups Collections](#writeups-collections)


# Resources

*Tools used for solving CTF challenges*

## Crypto

*Tools used for solving Crypto challenges*

- [FeatherDuster](https://github.com/nccgroup/featherduster) - An automated, modular cryptanalysis tool
- [Hash Extender](https://github.com/iagox86/hash_extender) - A utility tool for performing hash length extension attacks
- [PkCrack](https://www.unix-ag.uni-kl.de/~conrad/krypto/pkcrack.html) - A tool for Breaking PkZip-encryption
- [RSACTFTool](https://github.com/Ganapati/RsaCtfTool) - A tool for recovering RSA private key with various attack
- [RSATool](https://github.com/ius/rsatool) - Generate private key with knowledge of p and q
- [XORTool](https://github.com/hellman/xortool) - A tool to analyze multi-byte xor cipher

## Forensics

*Tools used for solving Forensics challenges*

- [Aircrack-Ng](http://www.aircrack-ng.org/) - Crack 802.11 WEP and WPA-PSK keys
  - `apt-get install aircrack-ng`
- [Audacity](http://sourceforge.net/projects/audacity/) - Analyze sound files (mp3, m4a, whatever)
  - `apt-get install audacity`
- [Bkhive and Samdump2](http://sourceforge.net/projects/ophcrack/files/samdump2/) - Dump SYSTEM and SAM files
  - `apt-get install samdump2 bkhive`
- [CFF Explorer](http://www.ntcore.com/exsuite.php) - PE Editor
- [Creddump](https://github.com/moyix/creddump) - Dump windows credentials
- [DVCS Ripper](https://github.com/kost/dvcs-ripper) - Rips web accessible (distributed) version control systems
- [Exif Tool](http://www.sno.phy.queensu.ca/~phil/exiftool/) - Read, write and edit file metadata
- [Extundelete](http://extundelete.sourceforge.net/) - Used for recovering lost data from mountable images
- [Fibratus](https://github.com/rabbitstack/fibratus) - Tool for exploration and tracing of the Windows kernel
- [Foremost](http://foremost.sourceforge.net/) - Extract particular kind of files using headers
  - `apt-get install foremost`
- [Fsck.ext4](http://linux.die.net/man/8/fsck.ext3) - Used to fix corrupt filesystems
- [Malzilla](http://malzilla.sourceforge.net/) - Malware hunting tool
- [NetworkMiner](http://www.netresec.com/?page=NetworkMiner) - Network Forensic Analysis Tool
- [PDF Streams Inflater](http://malzilla.sourceforge.net/downloads.html) - Find and extract zlib files compressed in PDF files
- [ResourcesExtract](http://www.nirsoft.net/utils/resources_extract.html) - Extract various filetypes from exes
- [Shellbags](https://github.com/williballenthin/shellbags) - Investigate NT\_USER.dat files
- [UsbForensics](http://www.forensicswiki.org/wiki/USB_History_Viewing) - Contains many tools for usb forensics
- [Volatility](https://github.com/volatilityfoundation/volatility) - To investigate memory dumps


*Registry Viewers*
- [RegistryViewer](http://www.gaijin.at/en/getitpage.php?id=regview) - Used to view windows registries
- [Windows Registry Viewers](http://www.forensicswiki.org/wiki/Windows_Registry) - More registry viewers

## Operating Systems

*Penetration testing and security lab Operating Systems*

- [BackBox](https://backbox.org/) - Based on Ubuntu
- [BlackArch Linux](https://blackarch.org/) - Based on Arch Linux
- [Fedora Security Lab](https://labs.fedoraproject.org/security/) - Based on Fedora
- [Kali Linux](https://www.kali.org/) - Based on Debian
- [Parrot Security OS](https://www.parrotsec.org/) - Based on Debian
- [Pentoo](http://www.pentoo.ch/) - Based on Gentoo
- [URIX OS](http://urix.us/) - Based on openSUSE
- [Wifislax](http://www.wifislax.com/) - Based on Slackware

*Malware analysts and reverse-engineering*

- [REMnux](https://remnux.org/) - Based on Debian

## Starter Packs

*Collections of installer scripts, useful tools*

- [CTF Tools](https://github.com/zardus/ctf-tools) - Collection of setup scripts to install various security research tools.
- [LazyKali](https://github.com/jlevitsk/lazykali) - A 2016 refresh of LazyKali which simplifies install of tools and configuration.

## Tutorials

*Tutorials to learn how to play CTFs*

- [CTF Field Guide](https://trailofbits.github.io/ctf/) - Field Guide by Trails of Bits
- [CTF Resources](http://ctfs.github.io/resources/) -  Start Guide maintained by community
- [Damn Vulnerable Web Application](http://www.dvwa.co.uk/) PHP/MySQL web application that is damn vulnerable
- [How to Get Started in CTF](https://www.endgame.com/blog/how-get-started-ctf) - Short guideline for CTF beginners by Endgame
- [MIPT CTF](https://github.com/xairy/mipt-ctf) - A small course for beginners in CTFs (in Russian)

## Wargames

*Always online CTFs*

- [Backdoor](https://backdoor.sdslabs.co/) - Security Platform by SDSLabs.
- [Ctfs.me](http://ctfs.me) - CTF All the time
- [Exploit Exercises](https://exploit-exercises.com/) - Variety of VMs to learn variety of computer security issues.
- [Gracker](http://gracker.org) - Binary challenges having a slow learning curve, and write-ups for each level.
- [Hack The Box](https://www.hackthebox.eu) - Weekly CTFs for all types of security enthusiasts.
- [Hack This Site](https://www.hackthissite.org/) - Training ground for hackers.
- [IO](http://io.netgarage.org/) - Wargame for binary challenges.
- [Over The Wire](http://overthewire.org/wargames/) - Wargame maintained by OvertheWire Community
- [Pwnable.kr](http://pwnable.kr/) - Pwn Game
- [Ringzer0Team](https://ringzer0team.com/) - Ringzer0 Team Online CTF
- [ROP Wargames](https://game.rop.sh/) - ROP Wargames
- [SmashTheStack](http://smashthestack.org/) - A variety of wargames maintained by the SmashTheStack Community.
- [VulnHub](https://www.vulnhub.com/) - VM-based for practical in digital security, computer application & network administration.
- [WebHacking](http://webhacking.kr) - Hacking challenges for web.
- [WeChall](https://www.wechall.net/) - Always online challenge site.
- [WTHack OnlineCTF](https://onlinectf.com) - CTF Practice platform for every level of cyber security enthusiasts.

## Websites

*Various general websites about and on ctf*

- [CTF Time](https://ctftime.org/) - General information on CTF occuring around the worlds
- [Reddit Security CTF](http://www.reddit.com/r/securityctf) - Reddit CTF category

## Wikis

*Various Wikis available for learning about CTFs*

- [Bamboofox](https://bamboofox.torchpad.com/) - Chinese resources to learn CTF
- [ISIS Lab](https://github.com/isislab/Project-Ideas/wiki) - CTF Wiki by Isis lab
- [OpenToAll](http://wiki.opentoallctf.com/) - Open To All Knowledge Base

## Writeups Collections

*Collections of CTF write-ups*

- [Captf](http://captf.com/) - Dumped CTF challenges and materials by psifertex
- [CTF write-ups (community)](https://github.com/ctfs/) - CTF challenges + write-ups archive maintained by the community
- [CTFTime Scrapper](https://github.com/abdilahrf/CTFWriteupScrapper) - Scraps all writeup from ctf time and organize which to read first
- [pwntools writeups](https://github.com/Gallopsled/pwntools-write-ups) - A collection of CTF write-ups all using pwntools
- [Shell Storm](shell-storm.org/repo/CTF/) - CTF challenge archive maintained by Jonathan Salwan
- [Smoke Leet Everyday](https://github.com/smokeleeteveryday/CTF_WRITEUPS) - CTF write-ups repo maintained by SmokeLeetEveryday team.
