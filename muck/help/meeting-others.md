---
title: Meeting Other Players
categories: muck, muck-help
---
# [MUCK Help](/muck/help) &raquo; Meeting Others

The main point of all this saying and posing, of course, is interacting with others, so it's helpful to know who's around, and how to get there.  If you're lucky (or clever) you're alraedy in a room with other folks in it.  To see who's around, use the `ws` command.  This is short for "Who Species", and gives a list of everyone in the room with you, and some basic info about them.

In the WS list, you may see some characters marked as [asleep].  This means they're not actually there, when someone is connected to the MUCK as a certain character, that character is awake, otherwise, they stay in the same place, marked as asleep.  Some characters may also have an idle time listed; this refers to how long it's been since they last did something on the MUCK.

Along with connection status and idle time, the WS list shows gender and species, these give some basic information about who's what, but most people also have an elaborate description, giving more detail.  To look at someone's description, type

    look [name]

This should give you a better view.  You can look at characters whether or not they're awake, you can also look at other objects in the room using their names as well.  Also, if you just type `look`, you'll take a look at the room yu're in.  Finally, the `look` command has an abbreviation too, `l` (lowercase L).

If there's no one in the room with you, or no one active, it's probably a good idea to try to find folks whoe ARE around and doing things.  There are two commands to help you find others on the MUCK.

First, the `wa` command (short for "Where Are") lists all the public rooms on the MUCK with connected players in them, and a little bit about the room. In order to see how to use the room, use the `#dir` option for the command:

    wa #dir

This will give you the room list again, but now with a list of commands to type to navigate to that room.  Commands are separated by > characters.  For instance, if the directions to a particular place are

    dream liminal > n > d

you should be able to type (hitting enter after each):

    dream liminal
    n
    d

and arrive where you want to ne.  The `wa #dir` commands should work from anywhere on the MUCK.

The second command for finding others is `fa`, short fo "Find All".  Typing that command will show you a list of whoever is online, and what room they're in (unless the character or room is set to be private). The 'fa' list doesn't show how to get to a place, since some places don't have public directions. However, if you know someone on the FA list, you may be able to send them a message to see if you can join them.

[Next: Communication &raquo;](communication)
