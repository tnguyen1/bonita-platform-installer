# Bonita BPM Platform Installer

This is part of [Bonitasoft](http://www.bonitasoft.com) Living Days #2 (July 2014) organized while celebrating 5th anniversary of the company.

An idea was to facilitate the installation of Bonita BPM platform starting from our famous Tomcat H2 bundle.
As a result we built an installer which enables to customize Tomcat and database configuration.
It also allows to bundle JRE and PostgreSQL database as an option.

This tool is built using [BitRock InstallBuilder](http://installbuilder.bitrock.com).

## Screenshots

![Installer screenshot 1](screenshots/setup1.png?raw=true)
![Installer screenshot 2](screenshots/setup2.png?raw=true)
![Installer screenshot 3](screenshots/setup3.png?raw=true)

## Disclaimer

- This installer is a proof of concept
- It has been implemented within 2 days
- It requires Bonita BPM Tomcat bundle zip and PostgreSQL zip to be served at http://192.168.0.53:8000
- Is has been demonstrated within a Linux environment


## Build instruction

1. Install BitRock Install Builder
2. Load **BonitaBPM-platform-installer.xml** into it
3. Build the installer
4. A **pom.xml** is also available for Maven freaks
