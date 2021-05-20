# Pyautogui-Bot

It is a very easy task and requires very short script to be written but for a change it feels amazing when you get the bot ready.

Demo of the bot playing Piano Tiles is provided in the [video](https://github.com/Taresh-oss/Bot-playing-Piano-Tiles/blob/main/Piano%20tiles%20BOT.mp4)

To try making such bot, the libraries that required are: 
- pyautogui
- win32api
- win32con


The major concept is fetching the pixel values that you want your pointer to point at. The area of the game from which the pixels have to be selected is basically, the four lanes which have the piano tiles on them. So we have to get the coordinates of those pixels and pass those coordintes along with the pixel's RGB values being Black (0), so that the mouse clicks on that particular area and for that you just have to run the given line of code and copy those pixel values to your script:

```Python
import pyautogui 
pyautogui.DisplayMousePosition()
```

As we want our bot to click on piano tiles, we can get the RGB values of that pixel using the same function mentioned above and pass 0(Black) for the RGB value as I have mentioned in my code.

Link of the game on which my bot worked is:
https://www.agame.com/game/magic-piano-tiles

