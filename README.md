## PLEASE READ THIS NOTE

Thanks for showing interest in my project. I know the code is a bit messy, it still works well.
In the next update I add either online play or upgrade singleplayer.

Put your thoughts down in the issues section.

PLEASE KEEP DOWNLOADING THE LATEST VERSION OF THE GAME AS THEY CONTAIN BUG FIXES AND 
PERFORMANCE OPTIMISERS.

Notify me in the issues section if you have anything to say (bug reports, suggestions, ideas, etc).

# My-PyChess
A Multiplayer/SinglePlayer Chess app written in Python using Pygame Library.

## Welcome to PyChess!

This is a python app purely created from scratch using just Python(version 3.7.3) and Pygame.

This game does not support Python 2 and some of the older versions of Python 3.
(Python 3.5 till Python 3.7.3 supported and tested)
(may even work on Python 3.3 and 3.4)
It even needs a roughly recent version of pygame to work.

To run the game, download the file and run the main.py file.
Choose from the menus options.

If you choose multiplayer, you will see the chess board appear. Go ahead and enjoy the chess match with your friend.

Singleplayer is a random move generator for beginners.
Harder levels of difficulty coming soon.
You can save/load games.

If you take a look at the source code, you can observe that Object Oriented Programming style has not been used.

To explain in short- how the logic works in the chess game,
- Pygame provides the tools for GUI and mouse motion handling.
- There are 2 lists that hold the position of each piece.
- The functions are written, each with a specific use to handle data and play chess.
- This encorporates almost all the features of chess(except en-passant).

Feel free to download the code, use it and please notify me if you come across bugs and glitches.

## How to customise the game Using Preferences

- In the main game menu(You see this after running main.py), click preferences.
- Here you have a few settings(more coming soon).
1) Animations: When this is True, it will show the pieces that you move to slide smoothly(recommended to be True always, look better).
2) Sound: When this is True, it will play sounds(recommended to be False for now, I am working on it)(a placeholder for future upgrade).
3) SlideShow: When this is True, it will show a slideshow of images on main menu (recommended to be True always, look better).
4) Show moves: When this is True, it will show all legal move options for a selected piece during gameplay (recommended to be True, highly helpful for beginners (my favourite feature)).
5) Undo: When this is True, it allows users to undo(recommended to be True)(a placeholder for future upgrade).
6) Border color: RGB colour Code for chess board borders.
7) Screen size: Size of the screen (a placeholder for future upgrade).

- RE-RUN THE GAME TO APPLY NEW SETTINGS.
- You can also open preferences.txt and edit the file there (not recommended to do unless you know what you are doing, it might spoil the app if you do it the wrong way).

## What's New in this Version 2.2
- Minor performance upgrades
- Further upgraded preferences.
- Upgraded loadgame menu.
- Minor changes made to the interface.
- Placeholder code added to comply with future updates.

## What was New in Version 2.1
- The upgrade optimised the game even further, fixing a bug.
- When you click a piece, it shows all the available spaces it can go.
- The upgrade added a new preference Menu where you can customise some game features (read the note above).
- The upgrade adds background animations on the home menu.

## Wha was New in Version 2.0

- Revamped Home Menu so That it looks better.
- Fixed Bugs.
- Made some changes that ensure that it can work on all platforms.
- Further optimised the code (The game does not lag on my Raspberry Pi anymore).
- Added Save/load game features.
- Added basic SinglePlayer.

## Features
- Clean, easy to use GUI with a good homepage.
- It allows users to make only valid moves.
- It does not allow users to make moves that puts the users king at check.
- It detects check, checkmate, stalemate and informs user.
- It supports things like castling, pawn promotion etc.
- It supports saving and loading games (in a non-standard format).
- It has single player mode (random move generator which is easy for beginners).
- It has a preference menu where, you can customize the game to meet your needs.

## What's next in (v3)(planned)

- EXPECTED TIME OF RELEASE: FEBRUARY 2020
- The code will be revamped.
- Undo moves option.
- Save/load games with a new way of storing gamedata (as a list of FEN strings) .
- Online play may be added.
- Singleplayer may be upgraded.
- I WILL BE REMOVING SUPPORT FOR THE CURRENT FORMAT FOR SAVING GAMES.

## Long term Future Goals with the Game

- Clean, easy to understand code to be implemented.
- Support for Pygame v2 (which is releasing soon).
- Online Gameplay (on wlan and lan) with Chat interface.
- Better SinglePlayer.
- Adding sound effects.
- En Passant (This feature is coming soon).
