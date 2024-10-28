# Job-Listings-Using-React

Setup:
1) Have Node.js installed

2) Create folder using vite
   npm create vite@latest <name-of-repository>

3) Select React + JavaScript to create boilerplate

4) Open folder in IDE

5) Assign server port in vite.config.js

6) Install Dependencies
    npm install

7) Run dev server
npm run dev

8) Setup Tailwind CSS

In new terminal...
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p

Modify tailwind.config.js
/** @type {import('tailwindcss').Config} */
export default {
  content: [
    "./index.html",
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
}

Add Tailwind directives to src/index.css file
@tailwind base;
@tailwind components;
@tailwind utilities;