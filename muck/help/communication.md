---
title: Communication Skills
categories: muck, muck-help
---
# [MUCK Help](/muck/help) &raquo; Communication

The communication commands we've discussed so far only work for characters in the same room as you.  In order to talk to others, you'll need to use the `page` command:

    page [character]=[message]

For instance, to page Indi with the message "Hi there!":

    page Indi=Hi there!

Poses also work inside pages, just start your page with the : character.

    page Indi=:waves cheerfully!

The page command has a number of shortcuts available too; the command itself can be shortened to `p`, and if you want to send another page to the person you just paged, you can leave off the name:

    p =:waves again!

You can also reply to someone who just paged you by using `#r` rather than the name.

    p #r=:waves back!

## IC/OOC Communication

There's another command, `whisper` (`w` for short), which works almost exactly like page, including all the above options, but only works for people in the same room.  Why use this rather than page, especially when you can still page someone who's in the same room anyway??  Usually, pages are considered out-of-character (OOC) and whispers are in-character (IC).  This isn't always the case, some characters have a perfectly reasonable means to communicate over long distances, so could do IC pages, but this provides a general distinction.

Speaking of IC/OOC concerns, there's one more command that's useful to make that distinction when necessary, the `ooc` command.  This prints a message to the room you're in, prepended with a marker to let everyone know it's out of character.  For instance:

    ooc I have to go offline now, sorry!

will result in

`[OOC] Someone says, "I have to go offline now, sorry!"`

As with pages and whispers, you can make an OOC pose as well by starting your message with the : character.

## Chat Channels

The other way to talk with folks in different rooms is using the chat channels.  There is one channel, the Public channel, that every character is subscribed to by default.  The public channel is usually used for casual chatter, loosely drifting between in-character and out-of-character.

Using the public channel is very similar to the ooc command:

    pub [message]

You can also turn off the public chat channel using `pub #off`.  See `pub #help` for more information.

There are also other chat channels which you'll need to join specifically.  These are accessed using the `chat` command.  Again, the syntax is similar to the above commands, and `chat #help` will give you the full info.

[Next: Looking Good &raquo;](looking-good)
