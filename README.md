# Twitch Modgreeter
## (and meme trigger!)

OBS Browser source file that plays videos when mods chat for the first time in a while, or videos triggered by any trusted viewer via a twitch !command message (default is !meme).

### Instructions

1. Download, unzip. 
2. Add *index.html* file as browser source (local file) in OBS.
3. Place your mp4 files into same folder as index.html file.

The name of your mp4 file *must* match the name of either a mod or a meme trigger.

i.e. 

If your mod is called **bobmitch**, your mp4 file should be called **bobmitch.mp4**  
If your !meme trigger is !meme test, your mp4 file should be called **test.mp4**  

The **!meme** trigger can be changed to any command you like by clicking the **Meme Trigger** button when interacting with the browser source.

A test.mp4 file is included, so you can type *!meme test* into chat to test before adding your own.

### Configurable Options

- Timeout period for mods being considered 'away' - defaults to 30 minutes
- Meme trigger command text - doesn't have to be !meme, can be whatever you like after the !
- Ignore List - specify comma seperated list of users to ignore, like bots who are commonly mods but not considered worthy of a greeting. :)
- Channel Switch - quickly connect to another channel

