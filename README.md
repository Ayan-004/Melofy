<<<<<<< HEAD
=======
<<<<<<< HEAD
# Melofy
=======
>>>>>>> 9fc6fdb (first commint)
# React + TypeScript + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend updating the configuration to enable type-aware lint rules:

```js
export default tseslint.config({
  extends: [
    // Remove ...tseslint.configs.recommended and replace with this
    ...tseslint.configs.recommendedTypeChecked,
    // Alternatively, use this for stricter rules
    ...tseslint.configs.strictTypeChecked,
    // Optionally, add this for stylistic rules
    ...tseslint.configs.stylisticTypeChecked,
  ],
  languageOptions: {
    // other options...
    parserOptions: {
      project: ['./tsconfig.node.json', './tsconfig.app.json'],
      tsconfigRootDir: import.meta.dirname,
    },
  },
})
```

You can also install [eslint-plugin-react-x](https://github.com/Rel1cx/eslint-react/tree/main/packages/plugins/eslint-plugin-react-x) and [eslint-plugin-react-dom](https://github.com/Rel1cx/eslint-react/tree/main/packages/plugins/eslint-plugin-react-dom) for React-specific lint rules:

```js
// eslint.config.js
import reactX from 'eslint-plugin-react-x'
import reactDom from 'eslint-plugin-react-dom'

export default tseslint.config({
  plugins: {
    // Add the react-x and react-dom plugins
    'react-x': reactX,
    'react-dom': reactDom,
  },
  rules: {
    // other rules...
    // Enable its recommended typescript rules
    ...reactX.configs['recommended-typescript'].rules,
    ...reactDom.configs.recommended.rules,
  },
})
```
<<<<<<< HEAD
=======
>>>>>>> bd2910e (first commint)
>>>>>>> 9fc6fdb (first commint)


📀 Melofy

Melofy is a modern music player website built with React.js and Tailwind CSS.
It integrates the iTunes API to let users search for songs and listen to 30-second previews, all within a clean, minimal, and responsive interface.

🌐 Live Demo: melofyy.netlify.app

 <!-- Replace with actual screenshot link if you upload one -->


---

✨ Features

🎵 Search and play 30-second song previews

🔍 Dynamic search for favorite tracks and artists

🖌️ Modern, minimal, and responsive UI built with Tailwind CSS

⚡ Fast and lightweight single-page app built on React.js



---

🛠 Tech Stack

Frontend: React.js

Styling: Tailwind CSS

API: iTunes Search API



---

🚀 Getting Started

Follow these steps to run Melofy locally:

# Clone the repository
git clone https://github.com/Ayan-004/Melofy.git

# Navigate to the project directory
cd Melofy

# Install dependencies
npm install

# Start the development server
npm run dev

The app will be available at http://localhost:3000.


---

📷 Screenshots

<!-- If you add screenshots to your repo, add them like this: --> 


---

📦 Deployment

This project is deployed on Netlify.
You can easily deploy your own fork using Netlify, Vercel, or any static hosting that supports React apps.


---

🙋‍♂️ Author

Ayan

GitHub: @Ayan004



---

⭐️ Show your support

If you like this project, please consider giving it a ⭐️ on GitHub!
It helps others discover the project and motivates me to keep improving it.


---

📄 License

This project is open source and available under the MIT License.


---
