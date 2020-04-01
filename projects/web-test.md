# web-test
[Link to Project](https://github.com/benjamin-shen/web-test) (demo credentials available on request)  

### Context
**Purpose:** final project for high school class

This was originally a project for the IntroCS2 class I took my sophomore Spring at Stuyvesant. I worked with my friend Albert Ryu. We were in different periods, so the only time we could work together was after school. One of my fondest memories is ordering two large cajun fries from Five Guys for dinner and working at his house until late at night.

Stuy used Apache, which ran each Python CGI script that was called, and displayed the rendered HTML that was printed. I cleaned up some code (like broken absolute links and the outdated print statements) and tried to host it on Heroku for the sake of nostalgia. However, I soon learned that hosting the project there didn't run the CGI scripts correctly, so I had to fix a lot of code for anything to work. Eventually, all the functionality was migrated successfully.

### Accomplishments
**Technologies:** Python <del>CGI</del> Flask, Heroku, web development

When first building this project, I learned a lot about web development (particularly web forms and user authentication) and Python (particularly CGI scripts and file manipulation/permissions). But the project mostly focused on frontend development; the backend was very hand-wavy at that time.

To fix up the code (still written in Python 2), I used the Flask framework. I had to handle requests slightly differently and make every script contain a function that returned HTML, rather than simply printing it. The biggest challenge in this was definitely debugging, since I was pretty unfamiliar with the old code (and how to test it).

I hosted the website on Heroku, which wasn't very difficult because I had worked with it before. I shared it with Albert (the og) and I'm still proud of the project to this day.

### Reflection
**Verdict:** would reprogram entirely

If I were building this project for someone else, I would probably reprogram the entire thing in PHP/JS and employ better web (UI/UX) design. We had to use Python because the class used that language, but in hindsight I would've liked to use an alternative for web development. I would also prefer an actual relational database (like Firebase) over a file database system.

There are several flaws in this web-test app; for example, the data will reset every time I update the app and multiple people can't be using it at the same time. Nevertheless, it was an awesome project in high school and I'm glad I got to revamp it in college.

#### Thanks for reading!
[Link to Project](https://github.com/benjamin-shen/web-test) (demo credentials available on request)  

*[Back to Home](/../../../about)*  