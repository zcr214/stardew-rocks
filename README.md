# stardew-rocks

Stardew Rocks is a tool for Stardew Valley that collects saved games and shares them with the community. 

We create and share screenshots of your game with everyone - no complicated setup needed!

Discord server for stardew.rocks chat: https://discord.gg/0tpEyZrnOVQKA93b

# For Farmers

Install the Stardew Rocks client to share your farm state with the rest of the community! Farm screenshots will automatically appear here every time your game is saved: http://stardew.rocks (website is work in progress, hehe).

 - [Download Stardew Rocks!](https://github.com/nictuku/stardew-rocks/releases/download/v0.5/stardew_rocks.exe)

WARNING: 64-bit executable only for now. Sorry. See issue #2 for details.

Just download the .exe file and run it. It stays on your system tray and looks like this:

![Screenshot](assets/img/systray.png)

You can right click on that icon to close it.

The app is configured to run on startup for you. If you don't want that, just rename the *stardew_rocks.exe* executable to something else and it won't start automatically anymore.

Screenshots look like this:

![Farm Map](view/map-Aerlia_1458278945.png)

The screenshots are not perfect yet, but we're working on it as fast as possible!

# For Developers

The ampq URL is: `amqp://guest:guest@amqp.stardew.rocks:5672/`

We currently publish the following exchanges:

 - "SaveGameInfo-1" receives raw uncompressed XML files with contributors' SaveGameInfo.
 - "OtherFiles-1" receives raw uncompressed XML files with the super-large file saves.
 
# Planned features

- Authentication of some fashion
- Prettier farm maps
- A slick website showing people's farms!

# Thanks to our testers!

freaky-m0, Beener, Kylindra, Dristan
