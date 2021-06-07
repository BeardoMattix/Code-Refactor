# homework-week-1
First homework assignment for bootcamp

This assignment asked us to refactor existing code to keep the main functionality, while cleaning up errors and consolidate styles in css.

The first thing I did was open up the html in a browser and looked through the code to see what worked, and what didn't. I noticed some links that didn't function properly, the title was undefined, and also noticed that the images were missing the alt text. From there I made a To Do list. I started by making sure the images contained alt text so as to meet accessibility standards. Then added a concise and descriptive title. 

After that I checked the broken link on the "search-engine-optimization" href in the nav bar. I noticed that the div containing the seacrh-engine-optimization information was missing an id, which meant the href link would not jump to that section of the page when clicked. I added to id, which solved the issue. 

Next, I focused on the header that was functioning as the nav bar. Because it is a functionaly a navigation bar on the page, I changed the div to nav and then went into the css stylesheet and updated the corresponding sections to reflect the change from div to nav. 

Next I looked at the h1-h6 headers. I noticed that these headers were not in the right order, so I updated them to flow correctly. I also had to go into the css file and update the styles to match the changes made in the index.html. 

After digging through the index.html, I moved on the the css styles. I noticed that each of the of the headings in the Benefits section had their own saection in the css file, but the styles were the same for each. I consolidated them into 1 section to get rid of the excess code. 


