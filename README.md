# Pyautogui-Bot

It is a very easy task and requires very short script to be written but for a change it feels amazing when you get the bot ready.

To try making such bot, the libraries that required are: 
- pyautogui
- win32api
- win32con

The major concept is fetching the pixel values that you want your pointer to point at and for that you just have to run the given line of code and copy those pixel values to ur script:

```Python
import pyautogui 
pyautogui.DisplayMousePosition()
```

As we want our bot to click on piano tiles we can get the RGB values of that pixel using the same function mentioned above and pass 0 in case of black as I have mentioned in my code.



