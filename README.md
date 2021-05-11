# DiscoTape

Hi!

This is a LaTeX package and project I made that adds some commands to help you make a dialogue tape similar to the ones in Disco Elysium.

I'm not an experienced programmer and I have never done this before, so if you see any errors, please, contact me.

The commands are simple. Slash(\) and the first four first letters of the skill you want to talk and then between braces the text, for example: \voli{Hello world} will print "VOLITION --- Hello world" With volition in purple and the text in white.

There are some exceptions:
Endurance is \con, not \endu
When "you" speak you should use \you{text}, this will print: YOU --- text
For items (ITEM GAINED: 9mm pistol), you should use \ite
Ancient reptilian brain and limbic system are \anci and \limb
For other people or objects you want to make talk use \talk{nameofthespeaker ---] and \disc{text} to the message, this will print: NAMEOFTHESPEAKER --- text
For options you should use \disc{1.-}\opt{Walk away.}, this will print: 1.-Walk away
See the pictures in the project for more help.


If you have any questions or requests, ask me!

Installing the package:

Put the .sty and the photo named tira.png in a folder called DiscoTape you have to create in the install route of the packages. To see what route is that, open miktex ---> settings ---> directories and one of them must have the "purpose: install", something like this: C:\Users\alberto\AppData\Local\Programs\MiKTeX, now enter the folder \tex\latex and create the folder DiscoTape here. You should then have a folder with the following route aproximately C:\Users\alberto\AppData\Local\Programs\MiKTeX\tex\latex\DiscoTape, here is where you have to put the .sty and the tira.png

IMPORTANT: When you finish all these steps, go to miktex ---> tasks ---> Refresh file name database, and wait a few seconds.
 

Also, I provide a .tex file with the configuration you need to have the correct format. IMPORTANT: put the tira.png in the same folder of the .tex


I think that is all, I will correct the errors as soon as possible.
