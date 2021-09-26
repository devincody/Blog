---
title: "The Voron 2.4 Build Experience"
date: 2021-09-26T00:31:49-07:00
description: "One of my quarantine projects this year was building a 3D Printer... with a 3D printer."
categories: ["3D Printing"]
dropCap: true
displayInMenu: false
displayInList: true
draft: false
resources:
- name: featuredImage
  src: "img/voron_print.jpg"
  params:
    description: "First print using my Voron2.4"
---


## Introduction

This year I joined a pyramid scheme: 3D printer building. Over the last six months, I’ve invested time, money, and possibly my sanity to build a 3D printer whose entire purpose is to print more 3D printer parts. But the final product has been so worth it!

I probably spent 3 months hemming and hawing over what 3D printer to buy or build. There’s a lot of vaporware in the 3D printing market these days and it’s hard to know what’s the right printer to go with. Ultimately, I decided to build a Voron2.4 due to its ability to work with tougher “engineering-grade” plastics, the rapid printing speeds that it’s able to achieve, and the strong community backing. In the end, I have a phenomenal 3D printer that’s met all my needs and then some.

## Pictures

{{<image src="img/frame_assembling.jpg" alt="Figure 0: Assembling the Frame" >}}
I assembled the 2020 extrusion frame on my kitchen counter top which is the flattest surface in my house. 
I used machinist blocks to ensure everything was plumb and square.

{{<image src="img/frame_assembled.jpg" alt="Figure 1: Assembled Frame" >}}
Assembled mechanical Frame. 

{{<image src="img/gantry_assembled.png" alt="Figure 2: Assembled Gantry" >}}
One of the coolest parts of the Voron2.4 build is the flying gantry. The gantry contains all the components of the core-XY mechanism. It’s called a flying gantry because the gantry is suspended by four belts which operate independently. This allows the printer to do “bed leveling” without moving the bed at all.

{{<image src="img/placement.png" alt="Figure 3: All the electronics placed underneath the printer" >}}
Let the wiring commence!

{{<image src="img/routing.png" alt="Figure 4: All the electronics wired together" >}}
Most time-intensive part of the project done! Doing all the wiring by hand probably took ten hours since I labeled every wire and kept them as tidy as possible. The result is fairly clean and professional. This was my first experience with mains voltages, but after watching about a dozen hours of videos discussing different electric systems, I felt confident enough to wire everything together safely.

{{<image src="img/mother_hen.png" alt="Figure 5: Voron Afterburner Toolhead with First Print" >}}
Like a mother hen looking over her chicks, the Voron tool head proudly watches over its first completed parts. Metaphors aside, configuring the firmware was surprisingly easy. The Klipper project has pretty good documentation and the Voron presets were very good. 

{{<image src="img/first_print.png" alt="Figure 6: First Print" >}}
This was an ambitious first print. Although, as I mentioned in the beginning, the goal of every 3D printer is to print more 3D printer parts. These tabs, were some of the final pieces that I needed to attach the side paneling to the printer. 


## Some thoughts about the Voron Experience
{{<image src="img/cad.png" alt="Figure -1: Voron CAD file" >}}

Overall, the build process went smoothly. Between the official documentation, YouTube videos from people that have built Vorons in the past, and their discord community, I was able to fit all the components together, wire everything without any electrical failures, including 120V mains, and configure the Klipper firmware in ~30 hours of work. The Voron bill of materials can be a little bit overwhelming (100 components sourced from a variety of vendors), but most people seem to buy kits to reduce the tedium of the process. This approach is roundly discouraged by the Voron dev-team (“if it isn’t our BOM, it isn’t a Voron”-type mentality). But in my experience, replacing one or two parts is worth it for the convenience. The official documentation was pretty good, but omitted a few steps I only discovered later. The CAD model of the printer is very good and could almost replace the official documentation. 

The dimensions of the printer that I built was 250mm X 250mm which is the smallest size that Voron offers. The larger dimensions are more popular, but there are a few reasons why I didn’t build a larger printer. The first reason is that I can’t think of many parts that I would print that an extra 10cm would help with. The second reason is that the printing failure rate scales with the volume of the printed part. So even if the part is only 40% bigger, the print is almost 3X more likely to fail. The third reason is that part of the reason why coreXY machines are better than bed slingers is that the moving parts are light and thus can move faster. When using a larger build volume, the gantry becomes heavier and thus the maximum speed is slower. Lastly, I live in a small apartment. A bigger build volume means less space for me. That being said, fitting all the electronics underneath the printer was a pain with the smaller working dimensions.