[//]: # (IRC README.md)

# IRC (Internet Relay Chat)

## What is IRC (Internet Relay Chat)?

IRC is a chat medium that was first used in 1988. 

Something important to keep in mind when using IRC is that you will only receive messages while you're online. This means that if your friend sends you a message, but you're not online when they send it, you won't receive it. 

## Why do people still use IRC?

IRC allows you to encrypt your chat conversations together with a tool like irssi or Pidgin. 

Personally, I use IRC because I can use it directly in Terminal, which makes me feel _really cool_. To run IRC in Terminal, you can use a program like IRSSI. It looks like this on my setup:

[//]: # (image of IRC in terminal)

(I feel like a HACKER)

I also use IRC because the Tor Project uses it for most of their meetings. 

## IRC's structure

Network > Server > Channel

On IRC, you can either chat with groups of people in _channels_, or you can chat privately with people who are on the same _network_ as you are. 

Channels are hosted on servers, and servers are hosted on networks.
Channel names begin with a # symbol.

## How to setup IRC

Before we get started setting up an IRC client, we first need to know what network we want to connect to. 

We can only chat with people who are on the same network as we are.

If we want to connect to a specific channel, we'll need to know what network hosts that channel. 

For example, the Tor Project channels are hosted on the OFTC network. 
So, in order to connect to a Tor Project channel, we'll need to first connect to the OFTC network.

So, now that we know what network we want to connect to, we can continue the process of setting up IRC.

### Using a webchat client

Some IRC networks, like OFTC and undernet, have their own online webchat clients. These webchat clients allow you to chat directly from your internet browser, without installing any extra software. 

For this example, we'll use OFTC's webchat client, available here: https://webchat.oftc.net/

On the OFTC webchat page, you'll be asked to enter a nickname and any channels you want to connect to. 

Pick any nickname you'd like to use, and enter a channel in the channel box. If you don't know any channels, you can enter #oftc for now. This is the OFTC support channel.

Click 'Connect' to connect to the channel.

Congratulations! You're using IRC. 

Some channels may require you to _register_ your nickname before you can join. For instructions on how to do this, skip to the _Registering a nickname on IRC_ section below. You should probably register your nickname anyway, just to make sure that others can't use your nickname and pretend to be you.

### Using irssi 

Some channels may require you to _register_ your nickname before you can join. For instructions on how to do this, skip to the _Registering a nickname on IRC_ section below.

#### How to setup irssi to automatically connect to a server or channel on startup

This is one of my favorite things about irssi. It makes it so easy for me to keep on top of my IRC messages; all I have to do is open my terminal at the beginning of my day, and type the 'irssi' command. irssi does everything else for me, which means I don't have to worry so much about missing important messages. 

### Pidgin

Some channels may require you to _register_ your nickname before you can join. For instructions on how to do this, skip to the _Registering a nickname on IRC_ section below.

### Registering a nickname on IRC

### Joining a network

To join a network, enter

`/network [network name]` 
### Other IRC commands

The most helpful command in IRC is the 'help' command. To use it, enter 

`/help`

into the message entry field.

The help command will show you all available commands. 

If you'd like more information on how to use a command, enter

`/help [your command]`

into the message entry field, replacing '[your command]' with whatever command you want to learn more about.

## Resources

> https://irssi.org/documentation/startup/

>> irssi's official startup guide. This will show you how to setup irssi.


