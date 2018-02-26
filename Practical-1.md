**Checkpoint: contribution to shared timeline**

## Task 1: Web Page Design

**Bad points:**
<!--- --->
1. No database used, so data may become inconsistent
2. No pagination and some pages can be very long
3. No way to sort some of the data
3. The style needs a lot of work (colour choices, max-width, font, tables)
4. Front page is not very intuitive 
5. Each ship name is a gif
6. Clicking on picture leads to another html page
7. Lots of broken links (http://irishwrecksonline.net/details/Chirripo150.htm, click on wreck list)
<!--- --->

**Good points:**
<!--- --->
1. Contains a huge amount of data about shipwrecks
2. Data is organised according to several categories (location, county, name, latest update)
3. We can search the whole website (using sitelevel)
4. Interactive map
<!--- --->

**Re-design**
<!--- --->
Some questions I would ask the site owner, if I were asked to redesign the website:
1. The webpage seems like a nightmare to maintain, can we use some sort of framework that automatically creates pages, or even better, a single page application?
2. Can we use a database to ensure data consistency?
3. Can we update the map (e.g. use google map overlay) and use latitude longitude. 
<!--- --->
<!--- https://www.youtube.com/watch?v=4T5KZFUw7Y8 --->
Demonstrations:
- http://glittershark.github.io/reactable/
- http://davidguttman.github.io/react-pivot/
- http://react-mega-man-robot-masters.herokuapp.com/ (may take a while to load since it is on heroku)

## Task 2: 

Create a google sheet (only one is needed per team), and then share it. You should get a link similar to this one:

<!--- https://docs.google.com/spreadsheets/d/1rITg1dMFxiWvyqS7yiB0EAdHsIMDSy3JKpd4eluPMAM/edit?usp=sharing --->
`https://docs.google.com/spreadsheets/d/13ah9vGCjvwVBv19lz75YDn5uJcxFYcmAtMPqkBk0qkY/edit?usp=sharing`
<!--- https://docs.google.com/spreadsheets/d/1FohWsxPJcjo-gw9xAb4m7kvPQ0YnVBpDaoLBn95FVVc/edit?usp=sharing --->
You then need to use this in your html.

## Task 3:

If you are keen, and you haven't done this sort of stuff before, you can easily host your page online using github. It means that you have to install git (comes preinstalled if you use a Mac), but this is something you will do anyway one day.

I think this is the fastest free method to push a single static html page online. Let me know if you know something faster. Main reference is at https://pages.github.com/

1. Create a github account (if you don't already have one)
2. Create a repository called username.github.io (where username is your github username)
3. Install git, if you don't have it yet
4. `git clone https://github.com/username/username.github.io.git`
5. Go inside `username.github.io.git` folder and add an `index.html` file
6. `git add index.html`
7. `git commit -m "first commit"`
8. `git push origin master`
9. go to username.github.io

## Extras:

1. Get started on PyCharm and bottle.py (http://bottlepy.org/bottle.py)
2. http://codingbat.com/python
3. HTML5 course on Lynda: https://www.lynda.com/HTML-tutorials/Welcome/182177/370804-4.html
4. https://hackernoon.com/how-it-feels-to-learn-javascript-in-2016-d3a717dd577f

## Resources:

For webpage design: 
- https://htmlcolorcodes.com/color-names/
- http://www.csszengarden.com/
