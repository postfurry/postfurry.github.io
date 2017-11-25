---
layout: muckhelp
title: Muck Help &mdash; Basics
categories: muck, muck-help, muck-help-basics
---
# [MUCK Help](/muck/help) &raquo; Basics

Hopefully by now you've successfully connected to the MUCK, so it's time to learn a few MUCK commands.  In this doc, when we talk about commands, they will be on their own line, in monospaced font,

    like this.

Also, most commands will need something filled in by you, representing what you want to say, do, etc.  For these, the part to replace will be marked by [...].  You don't need to type the [ or ] characters, just replace them with what you want.

One more important note before we get into specific commands.  Most commands have help text available, almost always by typing the command followed by the text `#help`.  For instance,

    wa #help

will give you help on the 'wa' command.  But we'll cover more about that later.

## Orientation

When you connect, you'll be in "Outside", where new players start from. There's not much to do here, so the first thing to do is move to another room. Moving is a command like any other, so the first thing you'll want to do move to a more central location by typing:

    drift
    
Type that and hit enter, and you'll see a new block of text appear. There's the room name (Possibility Space, Sector #877), the room description, and a list of room contents. The room contents includes other players, you can tell these because they will have `[asleep]` or `[awake]` after the names. "Awake" means the player is connected to the MUCK right now; "asleep" means they're disconnected. On a MUCK, disconnected players stay in the room they were last in, unless someone sends them home.

When you're wandering around the MUCK, you can always use the `drift` command to get back to this Sector #877 location, which can be very helpful when exploring, since all other public locations on the MUCK are ultimately connected back to that one.

## Talking and Acting

One of the main things you'll want to do on a MUCK are interact with other characters there.  The basic command for this is the `say` command, used like this:

    say [message]

For instance, if your name is Rory, and you type

    say Hello!

Everyone else in the room you are in will see

    Rory says "Hello!"

and you will see

    You say "Hello!"

There's more you can do than talking.  Often, you'll want to act something out as well.  For this, use the `pose` command.

    pose [message]

If you do

    pose waves!

everyone in the room, including you, will see

    Rory waves!

Since the `say` and `pose` commands are so commonly-used, they each have shorter versions.  These are `"` and `:` respectively.  So, for the examples above, you'd get the exact same results with

    "Hello!
    :waves!

Note that for the `"` command, you don't need a closing quotation mark, that'll get added for you.

[Next: Meeting Others &raquo;](meeting-others)
