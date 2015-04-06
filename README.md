# botbot
A jokebot-based IRC bot that makes snarky comments about the falls of other users and bots.

By zippynk. https://github.com/zippynk/botbot

Based on Hardmath123's jokebot. https://github.com/hardmath123/jokebot

# Usage

botbot <host> <channel (no #)> [--ssl|--plain] <nick> [--readconfig]

The `--readconfig` flag reads all other data from the file titled `config.json` in the same directory as botbot. This installation should contain an example configuration file, titled `config_example.json`.

The `--password` flag prompts the user for a password when starting botbot. Note that you may not be able to see the password as you type it, and that this can interfere with running botbot in a location where you cannot actively input text. Does not run with `--readconfig`, as it does not apply there; the `config.json` file has an option for a password.
