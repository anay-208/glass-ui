# @anay-208/glass-ui

A React component library for creating UI cards with a customizable background color and transparency.

## Installation

```bash
npm install @anay-208/glass-ui
```

## Usage

```jsx
import Card from '@anay-208/glass-ui';

function App() {
  return (
    <Card>
      <h1>Hello, world!</h1>
    </Card>
  );
}

export default App;
```

## API

### `Card`

A function component that renders a UI card with a customizable background color and transparency.

#### Props

- `bgColor`: The background color of the card. It can be in any CSS color format (e.g., hex, rgb, hsl, etc.). Defaults to "rgba(128, 128, 128)".
- `transparency`: The transparency of the background color. It should be a number between 0 (completely transparent) and 1 (completely opaque). Defaults to 0.30.
- `ref`: A ref to the underlying div element.
- `children`: The content to be displayed inside the card.

All other props are passed through to the underlying div element.

## License

MIT