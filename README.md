# Loading Screens by BloodNBonesGaming Documentation

## Background Adding:

This adds a custom background to the loading screen if Resource Loader is installed inside of the folder resources/mainmenu/bg.png

```
background = addStretchedTexture("top_left", "mainmenu:bg.png")
background.setRelRender(1, 1)
```
## Tip Adding:

This adds Tips to the top left of the screen named Tip 1, Tip 2, and Tip 3

```
tips = addRandomText("top_left")
tips.setAbsXOffset(5)
tips.setAbsYOffset(5)

tips.addTip("tip1")
tips.addTip("tip2")
tips.addTip("tip3")
