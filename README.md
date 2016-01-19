# Logitech - CSGO game integration
This project enables game interaction between [Logitech G910](http://gaming.logitech.com/en-us/product/rgb-gaming-keyboard-g910) and [Counter-Strike: Global Offensive](http://store.steampowered.com/app/730/) via [Game Integration](https://developer.valvesoftware.com/wiki/Counter-Strike:_Global_Offensive_Game_State_Integration). Please keep in mind that this is still in development, there may be bugs and there will be new features added.

# Requirements
* [Logitech G910](http://gaming.logitech.com/en-us/product/rgb-gaming-keyboard-g910) keyboard
* [Counter-Strike: Global Offensive](http://store.steampowered.com/app/730/)

# How to Install
1. First of all, make sure that "Allow games to control illumination" is enabled in Logitech Gameing Software.
2. Extract the archive anywhere on your computer.
3. Copy the "gamestate_integration_logitech.cfg" into "./steamapps/common/Counter-Strike Global Offensive/csgo/cfg/" folder
4. Run "Logitech-CSGO.exe"

## Included effects
* Team-based background color
* Health indicator
* Ammo indicator
* Bomb animation
* Flashbang effect
* Persistent color keys

## Video demonstration
[![Demo 1](http://img.youtube.com/vi/i-QCRJIRnDY/0.jpg)](http://www.youtube.com/watch?v=i-QCRJIRnDY)

# F.A.Q.
* Q: Can this give me a VACation?

   A: No. This uses Valve's [Game Integration](https://developer.valvesoftware.com/wiki/Counter-Strike:_Global_Offensive_Game_State_Integration) for CSGO, which allows developers to read game information without accessing memory of the game.

* Q: How do I add my own custom effects?

   A: At the moment, you cannot. But I do plan on allowing users to customize which keys are being lit per effect.

* Q: Why is Logitech G910 only supported?

   A: Logitech G910 is the only keyboard from Logitech that allows for per-key lighting effects.
   
* Q: I have found a bug. How do I report it?

   A: You can report bugs here, by creating a new Issue [here](https://github.com/antonpup/Logitech-CSGO/issues).

* Q: I wish to expand this, fixing and adding my own features.

   A: Feel free to fork this repo and make pull requests with your own code. I am open for suggestions for both features and optimization. :)