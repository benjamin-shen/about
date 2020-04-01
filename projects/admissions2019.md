# admissions2019
[Link to Project](https://github.com/benjamin-shen/admissions2019) (demo credentials available on request)  

### Context
**Purpose:** web application for testing at work

I wrote this app for testing the Admissions Application that the SC Johnson College of Business updates every year in their Admissions Project. The IT department's admin team was responsible for implementing the application changes in Salesforce (the customer relationship management system we used). Traditionally, each task on Workfront (the project management system we used) was added to a list of changes that had to be tested by following steps that were manually added. All of this was written on a Microsoft Word document with a bunch of tables.

I came up with the idea to use an application instead of a Word document to present and update the tasks.  I ended up making a web app that auto-numbered the tasks and made it much more convenient to mark test cases passed or failed, add test steps, and write comments.

### Accomplishments
**Technologies:** NodeJS, Heroku, web development, data management

I always wanted to learn Node, and thought that this was a perfect opportunity to do so. I already knew JavaScript syntax, so I did some research on Node.js and created an app to deploy on Heroku. I designed the web app to format correctly on various devices including tablet and phone. I added http-auth for security purposes, so people outside the company couldn't interact with the app.

I wanted a database system that my coworkers and supervisors could easily access and change. So, I used Google Sheets as a pseudo-database and shared it with my team. That way, the application could read from and write to the "database" while the admin team could bulk-update it very easily. I learned about spreadsheet scripting and wrote a simple macro to reorder numbers when rows (tasks) were rearranged. Finally, I loaded all the project data into the web app and sent it to my supervisor.

### Reflection
**Verdict:** will repurpose and test more vigorously

Since time was running short, I coded and tested this web app in around 10-20 hours at work and at home. There is a lot of missing functionality that I wanted to implement, but my first priority was that the app was bug-free.

I plan on upgrading the web app and using it for next year's Admissions Project.

#### Thanks for reading!
[Link to Project](https://github.com/benjamin-shen/admissions2019) (demo credentials available on request)  

*[Back to Home](/../../../about)*  
