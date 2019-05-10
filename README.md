# ROP Collection
A collection of ROP exploits and programs from the "Static Analysis of ROP Code" [paper](http://season-lab.github.io/papers/ropdissector-EUROSEC19.pdf) (EuroSec '19). 

This repository *(we are working behind the scenes, please bear with us)* aims at providing for each hosted ROP payload detailed information on the vulnerable application or vector and the characteristics of the chain, including:
* reference links for the exploit/program
* PE file(s) used as gadget source
* download link to the vulnerable application
* raw bytes extracted for the chain
* details on actions performed by the chain (e.g. executed library calls, CFG)
* a configuration file to run the chain in [ROPDissector](https://github.com/season-lab/ropdissector)

We will gradually be publishing details and setup to run the payloads over the next weeks. For the time being you may check the ROP programs that we host in the `demo-payloads` folder of the ROPDissector repository.

### Exploits and programs that will be hosted ###
* Adobe Reader U3D
* Audio Converter
* BigAnt Server
* Castripper
* ComSndFTP (2 variants)
* Easy File Sharing Web Server (3 variants)
* Free MP3 CD Ripper
* Mini-stream RM-MP3 Converter (2 variants)
* MPlayer
* NetTransport
* nfsAxe
* PDF weaponizations of Adobe Reader vulnerabilities
    * CVE-2013-0641 a.k.a. "number of the beast"
    * CVE-2010-2883
    * CVE-2011-2462
    * CVE-2013-2729
    * CVE-2018-4990

### Credits
* Andrea Salvati ([@AnSlvt](https://github.com/AnSlvt))
* Daniele Cono D'Elia ([@dcdelia](https://github.com/dcdelia))
