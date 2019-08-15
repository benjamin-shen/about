# clear_immersion
[Link to Project](https://github.com/benjamin-shen/clear_immersion)  

### Context
**Purpose:** script for data cleanup

When I described my job (or what I initially perceived it to be) to my friend Cameron, he told me this: anything repetitive could be automated. All I had to do was write a program to do my job and I'd get paid for the work it did for me.

As a student worker, I was inevitably assigned menial/repetitive tasks that ended up pretty boring. Data cleanup (changing hundreds to thousands of individual records) was a good example. So, instead of spending days mindlessly clicking and doing data cleanup, I wrote a simple script that updated records for me. I then sat back and watched for any errors while my computer did its magic.

### Accomplishments
**Technologies:** Python AutoGUI

This project was my first experience with AutoGUI (a module that simulates mouse and keyboard inputs). I had to be sure to implement failsafes in case I needed to terminate the program. There were timeouts after almost every action, just to make sure the browser and Salesforce servers could keep up.

I also experimented with some photo (screenshot) recognition but it was a bit too buggy for my liking, so I used screen coordinates to direct the mouse clicking. This means I couldn't run the script on my desktop computer at work (if it had Python installed). That being said, this script was extremely situational and it's certainly never getting run again. It worked fine for my purposes, so there wasn't really a reason to add superfluous functionality/compatibility.

### Reflection
**Verdict:** time is money

I read on Reddit that someone accidentally got his boss's secretary fired for automating her job too well. I figured there was no way a data cleanup script could ruin someone's life in this company, so I went ahead and made it. I spent a few hours coding, and then another hour or two to run the script (because of the  necessary timeouts). All in all, it took about a day's work to do a week's work and it was much less mind-numbing.

If there ever was a cleaner non-AutoGUI option to automate the data cleanup (like bulk updating), I would've definitely gone with that instead. Even with a script, I had to monitor the screen the entire time to make sure there weren't any slow requests, premature clicks, or unexpected layout changes. I can definitely see myself writing more scripts for similar issues, though. It sure beats sitting at a desk and clicking away for hours and hours.

#### Thanks for reading!
[Link to Project](https://github.com/benjamin-shen/clear_immersion)  

*[Back to Home](/../../../about)*  