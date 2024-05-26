# Phantasy Star Online Episode 3 Plus
Phantasy Star Online Episode 3 Plus is a modification for the NTSC-U version of Phantasy Star Online Episode 3.

To play this modification online, the server must explicitly support it, or there may be save data loss or strange behaviour. [newserv](https://github.com/fuzziqersoftware/newserv) instances may support this; [ragol.org](ragol.org) is a public server with support for this modification.

This modification was originally created by **Gigobooma** (previously known as **Eyce**) with help from [fuzziqersoftware](https://github.com/fuzziqersoftware).

**Table of contents**
* [Installation](#installation)
    * [newserv setup](#newserv-setup)
* [Features](#features)

# Installation

Currently, these installation instructions require the usage of a Windows program, so you will need a Windows PC or a way to run Windows programs, such as Wine.

You will need to provide your own NTSC-U iso copy of the game.

1. Download [GCRebuilder](https://gamebanana.com/tools/6410)
2. Open GCRebuilder, click Image and load your copy of Episode 3.
3. Right-click the root folder and extract it to anywhere on your computer, then close GCRebuilder.
4. Download the latest release from the releases page.
5. Place all files from the release into the extracted root folder.
6. Open GCRebuilder again, click Root, then Save and enter the name of your patched ISO.
7. Click Root again, then Rebuild, and wait for it to finish.

Once you have patched your copy of the game, you may now load it using homebrew, a softmodded Wii, or Dolphin.

## newserv setup

If you are planning to play online with Episode 3 Plus on your own [newserv](https://github.com/fuzziqersoftware/newserv) instance, you must set it up to support the Plus card definitions file, or you may experience save data loss as the server will load the original card definitions file when connecting online.

Simply download the `card-definitions.mnr` file in the `server-files` folder, and place it in newserv's `system/ep3` folder, and reload the server or `ep3-cards` to finalise the set up.

# Features

Episode 3 Plus features the following modifications:

- All cards (except E-Rank) are avaiable in every mode at CLv 1, with equal drop rates
- 100 previously unobtainable cards available to collect
- All story characters are available when making a new character
- All COM decks are available when making a new character
- 10 cards are obtained after battles regardless of rank, win, or loss
- SEGA's official C.A.R.D. revo changes applied offline
- 23 cards rebalanced for Episode III Plus
- Booooo and Laughter sounds added to the sound board
- Many, many text fixes for card and ability descriptions
