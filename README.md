# Tailwind CSS Playground

A simple starter project for playing around with Tailwind CSS in a proper PostCSS environment.

Get started:

1. Clone the repository:

   ```bash
   git clone https://github.com/evan70/tailwind-css-playground.git tailwind-css-playground

   cd tailwind-css-playground
   ```

2. Install the dependencies:

   ```bash
   # Using npm
   npm install

   # Using Yarn
   yarn
   ```

3. Start the development server:

   ```bash
   # Using npm
   npm run serve

   # Using Yarn
   yarn serve
   ```

   Now you should be able to see the project running at localhost:8080.

4. Open `public/index.html` in your favourite editor and start experimenting!

## Building for production

Example of setting up [cssnano](https://cssnano.co/) to optimize your CSS for production.

To build an optimized version of your CSS, simply run:

```bash
# Using npm
npm run production

# Using Yarn
yarn production
```

That's done, check out `./public/build/tailwind.css` to see your optimized output.
