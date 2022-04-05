# Private Tools
The main projects I work on are private repositories. The main reason I decided to keep these tools private are:
- I don't want the tools to be hashed and uploaded to a AV.
- I don't want the tools to be misused for malicious purposes.
- Tools may contain private information

One day these tools may be made public, but for now I have no intent to do so.

# Moray: C2 Application
Moray is a C2 application written in Golang. This was initially developed for a Red Team Competition tool, but development is continuing afterwards since I am having a lot of fun developing this.

This application has full C2 capabilities including a multi-handler, interpreter, custom cryptography, session management, data discovery, data exfiltration, and persistence. In addition, The malware can control the mouse and keyboard on the infected machine. A side goal of the malware is to aggravate the victim by mimicking common user errors. This is achieved by pressing the caps lock key, moving the mouse to a random position, scrolling, clicking the mouse, etc. Infiltrate, exfiltrate, aggravate. 

You can read more about this tool on my website: https://f1shh.dev/posts/Moray/

# Candiru: Discord RAT
Candiru is a piece of discord spyware/remote administration tool. This application poses as a discord bot, and once added to a server gives the bot handler full administrative access to the server. The bot also has c2 capabilities, where you can add it to multiple servers and control the bot from direct messages. Using the bot, you can ban/kick members, remove posts, add reaction, send message, view hidden channels (if permissions permit the bot to see the channel), view all server members, view all server channels by category, and change nicknames. 

You can configure the bot to watch a specified channel, and any messages or images sent over in that channel will then be sent to the bot handler through private messages. This bot heavily utilizes discord buttons and embeds, to make the user experience as smooth as possible.

More information on this software can be found here: https://f1shh.dev/posts/Candiru/

# Programming for infosec
This repo is a collection of labs and classwork for my Programming for information security class. This repository is private since I believe assignments are reused year to year. That being said, I did some pretty cool things foe this class including binary exploitation.

# CompSci1
Repository with all my classwork and notes for Computer science one. Private for the same reason as Programming for infosec

# Classwork
Repo with all my notes. This includes classwork, website writeups, ctf notes and tips, and generally anything I need to write down. This repo is synced through obsidian git.
