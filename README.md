# What is this fork?

This fork strip ical-generator of all file system and server facilities, so the toold is now used simply to generate an iCal file as a string. I've done this because I needed an easy way to generate iCal client-side.

For installation and usage, follow the original ical-generator docs (but bear in mind that no server/filesytem operation will work - it's toString only!)


# ical-generator

[![License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](LICENSE)
[![CI Status](https://img.shields.io/travis/sebbo2002/ical-generator.svg?style=flat-square)](https://travis-ci.org/sebbo2002/ical-generator)
<!-- [![Test Coverage](https://sebbo.helium.uberspace.de/teamcity-badges/ICalGenerator_UnitTests/coverage-istanbul)](https://ci.sebbo.net/project.html?projectId=ICalGenerator&tab=preport_project1_Test_Coverage&guest=1) -->

ical-generator is a small piece of code which generates ical calendar files. I use this to generate subscriptionable
calendar feeds.


