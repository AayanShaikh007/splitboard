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

# June 20th- 3 hours spent
I had to take a break from the project due to undercity. Today, I worked with other hack clubbers to collectively finish/work on our keyboards. I took the opportunity to finalize a Kicad schematic and gather all required footprints for the project. 

<img width="1143" height="799" alt="image" src="https://github.com/user-attachments/assets/28ab90f5-3c64-4b94-a52f-cedce50648a0" />
Schematic for splitboard left. 

With this done, I will now work on the PCB of the board. 

# June 21st- 2 hours spent
Today, I decided to begin the PCB design of the board. I spent around 2 hours arranging the keyswitch footprints to their correct locations. Kicad was acting funny again just like with the last keyboard. Tomorrow I will arrange the LEDs and do the same with the splitboard right. I am also thinking about removing the trackball from the keyboard and making it into its own entity (a seperate pcb). I will focus on this later. 

<img width="944" height="598" alt="image" src="https://github.com/user-attachments/assets/85d6c529-1091-4e72-b9f1-ae0ffa22c931" />

# June 22nd
