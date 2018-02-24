## Task 1: Web Page Design

Bad points:
1. No database used, so data may become inconsistent
2. No pagination and some pages can be very long
3. No way to sort some of the data
3. The style needs a lot of work (colour choices, max-width, font, tables)
4. Front page is not very intuitive 
5. Each ship name is a gif
6. Clicking on picture leads to another html page
7. Lots of broken links (http://irishwrecksonline.net/details/Chirripo150.htm, click on wreck list)

Good points:
1. Contains a huge amount of data about shipwrecks
2. Data is organised according to several categories (location, county, name, latest update)
3. We can search the whole website (using sitelevel)
4. Interactive map

Some questions I would ask the site owner, if I were asked to redesign the website:
1. The webpage seems like a nightmare to maintain, can we use some sort of framework that automatically creates pages, or even better, a single page application?
2. Can we use a database to ensure data consistency?
3. Can we update the map (e.g. use google map overlay) and use latitude longitude. 

<!--- https://www.youtube.com/watch?v=4T5KZFUw7Y8 --->
Demonstrations:
- http://glittershark.github.io/reactable/
- http://davidguttman.github.io/react-pivot/
- http://react-mega-man-robot-masters.herokuapp.com/ (may take a while to load since it is on heroku)

## Task 2: 

URL for 

<!--- https://docs.google.com/spreadsheets/d/1rITg1dMFxiWvyqS7yiB0EAdHsIMDSy3JKpd4eluPMAM/edit?usp=sharing --->

<!--- https://docs.google.com/spreadsheets/d/13ah9vGCjvwVBv19lz75YDn5uJcxFYcmAtMPqkBk0qkY/edit?usp=sharing --->

<!--- https://docs.google.com/spreadsheets/d/1FohWsxPJcjo-gw9xAb4m7kvPQ0YnVBpDaoLBn95FVVc/edit?usp=sharing --->

Fastest method to push a static html page online that I know of: https://pages.github.com/

1. Create a github account (if you don't already have one)
2. Create a repository called username.github.io (where username is your github username)
3. Install git, if you don't have it yet (you really should)
4. `git clone https://github.com/username/username.github.io.git`
5. Add an `index.html` file inside the `username.github.io.git` folder
6. `git add index.html`
7. `git commit -m "first commit"`
8. `git push origin master`
9. go to username.github.io

