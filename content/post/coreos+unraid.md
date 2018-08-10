---
title: "coreos + unraid "
date: 2018-08-04T13:07:16+10:00
draft: true
---


ohh man. I've spent the past 6 hours trying to get coreos to pxe boot, then http boot, then boot from a image.

nothing worked. I followed the guides on the core os, setup their softare and every and setup the dnsmsq service to enable all the pxe/http boot.

nothing.

So I decided to install kubernetes on ubuntu 18.04. I've got the cluster initialized with ansible so ill create a repo of what I did so people can know "ohh this is how alex fucked up"

First thing I hit was iops as I was trying to run this on a 7200 rpm hard drive. I'm currenly copying the image to a ssd so once that's done i'll kick off the initialize for kubernetes again and go to bed

fun times indeed
