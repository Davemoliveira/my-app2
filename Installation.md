# INSTALL NPM
    https://www.npmjs.com/

# INSTALL TAILWIND CSS
npm install -D tailwindcss
npx tailwindcss init

## Configure template paths:

/** @type {import('tailwindcss').Config} */
module.exports = {
content: ["./src/**/*.{html,js}"],
theme: {
    extend: {},
    },
plugins: [],
}   

## Add the Tailwind directives to CSS (input.css)
@tailwind base;
@tailwind components;
@tailwind utilities;

## Start build process
npm run start


## Example

export default function App() {
  return (
    <h1 className="text-3xl font-bold underline">
      Hello world!
    </h1>
  )
}