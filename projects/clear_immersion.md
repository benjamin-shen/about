# clear_immersion
[Link to Project](https://github.com/benjamin-shen/clear_immersion)  

### Context
**Purpose:** script for data cleanup

When I described one of my admin tasks to my friend Cameron, he told me this: anything repetitive could be automated. All I had to do was write a program to do my job and it'd be far more productive and fun.

As a student worker, I was inevitably assigned some repetitive tasks, such as data cleanup (updating hundreds to thousands of individual records). So, instead of spending days mindlessly clicking and potentially making mistakes, I wrote a simple script that updated each record for me. I then sat back and watched for uncaught errors while the script ran.

### Accomplishments
**Technologies:** Python AutoGUI

This project was my first experience with AutoGUI (a module that simulates mouse and keyboard inputs). I had to be sure to implement failsafes in case I needed to terminate the program. I added a timeout after almost every action, just to make sure the computer and Salesforce servers could keep up.

I also experimented with some python photo recognition but it was too inaccurate for the purposes of this script. Instead, I used screen coordinates to direct the mouse clicking. In hindsight, I could have used Selenium or JavaScript with HTML-element recognition instead.

### Reflection
**Verdict:** time is money

I spent a few hours coding, and then another hour or two to run the script. All in all, it took about a day to do a week's worth of work and it was much more interesting and error-free. If I could've bulk-updated the records in Salesforce, I would've definitely gone that route instead. Even with a script, I had to monitor the screen the entire time to make sure there weren't any slow requests, premature clicks, or unexpected layout changes.

This was a single-use script, but it was well worth writing. I can see myself writing similar scripts for future data cleanup tasks.

#### Thanks for reading!
[Link to Project](https://github.com/benjamin-shen/clear_immersion)  

*[Back to Home](/../../../about)*  