---
title: Basic Interaction
categories: muck, muck-help
---
# [MUCK Help](/muck/help) &raquo; Basic Interaction

Hopefully by now you've successfully connected to the MUCK, so it's time to learn a few MUCK commands.  In this doc, when we talk about commands, they will be on their own line, in monospaced font,

    like this.

Also, most commands will need something filled in by you, represntiong what you want to say, do, etc.  For these, the part to replace will be marked by [...].  You don't need to type the [ or ] characters, just replace them with what you want.

One more important note before we get into specific commands.  Most commands have help text available, almost always by typing the command followed by the text `#help`.  For instance,

    wa #help

will give you help on the 'wa' command.  But we'll cover more about that later.

## Talking and Acting

One of the main things you'll want to do on a MUKC are interact with other characters there.  The basic command for this is the `say` command, used like this:

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

Note that for the `"` command, you don't need a closing quotemark, that'll get added for you.

[Next: Meeting Others &raquo;](meeting-others)
