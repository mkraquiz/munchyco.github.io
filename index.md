[comment]: <> (To begin with, the home page should provide a good description of the goals of the project, what the system should eventually provide, and screen shots of the mockup pages you plan to use as a basis for your final project.)

* [Project Goals](#project-goals)
* [Milestones](#milestones)
* [Mockups](#mockups)
* [Galaxy Pages](#galaxy-pages)
* [User Guide](#user-guide)
* [Installation](#installation)
* [Community Feedback](#community-feedback)

## Project Page: <a href="http://munchiesmanoa.meteorapp.com/">http://munchiesmanoa.meteorapp.com/</a>

# Overview 

manoa munchies™ is a directory for students to find food on campus they might enjoy based on their preferences. Here they are able to discover a selection of vendors as well as their information on hours of operation and location. Being a team of hardworking college students ourselves, we thought that every student should have a reliable and pleasant experience of finding places where they can eat. Because after all, food is what brings us together and keeps us going in this tough college life.

# Project Goals

To create a platform for Manoa students to find what food is available on campus, and cater that information to their personal preferences as well as the current time/date.

- Comprehensive Campus Menu Platform
- Customized to user's preferences 
- Dynamic suggestions based on time/date/location


## Stretch Goals

- Notifications to users about closing times/wishlist food items
- Integrating Sales/Coupons/Limited Time offers
- Food truck location data from Twitter/GPS(if offered)

# Milestones

## Milestone 1: <a href="https://github.com/munchyco/manoa-munchies/projects/1">Click Here</a>

## Milestone 2: <a href="https://github.com/munchyco/manoa-munchies/projects/2">Click Here</a>

## Milestone 3: <a href="https://github.com/munchyco/manoa-munchies/projects/3">Click Here</a>

# Mockups

- Landing page

<img src="/screencaps/landingpage.png">

- User home page

<img src="/screencaps/userhomepage.png">

- Vendor home page

<img src="/screencaps/venderhomepage.png">

- Today’s top picks page

<img src="/screencaps/toppick.png">

- Add Vendor page

<img src="/screencaps/addvendorpage.png">

- User profile page


- Foods available right now page

<img src="/screencaps/toppick.png">

# Galaxy Pages 
(UPDATED AS OF APRIL 21ST 2019)

- Landing page <a href="http://munchiesmanoa.meteorapp.com/">http://munchiesmanoa.meteorapp.com/</a>

<img src="/screencaps/galaxylanding4-22.png">

- User Home Page <a href="http://munchiesmanoa.meteorapp.com/">http://munchiesmanoa.meteorapp.com/#/userhome</a>

<img src="/screencaps/galaxyuserhome4-22.png">

- Vendor List page <a href="http://munchiesmanoa.meteorapp.com/#/user">http://munchiesmanoa.meteorapp.com/#/vendorhome</a>

<img src="/screencaps/galaxyvendorlist4-22.png">

- Today’s top picks page <a href="http://munchiesmanoa.meteorapp.com/#/toppick">http://munchiesmanoa.meteorapp.com/#/toppick</a>

<img src="/screencaps/galaxytoppick4-22.png">

- Add Vendor page <a href="http://munchiesmanoa.meteorapp.com/#/add">http://munchiesmanoa.meteorapp.com/#/add</a>

<img src="/screencaps/galaxyadd4-22.png">

- User profile page <a href="http://munchiesmanoa.meteorapp.com/#/user">http://munchiesmanoa.meteorapp.com/#/user</a>

<img src="/screencaps/galaxyuser4-22.png">

# User Guide

Users will be welcomed to the manoa munchies landing page to there they are able to register a free account or log in if they are already registered.

<img src="/screencaps/galaxylanding4-22.png">

After registering or logging in, users will be redirected to the user home page where they may begin using the manoa munchies system. 

<img src="/screencaps/galaxyuserhome4-22.png">

Now to get the most usability out of munchies manoa, you can begin by filling out your profile Preferences. Depending on what you choose, manoa munchies can provide a better selection suited for you.

<img src="/screencaps/galaxyuser4-22.png">

manoa munchies also provides a top picks of vendors for people who are a bit unsure of what to eat and maybe want a recommendation.

<img src="/screencaps/galaxytoppick4-22.png">

Here is a list of all our vendors that you may choose from. More will be added in the future.

<img src="/screencaps/galaxyvendorlist4-22.png">

# Installation

## Developer Guide: Installation (MAC)

To get manoa munchies setup in a local environment, you must have the latest version of <a href="https://www.meteor.com/install">Meteor</a> and <a href="https://nodejs.org/en/download/">NodeJS</a> installed. If you want to modify the code a platform such as IntelliJ IDEA is highly recommended.

1. To begin, you can retrieve the manoa munchies source code from our GitHub repository <a href="https://github.com/munchyco/manoa-munchies">here</a>. Downloading the raw zip is possible however it is recommended you use GitHub Desktop. This guide will be using GitHub Desktop.

2. Clone the repository to GitHub Desktop.

3. Right click the repository and click "Open with Terminal"

<img src="/screencaps/DevGuide-RightClick.png" width="300">

4. Once in the terminal, type `cd app` to change directory to the app folder.

5. In the app folder, type `meteor npm install` to install the needed plugins to run the app.

6. Next, type `meteor npm run start` to run the program. This should take a bit.

7. Congrats! Your app should now be hosted locally at http://localhost:3000. 


## Developer Guide: Installation (WINDOWS)

1. To begin, you can retrieve the manoa munchies source code from our GitHub repository <a href="https://github.com/munchyco/manoa-munchies">here</a>. Downloading the raw zip is possible however it is recommended you use GitHub Desktop. This guide will be using GitHub Desktop.

2. Clone the repository to GitHub Desktop.

3. Right click the repository and click "Open with Command Prompt"

<img src="/screencaps/windows-rightclick.png" width="300">

4. Once in the cmd, type `cd app` to change directory to the app folder.

5. In the app folder, type `meteor npm install` to install the needed plugins to run the app.

6. Next, type `meteor npm run start` to run the program. This should take a bit.

7. Congrats! Your app should now be hosted locally at http://localhost:3000. 


## Developer Guide: Modifying the Code

It is highly recommended to use a software such as IntelliJ to edit and modify manoa munchies. Once acquiring the necessary software, majority of the components and functionality is located in the "client" and "imports" folder. 

# Community Feedback

We have requested five anonymous people to review manoa munchies and give their honest opinion about it. Here's what they have to say about our app.

## Experimentee #1

"At first glance, the website is pretty well put together with a modular design. Some improvements would be to modify the header and navigation bar to stand out more. As for the functionality, if possible I would like to see a review system for the Vendors from the Customers. Overall I was very satisfied with the app."

## Experimentee #2

"It's aesthetically pleasing ... not too crowded with many links and the interface is fairly easy to navigate. Some potential improvements may be to organize the drop down menu for Food Types in Add Vendors, a bit more description dedicated to the purpose of the pages, and maybe some clean up here and there. Overall it's alright."

## Experimentee #3

"Looking at the first page you're directed to on the website, I like how it's not too flashy and has a very clean look. The short description helps as well. With that being said, dont be afraid to add a little more to make it took interesting. If you go for that minimalist theme it can sometimes leave your website looking very barebones. As for functionality, the features provided on manoa munchies are pretty good, but once again there's always room for more features. One thing I would like to see is a sort of "Google Maps" type of feature where every Vendor could be easily located through there when clicking on their vendor. Aside from that I like it! "

## Experimentee #4

"My impression of manoa munchies at first was OK. I do like the concept of being able to find foods you like based on your own preferences but the website has to entice me to eat. I would say that the website itself is not necessarily food themed, but, nontheless it does provide a good pavement to showcase its features. As for the features, they are good as it is but they can definitely be improved. "

## Experimentee #5

""

## Contact Us

:) 
