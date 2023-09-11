# zuri-internship-movie-discovery-webapp

# This project uses NextJS with TaiwindCSS.
**Project Link**: 

## PROJECT FEATURES:

----------------------------------------------------------------
- NextJS
- TaiwindCSS
- PostCSS
- ESlint

----------------------------------------------------------------
## To view locally
----------------------------------------------------------------

- clone repository to local machine
- open directory
- run npm install
- run npm run dev 

----------------------------------------------------------------
## To create your own Project:
----------------------------------------------------------------
- npx create-next-app@latest moviebox_app --javascript --eslint 
(Yes - TaiwlindCSS , NO - Typescript, NO - App router- use pages instead)

- cd moviebox_app

----------------------------------------------------------------
## installTailwind CSS
----------------------------------------------------------------
- npm install -D tailwindcss postcss autoprefixer
- npx tailwindcss init -p

----------------------------------------------------------------
## Configure taiwind CSS
----------------------------------------------------------------

- # in your taiwind.config file
 - /** @type {import('tailwindcss').Config} */
 - module.exports = {
 - content: [
 -   "./app/**/*.{js,ts,jsx,tsx,mdx}",
 -   "./pages/**/*.{js,ts,jsx,tsx,mdx}",
 -   "./components/**/*.{js,ts,jsx,tsx,mdx}",
 -
 -   // Or if using `src` directory:
 -   "./src/**/*.{js,ts,jsx,tsx,mdx}",
 - ],
 - theme: {
 -   extend: {},
 - },
 - plugins: [],
- }

- # Add directives to css to global.css file
  @tailwind base;
 @tailwind components;
 @tailwind utilities;

## run 
- npm run dev
