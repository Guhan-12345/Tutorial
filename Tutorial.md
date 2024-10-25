# Piano

## {Introduction @unplugged}

![Cartoon of the Rock Paper Scissors game](https://raw.githubusercontent.com/Guhan-12345/Tutorial/master/docs/static/test1.png)


Turn your micro:bit into a **Rock Paper Scissors** game that you can play with your friends!



## {Introduction @unplugged}

# Connection Step 1
![Cartoon of the Rock Paper Scissors game](https://raw.githubusercontent.com/Guhan-12345/Tutorial/master/docs/static/S1.png)


Turn your micro:bit into a **Rock Paper Scissors** game that you can play with your friends!

## {Step 1}

First we need to make a variable to keep track of whether we have a Rock, Paper or Scissors in our hand. A variable is a container for storing values. Click on the ``||variables:Variables||`` category in the Toolbox. Click on the **Make a Variable** button. Give your new variable the name "hand" and click Ok.

![A animation that shows how to create a variable](/static/mb/projects/rock-paper-scissors/newvar.gif)

## {Step 2}
``

```blockconfig.global
randint(1, 3)
```

```template
input.onGesture(Gesture.Shake, function() {})
```