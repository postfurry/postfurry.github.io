---
title: Looking Good
categories: muck-help
---
# Looking Good

You've seen some of the details on other characters now, like gender, species, and description.  Now you can set those up yourself.

Basic properties are most easily set up using the `editplayer` program.  This presents you with a menu of a number of settings you can set on your character. Just select one of the numbered options, and follow the directions, and `Q` when you're done.  Also, at any point in an interactive program like editplayer, you can use the `@Q` command to quit out of the program immediately, without having to return to a menu.

The most important options for now are 2, 3, and 4.  Options 3 and 4 set your gender and species, as shown in the ws listing. Option 2 lets you set what someone sees when they look at you.  When you first run this program, you may see a message:

    Would you like to convert this description to standard MPI (this may not work for complex MPI or MUF-based descriptions)? (YES/no)

Just respond 'yes', this will put you into an editor program that allows you to write a long, multi-paragraph description.  This editor is powerful but a bit complicated, the best way to use it as a new user is to write up a description in another text editor.  Once you're satisfied with your description, you can simply enter the description editor, copy it, and paste it in all at once.  Once you paste it, type `.end` and you should see the complete description listed in the menu. (Hint: If you want blank lines in your description, put a single space on the line, or it might get skipped in input)

## Further Personal Information

Many characters have more information entered past just gender, species, and description.  Other commands are available to show detailed character info, and roleplay preferences.

First, there's an easy and fun way to show what you're interested in when it comes to roleplay, the `wi` command, short for "WhatIs".  To see someone's wi info, just type `wi [name]`  You will get a list of interests, from a large master list.  You can type just `wi` to se the wi listings for everyone in the current room.  Using `wi #flags` will show you the full list.  The easiest way to set up your own wi listing is to look through that list, marking down each thing you're interested in in a text editor, all on one line.  Then, you can just enter

    wi #set [big list of flags]

and you'll be all set up.  For instance, to show your interest in cyborgs, psionics, and romance, you'd do

    wi #set cyb psi rom

If you're not sure what any flags mean, be sure to ask your fellow players.  They'll likely be happy to explain, possibly at length.

Next, there is `pinfo`, short for "Player Info" which lets you give long-form information that doesn't necessarily fit into a description.  You can see another cuaracter's info by typing `pinfo [name]`, and you can see how to set your own by typing `pinfo #help`.
