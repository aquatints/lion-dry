# lion-dry — a Laundry Management App for Penn State

### Note: As of the end of the competition expo (on 11/13/16), we've taken the database the app pulls from down.  The login screen will still work, but upon selecting a residence hall, the app will crash.  

![Cred to Wendy for this SWEET logo](https://github.com/aquatints/lion-dry/raw/master/android/app/src/main/res/drawable/lion_dry_logo2_color.png)

## What did we make?
We've created a starter demo of the app.  It currently retrieves information on 6 washer and dryer machines stored in a DynamoDB table on Amazon AWS.  It displays whether or not the machine is in use according to that table.  We did not implement the trend graph or the reservation system. 

## How to run
If you have an Android device, click the "Download APK" button at the top of the page.  When it finishes downloading on your Android phone, open it to install (you may need to allow installations from unknown sources).  The application will ask for a psu email and password.  It does NOT link to your access account at PSU.  Instead, use these example credentials:

    Email: abc1234@psu.edu
    Password: hello

## What was the goal of this app? (written _before_ staying up for 21 hours)
Having lived on campus for all of our time in University Park so far, the three of us have found ourselves frustrated when doing laundry.  Depending on where on campus you're living, laundry may be right across the hall from your dorm room, or it could be on a completely different floor.  This is annoying if you are lugging your laundry up the stairs and find when you arrive at the laundry room that there are no open machines.  

We hope we're creating a way to eliminate this frustration.  With Lion-Dry, we are creating a washer/dryer reservation system.  Without going too far into the technical details, the user can sign in with their PSU Access Account to verify they're a student, select their building and floor, and view open machines.  If one is open, they can reserve it for the time it takes them to get to the laundry room. 



_Created for HackPSU Fall 2016_


## Who We Are
### Pat Heaney
Pat Heaney is a sophomore at the Pennsylvania State University. He is pursuing a B.S. in Security and Risk Analysis at the College of Information Sciences and Technology with a focus in Information & Cybersecurity (ICS). 

### Ryan Dougherty
Ryan Dougherty is a sophomore at the Pennsylvania State University. He is pursuing a B.S. in Information and Science Technology at the College of Information Sciences and Technology with a focus in Design and Development of Applications. 

### Wendy Davis
Wendy Davis is a sophomore at Penn State majoring in Wildlife and Fisheries Science with a focus on wildlife stuides.
