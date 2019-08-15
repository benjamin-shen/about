# web-test
[Link to Project](https://github.com/benjamin-shen/web-test)  

### Context
**Purpose:** final project for class

This was originally a project for the IntroCS2 class I took my sophomore spring at Stuyvesant. I worked with my friend Albert Ryu. We were in different periods, so the only time we could work together was after school. Thinking back, my fondest memory is ordering two large cajun fries (from Five Guys) for dinner and working at his house until my mom told me I had to go home.

Stuy used Apache, which ran each Python CGI script that was called, and displayed the rendered HTML that was printed. I cleaned up some code (like broken absolute links and the outdated print statements) and tried to host it on Heroku for the sake of nostalgia. However, I soon learned that hosting the project there didn't run the CGI scripts correctly, so I had to fix a lot of code for anything to work. Eventually, all the functionality was migrated successfully.

### Accomplishments
**Technologies:** Python <del>CGI</del> Flask, Heroku, web development

When first building this project, I learned a lot about web development (particularly web forms and user authentication) and Python (particularly CGI scripts and file manipulation/permissions). But the project mostly focused on front-end development; the back-end was very hand-wavy. "Print HTML and HTML will be displayed correctly," they said. Hahaha... if only life was that easy.

To fix up the code (still written in Python 2, by the way), I used the Flask framework. I had to handle requests slightly differently and make every script contain a function that returned HTML, rather than simply printing it. The biggest challenge in this was definitely debugging, since I was pretty unfamiliar with the old code (and how to test it). There were a lot of cringey programming choices, but I can't complain; I'm positive future me is going to say the same about my code today.

I hosted the website on Heroku, which wasn't very difficult because I had worked with it before. I shared it with some college friends and, of course, Albert (the og) because I'm still proud of it today.

### Reflection
**Verdict:** would reprogram entirely

I feel like I can finally be honest, now that I graduated from Stuy. I absolutely loved the project but the logistical stuff (documentation, counting hours, real world stuff, etc.) was miserable. We definitely underreported the hours we spent on the project because we didn't want to seem like we were trying too hard. Seriously, the best part was collaborating with a friend and creating something that everybody who tried it loved.

If I was more serious about this idea, I would probably reprogram the entire thing in PHP/JS and employ better web (UI/UX) design. We had to use Python because the class used that language, but in hindsight I would've liked to use an alternative for web development. I would use an actual relational database instead of a file database system (in this case, the data will reset every time I update/push metadata and I have no idea what'll happen if multiple people are trying to update the same file at the same time). For a while though, it was an awesome project for the Apache servers at school and I felt like the coolest kid.

#### Thanks for reading!
[Link to Project](https://github.com/benjamin-shen/web-test)  

[Back to Home](/../../../about)  