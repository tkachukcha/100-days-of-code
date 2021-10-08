# 32/100 Days Of Code - Log

### Day 32: October 8 2021
##### Project 3: Surf Forecast Data Scraper

**Today's Progress**: 
Playing with array I get off third site and using regexps to get needed data. Working little bit slow at the moment. 

**Things learned**: 
- New regexp tokens

**Link to repo:** [Web scraper](https://github.com/tkachukcha/MSW_WebScraper)


### Day 31: October 7 2021
##### Project 3: Surf Forecast Data Scraper

**Today's Progress**: 
Started figuring out how to get data off the third website. For that I use puppeeter package which runs headless browser to get the info.

**Things learned**: 
- Basics of Puppeteer tool

**Link to repo:** [Web scraper](https://github.com/tkachukcha/MSW_WebScraper)

### Day 30: October 6 2021
##### Project 3: Surf Forecast Data Scraper

**Today's Progress**: 
Fuck yes. I've made it! Now when I start script new data is written to markdown file in nice formatted way. If there were no problem with third site scraping, project would have been finished by now. But, I still has to figure out how to extract data from third site. And also I need to write surf spot name

**Things learned**: 
- Appending new data to start of file
- Markdown (GFM) tables syntax

**Link to repo:** [Web scraper](https://github.com/tkachukcha/MSW_WebScraper)

### Day 29: October 5 2021
##### Project 3: Surf Forecast Data Scraper

**Today's Progress**: 
Okay, coming to an almost end, just need to output date to MD file

**Things learned**: 
- FS module writeStream
- MarkDown syntax basics

**Link to repo:** [Web scraper](https://github.com/tkachukcha/MSW_WebScraper)

### Day 28: October 4 2021
##### Project 3: Surf Forecast Data Scraper

**Today's Progress**: 
Short session as tomorrow is a long day. 

**Things learned**: 
- Basics of PUG

### Day 27: October 3 2021
##### Project 3: Surf Forecast Data Scraper

**Today's Progress**: 
Shortened code a bit, changed structure of objects, went to third site and found out that I cannot extract data off there somehow

**Things learned**: 
- There is some way to hide a code from cheerio

**Link to repo:** [Web scraper](https://github.com/tkachukcha/MSW_WebScraper)

### Day 26: October 2 2021
##### Project 3: Surf Forecast Data Scraper

**Today's Progress**: 
Now data is for tomorrow. And I formatted output from Surf Forecast. Also got angle and letters for MSW swell directions out of single string. Code is a real mess, needs cleaning. 

**Things learned**: 
- Slice method
- Practical use of regex

**Link to repo:** [Web scraper](https://github.com/tkachukcha/MSW_WebScraper)

### Day 25: October 1 2021
##### Project 3: Surf Forecast Data Scraper

**Today's Progress**: 
Been figuring out how to delete null element out of array with objects and changing angle property inside the swell objects. Started to restructure outputted object in order data from both websites would be uniform. 

**Things learned**: 
- Splice method

**Link to repo:** [Web scraper](https://github.com/tkachukcha/MSW_WebScraper)

### Day 24: September 30 2021
##### Project 3: Surf Forecast Data Scraper

**Today's Progress**: 
Added energy and started getting swell foreast from second site. And it's so much easier that previous!

**Things learned**: 
- Getting element's data attribute value using cheerio

**Link to repo:** [Web scraper](https://github.com/tkachukcha/MSW_WebScraper)

### Day 23: September 29 2021
##### Project 3: Surf Forecast Data Scraper

**Today's Progress**: 
Added tides and bit of formatting to console output. Finished with one website, started figuring out next one.

**Things learned**: 
- How to use "\n" symbol
- PUsing variable as a key of object

**Link to repo:** [Web scraper](https://github.com/tkachukcha/MSW_WebScraper)

### Day 22: September 28 2021
##### Project 3: Surf Forecast Data Scraper

**Today's Progress**: 
Found the simplest way to work with data table on targeted website and as a result - I got data about all three swells. Now I can move on to get data for tides and to get data from other website.

**Things learned**: 
- Gotta find the easiest workaround - it's the best most of the time 

**Link to repo:** [Web scraper](https://github.com/tkachukcha/MSW_WebScraper)

### Day 21: September 27 2021
##### Project 3: Surf Forecast Data Scraper

**Today's Progress**: 
Went back to my code as with my friends code I was only reading documentation, but not actually coding. 
I extracted data from get request into JSON file and read it outside of the promise so now I can use this data to actually post it on web page by myself. 

**Things learned**: 
- Read and write JSON file with data. Using it in project. 

**Thoughts**:
- The main problem that this project take too long (apart I'm not working for more than 1 hour a day on it) is difficult structure of targeted web page... it's actually a pain the ass to get needed data. 

**Link to repo:** [Web scraper](https://github.com/tkachukcha/MSW_WebScraper)

### Day 20: September 26 2021
##### Project 3: Surf Forecast Data Scraper

**Today's Progress**: 
Went back to my code. Structuring output and figuring out how to get the data off the targeted website. I can foresee a lot of problems to solve in the closest future...

**Things learned**: 
Gotta be well rested to code properly

### Day 19: September 25 2021
##### Project 3: Surf Forecast Data Scraper

**Today's Progress**: 
My friend check my code and did everything in a proper way through using nodejs server and pug processor. My progress is that I made his code work on my system with typescript and other packages. And then I checked his code trying to understand, how it works. Seems okay, but still so much to learn. My had is gonna blow up.

**Things learned**: 
- Typescript configuration and basics
- Pug preprocessor. First glance
- Express JS first glance
- Starting my own nodejs server

**Thoughts**: Harder than I thought. But there is nothing that I cannot learn.


### Day 18: September 24 2021
##### Project 3: Surf Forecast Data Scraper

**Today's Progress**: 
Today I was trying to figure out the structure on needed output of scraper and started to make it in the object I'm getting off the page. Still not much of a progress

**Things learned**: 
- string.split method 
- the use of regular expression with split method

**Thoughts**: Getting used to working with data, bot with visual objects, as I'm used to

### Day 17: September 23 2021
##### Project 3: Surf Forecast Data Scraper

**Today's Progress**: 
Not much, trying to figure out how to work with cheerio and axios packages. Have been reading references and playing with code a bit

**Things learned**: 
- How cheerio can be used
- Get method of axios

### Day 16: September 22 2021
##### Project 3: Web Scraper

Started new project - web scraper - which is completely new for me. I didnt know anything about scrapers before except what you can use them for. 
I wished long time ago to code my own web scraper which would extract surf forecast data to markdown file. And I'm so exciting that I extracted my first data!!! 

**Today's Progress**: 
- Done my first data extraction from website!
- Exctracting data to an object and looking through it in console. But it's so amazing!

**Things learned**: 
- Getting my first try with Node.Js, as well as cheerio and axios packages

**Thoughts**: This is so exciting!!!

**Link to repo:** [Web scraper](https://github.com/tkachukcha/MSW_WebScraper)

### Day 15: September 21 2021
##### Project 2: JS Clock

**Today's Progress**: 
- Changed style of digital clock

**Thoughts**: Styling takes too much time, I'd better focus on coding JS 

**Link to project:** [JS Clock](https://tkachukcha.github.io/JS-Clock/)

### Day 14: September 20 2021
##### Project 2: JS Clock

**Today's Progress**: 
- Analog clock fully functional. Just need to add some styling

**Things learned**: 
- GitHub Pages - it's so amazing and easy!

### Day 13: September 19 2021
##### Project 2: JS Clock

**Today's Progress**: 
- Made code nice and clean. Added few functions to shorten code. Changed names of functions to follow JS naming convention
- Started making analog clock
- Added dynamically generated seconds marks on clock face
- Seconds arrow is alive!

**Things learned**: 
- How to organize code
- Relearned naming conventions for functions
- Using several transform properties at once

**Thoughts**: 
- Now I can see that code is really a poetry. Mine maybe not as good as can be, but I'm trying hard :)
- More I code, more gettin into it. S O  M U C H  F U N !!!

### Day 12: September 18 2021
##### Project 2: JS Clock

Cheat day. Was away from home and my laptop so couldnt actually code, but I installed programming keyboard and JS code editor (SPCK - which is really nice actually, you can even use git there). From my phone I played little bit with regular expressions - yesterday watched tutorial and today tried different variations and methods. 

**Today's Progress**: 
- No progress in project. But tomorrow will give more focus and time to my project! Wanna make analog clock!

**Things learned**: 
- Started understanding regular expressions

**Thoughts**: Gotta sleep more not to oversleep mornings to code... 

### Day 11: September 17 2021
##### Project 2: JS Clock

**Today's Progress**: 
- am/pm mode added
- User preferences of dark and am/pm modes are now stored in localStorage and dont reset on page reload

**Things learned**: 
- Local storage usage

**Thoughts**: Finding something new everyday is so much fun. Love this challenge!

**Link to repo:** [JS Clock](https://github.com/tkachukcha/JS-Clock)

### Day 10: September 16 2021
##### Project 2: JS Clock

**Today's Progress**: 
- Yesterday later in the evening I added dark mode button, today I added animation for it and functionality. 
- Also started implementing switching between Am/Pm and 24H modes

**Things learned**: 
- Learned how to make switch button using css and ::after pseudo-element

**Link to repo:** [JS Clock](https://github.com/tkachukcha/JS-Clock)

### Day 9: September 15 2021
##### Project 2: JS Clock

**Today's Progress**: 
- Refuse to use Tailwind, seems to be confusing. Cannot understand why it's better than pure CSS. HTML looks messy and with few similar elements it takes much more time to customize same looking elements. Glad that I have only 3 of them
- Spent half an hour to trying stylize my elements with tailwind, but after I erased everything and rewrote styles with pure css. 

**Things learned**: 
- Tailwind is not easy and should be used for particular projects. Or is there anything that I'm missing?

**Link to repo:** [JS Clock](https://github.com/tkachukcha/JS-Clock)

### Day 8: September 14 2021
##### Project 2: JS Clock

**Today's Progress**: 
- Added some style (need to improve)
- Added basic functionality - clocks show local time now

**Things learned**: 
- Setting up and basic use of TailwindCSS
- Working with Date object

**Thoughts:** 
- Wish I had design skill... 

**Link to repo:** [JS Clock](https://github.com/tkachukcha/JS-Clock)


### Day 7: September 13 2021
##### Project 1: Rock Scissors Paper Lizard Spock

**Today's Progress**: 
- Added GUI for scores, added reset scores button
- Removed bug with double clicking
- Game is finished now

**Things learned**: 
- One of the ways to restrict clicking button many times
- How to use .gitgnore file

**Thoughts:** 
- Wondering what will I say looking at this code in one year from now?

**Link to game:** [Rock Scissors Paper Lizard Spock Game](http://dan-tkachuk.com/RSPLS/)
**Link to repo:** [Rock Scissors Paper Lizard Spock Repo](https://github.com/tkachukcha/rock-lizard-spock)


### Day 6: September 12 2021
##### Project 1: Rock Scissors Paper Lizard Spock

**Today's Progress**: 
- Removed arrow creating functions and instead added arrow class
- Removed separate helpers

**Things learned**: 
- Static class methods

**Thoughts:** 
- How to figure out when project is ready?

**Link to work:** [Rock Scissors Paper Lizard Spock Game](https://github.com/tkachukcha/rock-lizard-spock)


### Day 5: September 11, 2021
##### Project 1: Rock Scissors Paper Lizard Spock

**Today's Progress**: 
- Added border color changes on win or lose
- Cleaned code a little bit.

**Things learned**: 
- figuring out "this" context little bit more

**Thoughts:** 
- Tomorrow is a trip day, no chance to code, therefore done today 1 hour more.

**Link to work:** [Rock Scissors Paper Lizard Spock Game](https://github.com/tkachukcha/rock-lizard-spock)


### Day 4: September 10, 2021
##### Project 1: Rock Scissors Paper Lizard Spock

**Today's Progress**: 
- Added computer animation and simple text with result. Still have some bugs, like everything brakes down if you click figure two times.

**Things learned**: 
- Learned @keyframes css animations. Simple and fun

**Thoughts:** 
- Coding part was easy and fast, but GUI will take some time for sure.
- Understood, that even such a simple app can be improved, you could add new functionality, write better, more effective code, tune GUI and so on. 

**Link to work:** [Rock Scissors Paper Lizard Spock Game](https://github.com/tkachukcha/rock-lizard-spock)

### Day 3: September 9, 2021
##### Project 1: Rock Scissors Paper Lizard Spock

**Today's Progress**: Now game is playable, although at the moment winner is announced in console. Added graphics of computer "deciding" his choice. 

Things learned: 
- Used timeouts functions by myself for the first time. Maybe can rewrite this part of code to use promises
- Found out that you cannot use array.include method to check if there's array or object inside of main array

**Thoughts:** Looks like that  my unconsious mind has been working a lot since yesterday to figure out game logic, because the solution came to my mind right after I started to code today.

**Link to work:** [Rock Scissors Paper Lizard Spock Game](https://github.com/tkachukcha/rock-lizard-spock)


### Day 2: September 8, 2021
##### Project 1: Rock Scissors Paper Lizard Spock

**Today's Progress**: Still trying to figure out game logic. Tested few things, added few useful functions/

Things learned: 
You cannot use object property "name" to find index of that object with the same name. This.name not working. But this - does!

**Thoughts:** To solve a problem sometimes you gotta stop trying to do this and do something different

**Link to work:** [Rock Scissors Paper Lizard Spock Game](https://github.com/tkachukcha/rock-lizard-spock)

### Day 1: September 7, 2021
##### Project 1: Rock Scissors Paper Lizard Spock

**Today's Progress**: I started this project month ago, but worked on it for only 4 hours, after I had working project that I had to deal with, so I postponed working on this project. 
Therefore, today I checked my code and found out that I can make it better. 
So I added few functions to shorten code, added new Class, and at the moment trying to figure out how to compare two choices of player and computer. 

Things learned: 
- how to pass function name as a string
- getting used to OOP
- mergin stash with main branch in git

**Thoughts:** I sat, started to code, and BAM, two and half hours gone in a click. Oh how I love to code!

**Link to work:** [Rock Scissors Paper Lizard Spock Game](https://github.com/tkachukcha/rock-lizard-spock)

### Day 0: September 6, 2021

**Today's Progress**: Planned which projects gonna work on at first

Projects: 
1. Rock Scissors Paper Lizard Spock Game
2. JS Clock
3. Web Scraper



