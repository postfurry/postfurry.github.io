---
title: Getting Connected
categories: muck, muck-help
---
# [MUCK Help](/muck/help) &raquo; Getting connected

The first thing you can do to make things easier for yourself is to get a MUCK Client.  This is a program that will store connection info, present MUCK activity in a reasonable way, and make it a lot easier to interact with. Here's what we think are the best clients for the various OSes:

* **Windows**
    * [BeipMU](http://www.beipmu.com/)
    * [MUSHClient](http://www.mushclient.com/mushclient/mushclient.htm)
* **Mac**
    * [Atlantis](http://www.riverdark.net/atlantis/)
* **Linux/Other UNIX**
    * [KildClient](http://kildclient.sourceforge.net/phpwebsite/index.php)
    * [TinyFugue 5.0](http://tinyfugue.sourceforge.net/) (Command line)

Each client has a different method for setting up a connection, but they'll all ask for a server and port.  For Postfurry MUCK, these should be:

    Server: muck.postfurry.net
    Port:   4444

(If your MUCK client supports SSL/TLS, you can set that option on and connect to port 5555 instead, to encrypt your connection)

You will know you are correctly connected when you see a wecome screen, which is a big triangle design and a link to this website. This is where you will provide your login info.

Many clients can be set up to automatically proide your login info. Check out the website for your MUCK client to see if it has instructions for how to set this up.

If your client doesn't automatically set up your connection information, all you have to do is type the following at the login screen:

    connect [name] [password]

For instance, if your name is Rory and your password is "secret" (Let's hope it's better than that!) you'd type:

    connect Rory secret

Hit Enter, and you're in!

[Next: Basic Interaction &raquo;](basics)
