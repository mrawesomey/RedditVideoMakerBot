# Reddit Video Maker Bot 🎥

All done WITHOUT video editing or asset compiling. Just pure ✨programming magic✨.

Created by Lewis Menelaws & Heavily modified by [Jason Cameron](https://github.com/JasonLovesDoggo)

https://github.com/JasonLovesDoggo/RedditVideoMakerBot/tree/master/examples

## Motivation 🤔

These videos on TikTok, YouTube and Instagram get MILLIONS of views across all platforms and require very little effort.
The only original thing being done is the editing and gathering of all materials...

... but what if we can automate that process? 🤔

## Disclaimers 🚨

- This is purely for fun purposes.
- **At the moment**, this repository won't attempt to upload this content through this bot. It will give you a file that
  you will then have to upload manually. This is for the sake of avoiding any sort of community guideline issues.

## Requirements

- Python 3.6+ (3.10 is recommended tho )
- Playwright (this should install automatically in installation)

## Installation 👩‍💻

1. Clone this repository
2. Rename `.env.template` to `.env` and replace all values with the appropriate fields. To get Reddit keys (**
   required**), visit [the Reddit Apps page.](https://www.reddit.com/prefs/apps) TL;DR set up an app that is a "script".
   Copy your keys into the `.env` file, along with whether your account uses two-factor authentication.
3. Run `pip3 install -r requirements.txt`
4. install [SoX](https://sourceforge.net/projects/sox/files/sox/)
5. Run `playwright install` and `playwright install-deps`.
6. Run `python3 main.py`
7. Enjoy 😎

## Contributing & Ways to improve 📈

In its current state, this bot does exactly what it needs to do. However, lots of improvements can be made.

I have tried to simplify the code so anyone can read it and start contributing at any skill level. Don't be shy :)
contribute!

- [ ] Creating better documentation and adding a command line interface.
- [x] Allowing users to choose a reddit thread instead of being randomized.
- [x] Allowing users to choose a background that is picked instead of the Minecraft one.
- [x] Allowing users to choose between any subreddit.
- [x] Allowing users to change voice.
- [x] Checks if a video has already been created
- [x] Light and Dark modes
- [x] Nsfw post filter
