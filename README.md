# CarX-Spotify-Mod

## Setup Guide

Follow these simple steps to set up the CarX-Spotify mod:
## Only works with Spotify Premium 
1. **Check Files:**
   - Ensure you have `config.json` and `SpotifyMod.zm` in your mods folder.
   - if u dont have `config.json` start the game and it should create it

2. **Create Spotify App:**
   - Go to [Spotify Developer Dashboard](https://developer.spotify.com/dashboard).
   - Create a new app with any name and description.
   - Set the Redirect URI to `http://localhost:5000/callback`.

3. **App Configuration:**
   - Select "Web API" and create the app.
   - Copy the Client ID and Client Secret.
   - Add these details to `config.json`. *(Keep these details private!)*

4. **Launch the Game:**
   - Open the game and click the "Spotify Auth" button to complete the setup.

- ToDo (Dev checklist)
  - [x] Increase Volume
  - [x] Decrease Volume
  - [x] Make Token refresh automatically
  - [ ] Display song name+author in toolbox
  - [ ] Display song image
