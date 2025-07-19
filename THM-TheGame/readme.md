# TryHackMe - The Game

You can find this room [here](https://tryhackme.com/room/hfb1thegame).

![Room header](room_header.png)

## Looking for the flag

The room is rated as "Easy", so it shouldn't require too much effort. There is a file to download; this file include a ```.exe``` file. So, despite it has been compiled for Windows system, I want to search inside it using the ```strings``` command in my Kali system.

![strings command](strings_command.png)

This is the result:

![strings result](strings_result.png)

There are many strings in the file, but I know that the string I'm looking for starts with *THM{*. So, I can ```grep``` the result:

![strings_grep](strings_grep.png)

And I obtain my flag!

![strings_grep_result](strings_grep_result.png)

Really this room was easy, and the flag can be captured in few minutes.
