# Steak or Dies!

A fun, React-based steakhouse menu app that lets you browse a selection of premium steaks, view their ingredients, and see which are currently available or sold out. Declare a war on veganism with our meat-centric menu!

## Features

- Interactive steak menu with images, prices, and ingredients
- Sold-out items are clearly marked
- Responsive, modern design
- Order button (demo only)
- Open/closed status based on the time of day

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v14 or higher recommended)
- npm (comes with Node.js)

### Installation

1. Clone the repository:
   ```bash
   git clone <repo-url>
   cd steak-or-dies
   ```
2. Install dependencies:
   ```bash
   npm install
   ```

### Running the App

Start the development server:

```bash
npm start
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the app.

### Building for Production

To create a production build:

```bash
npm run build
```

The optimized build will be in the `build` folder.

## Project Structure

- `src/` - React components and styles
- `public/assets/img/` - Steak images
- `public/data.js` - Steak menu data

## Customization

You can add or edit steak items in `public/data.js` or directly in `src/index.js` under the `steakData` array.

## License

MIT

---

Made with 🥩 by Steak or Dies!
