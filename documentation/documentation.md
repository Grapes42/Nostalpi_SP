# Max Dowdall - AS91900
***Conducting a Critical Inquiry to Propose an Electronics Outcome***

## 1. Project Focus
### Problem Brainstorming:
1. Remembering and creating secure passwords.
2. Losing items.
3. Social media being a mindless attention grabber.
4. Modern phones all being owned by large data collecting corporations.
5. Modern phones all being the same glass rectangle, there is no individuality.

### Problem Summary
For my project problem I have decided to focus on a combination of 3, 4, and 5. I will expand on each of the points. 
#### Social Media
Modern social media is designed with the sole intent of keeping you scrolling for as long as possible to gather information about you. I, as well as so many others find it far too easy to pickup their phone and just start scrolling. Social media becomes draining and there is no sense of achivement. 

My solution comes from when I discovered the wonderful world of game emulation. When I had some down time and wanted something relaxing to do, whether that be on the bus, in bed, etc, instead of scrolling and achieving nothing, I felt joy from winning a Pokémon battle or finally beating that boss in Castlevania.

Phones work for some games, mostly turn based, but trying to play fast paced games is an absolute nightmare. Creating a device with physical buttons designed for emulation would result in a far superior experience.

#### Data Collecting Corporations
All modern smartphones are software locked down and proprietary, this means you do not have full control over the device and are unable to see what the phone is doing without you knowing. This creates major privacy issues where the company owning your phone is able to do whatever they please with your information. Yes there are legal restrictions, but often these are not enough. It also creates issues where you are unable to do anything if they randomly stop supporting some piece of software, you are at their whim.

My device will run on purely open-source software, these means you have full control over the device and are able to see whatever it may be doing. It creates a much healthier user to software relationship, respecting you as a consumer.

#### Lack Of Individuality
Modern smartphone have very much converged to a standard design, a thin glass brick. While this definitly helps with industry standardisation, it removes all individuality. I much personally prefer the innovative and charming phones of the early 2000s:
|<img src="images/rotating_vodafone.jpg" alt="gba" width="300"/>|<img src="images/t_mobile.jpg" alt="gba" width="300"/>|
|-|-|
|<img src="images/nokia_7280.jpg" alt="gba" width="300"/>|<img src="images/nokia_7600.jpg" alt="gba" width="300"/>|
|<img src="images/siemens.jpg" alt="gba" width="300"/>|<img src="images/nokia_ngage.jpg" alt="gba" width="300"/>|

## 2. Inquiry Questions
- What are common games people emulate? What controls will my device need? How powerful will it need to be?
- What connections/ports will I need to add to make this viable for anyone to use and charge? Will it need modern connections like bluetooth, USB-C, etc?
- How will the device last a day of use? What size battery will it need? Will it need a power-saving mode?
- How will the device be durable enough for every day use? What materials will it be made of? Will it need waterproofing?
- How will it be comfortable to use? How should the buttons be layed out? What should the screen be like to avoid eye-strain.

## 3. Milestones
The project can start when I have received the parts which should be around the start of September, and it must be completed by the due date 27 September. This gives me ~25 days to complete the physical parts of the project. As I have to wait until the parts arrive, all programming and design should be completed first. 
|Target|Date|
|-|-|
|Design the Schematic|27 August|
|Design the PCB|29 August|
|Programming for the power logic|1st September|
|Install and setup Retropie|5th September|
|Test games|5th September|
|Test on a breadboard|7th September|
|Manufacture PCB|15th September|
|Modify case to allow the PCB to fit well|17th September|
|Solder together parts|19th September|
|Assemble case|20th September|
|Test games and all inputs|21st September|
|Test battery life and charging|22nd September|
|Revise and adjust|25th September|

This gives me 2 days space in case anything required more time.

## 4. Research
The world of handheld devices has now been completely dominated by the smartphone, there are modern devices designed for playing games such as the Nintendo Switch, but this is far too large and pricey for what I want to create. 

Looking back to the early 2000s there are some great examples of pocket handhelds such as:

|Name|Picture|Features|Issues|
|-|-|-|-|
|Nintendo Gameboy Advance|<img src="images/gba.jpg" alt="gba" width="200"/>|<ul><li></li></ul>|
|Sega Game Gear|<img src="images/sega_game_gear.jpg" alt="sega game gear" width="200"/>|
|Nintendo DS|<img src="images/ds.jpg" alt="ds" width="200"/>|

And many others. The one that stands out to me the most is the Nintendo Gameboy Advance SP.

<img src="images/gba_sp.jpg" alt="gba sp" width="400"/>

It features a compact pocket design, which then unfolds into a comfortable handheld device. This clamshell design doubles to protect the screen and buttons.

## 5. Research Analysis  
### The Brain
For the brain of the computer I will need a small singleboard computer as designing an entire motherboard is out of the scope of this project. There are many available options such as:

