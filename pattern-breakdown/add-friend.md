# 🏹 Pattern Breakdown

# Add friend

## Exercise 1

Whether you put it before or after the setWalk call makes no difference. That render’s value of walk is fixed. Calling setWalk will only change it for the next render, but will not affect the event handler from the previous render.
