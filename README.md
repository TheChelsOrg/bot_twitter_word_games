# Word Games Bot for Twitter

> This repo contains two game types that post on twitter.

## MssngVwlsRnd

Missing Vowels Round Style Game for Twitter. Based on the game seen in the TV show, Only Connect, will tweet a player's name from the CSV file after removing all the vowels and spaces from the string. The answer is tweeted 10 minutes later.

## Anagrams

Anagrams are a simple shuffle of the characters of the player's names and tweeted, the answer is tweeted 10 minutes later.

## Architecture and Code

The repository is made up of a CSV file that needs to be kept up to date with player names. The rest are python scripts in the `python` folder - these are used by scheduled GitHub actions. These actions run on the latest ubuntu, install python and some some packages. It runs the code then completes, deleting the inftastructure hosted by GitHub.
