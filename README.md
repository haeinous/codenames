# Codenames spymaster helper
This is a tool that helps Codenames spymasters, who give one-word "hints" to their agents . Enter two or more words and the program will give you a list of terms that could serve as potential hints
This helps spymasters come up with good clues for their agents.

## What's Codenames?
Codenames is a really fun board game! You can read more about it on the [Codenames Wikipedia page](https://en.wikipedia.org/wiki/Codenames_(board_game)) and the game's [official website](https://czechgames.com/en/codenames). It's likely sold at a mass retailer near you (or online).

## How do I use this program?
Here's what you need to do:
* Download the codenames.py file and save it on your Desktop.
* If you have a mac, open terminal (command + space, type terminal, and press enter).
* Type `pip install python` and press enter (this installs Python 3).
* Type `pip3 install python-datamuse` and press enter (this installs the [Datamuse module](https://pypi.python.org/pypi/python-datamuse)).

Now you're all set to start using the program. Here's what you need to do to get started:
* Type `cd Desktop` and press enter.
* Type `python codenames.py` and press enter.
* Follow the instructions on that appear on your console and you're all set!

### Some examples
The program only works sometimes, and generally when you have fewer words (two works best).

Here are some examples where the program did good:
* [__cold__, __key__]: facts, hot (like hot key!!)
* [__ninja__, __green__]: turtle (!!), and a bunch of other less relevant terms
* [__chocolate__, __mug__]: milk, and a bunch of other less relevant terms

Here are some examples where I was disappointed:
* [__octopus__, __teacher__]: whose, great, young, female, male (as a human, I would've used "biology" as the hint)
* [__doctor__, __back__]: didn't turn up anything (I would've gone with "spine," "orthopedics," or "chiropractor.")
* [__piano__, __teacher__]: lessons, students, conservatory, studied, ballet, teaching, old, excellent, beloved, wonderful (I would've gone with "music")

## What's next?
The program as it currently exists isn't that great. I think there are three ways I can improve it:
* Simple fixes to improve the program's current features (improving UX, making the scoring system more sophisticated so it penalizes words that have a large score differential)
* Expanding data sources beyond the datamuse API to [Wordnik](https://www.wordnik.com/about), [Wikipedia](https://www.mediawiki.org/wiki/API:Main_page), and others.
* Adding more game features: This program only really works for 2-4 words, whereas in Codenames you start off with 8-9 words. The program could analyze all words, and suggest a few hints for 2-4 words. It could also take into account the black sudden death card (and your opponents' words/cards) and strike out any potential hint that could end the game or give you opponent a leg up.

## Resources
If you want to use the Datamuse API in Python, be sure to check out this client library on GitHub: https://github.com/gmarmstrong/python-datamuse
