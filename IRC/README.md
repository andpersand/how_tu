[//]: # (IRC README.md)

# IRC (Internet Relay Chat)

Table of contents: 

- What is IRC (Internet Relay Chat)?
- Why do people still use IRC?
- IRC's structure
- How to setup IRC

-- Using a webchat client

-- Using Irssi

--- Installing Irssi on Ubuntu

-- How to setup Irssi to automatically connect to a server or channel on startup

-- Using Pidgin
- Registering a nickname on IRC
- Joining a network
- Joining a channel
- Other IRC commands
- Resources

## What is IRC (Internet Relay Chat)?

IRC is a chat medium that was first used in 1988. 

Something important to keep in mind when using IRC is that you will only receive messages while you're online. This means that if your friend sends you a message, but you're not online when they send it, you won't receive it. 

## Why do people still use IRC?

IRC allows you to encrypt your chat conversations together with a tool like Irssi or Pidgin. 

Personally, I use IRC because I can use it directly in Terminal, which makes me feel _really cool_. To run IRC in Terminal, you can use a program like Irssi. It looks like this on my setup:

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

### Using Irssi 

Irssi is free software that you can use on a UNIX operating system. This includes Linux, MacOS, BSD, Solaris, Cygwin, and others. 

To get Irssi, head to the download page here: https://irssi.org/download/

Select your operating system from the list and follow the instructions. 

#### Installing Irssi on Ubuntu

To install Irssi on Ubuntu, you'll need to do it in terminal.

To install Irssi, open a terminal window (you can do this by pressing Ctrl + Alt + T), then enter the following:

`sudo apt install irssi`

You will be asked to enter your password. Once you've done that, the install process will begin.

(Running into issues installing Irssi on your Ubuntu system? Check out our Ubuntu guide for help.)

Once you've installed Irssi on your Ubuntu system, you can run it by entering the following into a terminal window:

`irssi`

You'll see the irssi startup screen in your terminal window. From here, you can join a network by entering the following:

`/network [network name]` 

Once you've joined a network, you can join a channel on that network by entering the following: 

`/join [#channelname]`

replacing '[#channelname]' with the name of the channel you want to join. Remember that channel names start with the # symbol. 

Some channels may require you to _register_ your nickname before you can join. For instructions on how to do this, skip to the _Registering a nickname on IRC_ section below. You should probably register your nickname anyway, just to make sure that others can't use your nickname and pretend to be you.

#### How to setup Irssi to automatically connect to a server or channel on startup

This is one of my favorite things about Irssi. It makes it so easy for me to keep on top of my IRC messages; all I have to do is open my terminal at the beginning of my day, and type the 'irssi' command. Irssi does everything else for me automatically (including connecting to networks, channels, and registering my nickname), which means I don't have to worry so much about missing important messages. 

### Using Pidgin

Pidgin is one of the easier-to-use IRC clients available, and it also allows you to encrypt your chats. 

Some channels may require you to _register_ your nickname before you can join. For instructions on how to do this, skip to the _Registering a nickname on IRC_ section below. You should probably register your nickname anyway, just to make sure that others can't use your nickname and pretend to be you.

### Registering a nickname on IRC

### Joining a network

To join a network, enter

`/network [network name]` 

replacing '[network name]' with the name of the network you'd like to join.

### Joining a channel

To join a channel, enter

`/join [#channelname]`

replacing '[#channelname]' with the name of the channel you want to join. Remember that channel names start with a # symbol.

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

>> Irssi's official startup guide. This will show you how to setup Irssi.


