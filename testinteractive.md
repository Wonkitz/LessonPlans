# Blinking LED

Let's make an LED blink on the micro:bit!

```blocks
basic.forever(function () {
    led.toggle(2, 2)
    basic.pause(500)
})
