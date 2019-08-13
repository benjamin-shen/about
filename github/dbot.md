# dbot
[Link to Project](https://github.com/benjamin-shen/dbot)  

### Context
**Purpose:** for fun!

My friend and former Cornell Glee Club webmaster Collin Montag created a python chatbot for the group chat on GroupMe. It responded to certain commands and often led to perfectly-timed inside jokes. I drew inspiration from this "mbot" and decided to create my own bot using python for one of the subset group chats I was in, GLOZZ (Glee Club and Chorus Class of 2022).

It was approaching the end of the school year and, in spite of finals and academic stress, I finished a completed version in a weekend and kept polishing it for a few more weeks. I named it "dbot" after the first initial of one of my close (memer) friends in the Glee Club. This was the first project I wrote in Python in a long time, and it felt a bit liberating to write in an interpreted language again. Dbot can initiate actions in response to commands, send messages in response to keywords, and pull information from the internet.

### Accomplishments
**Technologies:** Python Flask, Heroku, Web APIs

I was honestly a bit rusty when I took on this project. I worked with Python scripting in my sophomore year (Spring 2016) and only touched Java since. Of course, the syntax was super easy to pick back up, but I had never worked with Flask or any frameworks. I read through so many help pages for Flask and basically faked it 'til I made it. Through GroupMe bot tutorials, I successfully created a super basic bot that ran on a local server (i.e. hosted on my computer) and that could send messages to my private developer/testing group chat. This was a huge success to me, but I didn't want to keep my computer on 24/7 to run the bot.

I looked up how to host my project for free on the interwebs but, as expected, most results cost some amount of money. Then I found Heroku, with the only obvious downside being a one-dyno limit per account. Several tutorials later, I added the necessary files to run my app on Heroku. I learned all about the Heroku CLI (although I think I prefer Github) and git-push-heroku-master-ed all that good stuff online. After a bunch of testing, I had deployed my first Heroku app.

Along the way, I also learned so much about Web APIs (not only GroupMe's API, but also weather and transportation APIs). That then led to learning about things like HTTP requests, access tokens, environmental variables, and app security. This project definitely made me more well rounded and experienced as a developer.

### Reflection
**Verdict:** future plans in store

Although this was a relatively simple project, it really taught me a lot about how to learn (I Googled a LOT) and how to manage my workflow. I'm really proud of dbot and I plan on creating my own tutorial, maybe for some non-programmers to learn without having to do so much research. This project also got me really interested in electronics, and I bought a Raspberry Pi to act as my own mini server for potentially more bots.

In hindsight, testing got pretty annoying; every time I upgraded dbot, I would have to transfer the group chat ID to my developer group chat. A few times, I was too lazy and dbot ended up spamming my poor guinea pigs dozens of identical messages (that's why you always implement a timeout, by the way). Then for everything I changed, I would have to message a prompt and wait for an expected response. Changing the test methodology would probably be the number one thing I would change - maybe with an auto-tester helper bot?

Obviously, as with every project, there is a huge list of cool things I want to add. However, I think this version of dbot is completed and, if anything, I'll create a new bot for GroupMe (gbot?). Maybe I'll move on to other messaging services like Discord.

#### Thanks for reading!
[Link to Project](https://github.com/benjamin-shen/dbot)  