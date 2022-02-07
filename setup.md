---
layout: page
title: Setup
---

# Required Software

Thesse lesson requires the installation of R, RStudio, and BASH. The R open-source software is an object-oriented programming language for statistical computing and graphics. It compiles and runs on a wide variety of UNIX platforms, Windows, 
and MacOS. 

RStudio is a set of integrated tools designed to help you be more productive with R. It includes a console, syntax-
highlighting editor that supports direct code execution, and a variety of robust tools for plotting, viewing history, debugging, and managing your workspace.

The command line terminal available to Mac OS and Linux is a powerful tool and where the magic happens. It’s excellent for software development, file management, remote analysis, and a myriad of other tasks.
 
## Windows
To download R, visit https://cran.r-project.org/ and at the top of the page, select the Windows operating system.
- Select the "Download R for Windows" link on the main page.
- Select the "base" link in the Subdirectories.
- Select the "Download R 4.1.2 for Windows" link, and the R installer will begin to download. 
- Open the installer and follow the instructions.

To download RStudio, visit https://www.rstudio.com/products/rstudio/download/#download and follow the instructions to:
- “1. Install R”, which you have already done.
- “2. Download RStudio Desktop”
- Select the "Download RStudio for Windows" button and the R Studio installer will begin to download.
- Open the installer and follow the installation instructions.

The Ubuntu terminal for Windows has many of the same features you’ll find using the terminal on Ubuntu for Linux, visit https://ubuntu.com/tutorials/ubuntu-on-windows#1-overview. Note that you will need a x86 PC running Windows 10.
- As a first step the Windows Subsystem for Linux needs to be installed for your version of Windows 10.
- For Windows 10 systems updated to the Windows 10 Fall Creators update released October 2017, run the following in PowerShell as Administrator: 
> ~~~
> dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
> ~~~
> {: .language-r}
- For Windows 10 systems updated to the Windows 10 May 2020 update and newer run the following in PowerShell as Administrator: 
> ~~~
> dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart
> ~~~
> {: .language-r}
- Then restart your computer.
- Now Ubuntu can be installed from the Microsoft Store:
- Use the Start menu to launch the Microsoft Store application.
- Search for Ubuntu and select the first result, "Ubuntu", published by Canonical Group Limited.
- Click on the Install button. Ubuntu will be downloaded and installed automatically. Progress will be reported within the Microsoft Store application.
- Ubuntu can now be launched in the same way as any other Windows 10 application, such as searching for and selecting Ubuntu in the Start menu.
- When launched for the first time, Ubuntu will inform you that it’s "Installing" and you’ll need to wait a few moments. 
- Then enter a username and password specific to your Ubuntu installation, which don’t need to be the same as your Windows 10 credentials. With this step complete, you’ll find yourself at the Ubuntu bash command line.


## Mac OS
To download R, visit https://cran.r-project.org/ and at the top of the page, select the macOS operating system.
- Select the "Download R for macOS" link on the main page.
- Select the "base" link in the Subdirectories.
- Select the "R-4.1.2.pkg" link, and the R installer will begin to download. 
- Open the installer and follow the instructions.

To download RStudio, visit https://www.rstudio.com/products/rstudio/download/#download and follow the instructions to:
- “1. Install R”, which you have already done.
- “2. Download RStudio Desktop”
- Select the "Download RStudio for Mac" button and the R Studio installer will begin to download.
- Open the installer and follow the installation instructions.