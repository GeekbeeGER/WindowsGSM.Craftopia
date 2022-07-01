# WindowsGSM.Craftopia

WindowsGSM plugin that provides Craftopia Dedicated server support!

# The Game
https://store.steampowered.com/app/1307550/Craftopia/

# Requirements
WindowsGSM >= 1.2x.x

7 GB Disk space

# Server Ports
TCP: 6587, 27015-27030, 27036-27037

UDP: 4380, 27000-27031, 27036

# Server Configuration
You can find your "ServerSetting.ini" file in your "serverfiles" folder.
If you want to use a password, you need to change

usePassword=0 to usePassword=1

And with

serverPassword=123456

you can choose a password. Keep in mind, that the password can only be numbers at this time!

# Converting your Singleplayer World into Multiplayer

To convert your Singleplayer world into Multiplayer you have to open the following folder:

C:\Users\%USERNAME%\AppData\LocalLow\PocketPair\Craftopia\save

This is your singleplayer savegame, you can now copy this into your serverfolder!
Copy everything beside the "steam_autocloud.vdf" file!

Now go into "ServerSetting.ini" and change

name=NoName

into the name you put your world's name, mine for example would be:

name=Aincrad






