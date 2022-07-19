# Glitchless Parts
[Video Example of AutoSplit](https://www.youtube.com/watch?v=h3mA_OdqE2w)

Glitchless Parts is a project that allows you to practice different parts of the full game, instead of ILs, with LiveSplit
auto split support. The idea is that practicing sections instead of the IL is more beneficial to your muscle memory, as it makes 
you learn how to go from map to map without just doing full game runs.

The game has been split up into 5 different parts:

```
- Part 1: 00/01 through 04/05
- Part 2: 06/07 through 10
- Part 3: 11/12 through 15
- Part 4: 16    through 18
- Part 5: 19    through e02
```

SiDiouS and I tried to part out the full game by deciding where the game "changes pace" in terms of play style.
It shouldn't be too difficult to use this as a reference to make your own part splits, but I personally like these.

## Files Included

In the zip file included in the releases section, there are splits files for all 5 parts, a layout file, and saves. The
saves aren't necessary, you can use any IL save as long as it transitions from the previous map to the first map in the
part you are running. The layout provided is nice because it works for all 5 of the parts.

Lastly, all the splits contain a "Sid" comparison, which are split times that SiDiouS reasonably obtains RTA. This is a
brutal thing to compare against for most people, but it can help highlight where you might be bleeding the most time.

## Setup

1. Download the [latest release of Glitchless Parts](https://github.com/ChrisUMB/glitchless-parts/releases/download/release/Glitchless-Parts-v1.0.zip) from the GitHub releases section
2. Download the [latest version of SourceSplit](https://drive.google.com/drive/folders/1HAlTbF91NEzJVgzpmxlwhjv7JEZZGCAK) maintained by 2838 (at the time of writing is 3.2.3.3)
3. Unzip the zip file somewhere, most likely in your Portal speedrun folder
4. Open the splits file for the part you want to practice, and make sure you swap the comparison to Game Time
5. Load an IL save for the first map in the part, or one of the saves provided in the zip file. The splits should auto start,
split, and end

## Why?

I made this mostly for myself, because I believe practicing in sections is better than ILs without the struggle of just
brute forcing runs over and over. Previously, the only way to practice parts like this was to auto-start splits and, if
I remember correctly, also split manually. Thankfully I was able to ask 2838, the maintainer of SourceSplit, if he could
add a way to auto-start splits on map transitions, and he did so within hours of me asking, so a huge thank you to him.