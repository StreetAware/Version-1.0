Iteration 1:

This was my old priorities list.

1)	Setup my database + the connection
a.	The database will run on a machine and it will connect to the app.
b.	It will do this by: the app sending requests via an API which will access the DB and return the data over HTTPS.
2)	Fill the database with dummy data
3)	Create a basic user interface
a.	Very simplistic
b.	Include navigation
4)	Release Information	
a.	Create code to pull in data for release information
b.	Display that data in the
i.	Home screen page
ii.	Brand Release page 
iii.	Specific Item page
5)	Create the release calendar and add in the functionality for it on the home screen
a.	Create a timer setting so the user will be notified before a drop occurs
6)	Create the CopTheFit section
7)	Create the RateMyFit section as they should be very similar
8)	Get the camera and upload functionality working
9)	Setup posting abilities for CopTheFit and RateMyFit
10)	Setup CopTheFit and RateMyFit InDepth section
a.	Add in functionality to like
b.	Add in functionality to comment
c.	Add in functionality to reply
11)	Create the Articles and News Section
a.	Will follow a similar format to homescreen brands
b.	Create the specific article page
12)	Create the What’s Hot section that will view most favorited items of the day/week/month etc.
13)	Create the Login
14)	Create the Settings
15)	Create the FAQ

After discussing with Bill, I decided to focus on a basic splash screen for my first iteration and hopefully begin setting up my db and connection with dummy data in the next iteration!

My main aim for iteration 1 will be creating a top navigation drawer and a bottom navigation bar. I will style them and will create the relevant fragments and activities needed. These will bring the user to all the different areas of the application. By doing this I will be getting used to coding in android studio, I will get a better feel of the environment and my app will have full manoeuvrability minus the data. It should provide me with a basic framework to start with!

I began by selecting the top navigation drawer activity. I deleted current data and filled in my own items and added in the vector assets for them.
I then made it so that each item would open up a new fragment. After this I had to make sure that the name displayed in the top bar correlated with the selected fragment.
I initialised the 3 fragments and created corresponding constructors for them.
I created a drawable ‘circle_new’ and a layout ‘navdrawerdot’ to display next to items in the nav drawer when a new item is available e.g. a new article has been posted that the user hasn’t seen.
Added in extra fragments to top nav drawer (RateMyFit & DesignIT)
Included About Us and Privacy Policy in the top nav drawer and set the re-direct to go to an activity instead of a fragment.
I got a Privacy Policy text file (information in resources used), brought it to my drop box and styled it, then made it so the navigation drawer will bring you to this link
Changed around the settings icon for the top navigation drawer and set it to lead to an activity (Setting Activity) which I have created a default template for.

For the bottom navigation drawer, I added in the selected buttons I wanted, created corresponding fragments (Camera, Home and User) from which they would open in to and changed around the colour and styling. I created all the constraints necessary and made sure that my frame layout would not overlap the bottom nav bar.

Resources Used:
	https://www.youtube.com/watch?v=EbcdMxAIr54
	https://www.youtube.com/watch?v=SIW6RCYmBBo
	https://www.androidauthority.com/using-coordinatorlayout-android-apps-703720/
https://www.youtube.com/watch?v=kWEwnPIees8 (For Privacy Policy File)

Settings/Privacy Policy/ Cop the Fit and Rate my Fit icons made by: 
https://www.flaticon.com/authors/smashicons" title="Smashicons"
