---
layout: post
title:      "The Rotten Tomatoes: Top 25 Horror Movies CLI Ruby Gem"
date:       2019-11-22 23:49:43 -0500
permalink:  rotten_tomatoes_top_25_horror_movies_cli_ruby_gem
---

<img width="630" alt="Screen Shot 2019-11-22 at 12 38 21 AM" src="https://user-images.githubusercontent.com/24573221/69467910-04617380-0d58-11ea-86cc-6fe3a0f916e3.png">

Admittedly, creating my first Flatiron School project was anxiety inducing, so much so that I can say I stalled a bit before tackling it. My hesitation was evenly distributed into two buckets: concern related to my ability and concern related to the actual build. However, despite my lingering fears, I can FINALLY say I’ve tackled and completed my very first portfolio project and created my first Ruby gem! 

### **Project Walkthrough**

For my first project I knew that I wanted to make something fun, that I myself would want to use. I love horror movies and often find myself perusing top horror lists, in hopes of finding new movies and opinions on them. Creating a top horror movies Ruby CLI gem was a logical way to combine horror and code. The next step involved finding a website from which I could scrape my data. The Rotten Tomatoes website seemed like a great choice because the interface was simple, and the data is always evolving since it is updated frequently.

**What does this Ruby CLI gem do?**

<img width="700" alt="Screen Shot 2019-11-22 at 12 38 41 AM" src="https://user-images.githubusercontent.com/24573221/69467911-04617380-0d58-11ea-9627-5ec89ce838ba.png">

This CLI gem provides an interactive top 25 horror movie list, from the Rotten Tomatoes website. The user is given the list upon entering the program and is prompted with the question “would you like further information on a movie?” The user can then enter the number that corresponds with the movie they would like to learn more about. This will open the movie stats section with info on: rank, rating percentage, title, link to Rotten Tomatoes page, and total number of reviews.

<img width="500" alt="Screen Shot 2019-11-22 at 12 39 32 AM" src="https://user-images.githubusercontent.com/24573221/69467908-04617380-0d58-11ea-9dd5-f449fdbda101.png">

At this level, the user can then choose to see a short synopsis on the movie and a random critic’s review. 

<img width="800" alt="Screen Shot 2019-11-22 at 12 40 25 AM" src="https://user-images.githubusercontent.com/24573221/69467912-04617380-0d58-11ea-9175-d48458ab070f.png">

Lastly, the gem prompts the user asking if they would like to see another movie. If yes, it will loop right back to the top 25 horror movie list; if no, the user will be ushered out of the program by some spooky skulls!

<img width="365" alt="Screen Shot 2019-11-22 at 12 40 48 AM" src="https://user-images.githubusercontent.com/24573221/69467909-04617380-0d58-11ea-858e-33ce68bf600c.png">

**Thoughts on the Experience of Creating My First Project**

The overall project was somewhat challenging for me. This was my first experience creating any big project with code. Putting together all my knowledge into one big project felt like putting together one of those 1000 piece puzzles – I knew the info was in my brain... somewhere, but I had to work hard at piecing it all together. But, I did learn a couple of things throughout this process. 
1. I am obsessed with leaving WEIRD RANDOM SPACES ALL OVER MY CODE, which as you can imagine is super problematic when testing it because I get a million error messages.
1. I can trouble-shoot and ask for help! I needed assistance throughout this project, but allowed myself to struggle a bit, look up resources and eventually, reach out to programmers in my network. Took a while, but I have struck a healthy balance between the three.
1. I should commit my code more routinely, and would benefit from committing smaller chunks with concise messages. Looking back through my commits, it would have been helpful to see the project broken down into even smaller pieces. 
1. With that in mind, though the record of my project build is a little sparse, I effectively planned it ahead of time. Planning ahead was useful in carrying out all the small stuff (i.e. writing needed methods & objects and knowing where they should go).
1. I enjoyed working with data collection and scraping a whole lot! It might sound silly, but I found sifting through data and organizing it to be fun. If it were not for the time constraint and focus on creating a minimal viable product (project), I would have created more levels of information.
1. Lastly, creating a gem was surprisingly difficult for me. When adding files to a commit, I added the “.gem” file itself, which created chaos. After living in gem-creation-hell for around an hour, an important lesson was learned. With assistance, I filtered out any files that ended with “.gem” for it to work.

**Moving Forward**

Overall, this was a challenging, but meaningful experience. I saw a project through from start to finish and made it through the hard stuff, which taught me to believe in myself way more than I did before. In relation to the CLI Ruby gem, in the future, I hope to refactor my code and possibly add other levels to enhance the user experience!


If you are interested in checking out this project or would like to contribute to it's development, feel free to look at the repository on [Github](https://github.com/watchjazcode/horror-movie-cli).



