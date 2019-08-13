# admissions2019
[Link to Project](https://github.com/benjamin-shen/admissions2019)  

### Context
**Purpose:** application for testing at work

I wrote this app for testing the Admissions Application that the SC Johnson College of Business updates every year in the annual Admissions Project. My team, the IT department's admin team, was responsible for implementing the application changes in Salesforce (the customer relationship management system we used). Traditionally, each task on Workfront (the project management system we used) was added to a list of changes that had to be tested by following manually added steps. All of this was written on a word document with a bunch of tables.

My idea to computerize the testing methodology came from the fact that, when rearranging tasks, each task number affected had to be manually updated. (i.e. moving task 5 before task 2 meant relabeling 1/5/2/3/4/6 to 1/2/3/4/5/6). I ended up making a web app that not only fixed the organization issue, but also made it more convenient to mark test cases passed or failed, add test steps, and add comments.

### Accomplishments
**Technologies:** NodeJS, Heroku, web development, data management

I always wanted to learn Node, and thought that this was a perfect opportunity to do so. I already knew JavaScript syntax, so I did some learning about Node.js and created an app to deploy on Heroku. I emphasized good design in this project, and tested the web app on various devices including tablet and phone. I added http auth for security purposes (so people not in the company couldn't mess with the app).

I wanted a database system that my coworkers and supervisors could easily access and change. So, I used Google Sheets as a pseudo-database and shared it with my team. That way, the application could read from and write to the "database" while humans could bulk update it very easily. I learned about macros and wrote a simple one to reorder numbers when rows (tasks) were rearranged. Finally, I loaded all the project data into the web app and sent it to my supervisor.

### Reflection
**Verdict:** will repurpose and test more vigorously

Since time was running short, I coded and tested this web app in around 10-20 hours at work and at home. There is a lot of functionality missing that I want to implement, but when I created the app I considered bug-free a priority over fancy.

Unfortunately, the app was never used for the project because the traditional word document method was safer and had already been started. There was definitely a lack of communication that I learned from. However, there were some other projects whose tasks I tested that I think could've used a very similar (repurposed) web app. I haven't given up on this project yet, and I hope I can polish it and eventually convince the Cornell Business IT Department to use an upgrade entirely envisioned by myself.

#### Thanks for reading!
[Link to Project](https://github.com/benjamin-shen/admissions2019)  
[Back to About](/../../)  