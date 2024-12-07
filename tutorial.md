# STEM - Code Club Badge

## Step 1 - Show your micro:bit Name
Let's start by showing your micro:bit's name when we press the A button
```blocks
input.onButtonPressed(Button.A, function () {
    basic.showString(control.deviceName())
})
```

## Step 2 - Create a variable called Team
Let's create a Variable called "Team", your micro:bit will use this to show your team name
Set your Team name in the "Team" variable 
```blocks
let Team = ""
Team = "Zork"
```
## Step 3 - Show your Team Name
Let's show your team name with the B button is pressed
```blocks
input.onButtonPressed(Button.B, function () {
    basic.showString(Team)
})
```
## Step 4 - Download your code onto your micro:bit to see it working
Button A will show your micro:bit's name.  Button B will show your team name