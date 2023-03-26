# Software Projects 💻

Check out [my github](https://github.com/cboin1996) for the latest projects
I am working on. Feel free to reach out if you have any ideas for projects,
or think it would be productive to collaborate.

## Songbird 🐦

Source code is found [here](https://github.com/cboin1996/songbird).

Songbird is Jukebox’s replacement, designed to be simpler to use and
more streamlined. This application features the ability to download albums,
songs while formatting them with valid mp3 or m4a tags. Songbird
integrates with iTunes, and Google Drive. In addition, the app is
Dockerized for easier installation by users.

## JukeBox (archived) 🎛️

Source code is found [here](https://github.com/cboin1996/WebTools).

JukeBox is a command line interface (CLI) program inspired by my challenges
as a kid using youtube to mp3 software. JukeBox is entirely written in
Python3, and was my first large project I worked on. As such, it is not
my finest programming, however there are an abundance of features my
friends enjoy. JukeBox presents users with a way to link their iTunes account,
and using the VLC python library provides a media player with
voice activated commands. The user may choose to download songs not in
their library, formatting them with the appropriate MP3 tags and album artwork.

## Dalle-ays 🖼️

Source code is found [here](https://github.com/cboin1996/dalle-ays).

Dalle-ays is a FastAPI server designed to download and cache dalle-mini
models to make image generation from text quick and easy. As a frontend,
I have created a [discord bot](https://github.com/cboin1996/pigbot) as a
way for users to interact with the server. Both applications are dockerized,
and I plan to make helm charts so they will eventually be deployable
in Kubernetes.

## AVDDPGG 🏎️

Source code is found [here](https://github.com/cboin1996/avddpg).

AVDDPG is a publication from my MASC work. This project applies the
deep deterministic policy gradient (DDPG) algorithm to co-operative
adaptive cruise control models. Through deep reinforcement learning (DRL),
each DRL model learns how to control each vehicle in a autonomous
vehicle platoon. In addition, I apply federated reinforcement learning to
my platooning environment and investigate the benefits. The work is
discussed and best summarized in [my publication](https://intellrobot.com/article/view/4885).

## Chesster ♛

Source code is found [here](https://github.com/cboin1996/Chesster)

Chesster was a school project and a fun challenge to build. By
implementing  [this repository](https://github.com/Zeta36/chess-alpha-zero),
I gained a
thorough understanding of how Monte Carlo Tree Search was applied in Google’
s Alpha-zero chess playing AI. Chesster may be trained through
supervised learning by importing PGN chess data, or through self play. I
often play against Chesster for fun, he has become pretty good at chess
and most of the time beats me.

## ShowMeTheMoney 💰

Source code is found [here](https://github.com/cboin1996/showMeTheMoney).

If you don’t know this by now, whenever I find a problem in my life I
usually try to write software to solve it when possible. This time I
decided it was time to begin budgeting. My first iteration of a
budgeting solution was to manually input transactions by store, expense
and amount in an iOS app. The iOS app would push the data to an SQL backend
, powered by a PHP script hosted off of this website. I used this app
for around a year, but eventually decided it was too much work and too
error prone to manually input data. Next, I decided to recreate the app as
a desktop CLI application. ShowMeTheMoney works by taking CSV data as
input from bank websites. It parses the data into income and expenses,
and then instructs the user to categorize each transaction’s store
with expenses. As the app gains more information, it then can reference
the database to further automate data imports. Data is presented to the
user via python bar charts, plotting their budgeted amounts versus
amounts remaining by month, year or both.
