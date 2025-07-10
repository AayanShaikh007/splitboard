---
title: "splitboard"
author: "@Scalar"
description: "wireless split keyboard"
created_at: "2025-07-09"
---

# Splitboard

## July 9th, 1:17am

Officially begin splitboard. But before that, the project description- splitboard is a hotswappable keyboard that I will be making to address issues in my last keyboard, scalars-keyboard (also on my github profile). 

- Firstly, I completely underestimated the size of the keyboard and what should have been a mid-sized keyboard came out to be bigger than the keyboard i have on my laptop. **Compact form factor is a major element of this project.**
- Next, Ive wanted to try a wireless keyboard design ever since the pico W got bluetooth connectivity. **Wireless connectivity is a must.** Therefore, I need to handle **bluetooth connectivity** and how to **power the board using a battery**. 
- Finally, I want to try a **split keyboard design** for this keyboard for ergonomics.

In my research, I found out about a keyboard called the ergodox. I will aim for a design similar to it, but I intend to add two other unique elements:
- ~~A mini trackpad (similar to a thinkpad)~~ I decided not to add this as the trackball will be take its functionality. 
- A trackball (to navigate menus and 3d softwares). 

I will also try to add some sort of backlight similar to the original.
![image](https://github.com/user-attachments/assets/7e87596d-ba02-42c9-b880-46d6aaa68bcf)


# June 9th, 2:04am
With that out of the way, I will now begin with a rough design from a online configurator. 

Left Half: 38 total switches

![image](https://github.com/user-attachments/assets/526f177f-7a6a-4c26-ae10-44a6ebb58035)

Right half: 32 total switches

![image](https://github.com/user-attachments/assets/b1bf222c-4823-40c3-9060-7f29b7a535fd)

Since the left half is simpler, I will start making the pcb for it. **I will need to make the entire trackball assembly for the right side.**

The microcontroller I chose to work with is a Adafruit Feather nRF52840 Express, because of its bluetooth connectivity and power management / battery charging support. 

