---
layout: post
title: Public Building
categories: []
tags: []
status: publish
type: post
published: true
meta: {}
---
A number of folks have asked about how to build new public areas on the MUCK, which is awesome. (Just as a reminder though, all the old locations are still there too, and it's totally cool if you want to hang out at old places as well!)  The new Possibility Space hub is set up to encourage adding new places nearby. We already have one new place, a new Bazaar, reachable from there, and we'd love to see more.

MUCK building is a bit complex, and it's not covered in the guides on our site yet, so in the meantime, here's [a guide](http://www.avians.net/snowfeather/Mucks/MuckBuilding.html) that does a good job of covering the basics.

In addition to the commands in there, we also have the @xdig command, which speeds up building a lot since it lets you create a room and the exits into and out of it all at once.  This is also the easiest way to create a room connected to Possibility Space; the @xdig program is set up to allow anyone to create an exit and room from there.  Type `@xdig #help` for more info on how to use that.

If you want your place to be easy to get to, there's a few other things that you'll probably want to set up too:

* It's a good idea to have a section at the bottom of your room description that describes the general feel the room is going for.  Is your room geared toward particular kinks, or other activity?  That's the place to put it. We usually refer to this as the 'vibe' of a room, not as strong as a theme or a set of rules (though you can have those too if you think you need them), but just some pointers toward general feel.  Usually this is in the desc inside double brackets, like so:
: `[[ Vibe: <whatever> ]]`

* To make it easy to get to your place, you'll probably want to add it to the global teleport list.  Anyone can do this, using this command:
: `t #gadd <name>=<room dbref#>`

* You can also have your place show up on the WhereAre list.  Make sure to set both the text shown when typing just wa as well as the direction info shown in wa #dir.  To do this, use these commands in the room you want to be listed:
: `wa #set <comment>`
: `wa #setdir <directions, like 't place'>`

If you have any questions, don't hesitate to contact the staff, we're always happy to help!
