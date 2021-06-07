# <Homework Week 1: Code-Refactor>

This assignment asked us to refactor existing code to keep the main functionality, while cleaning up errors and consolidate styles in css. I was motivated to understand what it means to take existing code and clean it up without changing the functionality of the website. 

The first thing I did was open up the html in a browser and looked through the code to see what worked, and what didn't. I noticed some links that didn't function properly, the title was undefined, and also noticed that the images were missing the alt text. 

From there I made a To Do list I started by making sure the images contained alt text so as to meet accessibility standards. Then added a concise and descriptive title. 

After that I checked the broken link on the "search-engine-optimization" href in the nav bar. I noticed that the div containing the seacrh-engine-optimization information was missing an id, which meant the href link would not jump to that section of the page when clicked. I added to id, which solved the issue. 

Next, I focused on the header that was functioning as the nav bar. Because it is a functionaly a navigation bar on the page, I changed the div to nav and then went into the css stylesheet and updated the corresponding sections to reflect the change from div to nav. 

Next I looked at the h1-h6 headers. I noticed that these headers were not in the right order, so I updated them to flow correctly. I changed the headers of each section to I also had to go into the css file and update the styles to match the changes made in the index.html. 

After digging through the index.html, I moved on to the the css styles. I noticed that each of the of the headings in the Benefits section had their own saection in the css file, but the styles were the same for each. I consolidated them into 1 section to get rid of the excess code. 

While looking through the css stylesheet I noticed some issue between the code and the mockup we were given. I changed the text color in the .benefits container from black to white, and changed the margins so there was a defined space between each sub section of benefits (I added a larger bottom margin to the .p section). I also chaged the margin on the images in the benefits section to make the spacing look better. 

I also reorganized the order of the styles in the css file to follow the structure of the html code. This should make it easier to adjust styles because it is organized the same way. 

The problem solved by this project is: 
1). It makes the website meet accessibility standards.
2). It cleans up the existing code to follow semantic html best practices.
3). Fixes sections of broken code.
4). Cololidates and reorganizes the CSS stylesheet to follow the structure of the html index.

In this project I learned how to examine existing code and look for broken code and code that does not follow semantic html. I also learned the value of having a css stylesheet that follows the structure of the html index, which makes changing styles a lot easier to navigate. I also learned how to apply the css lessons from the past week of bootcamp classes and integrate them into this project (specifically when consoildating code). 