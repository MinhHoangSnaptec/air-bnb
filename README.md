<div align="center">

  <img src="https://user-images.githubusercontent.com/99184393/185779974-a31a9f47-f8d3-42ea-b7f8-4a2971774615.png" alt="logo" width="250" height="auto" />
  
# Airbnb Clone with Next.js 13!
  
  <p>
Full Stack Airbnb Clone with Next.js 13 Tailwind-css, Prisma, MongoDB, NextAuth, Framer-motionSocial, Login (Google and Facebook), Image upload, Cloudinary CDN, Location selection, Map component, Country autocomplete, Fetching listings with server components.
  </p>

<!-- Env Variables -->

### :key: Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`DATABASE_URL`

`GOOGLE_CLIENT_ID`

`GOOGLE_CLIENT_SECRET`

`FACEBOOK_ID`

`FACEBOOK_SECRET`

`NEXTAUTH_SECRET`

`NEXTAUTH_URL`

`NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME`

`NEXT_PUBLIC_LOOKUP_KEY`

### :gear: Installation

Install dependencies

### :test_tube: Install Tailwind CSS with Next.js

#### Install Tailwind CSS

![](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

Install tailwindcss and its peer dependencies via npm, and then run the init command to generate both `tailwind.config.js` and `postcss.config.js`.

```
npm install -D tailwindcss postcss autoprefixer
```

```
npx tailwindcss init -p
```

#### Configure your template paths

Add the paths to all of your template files in your `tailwind.config.js` file.
<br>

```js
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: [
    "./app/**/*.{js,ts,jsx,tsx}",
    "./pages/**/*.{js,ts,jsx,tsx}",
    "./components/**/*.{js,ts,jsx,tsx}",

    // Or if using `src` directory:
    "./src/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
};
```

#### Add the Tailwind directives to your CSS

Add the `@tailwind` directives for each of Tailwind’s layers to your `./styles/globals.css` file.

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```
