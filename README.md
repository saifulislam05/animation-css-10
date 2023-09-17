# Animation Ass-10 CSS

## Project Description
The "Animation Project" is a web page project that showcases animated images of different watches. The project features a responsive layout and CSS animations applied to the images.

## HTML Structure

### Wrapper (`div.wrapper`):
- A container for the images.

### Images (<img>)
- Three image elements with different source (src) attributes for the watch images.
- Each image has an alt attribute for alternative text.

## CSS Styles

### Global Styles (`*`)
- `margin: 0;`: Resets margin for all elements.
- `padding: 0;`: Resets padding for all elements.
- `box-sizing: border-box;`: Ensures elements include padding and borders in their total width.

### Body (`body`)
- `height: 100vh;`: Sets the body's height to 100% of the viewport height.
- `display: flex;`: Arranges content in a flex container.
- `justify-content: center;`: Centers content horizontally.
- `align-items: center;`: Centers content vertically.
- `background-color: #000;`: Sets the background color to black.

### Wrapper (`div.wrapper`)
- `.wrapper`:
  - `max-width: 1100px;`: Sets the maximum width of the wrapper.
  - `display: flex;`: Arranges images in a row.
  - `justify-content: space-between;`: Separates images with space.
  - `align-items: center;`: Centers images vertically.
  - `-webkit-box-reflect: below 1px linear-gradient(transparent, transparent, #0004);`: Adds a reflection effect below images.

### Images (`img`)
- `img`:
  - `max-width: 350px;`: Sets the maximum width of images.
  - `height: 350px;`: Sets the height of images.
  - `border-radius: 5px;`: Rounds the corners of images.
  - `box-shadow: 0px 0px 8px #808080;`: Adds a subtle shadow effect.
  - `transform-origin: center;`: Sets the transformation origin to the center of images.
  - `transform: perspective(800px) rotateY(20deg);`: Applies a 3D rotation effect.
  - `transition: 0.5s;`: Adds a smooth transition effect.
  - `-webkit-transition: 0.5s;`: Adds a smooth transition effect (for Safari).
  - `-moz-transition: 0.5s;`: Adds a smooth transition effect (for Firefox).
  - `-ms-transition: 0.5s;`: Adds a smooth transition effect (for Microsoft Edge).
  - `-o-transition: 0.5s;`: Adds a smooth transition effect (for Opera).

- `img:hover`:
  - `transform: perspective(800px) rotateY(0deg);`: Resets the 3D rotation on hover.
  - `opacity: 1;`: Sets the opacity to 1 on hover.


