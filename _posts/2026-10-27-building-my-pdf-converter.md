---
layout: post
title: "Solving a Real-World Problem: Why I Built a Native macOS PDF Converter"
date: 2026-10-27
---

As a weekly volunteer contributor to the South Brunswick Library's Teen Services blog, I spend a lot of time researching and writing articles on everything from STEM topics to electric vehicle physics. 

However, I quickly ran into a logistical bottleneck: formatting. 

I write all my drafts using Apple Pages, but the library’s submission system cannot open `.pages` files. They strictly require standard PDF documents. While Pages has an export feature, navigating the drop-down menus for every single weekly submission—or relying on ad-heavy, slow online converters when dealing with image scans—felt incredibly inefficient. 

As a software engineering student, I realized this was a problem I could automate. Instead of changing my workflow, I decided to build my own tool.

**The Solution**
I engineered a native macOS desktop utility that instantly converts files and images into clean, formatted PDFs. Rather than building a web app that requires an internet connection and compromises privacy by uploading files to a random server, I chose to build it "bare-metal" for the Mac.


**The Result**
Today, my app sits quietly on my Mac. When I finish my weekly library article, I just drag it in, and it instantly outputs the exact PDF format the library coordinators need. 

Building this taught me that the best software doesn't always have to change the world—sometimes, it just has to save you five minutes every single week.
