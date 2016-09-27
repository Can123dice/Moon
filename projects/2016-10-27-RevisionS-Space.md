---
layout: post
title:  "RevisionS.Space"
date:   2016-10-27
excerpt: "a productivity app for revising individual sentences"
project: true
comments: false
---
Revisions.space is a productivity app for writers to help with revising individual sentences.

ROLES: Development\UI\UX

RevisionS.Space started out as a way for me to learn Python and Natual language processing simultatniously. It tries to solve an emidiate need I have, manipulating sentences given set constraints. I could not find any comparable services at the time.

I started out prototyping way to early in the first itteration, and I ended with something that was far removed from my original vision after quite a few months. The scope was also far to broad. In the first few iterations included extra modules and even a worskpace for tracking revisions. It was humbling to go right back to the planning stages. My initial user tesing (I know,I know :-P) came up with quite a few surprising insights. This was simply a paper and pencil interview after doing a walkthough of the system as it was at that stage. The word manipulation was only a side avennue, eliminated everything else and kept the word manipulation workspace. At this stage I was already using the module straight from my IDE to do rule based phrase completion for myself, based on two custom database and the NTLK libraries and simply copying the output to my clip board. 

The challenge shifted to how to represent the data returned from the module in a meaningfull way.
There was a lot of data that had to be represented on screen, and too me it was quite obvious on how the results are structured,even just as a set of unordered lists. I also had to refine the workflow.

All the data returned has to be represented on screen, not only for one word, but for all of the words in the phraze. That makes for a very cluttered workspace. Encourage the user to manipulate the words and change the word order if the felt like it, changing the rhyme and rhythm of the phrase.

The other big challenge was with the user interface. How would I represent an empty space in a phrase, as a user accesing the app from the user interface. It is the question I am working with at the moment. For now, users have to type in a word similar in length\structure/part of speech/rhythm.
