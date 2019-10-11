How do you add extenstions.

# Motion with the Microbit

## Introduction @unplugged
Make things move using a servo.

## Step 1

Today we are going to make things move using the Microbit. 
We are going to connect a servo. I have already added the extension for you.

## Step 3

Add two ``||servos:servo||`` blocks to the ``||basic:forever||`` block

```blocks
basic.forever(function () {
    servos.P0.setAngle(0)
    servos.P0.setAngle(180)
})
```

## Step 4

Add two  ``||basic:pause||`` blocks to the ``||basic:forever||`` block.

```blocks
basic.forever(function () {
    basic.pause(1000)
})
```

## Step 5

Your code should now look like this.

```blocks
basic.forever(function () {
    servos.P0.setAngle(0)
    basic.pause(1000)
    servos.P0.setAngle(180)
    basic.pause(1000)
})
```

## Step 6 @unplugged

Now tweak your code to get your servo moving how you would like. 


```package
servo
```
