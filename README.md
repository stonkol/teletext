# teletext

## Index

1. [Project Direction](#1-project-direction)
2. [Visuals](#2-visuals)
3.
4.
5.

## Project Direction

📺 Teletext on the browser, recreation with news, weather, channel streaming, world map and other easter eggs.

The 21st century teletext. A pixel art project. 
A refined, animated, more easy to use.
Including hot keys. Can be used mouse-less.

*Keep it simple and well categorize* 
All you need for the day to day information take.

Indoor body; outdoor mind

Limit to have only the 100~899 page


### All the knowdledge you can have:

  - **Past Knowledge**: encyclopedia, dictionary, books, recipes, quizzes, maps.
  - **Current Knowledge**: news, radio, tv, newspaper, planes and ships rn on the map.
  - **Future Knowledge**: stocks, weather, horoscope predictions. Public transport (trains) time tables. 

## Visuals

**need to decide**:
- [ ] If the whole page will be text based (ASCII) or text+imgages+svg based
- [ ] Pixel aligned (like the old days) or not

### Design language

70s 80s Pixel art on games and OSs. Of course the teletex

Try some Skeumorphic pixel art. (is that even a thing?)

### Colors
Based on ANSI 16 colors mapping all the visuals.  
For example the top nav bar is `color-3` which is mapped on the the number 3 of the 16 colors map.
So people can easily change themes and even have an inedit light mode.  
also can set light mode to be one theme and dark mode theme.


### Font

Use pixel font?
Although maintaining the original teletext monofont here we will have bold

## Special features

Have sound decode and encode for transferring files.

## What is teletext?
It is a standard for displaying **text** and **rudimentary** graphics on suitably equipped television sets.  
Teletext was created in the United Kingdom in the early 1970s 

<div align="center" display="flex">
<img src="https://teletextart.co.uk/wp-content/uploads/2017/04/ceefax_holidays2.png" width="33%">
<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/36/Antiope_%C3%A0_Moscou-Portail_Tourisme.jpg/640px-Antiope_%C3%A0_Moscou-Portail_Tourisme.jpg" width="33%">
<img src="https://upload.wikimedia.org/wikipedia/commons/4/4b/Teletexnews.png" width="33%">
<img src="https://hackaday.com/wp-content/uploads/2022/01/pi-ceefax-featured.png" width="33%">
<img src="https://e3.365dm.com/16/07/1600x900/ceefax-final-page-1_3694540.jpg?20160706145856" width="33%">
<img src="https://teletext.mb21.co.uk/gallery/world/malaysia/beriteks298.jpg" width="33%">
<img src="https://upload.wikimedia.org/wikipedia/en/1/16/JTES_example.png" width="33%">
<img src="https://teletext.mb21.co.uk/gallery/extra/abroad2.jpg" width="33%">
<img src="https://teletext.mb21.co.uk/gallery/extra/abroad3.jpg" width="33%">
<img src="https://teletext.mb21.co.uk/gallery/extra/abroad4.jpg" width="33%">
<img src="https://hips.hearstapps.com/elleuk.cdnds.net/16/32/640x541/gallery-1470836355-tumblr-n3igb0ekhl1rdyyyuo1-1280.png?resize=1024:*" width="33%">
<img src="https://cached.imagescaler.hbpl.co.uk/resize/scaleHeight/815/cached.offlinehbpl.hbpl.co.uk/news/OMC/Yourparagraphtext(67).png" width="40%">
</div>

### The tech behind
Teletext sends data in the broadcast signal, hidden in the invisible vertical blanking interval area at the top and bottom of the screen.

Graphic coordinates were encoded in multiple 6 bit strings of XY coordinate data, flagged to place them in the printable ASCII range so that they could be transmitted with conventional text transmission techniques. ASCII SI/SO characters were used to differentiate the text from graphic portions of a transmitted "page".

### Bonus

Another tech wirth to mention is **Videotex**, an interactive information service that worked over telephone lines, enabling users to request and receive specific content from a central database. Videotex systems used a terminal or modified TV connected to a modem. Users navigated menus using a keyboard or remote, sending requests via a dial-up connection to a server, which then sent back the requested information.

| Feature           | Teletext                          | Videotex                             |
|------------------|-----------------------------------|--------------------------------------|
| Communication    | One-way (broadcast)               | Two-way (interactive)               |
| Transmission     | Via TV signal                     | Via telephone line (dial-up)        |
| Interactivity    | Limited (page navigation)         | Fully interactive (menu-driven)     |
| Graphics         | Basic blocky graphics             | Character-based graphics             |
| Use case         | TV info pages, subtitles          | Online services: shopping, booking, messaging |
| Popular example  | Ceefax (UK), ORF Teletext (Austria)| Minitel (France), Prestel (UK)      |

Also shout out to [**JTES**](https://en.wikipedia.org/wiki/JTES) (Japanese Teletext Specification). It supports the display of Kanji, Katakana and Hiragana characters. The service can be used to display subtitles, cyclic text pages or pseudo interactive programs. There's support for presentation of photographs, geometry or sound. Because Japanese characters are different from the western alphabets, therefore they developed their own transmissions method, called *"pattern method"*, it sends scanning signals similar to a fax, at a rate 20 times faster than existing methods.

## Important words

Keep calm, be patient.
Do it everyday and have fun.
