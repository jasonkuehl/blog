---
title: Stop Using ISP Provided DNS
description:  ISP Provided DNS is filtering you cant control
slug: ISP Provided DNS is filtering you cant control
date: 2025-08-13
image: cover.jpg
categories:
    - ISP
    - Networking
tags:
    - Xfinity

weight: 1       # You can add weight to some posts to override the default sorting (date descending)
---

ISP URL Filtering and Blocking

Most, if not all, ISPs offer URL-based protections. These are mostly automated systems that decide if a site is malicious or not. To name just a few

Xfinity xFi Advanced Security
Comcast  Xfinity xFi Advanced Security
Comcast Business SecurityEdge
Cox Advanced Security
spectrum Site Shield
ATT Smart Home
Tmobile Web Guard

The major issue with most of these systems is their automated nature in identifying what is, in quotes, “Bad.” See my post here about Xfinity blocking my Corp VPN Several times over the years and never getting a reason why. Recently, I assisted a friend with transferring his online store from Squarespace to Shopify, and users on the spectrum received a message about a suspicious site being blocked. There was no reason as to why, or what category, just blocked.

Check out this site at https://rocketprops.store/

Now, what is the solution? Most of these companies have a procedure to remove the block, but that can take up to one week. Its a really shiity process and unless you’re technically enough, you might not know what to do as an owner of a website or other service that get blocked by an ISP like this. And, they dont need to remove it.

Knowing what you know about this, what can you do? Well, you have 3 total options: paid service, a non-paid service that targeted, and build something yourself.

Paid Options 

https://meetcircle.com/
https://nextdns.io/
https://controld.com/plans?step=plans

Free Targeted filtering options
https://signup.opendns.com/homefree/
Quad9 for malicious domain blocking

.cloudflare.com/introducing-1-1-1-1-for-families/
https://one.one.one.one/family/
Malware Blocking Only
Primary DNS: 1.1.1.2
Secondary DNS: 1.0.0.2
Malware and Adult Content
Primary DNS: 1.1.1.3
Secondary DNS: 1.0.0.3
These are self-hosted services that you can run to give you that control, but they are more advanced to set up and maintain, and you’re the maintainer.

Pihole
AdGuard
