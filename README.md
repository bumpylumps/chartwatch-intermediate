# ChartWatch Intermediate
This is a static site built for ThinkMD. It consumes data from the itunes top 100 charts RSS feed. It imports information from the current top 100 albums on itunes and displays their covers, their titles, and the artists that made them. It is also a front end application that utilizes Angular, alongside some animations with Sass to make it more interesting to look at. 

**A demo is available here:** https://bumpylumps.github.io/chartwatch-intermediate/

![picture of landing page for Chartwatch Intermediate](https://res.cloudinary.com/bumpsites/image/upload/v1673290414/intermediatePic_osrtqq.jpg)

## How It's Made:

**Tech used:** HTML, Angular, Sass, Typescript

Chartwatch Intermediate is a front end application that utilizes Angular and Typescript as a front end and Sass(.sass) for styles. It consumes data from the itunes top 100 rss feed which is supplied by the album.service in it's src/app directory.     

## Optimizations

I didn't want this technical exercise to take longer than a reasonable amount of time to deliver, but if I gave myself more time with it I would update the chart display with some more interactivity. Giving the user the option to click on specific albums in order to get their track listings, or links to their shop page on itunes would be interesting to build. I would also make it full stack and offer different sources for the top 100 chart for users to choose from (i.e. Spotify's top 100, soundcloud's, bandcamps, etc.). It would be interesting to see which albums are popular on each one, and elevate the application from a basic display to something more interesting for the user to interact with. Adding a backend would also allow me to embed the rss feed (as if it were an API key) so that it's not constantly being exposed by the browser, and utilize a schema to more easily organize the data being consumed. Right now the data returned from the RSS feed is organized by a map function in the app's service, which does not feel like best practices, but allows for organizing the data without a server or controllers.  

## Lessons Learned:

This was my first exposure to working with Typescript and Angular as an alternative to previous experience with React. I wanted to test my learning skills, and break out of my comfort zone code-wise. Getting more familiar with Typescript also helped me better understand strict typing and error handling with a compiled language. It also helped me better understand some of the quirks I had run into with Javascript and the silent errors it normally lets through when being parsed. Working with Angular helped me better understand front end frameworks in general, especially with some of the core concepts that are applicable across different ones (i.e. components with React). Finally, working with Sass was also a new experience for me, especially getting used to it's syntax and the way it's organized. I also really enjoyed learning how to utilize loops in Sass in order to make more interesting animations. I wanted to show that I can overcome obstacles when working with new technology that I was unfamiliar with, and learned alot about my own development style in the process. Typescript also helped me get better at googling errors, and Angular taught me how to use better context when sifting through documentation.  

## Related projects:
Different versions of this application were built alongside this project, and a repository of them can be found here: 

**Basic through Bonus projects:** https://github.com/bumpylumps/top-100-thinkMD

I seperated this from the rest of the other versions in order to deliver a clean set of codes for easier review. The repository linked above is more a display of what I built for the other difficulty levels provided by ThinkMD's challenge, where the full scope of the work and it's development timeline is displayed. 




