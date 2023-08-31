## Huez

Automatic UI Color Palette Generator from a Base Color

[huez](https://huez.ciobanunicolae.com)

## Installation

```
npm install huez
```

## Usage

```jsx
import { huez } from "huez";

const baseColor = "#0077cc";
const colorFormat = "hex"; // "hsl", "rgb", or "hex"

try {
  const palette = huez(baseColor, colorFormat);
} catch (error) {
  console.error(error.message);
}
```

## License

[MIT](https://opensource.org/license/mit/)
