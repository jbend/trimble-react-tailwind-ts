# React app for Trimble with TailwindCSS

## Setup

### Create Typescript React App

```
npx create-react-app@latest trimble-react-tailwind-ts --template typescript
```

### Setup Tailwind

Tailwind React setup docs

Install Tailwindcss

```
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

Configure Tailwindcss

```
module.exports = {
  content: [
    "./src/**/*.{js,jsx,ts,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}
```