|Name|Picture|Pros|Cons|
|-|-|-|-|
|Orange Pi 5 Plus|<img src="images/orange_pi.jpg" alt="gba" width="200"/>|<ul><li>Designed for GNU/Linux</li><li>2.4GHz 8-core CPU with 16GB ram (Very fast)</li><li>Built in USB-C, HDMI, Power Button, WiFi, Bluetooth, microphone, headphone jack, and speaker connector</li></ul>|<ul><li>Expensive</li><li>Too large to embed</li><li>Will need cooling</li></ul>|[//]: ----------
|Raspberry Pi 4 Model B|<img src="images/pi_4.jpg" alt="gba" width="200"/>|<ul><li>Designed for GNU/Linux</li><li>1.8GHz Quad-core CPU (Fast)</li><li>Multiple choices for amount of RAM 1-8GB</li><li>Built in USB-C, HDMI, USB2$\times$2, USB3$\times$2, Gigabit ethernet, 5GHz Wi-Fi, Bluetooth 5.0</li></ul>|<ul><li>Moderately expensive</li><li>Too large to embed</li></ul>| [//]:----------
|Pi Zero|<img src="images/pi_zero.jpg" alt="gba" width="200"/>|<ul><li>Designed for GNU/Linux</li><li>Super cheap</li><li>Very small</li></ul>|<ul><li>Single core 1GHz CPU with 512MB ram (too slow for a comfortable emulating experience)</li><li>Lack of inbuilt ports and wireless connection</li></ul>| [//]:----------
|Pi Zero 2 W|<img src="images/pi_zero_2.jpg" alt="gba" width="200"/>|<ul><li>Designed for GNU/Linux</li><li>Very cheap (slightly more expensive than the Pi Zero)</li><li>Very small (Same size as the Pi Zero)</li><li>Inbuilt 2.4GHz Wi-FI, Bluetooth 4.2</li></ul>|<ul><li>Lack of inbuilt ports</li></ul>| [//]:----------
|Arduino Pro Portena X8|<img src="images/arduino_portena.jpg" alt="gba" width="200"/>|<ul><li>Designed for GNU/Linux</li><li>9 cores: 4$\times$1.8GHz + Others around 500-400MHz (Fast)</li><li>Very small (Same size as the Pi Zero)</li></ul>|<ul><li>Lack of inbuilt ports</li><li>Very expensive</li></ul>| [//]:----------

I decided to go with the Pi Zero 2 W, as in my opinion it has the best tradeoff between size, performance, cost, adaptability, and functionality.
### The Power Supply
I researched some mobile power options for the Pi Zero:

|Name|Picture|Pros|Cons|
|-|-|-|-|
|Juicebox Zero|<img src="images/juicebox.png" alt="gba" width="200"/>|<ul><li>Easy to use</li><li>All required features built in</li></ul>|<ul><li>Expensive</li><li>Not as compact as other options</li><li>Fixed shape for all parts, so customisation is limited</li></ul>|[//]:----------
|Pisugar 3|<img src="images/pisugar.png" alt="gba" width="200"/>|<ul><li>Easy to use</li><li>All required features, plus some fun and useful other ones</li></ul>|<ul><li>Very expensive</li><li>Tall form factor which wont fit well</li></ul>|[//]:----------
|PowerBoost 1000C|<img src="images/powerboost.png" alt="gba" width="200"/>|<ul><li>Low cost</li><li>Compact</li><li>Customisable form factor which will make it easy to fit</li></ul>|<ul><li>Will require an external circuit</li></ul>|

I decided to go with the PowerBoost 1000C as I believe it has the best tradeoff between cost, size, and functionality.

## 6. Perspectives
To gain better and more diverse perspectives I decided to ask some of my friends to see how they would want to use such a device:
### Me:
#### Games:
- Turn based adventurers like 'Pokémon' and 'Final Fantasy Tactics Advance'
- Platformers fighters like 'Kirby & the Amazing Mirror' and 'Castlevania: Aria of Sorrow'
- Adventure games like 'The Legend of Zelda: The Minish Cap'
- Roguelikes like 'Brogue'

|Castlevania|Final Fantasy Tactics Advance|
|-|-|
|<img src="images/castlevania.jpg" alt="gba" width="300"/>|<img src="images/final_fantasy.jpg" alt="gba" width="300"/>|

#### Form
- Able to be taken everywhere
- Pocket sized
- Used often, requires long battery life

### Holly:
#### Games:
- Turn based adventurers like 'Pokémon'
- Farming games like 'Harvest Moon'
- Platformers like 'Kirby & the Amazing Mirror'

|Harvest Moon|Kirby & the Amazing Mirror|
|-|-|
|<img src="images/harvest_moon.jpg" alt="gba" width="300"/>|<img src="images/kirby_and_the_amazing_mirror.jpg" alt="gba" width="300"/>|

#### Form:
- Able to be taken everywhere
- Pocket or bag size
- Used often, requires long battery life

### Jack:
#### Games:
- Turn based adventurers like 'Pokémon'
- Fighting games like 'Street Fighter'

|Street Fighter|Pokémon Emerald|
|-|-|
|<img src="images/street_fighter.png" alt="gba" width="300"/>|<img src="images/pokemon_emerald.jpg" alt="gba" width="300"/>|

#### Form:
- Able to be taken everywhere
- Pocket sized
- Used often, requires long battery life

### Evaluation
According to my findings: 
- All users would prefer the device to be handheld.
- All users would prefer the device to have a long battery life.
- Users want to play a mix of slow pace/turn based games and fast paced action games.

This means the device must be:
- Compact enough to fit in a pocket
- Comfortable to hold long periods of time
- Large buttons suited for fast pace action
- Large battery for long run time

The challenge will be creating a design that balances these variables well. Too small and it will have a poor battery life and be uncomfortable to use. Too large and it will not be able to fit in your pocket. 

## 7. Critiquing
All my research has been taken from the data sheets from the manufacturer of the product so it is reliable. I have based my opinions off the data, this way my choice will not be swerved by a random person's personal preference.

Though, just a data sheet isn't enough to show whether a product is viable. To provide more info in the real usage of the product, user reviews would be good. I originally stayed away from this, but as long as I fact check the info and compare for and against views, user reviews can be a useful info source.

## 8. Refined Project Focus
Another issue was how clunky these emulators were, I could never trust just turning off my phone without my progress being lost, as often if I'm on the bus and in the middle of a fight I just dont have time to save.

## 9. Future Opportunities
This project, being a recreation of a retro handheld has the opportunity to easily be reshaped into various other handhelds of the time. The Pi Zero is more than capable of running various emulators, it is simply a matter of rearranging the circuit to fit the new form factor.

I would be able to recreate various handheld consoles using the same, or slightly modified circuit. Some popular ones I could recreate are:
- Gameboy/Gameboy Color
- Gameboy Advance
- Sega Game Gear
- Nintendo DS/Nintendo 2DS
- PlayStation Portable

There is also great opportunity to create my own design for handheld consoles in the style of at home consoles. These could be custom modelled and printed to keep elements of the design of the original console, all while compacting it into a handheld experience. Some popular ones of could create are:
- Atari 7800
- NES/SNES
- Commodore 64
- Sega Genesis/Sega Saturn
- Nintendo 64
- Sega Dreamcast
- PlayStation/PlayStation 2
- GameCube

## 10. Proposed Solution
As a kid, I had a great experience playing on my Nintendo 3DS, which unfortunately I no longer have. I want to create a handheld in a similar style to appeal to mine, and others' childhood nostalgia. I have always loved the design and formfactor of the Nintendo Gameboy Advance SP. It features a compact pocket design, which then unfolds into a comfortable handheld device. This clamshell design doubles to protect the screen and buttons. The brains behind the device will be a Raspberry Pi Zero 2 W.

This device is a tiny and low cost 64-bit single board computer, designed to run GNU/Linux, which is my preferred operating system, this one runs a specific distro called Raspian (I refuse to use the rebranded name Raspberry Pi OS). It boasts an impressive quad-core 1GHz CPU and 512MB of SDRAM. That’s otherworldly from the original Nintendo GBA SP’s single core 16MHz and 384Kb of total ram. This will allow a smooth and fast experience playing retro handheld games, as well as any application I implement. It also supports comes with Bluetooth 4.2 and 2.4GHz Wireless LAN, which will allow easy connection to the device, such as connecting Bluetooth headphones, wirelessly transferring games, automated updates, etc.

### Proposed Diagram
<img src="images/gamepi_sp_plans_inside.jpg" alt="gba" width="400"/> <img src="images/gamepi_sp_plans_outside.jpg" alt="gba" width="400"/>

Further decoration and polishing will be added to the case to create a refined outcome.

<img src="images/gamepi_sp_final_proposal.jpg" alt="gba" width="500"/>

## 11. Risks and Mitigations
### Risks
Some risks that may be apparent in implementing the proposed solution include:
- Battery shorts/other issues if the charging circuit has an issue.
- General shorts by parts touching one another.
- Case being too fragile due to removed materials.

### Mitigation
Some ways theses risks can be mitigated are:
- Thoroughly testing the charging circuit with a multimeter, to ensure it works as it should, before connecting a battery.
- Thoroughly testing the PCB and other components' connections with a multimeter to ensure they work as they should, before final assembly.
- Adequate spacing and/or insulation between layers to prevent shorts.
- Carefully removing as little material as possible to fit the parts, and if an area is too thin add reinforcement. The large amount of material will be removed using a rotary tool for the sake of speed, and the final parts will be removed using abrasive paper to ensure a precise fit. Material can be added by gluing small bits of plastic or metal.

## 12. Evaluation


## 13. Learnings and Reflections