---
layout: post
title: 'Linux IS-IS Worldwide Network'
description: "Routing through VPN Tunnels Around the World"
categories: [networking, isis, linux, sdwan, vpn]
date: 2019-03-14 13:59 -700
---

This is a bit of a work in progress, and has been on hold for a bit.

If you've seen my project [Zerotier - Quick setup secure SDWAN
solution](projects/zerotier-secure-sdwan) then you've seen that I have a bit of a large network
as a personal hobby.

On and off over the past few months I've added IS-IS to most of the nodes and am working on an
IPSec/GRE tunnel solution between each of the nodes to run IS-IS over.

Right now it's just going over ZeroTier, to do that you need to comment out the drop flow rules
(or you could add the ISO ethertypes)


TODO: fswatch solution to put this on a remote server? Doing that now.


