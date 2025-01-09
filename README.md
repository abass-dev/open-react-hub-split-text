# OpenReactHub SplitText

A React component for animating text by splitting it into individual characters, part of the OpenReactHub library collection.

## About OpenReactHub

OpenReactHub is a curated collection of open-source React libraries and components. Visit [OpenReactHub](https://openreacthub.vercel.com) for more amazing React resources!

## Installation

\`\`\`bash
npm install @open-react-hub/split-text
\`\`\`

or

\`\`\`bash
yarn add @open-react-hub/split-text
\`\`\`

## Usage

\`\`\`jsx
import { SplitText } from '@open-react-hub/split-text';

function MyComponent() {
  return (
    <SplitText 
      text="Hello, OpenReactHub!" 
      delay={500} 
      animationDuration={800}
      staggerDelay={50}
    />
  );
}
\`\`\`

## Props

| Prop | Type | Default | Description |
|------|------|---------|-------------|
| text | string | (required) | The text to be animated |
| delay | number | 0 | Delay in milliseconds before the animation starts |
| animationDuration | number | 500 | Duration of each character's animation in milliseconds |
| staggerDelay | number | 30 | Delay between each character's animation start in milliseconds |
| className | string | '' | Additional CSS classes to be applied to the container span |


## How it works

The SplitText component splits the input text into individual characters and animates each character separately using react-spring. This creates a smooth, staggered animation effect. You can customize the animation by adjusting the `delay`, `animationDuration`, and `staggerDelay` props to achieve different effects.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

MIT

## Author

Abass Dev - [GitHub](https://github.com/abass-dev)

---

This component is part of the [OpenReactHub](https://openreacthub.vercel.com) collection.

