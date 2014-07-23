#### Include an inline screenshot of your codeschool's points from the profile page:

<!-- Modify the Markdown to include your answers. Don't delete the questions! -->

##QUIZ
* Explain which tabs support the following actions and how.
  * Realtime editing of HTML and CSS 
  * Javascript Debugging
  * Performance Optimization 

* What's the quick key for your OS to spawn the Dev Tools inspector?

* Go to http://www.postmachina.com/ and analyze and tweak this nicely designed page.
  * What is the current background color for the page?  (Surprisingly, it's not just black!)
  * Tweak the background color to white.
  * Tweak the height of the side bar that contains the logo.  Shrink it down to 85px.
  * Roll over the navigation links.  When you hover over them, they dissapear.  Let's change the hover color to black instead.
  * Now take a screenshot of your new (and maybe not so improved) design.  It should match this screenshot: http://postimg.org/image/5ak1jkpl5/
  * Upload your own image to the imgs directory in the `1_Chrome_Dev_Tools` directory.  It should match the image above. The last nav link in the image above is black because the mouse was hovering there when the screenshot was taken. Do the same, and don't take a screenshot of your whole desktop, just the browser window. (This is part of the challenge.)

* For the postmachina website, why can't you tweak the color of the text "The most important things are not things"?  Please explain.

* Go to www.ticketswizard.com and analyze the page.  
  * What is the largest image on the website? 
  * Explain how you would find out this information, and list the URL of offending image here and how big it is.

* Test the www.ticketswizard.com website with google's [PageSpeed Insights](http://www.ticketswizard.com/).  (You can also download the chrome plugin).  What is the easiest thing to change to optimize the website?  How many kilobytes of data can be eliminated?

The tab that supports real time editing of HTML and CSS is the elements tab, and you can make changes by navigating through the DOM tree like interface selecting the code and editing as you see fit.  For faster navigation you can right click, and inspect an element and the developer tool will take you to that part of the code right away. You can edit your CSS in the same way under the styles tab by toggling the boxes on and off. To save changes you will then go to to source tab, right click and save as.

The tab that supports  JavaScript Debugging is the console tab, and you can debug by using console log commands. Additionally when you receive an error you can analyze it by clicking on the arrow and it will show you a stack trace where the error began. You will need double click it and it link you to the source tab to view the line where the error occurred.

The tab that supports Performance Optimization is the Network tab, and Page Speed tab. They work by disabling the cache on your computer, then running a diagnostic on how long it takes for your webpage to load up all the resources, and it provides data on what is causing your website to lag. Example are scripts, images, code. Page speed will download the webpage and rate it, then it will provide tweaks to optimize your page load time.



What is the current background color for the page? Hex #0b0f11

For the postmachina website, why can't you tweak the color of the text "The most important things are not things"?  You can't edit the text, because its a gif image.

What is the largest image on the website?  The link below at 316KB. I found this information by disabling my cache and going to the network tab, then refreshing the page and downloading the content again. Then just arrange the content by size.

http://www.ticketswizard.com/Images/Catalog/92624182-c482-4a35-8da2-4fbf2f502e94_Large_Large.png 

What is the easiest thing to change to optimize the website? How many kilobytes of data can be eliminated? They can properly format and compress the images and save  885.9KiB of data.