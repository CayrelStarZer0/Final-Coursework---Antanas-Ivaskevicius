This is the final coursework project of Antanas Ivaškevičius.

Idea/Purpose

The main idea of this website is to become a central hub to a network of Youtube accounts and Twitter/Facebook pages I've made as a content creator. Since managing all the accounts is quite bothersome, and in terms of advertising very inefficient, I've decided to create a website that would join all my current Youtube accounts, as well as social media pages into one place, from which I'd then could manage and advertise said pages. 


Website is mostly HTML/CSS based, with some basic Javascript functionality, for example, the menu on responsive version of the site is
functioning on few Javascript scripts. Since I don't know Javascript very well, I tried to do as much as possible using CSS, including animations and transfer effects.

Main idea for design was minimalistic functionality, with additional intention of site being easy on the eyes and not irritating with colors and flashing lights and whatnot, so entirety of the site has scrollable dark charcoal texture background, as well as black navbar and footer. Fonts in most places are white, for maximum contrast and readability. 
Few colors that were used on site were used as accents on certain elements, and also as hover on links/navbar items, to make navigation easier.
Across all pages the Menu navigation and Footer are the same, carried over from original file. Menu navigation features drop-down menus to make accessing different pages easier and faster. 
Footer has clickable links to social media pages, as well as Youtube main page.

Homepage also features 4 clickable animated cards, that also direct to social media pages. They were made using CSS Cards feature.

Blog page has manually written blog entries, at the moment just to fill up the page. Nothing fancy, just h1/h1/p elements.

Music page has a selection of videos, and uses jQuery to achieve Masonry-ish layout effect for the videos. 

Art-> Picture Gallery page uses different jQuery to get Masonry layout effect, somewhat inspired by the Masonry layout of Pinterest.
Actual goal for the Picture Gallery was to make it as similar to Pinterest as possible, as I find Pinterest layout to be quite efficient and aesthetically pleasing.

Aside from said pages, there isn't more content on the website at the moment, due to lack of time as a result of various issues.


Challenges/Problems

The main challenge was to integrate the Masonry layout to Music/Art pages. It took entirely way too long, and due to page being completely custom and not based on any boostrap, it was a real headache to adjust jQuery files and certain settings to work with the current pages. Most of the time was wasted on debugging and firetesting the functionality of the pages, which resulted in lack of time to produce more content for the website.
There was an option to not use Masonry layout and use just regular Flexbox or CSS Grid instead, but those solutions also gave bugs due to certain page elements, and especially on responsive version for small screens the site would constantly bug out.


Applied Technologies

HTML/CSS with jQuery and Javascript functions
HTML/CSS for the most part functioned properly and bug-free, with the exception of few times where page would stop responding to CSS stylesheet file assigned to said page, for no apparent reason and without any changes to HTML or to CSS file. For some reason, that issue could only be fixed by opening files in Visual Studio Code, deleting everything, pasting everything back and saving again. Despite nothing being changed, the functionality would return.
In case of Javascript and jQuery, a lot of problems occured while trying to integrate said elements into pages, especially with jQuery, as virtually all of jQuery functions were sourced from third parties, and would have to be adjusted for custom pages.

All in all, about 30% of the workflow was a breeze, the rest of it was a headache.


Future plans

Most important goal at the moment is create the rest of the pages, which should be done within few days. 
It is entirely possible that after the site is finished content-wise, I'll decide to overhaul the overall theme of the site to streamline all pages. 
Second most important goal is to integrate propper gallery layout system for art/music/cyber pages, as I'm planning to upload a lot of content to the site in the upcoming months after I put it online to World Wide Web. Having reliable system for content layout is key.
One of the most important features to be added is Content Management System, to allow uploading and editing of content without having to constantly open html files manually, especially in the case of blogposts. Currently, CMS is not integrated as I haven't decided on the future host of the site yet, but since most hosts offer their own CMS solutions, I chose not to add any CMS at this point to avoid possible need to change CMS later.
One of the more questionable features is the LOGIN page. Initially, the site was supposed to be kind of a "showroom" type, as in, all content would be available right there and then, without any need for further authentication, as I was planning to make site un-editable by anyone but me anyway. But, after investigating CMS and the way they work, Login page seems a must, so that is one of the things that possibly will be added within a few days.
The Low-Priority goal list features stuff like Discord/Facebook/Twitter integration into site, to make it trully the hub of a network, especially since Discord offers certain features that could be very useful for certain visitors to the site, such as the ability to write your own bot that moderates your Discord channel. Also, I've got a lot of media content on the discord channel, and am planning to upload that content to the website too, having Discord integration would streamline the whole process.
Debugging site further to guarantee 100% stability is also one of the main objectives for the time being, but its likely that will be the last step before the website launch, after all the other content has been added and properly managed.




