# Smart Mirror
This repository is the framework and modules for my own personal smart mirror.

## Features
**Screensaver**  
The screensaver is going to manage two separate concerns of mine with this project. First, is burn-in. I really hate seeing the past seered into the screen. It just screams of laziness and neglect. Secondly, is that is going to be featured/mounted just outside of the kitchen, thus being seen by guests in the home. 

My idea is to adapt a "timeout" feature similar to conference booth displays I've done in the past. After 3-5mins, a 10 second prompt will ask if you are still engaged with the mirror, if not it will take you back to the screensaver. In this case, a series of family photos that it will cycle through.

**Calendar**  
This seems like a no brainer. My wife and I maintain shared Google calendars that list everything from doctor's appointments for the family, pay weeks, days off, bills due, etc. All color coordinated for quick view. As I am looking to have this be a touch panel mirror as well, I will look to build some CRUD controls as well as just a view, but they will probably come in a later iteration.

**Weather**  
Another obvious addition. However, I feel like this feature will be something that evolves over time. Initially, it will be the basic current weather and a 5-10 day forecast. From there, it can take on more of the [windy.com](https://www.windy.com/?39.938,-74.795,11) features. In future interiations, I would like it to link up with the calendar and travel plans and provide addition weather for destinations of vacations automatically, without the manual addition.

**Traffic**   
There are two parts to this feature that I would like to have. Obviously, travel times to work, as I have to take I-95 to work, which is *always* under construction, and people just drive like assholes, it's basically a guarentee that there will be some kind of congestion due to construction, or an accident. I also have to cross a draw bridge. Luckily they have a text system that sends out alerts anywhere from 15-45mins in advance. Pending accessibility to an API, I would want to pull those alerts into the mirror.

**News**  
Description needed...

**Shopping Lists**  
Description needed...

**Basic Reminders**   
Description needed...

**Finances**   
Fiat and Crypto currencies. Description needed...  

**Smart Home**   
- **Thermostats & Zones**  
Description needed...
- **Smoke/CO2 Dectors**    
Description needed...
- **Front Door**  
Description needed...
- **Garage Door**  
Description needed...
- **Cameras**  
Description needed...
- **Lights & Fans**  
Description needed...
- **Sprinkler System**  
Description needed...


**Touch Enabled**   
Description needed...

**Voice Enabled**
- **Alexa**   
Description needed...
- **Google Assistant**   
Description needed...

**Video Call**  
Description needed...

## PARTS
- **LED TV**   
I ideally don't want to spend a lot of money on something that I'm going to be stripping down. Also size is an issue, I can't go bigger than a 24" and have enough room for the frame and not have it hanging over the sides of the wall. 
  - [VIZIO D-Series D24F-F1 - 24" LED Smart TV](https://www.amazon.com/VIZIO-SmartCast-Class-Certified-Refurbished/dp/B078Z1DYD9): $140 refurb
  - [LG 22LJ4540 22in Class Full HD IPS LED TV](https://www.ebay.com/itm/LG-22LJ4540-22in-Class-Full-HD-IPS-LED-TV/172789253991): $119 refurb
- **2-way mirror**   
I'm probably going to go with the VanityVision glass from [Two Way Mirrors](https://www.twowaymirrors.com/smart-mirror/). Mostly becuase it just takes the thinking out of this part. *These options are with 1/4" non-tempered glass, and sanded edges.*    
  - With the Vizio D24F-F1 24", the glass will cost: $101.60    
  - With the LG 22LJ4540 22", the glass will cost: $86.81    
- **Touch Overlay**     
While TWM offers suggestions for various touch overlays, all the options they recommend don't provide solutions for smaller than 32". I found myself on [Alibaba](https://www.alibaba.com/) getting decent results with a various range of sizes.  
- **Raspberry Pi**   
I have a Raspberry Pi 3 Model B already, waiting to get set up.  
- **Frame**  
I suppose that this will be the hardest part, as I don't have any wood working tools, and I doubt I am going to find a frame that will just work. Luckily, I have some carpenter connections that I might be able to get someone to make a custom frame for this project.  
