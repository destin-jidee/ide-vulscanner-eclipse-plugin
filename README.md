ide-vulscanner-eclipse-plugin-update-site
===========
IDE-VulScanner is an IDE agnostic tool for developers to identify vulnerable code dependencies during implementation phase, which in-tern would save huge security patching and maintenance costs. This usually is caught during CI/CD build phase.

### Features

* Vulnerability code scan during implementation phase
* Save security patch & maintenance costs
* Low overall high & critical vulnerabilities counts
* IDE agonistic, compatible to known IDE i.e. IntelliJ, eclipse, VS Code etc

### Installation

Install it from this update site:

https://github.com/destin-jidee/ide-vulscanner-eclipse-plugin/update-site/raw/main

Pig-Eclipse requires an Eclipse with at least Java 17. It has been tested on Indigo, Juno, Kepler and Luna.

### Guide

* Once installed you will see the faded IDE VulScanner icon on toolbar
* Load a Maven project and open pom.xml file in editor, to enable scanner make sure you select pom.xml file in project explorer
* Click on the icon and wait for report to get loaded
* Any errors can be seen on eclipse error.log view


### Latest Release

1.0.1 - Basic code scan