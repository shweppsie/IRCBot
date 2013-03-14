IRCBot
======

An IRC Bot which connects to a channel and relays messages sent to it over a socket.

Installation
------------

All you need to run IRCBot is python and the irc library.

If you have pip installed then installing the irc library is as easy as:

`pip install irc`

Operation
---------

  * Running the bot is as follows

`ircbot <bindaddress:port> <ircserver[:port]> <channel> <nickname>`

  * When using bash remember to escape # symbols

`ircbot 127.0.0.1:4567 irc.shweppsie.com \#test testing`

  * With the above command you can do the following to post messages to the channel

`echo "Hi" | telnet 127.0.0.1:4567`
