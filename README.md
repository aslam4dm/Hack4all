# Hack4all
A program used as a reference model for hacking/penetration testing. Contains favorite hacking/security commands in an interactive environment 
# rulez 
Add all good tools, commands, links and stuff onto the all_hack.txt file following the specific rules:
anything to do with hacking placed within the correct category, line must start with a '$' symbol one white space, and then command/tool name

e.g.
$ nmap -T4 -sS -f -O 192.168.2.0/24. -oA
$ tool (arguments)

the reason for this, for the moment is that the code uses split('$ ') to determine what is part of the cool hackery content on the file

the purpose of this stupid little project is that it could be used as a model/guide while doing ctfs, hacking or whatever all in a shell, thus you can hack away while the commands are there for copy/paste or just as hints/tips in an interactive shell rather than one large .pdf, .txt, .docx whatever.

This isn't anything big or huge, it's very non-technical, but hopefully useful to myself and you if you want to use it?
