# React Material Symbols
A simple and customizable React component library for integrating Material Symbols icons effortlessly into your applications. With easy-to-use props for size and name, you can enhance your UI with icons in no time!

## Installation

You can install the library using npm or yarn:

```bash
npm install react-material-symbols
```

or

```bash
yarn add react-material-symbols
```

## Usage

To use the `Icon` component, simply import it and provide the desired `size` and `name` props:

```tsx
import { Icon } from "react-material-symbols";

const App = () => {
  return (
    <div>
      <h1>Welcome to My App</h1>
      <Icon size={16} name="home" />
      <Icon size={24} name="settings" />
      <Icon size={32} name="favorite" />
    </div>
  );
};

export default App;
```

## Props

| Prop  | Type   | Description                      |
|-------|--------|----------------------------------|
| `size`| `number` | Optional. Size of the icon (in pixels). Default is 24. |
| `name`| `string` | Required. Name of the Material Symbol to be displayed. |

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue for any feature requests or bug reports.

## Acknowledgements

- [Material Symbols](https://fonts.google.com/icons?icon.query=material%20symbols) - for providing a great icon set.

```
