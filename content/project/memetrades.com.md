+++
date = "2017-02-05T04:00:00-05:00"
title = "MemeTrades.com"
draft = false
indev = true
tools = ["JavaScript", "HTML", "CSS", "D3", "Python", "Flask", "MongoDB"]
github = "https://github.com/QuadmasterXLII/memeClient"
link = "http://hgreer.com/meme-dev/"

+++
Links: [Github (Prototype)], [Github (New)], [MemeTrades.com]

Teammates: [Hastings Greer], [Brandon Davis], [Kyle Feng]

![Memetrades.com](/images/memetrades.png)

### The Gist
This is a website where users can buy and sell stocks of community-generated memes. Users start with 1000 "meme bucks" and they can invest in existing memes or create their own. Currently memes are simply strings, but we hope to expand the scope of our content to include images.

### My Role
In the original prototype I worked on small parts of the frontend and UI/UX, such as the user's portfolio display and the buy/sell interface. I also worked on a D3 bubble graph visualizer for the market.

In the current version, I'm contributing to the stock visualization and trend graphs. I'm also implementing functionality for user-uploaded images and automated moderation of this content.

### Challenges and Lessons
A couple weeks into the project, after our initial hype died down, the website was shared on a fairly popular Facebook page and the user base skyrocketed. There was a scramble to moderate the large amount of new content and manage the load on the server. I wasn't actively developing when the first wave of visitors arrived, but watching the other devs deal with this issue gave me some insight into handling a big userbase.

Memetrades was the first extensive web project (JS/HTML/CSS) for which I wrote usable code. It was also my introduction to backend programming and Flask. I learned how to create API views and use them to communicate information from client to server.


[Github (Prototype)]: https://github.com/QuadmasterXLII/memeClient
[Github (New)]: https://github.com/meme-exchange/server
[MemeTrades.com]: http://memetrades.com/
[Hastings Greer]: http://hgreer.com/flask/
[Brandon Davis]: https://subdavis.com/
[Kyle Feng]: http://kylefeng28.github.io/
