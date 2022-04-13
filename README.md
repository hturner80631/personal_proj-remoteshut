# personal_proj-remoteshut
Various projects that I am doing for fun/education purposes.
There are scripts on this project that have been depreciated since the underlying assets seem to have changed.
I am currently working on a fix for these.

The remote shutdown projects are projects that were created with the server environment in mind (most of these scripts work mostly with linux).
I have fixed one of the scripts in this repo, but I need to validate the rest of the scripts

I wanted to create a script that would potentially detect a loss of power on a neighboring computer that is not on a UPS.
If the computer is unable to ping the neighboring computer then it will initiate a shutdown process (since it is presumed that the computer or multiple computers have lost power).
You can also configure this utility to notify the IT admin that the computer is shutting itself down to prevent data loss and it should be able to support SMS and Email.
I used Twilio for the SMS portion so you will need to enter an API key in order to use that script but the other one with Email should allow you to do that without incurring costs.
