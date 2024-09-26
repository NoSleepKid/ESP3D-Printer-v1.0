# ESP3D-Printer-v1.0

## OVERVIEW (OR "WHY THIS PRINTER IS COOLER THAN YOUR EX")
Welcome to **ESP3D-Printer-v1.0**, my **still-in-progress**, Wi-Fi-powered **3D printing masterpiece** that’s not ready for the masses—**yet**. This isn’t your average, run-of-the-mill 3D printer controller; no sir. This one was **built from scratch**, designed to work only with **Tevo Tarantula G-code files** (because why not make things more complicated?). It’s powered by the almighty **ESP32**, because I wanted something that would make you feel like a Jedi in a world full of padawans. And no, **nobody else** has tried it yet. It’s so exclusive that **even I am still figuring it out**.

Oh, and **disclaimer**: the printer’s bed is a humble **255x255mm**—so yeah, it’s smaller than your mom. But let’s be real, so is pretty much **everything** else.

## TECHNICAL SPECIFICATIONS (LET'S GEEK OUT)
- **ESP3D Firmware** — This isn’t some firmware I found in the back of a drawer. No, it’s custom **ESP3D firmware** that I personally stitched together, line by glorious line. Why? Because I’m a perfectionist, and open-source is life.
  
- **Wi-Fi Powered** — Yes, **Wi-Fi**. Forget the days of fumbling around with USB cables like it’s 2010. Now you can upload files and monitor your prints remotely, making it easier to blame your bad print on **lag** instead of your setup.
  
- **12V 3A Power Supply** — Like any good piece of tech, it runs on a diet of **12 volts** and **3 amps**. Sure, I could’ve gone bigger, but this is enough juice to keep things chugging along without needing to rewire your house.
  
- **Node MCU ESP32S v1.1** — This bad boy has **Wi-Fi**, **Bluetooth**, and more processing power than most people need to make their morning toast. It’s the brain of this operation, keeping everything running smoothly.
  
- **Tevo Tarantula G-code Parsing** — It’s picky. This firmware **only** parses `.gcode` files for the **Tevo Tarantula**. Other G-codes need not apply unless you like breaking things. It's like a bouncer at a club that only lets in **one** type of file. Sorry, not sorry.
  
- **USB Webcam Support** — If you’re not live-streaming your 3D prints, are you even printing? Connect a USB webcam, sit back with a drink, and watch the magic unfold in real-time. It’s basically **print porn**—but, you know, the kind that’s safe for work. Probably.

- **Belt Powered** — Lead screws? Ha! Those are for amateurs. This baby is **belt-driven** for faster, smoother, and more precise printing. Think of it like a high-end **sports car** compared to your uncle’s station wagon. And who doesn’t love speed and precision?

## SETUP GUIDE (BECAUSE WE ALL NEED HAND-HOLDING SOMETIMES)
Alright, here’s how you put this thing together (once I’ve fully figured it out, that is). For now, you’re trusting **me**, and trust me, I’ve definitely got some experience in 3D printing… well, maybe a bit too much.

1. **Step One:** Flash the **ESP3D firmware** onto the **Node MCU ESP32S v1.1**. If you don’t know how to do that, you might want to sit down and spend the next few hours falling into an endless loop of **YouTube tutorials** and **forum posts**. Welcome to the rabbit hole.
   
2. **Step Two:** Connect the printer to **Wi-Fi** because physical cables are **so last decade**. Once connected, just imagine yourself controlling prints from anywhere—your couch, your bed, even the **bathroom** (because let’s be real, we all do it).
   
3. **Step Three:** Set up a **USB webcam** to watch your prints in action. There’s nothing like **live-streaming** your own genius, right? Plus, it gives you something to stare at while your print slowly becomes a masterpiece.
   
4. **Step Four:** Plug in that **12V 3A power supply** like a **boss**. We didn’t go full nuclear on the power because, well, **this printer isn’t a death machine** (but you never know—improper wiring might get exciting).
   
5. **Step Five:** Load up some **Tevo Tarantula G-code** files. Don’t try to feed it some random stuff from Thingiverse. This printer has standards, okay? Only **Tevo Tarantula-approved G-code** allowed. It’s basically the fine dining of G-codes.

## WHAT YOU GET TO BRAG ABOUT (AS IF THIS NEEDS MORE COOL POINTS)
- **ESP3D Firmware** — A niche, nerdy firmware that **nobody else has tried**, because you’re on the bleeding edge of innovation. When you flash it, you're **literally** pioneering something fresh.
  
- **Wi-Fi Connectivity** — No more tripping over USB cables. You can tell everyone you’re running your 3D printer from **the cloud** (because it sounds fancier than it actually is).
  
- **USB Webcam Streaming** — Why wait next to your printer when you can stare at it from the **comfort of your bathroom**? Yes, this is the future. Plus, you can brag about watching your prints live in 4K (or whatever quality your webcam can handle).
  
- **Belt Driven** — Flex on your friends with lead-screw setups. Belts mean speed and precision, and let’s face it, speed wins. **Sorry, not sorry.**

## YOUTUBE TUTORIAL (BECAUSE WE KNOW YOU NEED VISUALS)
If this text-based walkthrough isn’t doing it for you, don’t worry—I made a video. It’s on my YouTube channel, **[@NoSleepKid1](https://www.youtube.com/@NoSleepKid1)**. I walk through everything from flashing firmware to wiring up the motors. 

**Pro tip:** I may or may not say a few curse words when things go wrong, but hey, that’s part of the experience. Don’t forget to like, subscribe, and hit that notification bell—because we both know you want more **ESP32 nerdery** in your life.

## LICENSE (OR LACK THEREOF, BECAUSE I’M NOT A LAWYER)
No fancy licenses here. This isn’t under **MIT** or **GPL** or any other legal mumbo jumbo. **Do what you want with it.** Fork it, clone it, hack it, break it, fix it, or just stare at the code in awe of my brilliance. Just don’t ask me for a refund if things go south. This isn’t Amazon.

## DISCLAIMERS (FOR LEGAL REASONS, OBVIOUSLY)
- **This printer is still being developed**, and you’re looking at a prototype. I’m the **only one who’s tested it** so far, and it works for me… most of the time. If it doesn’t work for you, congrats—you’ve joined the beta testing team.
  
- The print bed is **255x255mm**, so your giant dreams (or your mom) might not fit on it. Sorry, **she’s just too big**. But hey, **small is efficient**, and **it’s what you do with the printer that counts**, right?
  
- If your print starts smoking, making weird noises, or **twerking** on the table, stop and double-check your wiring. And maybe grab a fire extinguisher, just in case. **I am not responsible** for your smoke alarms going off.

---

Welcome to the future of **Wi-Fi-enabled 3D printing**, where **everything’s nerdy** and the printer bed might be small, but the possibilities are **endless**.
