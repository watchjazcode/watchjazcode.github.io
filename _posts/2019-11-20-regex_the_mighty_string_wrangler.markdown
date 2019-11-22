---
layout: post
title:      "Regex: The Mighty String Wrangler"
date:       2019-11-20 19:57:58 -0500
permalink:  regex_the_mighty_string_wrangler
---



<img width="696" alt="Screen Shot 2019-11-22 at 12 38 21 AM" src="https://user-images.githubusercontent.com/24573221/69467910-04617380-0d58-11ea-86cc-6fe3a0f916e3.png">

 
It’s about 10pm and after a very long day, I’m working to complete the Flatiron School Tic-Tac-Toe AI project. The goal of this project is to build a version of Tic-Tac-Toe with 0-, 1-, and 2-player modes:

* A 0-player game has two computer players playing against each other with no interaction from the user.
* A 1-player game has a human playing against a computer.
* A 2-player game has two human players.

Overall, the lab was going well.. until I hit a wall with the `valid_move?` method. The method checks if the move a user wants to make is valid by ensuring two things happen:

* the space is not already taken 
* user input consists of a string that is a number from 1-9.

However, I had a bit of trouble figuring out how to confirm the user input is equal to a string that is a number. After struggling and testing a few things, I realized **regex** would be a great way to solve this problem! 

Regex (regular expressions) are a very helpful tool in obtaining information from any text by searching for one or more matches of a particular search pattern (i.e. letters, numbers, words, phrases, ASCII). One of the best features of regex is that once you've learned the syntax, you can use it in many programming languages.

Admittedly, my excitement in finding a solution to my `valid_move?` method problem was met with some hesitation. Though using regex is super helpful, as a newbie programmer, I still struggle with writing the proper syntax to have it work in my code. My next move for this project involved figuring out how to write the regex I needed to make my method work. As with many things code related, it required some help from our good old friend.. the internet. In my search, I came across several sources that were beneficial, and thought they are worth sharing. 

[Regex Tutorial by Jonny Fox](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)

A tutorial that is separated between basic, intermediate, and advanced usage. The basic overview provides information on anchors, quantifiers, and character classes.

[Rubular: A Ruby regex editor](https://rubular.com/)

Rubular is an awesome tool for visualizing what gets matched by a specific regular expression in Ruby. I use this tool pretty much every time I use regex. 

[Regex Cheat Sheet](https://www.rexegg.com/regex-quickstart.html)

Another regex cheat sheet website that is a bit more extensive. It includes tables on various topics, such as: characters, whitespace, anchors/boundaries, and logic used in regex.

[How to Test If A String is a Number in Ruby](https://stackoverflow.com/a/5661783)

This is the page on Stack Overflow that helped me with my Tic-Tac-Toe project.

After researching and using Rubular to test that my regular expression matched the pattern, I successfully finished my `valid_move?` method.

```
  def valid_move?(string_index)
    return false unless string_index =~ /^[0-9]+$/
    index = string_index.to_i - 1
    index.between?(0,8) && !taken?(string_index)
  end
```

I think it's safe to say that though regex is a bit confusing at times, it is a **mighty** tool and worth spending the time to learn. Regex adds value in writing functional and succinct code, and it is fun seeing just how funky these regular expressions can look!

