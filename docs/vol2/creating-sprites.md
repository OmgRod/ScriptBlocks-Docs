# Sprites

Sprites are a fundamental concept when developing using ScriptBlocks, so in this tutorial, we are going to show you how to make sprites.

## Loading the Sprite

First, we need to initialise our project. So, in `main.py`, we type the following:

```py
import scriptblocks
```

After this, it's time to load our `Sprite`! So, we type the following:

```py
testSprite = scriptblocks.Sprite("test")
```

This loads a `Sprite` from the sidebar with the name `test`. 

## Manipulating the Sprite

Now that we have created and loaded our `Sprite`, it's time to manipulate it! In ScriptBlocks, there are many ways to manipulate sprites, including the following ways:

### Changing the position

There are 3 ways we can change the position of a `Sprite`. The first way is to set the X position by itself:

```py
testSprite.setPositionX(50) # Change 50 to any float value
```

The second way is to set the Y position by itself:

```py
testSprite.setPositionY(35) # Change 35 to any float value
```

And the 3rd and final way to move a sprite is by setting both values at once:

```py
testSprite.setPosition(50, 35) # Set 50 and 35 to any float value
```

### Changing the visibility

When setting the visibility of a sprite, there are 4 functions to do that. The first one shows the sprite no matter what:

```py
testSprite.show()
```

The second one hides the sprite no matter what:

```py
testSprite.hide()
```

The third one toggles the visibility of the sprite:

```py
testSprite.toggleVisibility()
```

And lastly the fourth one changes the visibility based on the boolean value sent:

```py
testSprite.setVisible(true) # Use true to show and false to hide
```

### Changing the scale

The final main way to manipulate a sprite is by changing its scale. There are 6 ways to do this. The first way is to scale it only in the X axis, with 1 being 100% of the default size:

```py
testSprite.setScaleX(1.25)
```

The second way is to only scale it in the Y axis, with 1 being 10% of the default size:

```py
testSprite.setScaleY(0.5)
```

The third way is to scale it in both the X and Y axis, with 1 being 100% of the default size:

```py
testSprite.setScale(1.25, 0.5)
```

The fourth way is to scale it in only the X axis, but this time scaling it based on pixels:

```py
testSprite.setScaleXByPixels(250)
```

The fifth way is to scale it in only the Y axis, but this time scaling it based on pixels:

```py
testSprite.setScaleYByPixels(75)
```

The sixth way is to scale it in both the X and Y axis, but this time scaling it based on pixels:

```py
testSprite.setScaleByPixels(250, 75)
```