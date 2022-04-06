# Scroll Anim

A patch that scrolls through a texture.

## API

| Input | Type | Default | Description |
| --- | --- | --- | --- |
| Texture | Texture2D | n/a | Input texture to scroll through. |
| Viewport Height | Scalar | 1024 | Height of the viewport, in pixels. The texture size is assumed to be 1024x1024px. The viewport width is fixed and cannot be changed. |
| Position Offset | Vector2 | 0, 0 | Starting position of the viewport, in pixels. The texture size is assumed to be 1024x1024px. |
| Speed | Scalar | 1 | How fast the texture viewport should move, as a factor of 5 seconds for a complete loop. The minimum is 0 (stationary). |
| Reverse | Boolean | false | Scroll the texture from right to left instead of left to right. |

## Return value

A Texture2D that updates per tick, scrolling through the input texture according to the settings.

