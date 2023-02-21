# grapple-boy
_Grapple Boy_ is a platforming action title being developed for the Bandai WonderSwan as a part of the Senior Capstone Project course at the Marine Academy of Technology and Environmental Science. The game is built using the _C_ programming language with the ability to port the game to the system using the WonderWitch Developer Kit released by Bandai. The game follows the titular protagonist using his grappling hook to swing around and traverse levels.




cd C:\

C:\WWitch\lsic86ww\bin

C:\WWitch\bin\mkfent.exe

lcc86 -IC:\Development\WWitch\include\ -LC:\Development\WWitch\lib\ -LC:\Development\WWitch\lsic86ww\lib\s\ -o hello.bin hello.c

STEPS FOR C TO FX FILE CONVERSION:
Step 0: Run Setup.bat to ensure proper functionality
Step 1: open command prompt on windows 10/11, and navigate to C:\ directory using "cd C:\" command.
Step 2: navigate to lcc86 in lsic86ww\bin folder
Step 3: Run Command shown above, with file names changed as nessesary. (MAKE SURE C FILE IS IN SAME FOLDER)
Step 4: Move created folder to C:\WWitch\bin\mkfent.exe to create the .fx file.
Step 5: Run "C:\WWitch\bin>mkfent -f (Insert file name).bin" to create .fx file.
Step 6: Profit????????

Converting BMP images to sprites:
C:\WWitch\bin>bmpcnv
bmpcnv -cformat.txt Mario.bmp Mario.h
