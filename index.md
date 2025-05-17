## TheC-es

[![ci-nextjs-application-template](https://github.com/TheC-es/GamePlan/actions/workflows/node.js.yml/badge.svg?branch=main)](https://github.com/TheC-es/GamePlan/actions/workflows/node.js.yml)

## Overview
At the Warrior Rec Center, high demand for basketball and volleyball courts, especially after 5 PM, makes it difficult for students to secure playing time. Our web app solves this problem by allowing students to:
- Reserve court time for their groups.
- Find and join existing groups to secure a spot.

## Team Members
- Alan Reeves
- Anthony Nguyen
- Simon Lin
- Angelo Rosal
- Maya Buchanan

## Mockup Page
Our web app would contain the following pages:

- landing page

# <img width="500px"  src="/img/landingpage.JPG" >

- login and sign up page

# <img width="500px"  src="/img/Login.png" >
# <img width="500px"  src="/img/Register.png" >

- schedule page showing times already reserved
- page to reserve times for a group
- looking for team page, where players without a group can find one
# <img width="500px"  src="/img/reserve.png" >

## User-Guide
Welcome to GamePlan, the web app that helps you reserve basketball and volleyball courts at the Warrior Rec Center with ease. Below is a quick guide to navigating the website.

- Landing Page
- Explore the app’s features and get started

# <img width="500px"  src="/img/landingpage.JPG" >

- Sign In Page
- Returning users can log in to access reservations and groups

# <img width="500px"  src="/img/signin.JPG" >

- Sign Up Page
- New users can create an account to start booking courts

# <img width="500px"  src="/img/signup.JPG" >

- Basketball Game Page
- See the score or if there are any available slots of the day

# <img width="500px"  src="/img/basketgame.JPG" >

- Volleyball Game Page
- See the score or if there are any available slots of the day

# <img width="500px"  src="/img/volleygame.JPG" >

- Reservation Page
- This page will allow users to pick which sport, court, day, and time they want to reserve.

# <img width="500px"  src="/img/reservation.JPG" >

- Basketball Schedule Page
- View upcoming basketball games

# <img width="500px"  src="/img/basketschedule.JPG" >
# <img width="500px"  src="/img/schedule2.JPG" >

- Volleyball Schedule Page
- Check times for available volleyball courts

# <img width="500px"  src="/img/volleyschedule.JPG" >
# <img width="500px"  src="/img/schedule2.JPG" >

- About Us Page
- Learn more about the team behind GamePlan

# <img width="500px"  src="/img/aboutus.JPG" >

## Developer Guide
<h4>Download</h4>
From the github repo page, either fork the repo or download a zip file
<h4>Install</h4>
Inside your local directory for the source code, use npm install to install dependencies
<h4>Run</h4>
To run the webapp locally, use npm run dev. This will compile and run the code. The default address will be "http://localhost:3000".
Enter this address into a web browser to view the app. 
In order to access database functions, first create a database with your software of choice.
With postgreSQl, you would use "createdb youDatabaseNameHere"
Migrate the database by running "npx prisma migrate dev"
To associate the database to the app, copy the contents of sample.env to a file called just ".env".
Then assign the DATABASE_URL variable to the address of the database you created.
Seed your database with the seed.ts script in the prisma directory.
i.e. "npx prisma db seed"
The app should now run as intended.
<h4>Modifying</h4>
Modifying the source code can be achieved with any editor.

## Community Feedback
User 1: 
Sign-up crashes when I attempt to either make an account or try to log into the account. The sign-up appears to work, but I’m not sure if it updates on the website in real time. It could be because I can’t sign up, but the user interface at the top is easy to navigate

User 2:  
- “Meet the Memebers” is Members misspelled on purpose?
- Should hide the “sign out” option if users aren't signed in
- Should hide the “sign in” and “sign up” options if users are already signed in
- Add some indication for being signed in, like an icon
- “Forgot Password” page doesn't exist (probably don't need one for the grade tbh)
- Give an error message when signing up withan  email that also has an account
- Give an error message when signing in with the wrong password
- “Games” tab does not go anywhere
- The schedules let me type in the “Free” boxes, same with the games and scores
- I would make the text in each tab on the navbar justify center 
- I would add more color and more interesting fonts
- Also, I can't sign in anymore, it just gives me an error

User 3:
- Easy to navigate
- Improve the aesthetics of the site

User 4:
- Great for first timers
- Looks like a UH site
- Easy to use

User 5:
- I LOVE THE LOGO
- Easy to use
- Add more color, it looks boring

## Links
<a href="https://docs.google.com/document/d/1KdcFXI9BLMf4gpyHK3QJkyHCRpiOTgpeOwQljG6ItBs/edit?tab=t.wm0ujzkwwri" target="_blank">[Team Contract]</a>

<a href="https://github.com/orgs/TheC-es/repositories" target="_blank">[GitHub organization]</a>

<a href="https://gameplanz.vercel.app" target="_blank">[Deployment]</a>

<a href="https://github.com/orgs/TheC-es/projects/1)" target="_blank">[M1]</a>

<a href="https://github.com/orgs/TheC-es/projects/2" target="_blank">[M2]</a>

<a href="https://github.com/orgs/TheC-es/projects/3" target="_blank">[M3]</a>

## Development History
<h4>Milestone 1</h4>
<ul>
    <li>Deployed basic version to Vercel</li>
    <li>Created landing page</li>
    <li>Created mockups of other pages</li>
    <li>Created Github organization and project M1</li>
    <li>Created this organization homepage</li>
</ul>
<h4>Milestone 2</h4>
<ul>
    <li>Implemented Basketball page</li>
    <li>Implemented Volleyball page</li>
    <li>Implemented Schedule Game page</li>
    <li>Implemented Basketball Schedule page</li>
    <li>Implemented Volleyball Schedule page</li>
    <li>Implemented About Us page</li>
    <li>Implemented sign in/out/up forms</li>
    <li>Implemented playwright tests for all pages</li>
    <li>Placed system under continuous integration</li>
    <li>Added continuous integration badge to project homepage</li>
</ul>
<h4>Milestone 3 (Current)</h4>
<ul>
    <li>Create 50 reservations </li>
    <li>Implement reservation testing on new pages</li>
    <li>Update seed file</li>
    <li>Clean up sign in/up/out button</li>
    <li>Create Community Feedback Section</li>
    <li>Show reservations for Volleyball Schedule</li>
    <li>Show reservations for Basketball Schedule</li>
    <li>Remove Unused pages</li>
    <li>Get real sign ups</li>
    <li>Establish schema for reservation</li>
</ul>
