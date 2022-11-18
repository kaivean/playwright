# class: Touchscreen
* since: v1.8

The Touchscreen class operates in main-frame CSS pixels relative to the top-left corner of the viewport. Methods on the
touchscreen can only be used in browser contexts that have been initialized with `hasTouch` set to true.

## async method: Touchscreen.tap
* since: v1.8

Dispatches a `touchstart` and `touchend` event with a single touch at the position ([`param: x`],[`param: y`]).

### param: Touchscreen.tap.x
* since: v1.8
- `x` <[float]>

### param: Touchscreen.tap.y
* since: v1.8
- `y` <[float]>


## async method: Touchscreen.move
Dispatches a `touchstart` and `touchmove` and `touchend` event with a single touch at the position ([`param: startX`],[`param: startY`],[`param: endX`],[`param: endY`]).

### param: Touchscreen.move.startX
- `startX` <[float]>

### param: Touchscreen.move.startY
- `startY` <[float]>
### param: Touchscreen.move.endX
- `endX` <[float]>

### param: Touchscreen.move.endY
- `endY` <[float]>

## async method: Touchscreen.down
### param: Touchscreen.down.startX
- `startX` <[float]>

### param: Touchscreen.down.startY
- `startY` <[float]>

## async method: Touchscreen.up