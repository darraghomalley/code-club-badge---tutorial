# STEM - Quiz A or B
## Introduction - Let's build a Quick Draw app 
Let's build a Quick Draw project that will send your micro:bit's name to your teacher.
```template
//
```
## Step 1 - Show your micro:bit name 
Let's start by showing your micro:bit's name when it starts up
```blocks
basic.showString(control.deviceName());
})
```

## Step 2 - Set your radio group
Let's set your Radio Group; for this project the whole class will use radio group 255
```blocks
basic.showString(control.deviceName());
radio.setGroup(255)
})
```
## Step 4 - Set your radio group
Let's send your micro:bit's name using radio send string
```blocks
input.onButtonPressed(Button.A, function () {
    radio.sendString(control.deviceName())
})
```
## Step 3 - Try it out on your micro:bit
Download your code onto your micro:bit to see it working

<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>

