# FFXIVProgTracker
This is a tool for making Prog (or wipes, mostly wipes) Summary GIFs out of recorded logs in FFXIV

## Usage
1. Install [Python3.9.5](https://www.python.org/downloads/release/python-395/)
2. Download and unzip the latest version from [here](https://github.com/yaxes/FFXIVProgTracker/releases/)
3. Open cmd/terminal
4. `cd` to folder with the tool
5. install requirements by running `pip install -r requirements.txt`
6. Start the tool with `python main.py`
7. Select folder containing logs
8. It'll parse the logs and output GIF file in it's own folder

## Config

Default setup comes preconfigured for The Epic of Alexander (Ultimate) with killtimes adjusted for my group, but should be easily configurable for any other fights by editing these lines

`fightID = "80037586"` - specify fight ID, should be logline 33

`phaseColors = ['b','m','r','y','g']` - specify colors for certain phases

`phases = [1.9,2.5,5.5,11.6,18.83]` - phase average killtimes

`phaseNames = ["Living Liquid", "Limit Cut", "Brute Justice/Cruice Chaser", "Alexander Prime", "Perfect Alexander"]` - phase names


## Roadmap

Bold of you to assume i will do something much with it, i added a file picker, might do separate pre-configured files for UwU/UCoB, i guess making a readme might be useful to someone

## Credits

-[PikCeLL](https://github.com/PikCeLL/FFXIVLogParser) for making the original version of this tool

-i guess me? idk didn't do much
