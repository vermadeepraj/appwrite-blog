# React + Vite

# Appwrite Blog

A React-based blog application built using Vite, TailwindCSS, and integrated with Appwrite to provide a seamless blogging experience.

---

## Features
- **Create and Manage Blogs**: Effortlessly create, edit, and delete blog posts.
- **Responsive UI**: Styled with TailwindCSS to provide a user-friendly experience across devices.
- **Backend Integration**: Powered by Appwrite for robust and scalable backend support.
- **Environment Configurations**: Easy setup using `.env` for environment-specific variables.

---

## Tech Stack
- **Frontend**: React, Vite
- **Styling**: TailwindCSS, PostCSS
- **Backend**: Appwrite
- **Linting**: ESLint

---

## Installation

### Prerequisites
- **Node.js**: Ensure Node.js (version 16 or above) is installed.
- **Appwrite Server**: Set up an instance of Appwrite for backend functionality.

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/vermadeepraj/appwrite-blog.git
   ```
2. Navigate to the project directory:
   ```bash
   cd appwrite-blog
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Configure environment variables:
   - Rename `.env.sample` to `.env`.
   - Update the values based on your Appwrite server configuration.
5. Start the development server:
   ```bash
   npm run dev
   ```
6. Open the app in your browser at `http://localhost:3000`.

---

## File Structure
```
appwrite-blog/
├── src/
│   ├── components/   # Reusable React components
│   ├── pages/        # Application pages (e.g., Home, Blog Post)
│   ├── styles/       # Tailwind and custom styles
│   └── utils/        # Utility functions
├── public/           # Static assets
├── .env.sample       # Example environment variables
├── tailwind.config.js # TailwindCSS configuration
├── vite.config.js    # Vite configuration
└── README.md         # Project documentation
```

---

## Usage
1. **Create a New Blog Post**:
   - Navigate to the "Create Blog" section.
   - Fill in the title, content, and other details, then save.
2. **Edit Existing Blog**:
   - Select a blog from the dashboard.
   - Update details and save changes.
3. **Delete Blog**:
   - Click the delete icon next to a blog to remove it permanently.

---

## Deployment

### Vercel/Netlify
1. Build the project:
   ```bash
   npm run build
   ```
2. Deploy the `dist/` folder to your hosting platform.

### Appwrite Configuration
Ensure Appwrite is set up correctly with required collections and permissions for handling blogs.

---

## Contributing
Contributions are welcome! Feel free to fork this repository and submit pull requests.

---

## License
This project is licensed under the [MIT License](LICENSE).

---

## Acknowledgments
Special thanks to the developers and contributors of Appwrite, React, and TailwindCSS for providing amazing tools to build this project.



































This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
