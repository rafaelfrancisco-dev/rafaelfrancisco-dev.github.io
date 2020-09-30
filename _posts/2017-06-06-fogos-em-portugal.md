---
layout: post
title: fogos em portugal
slug: fogos-em-portugal

---

## forest fires in portugal

Fogos em Portugal was created with the intent of supplanting the then existing Android and iOS apps that made use of public API's for real-time forest fires in Portugal, which at the time were pretty much horrible to use, relying to this date in cross-platform solutions. Taking that into account both versions of my app are fully native, small in size, have a very low resource usage footpring and support all semi-recent versions of Android and iOS.

[app store](https://apps.apple.com/us/app/id1451721943)
[play store](https://play.google.com/store/apps/details?id=com.imaginarymakings.fogosemportugal)

## a new api
The data provided by ProCiv and ICNF are not "ready to use", they only have snapshots of current data without any support for historical data (not even relating to a still ongoing fire) which prompted the creation of our own backend API in Java to support the apps. It runs on a single low-specced VM without any issue, even on peak load times, when responding to hundreds of requests per second.