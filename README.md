# Two-Hour App #2: Automatic Django / Heroku Creator

In yesterday's two-hour app challenge, I had trouble deploying the final (crappy) app to Heroku. Today, I spent a lot of time digging into what files and settings needed to be adjusted in order to make that work.

In working through this, I started writing a small script that would create some files I would need: runtime.txt, requirements.txt, etc. After a little while I realized "Hey, I could just write a script to set up the whole project from the start." And that's exactly what I did.

Voila! [Heroku-Django](https://github.com/stevenrouk/heroku-django), a script I created in order to (1) Create a Django development environment, and (2) Deploy the basic starter Django app to Heroku.

Although I technically didn't build a web app today, I also sort of technically built about 30 of them as I tested the automatic creation and deployment script.

So now, whenever I want to set up a Django project that's going to end up on Heroku (which will probably be for the next several days at least), I don't have to worry about the environment or the deployment at all!

Which is pretty awesome, I think.
