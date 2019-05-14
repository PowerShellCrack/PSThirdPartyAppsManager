# 3rd Party Software Downloader

## Description 
  - Powershell script to download the latest 3rd party software

## Tags
  - msi
  - vlc-player
  - firefox
  - adobe-reader
  - chrome
  - powershell-script
  - google-chrome
  - downloader
  - 7zip
  - google-chrome-stable
  - powershell
  - third-party
  - java
  - sccm
  - mdt
  - mdt-automation-project


## Project: 
  - This is part of my <b>MDT/SCCM automation Project</b>

## What it does:
The script crawls through the 3rd party websites, looking for specific tags in the html and auto navigates to find the download link. Then it will download the files and store them in a folder. Once downloaded, it will build a Cixml that can be imported with another script (https://github.com/PowerShellCrack/MDTApplicationUpdater) to automaticaly updates MDT.

## Works on:
 - Currently it only updates wsf files (https://github.com/PowerShellCrack/MDTDeployApplications) 
 - NOTE: The wsf file must contain the variable: <b>sVersion</b>

## Supports:
 - Adobe Reader 
 - Adobe Reader Updates (and MUI)
 - Adobe Acrobat Reader DC Updates (and MUI)
 - Flash Player Active X
 - Flash Player NPAPI (Firefox)
 - Flash Player PPAPI (Chrome)
 - Shockwave (full, slim and msi)
 - Google Chrome Enterprise Edition (msi)
 - Google Chrome Standalone (exe)
 - Firefox (x86)
 - Firefox (x64)
 - Notepadd++ (x86)
 - Notepadd++ (x64)
 - 7Zip (x64) - MSI and EXE
 - 7Zip (x86) - MSI and EXE
 - VLC Player (x64)
 - VLC Player (x86)
 - Java 8 (x86)
 - Java 8 (x64)
