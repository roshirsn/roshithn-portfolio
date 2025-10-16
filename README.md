# Portfolio 🚀

A personal portfolio website built with React, Tailwind CSS, and Vite. Showcases projects, skills, and contact information. This project aims to provide a clean and responsive online presence for showcasing my work and connecting with potential employers or collaborators. It solves the problem of having a centralized and easily accessible platform to display my skills, projects, and contact information.

## ✨ Key Features

- **Responsive Design:** 📱 Adapts seamlessly to different screen sizes, ensuring a consistent user experience across devices.
- **Interactive Sections:** 🖱️ Engaging sections for Home, About, Projects, and Contact, providing a comprehensive overview.
- **Animated Scrolling:** 📜 Smooth reveal-on-scroll animations using a custom `RevealOnScroll` component.
- **Mobile Menu:** 🍔 A functional mobile menu for easy navigation on smaller screens.
- **Email Integration:** 📧 Contact form integrated with EmailJS for easy message sending.
- **GitHub Pages Deployment:** 🌐 Easily deployable to GitHub Pages with included scripts.
- **Skill Showcase:** 🤹‍♀️ Dedicated "About Me" section to display a range of skills.

## 🛠️ Tech Stack

- **Frontend:**
    - React
    - React DOM
- **Styling:**
    - Tailwind CSS
    - `@tailwindcss/vite`
- **Build Tool:**
    - Vite
    - `@vitejs/plugin-react`
- **Email Service:**
    - EmailJS
- **Linting:**
    - ESLint
    - `eslint-plugin-react`
    - `eslint-plugin-react-hooks`
    - `eslint-plugin-react-refresh`
- **Deployment:**
    - gh-pages
- **Other:**
    - JavaScript (ES6+)
    - JSX

## 📦 Getting Started

Follow these steps to get the project up and running on your local machine.

### Prerequisites

- Node.js (version >=16)
- npm or yarn

### Installation

1.  Clone the repository:

    ```bash
    git clone <repository-url>
    cd portfolio
    ```

2.  Install dependencies:

    ```bash
    npm install
    # or
    yarn install
    ```

3.  Set up EmailJS (optional, for contact form functionality):

    -   Create an account on [EmailJS](https://www.emailjs.com/).
    -   Create a new service and template.
    -   Get your Service ID, Template ID, and Public Key.
    -   Create a `.env` file in the root of the project and add the following (replace with your actual credentials):

        ```
        VITE_EMAILJS_SERVICE_ID=your_service_id
        VITE_EMAILJS_TEMPLATE_ID=your_template_id
        VITE_EMAILJS_PUBLIC_KEY=your_public_key
        ```

        **Note:** Make sure to prefix your environment variables with `VITE_` to be accessible in Vite.

### Running Locally

1.  Start the development server:

    ```bash
    npm run dev
    # or
    yarn dev
    ```

2.  Open your browser and navigate to `http://localhost:5173` (or the port shown in the console).

## 💻 Usage

-   **Development:** Use the `npm run dev` command to start the development server with hot reloading.
-   **Building:** Use the `npm run build` command to create a production-ready build in the `dist` directory.
-   **Previewing:** Use the `npm run preview` command to start a local server to preview the production build.
-   **Deployment:** Use the `npm run deploy` command to deploy the project to GitHub Pages. Make sure to configure the `homepage` field in `package.json` to your GitHub Pages URL.

## 📂 Project Structure

```
portfolio/
├── .eslintrc.cjs
├── .gitignore
├── index.html
├── package.json
├── postcss.config.js
├── src/
│   ├── App.css
│   ├── App.jsx
│   ├── assets/
│   │   └── react.svg
│   ├── components/
│   │   ├── MobileMenu.jsx
│   │   ├── Navbar.jsx
│   │   ├── RevealOnScroll.jsx
│   │   └── sections/
│   │       ├── About.jsx
│   │       ├── Contact.jsx
│   │       ├── Home.jsx
│   │       └── Projects.jsx
│   ├── index.css
│   ├── main.jsx
│   └── vite-env.d.ts
├── tailwind.config.js
└── vite.config.js
```

## 📸 Check it out

https://roshirsn.github.io/roshithn-portfolio/

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix.
3.  Make your changes and commit them with descriptive messages.
4.  Push your changes to your fork.
5.  Submit a pull request.

## 📝 License

This project is licensed under the [MIT License](LICENSE).

## 📬 Contact

Roshith N
[roshithnofficial@gmail.com](mailto:roshithnofficial@gmail.com)

## 💖 Thanks

Thank you for checking out my portfolio project! I hope you find it helpful and inspiring.

