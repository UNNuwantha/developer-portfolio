# 🚀 Personal Portfolio

[![React](https://img.shields.io/badge/React-18.2.0-61DAFB?style=for-the-badge&logo=react)](https://reactjs.org/)
[![Vite](https://img.shields.io/badge/Vite-5.1.1-646CFF?style=for-the-badge&logo=vite)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-4.1.17-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/)
[![Lucide React](https://img.shields.io/badge/Lucide_React-0.556.0-000000?style=for-the-badge&logo=lucide)](https://lucide.dev/)
[![EmailJS](https://img.shields.io/badge/EmailJS-4.4.1-000000?style=for-the-badge&logo=email)](https://www.emailjs.com/)

A modern, responsive personal portfolio website built with React, Vite, and Tailwind CSS. Showcase your projects, experience, and skills with a sleek and professional design.

## ✨ Features

- 🎨 **Modern Design**: Clean and responsive UI with smooth animations
- 📱 **Mobile-First**: Fully responsive design that works on all devices
- ⚡ **Fast Performance**: Built with Vite for lightning-fast development and builds
- 🎯 **Interactive Components**: Animated buttons, hover effects, and smooth transitions
- 📧 **Contact Integration**: Integrated contact form with EmailJS
- 🌟 **Customizable**: Easy to customize with your own content and styling

## 🛠️ Tech Stack

- **Frontend Framework**: React 19
- **Build Tool**: Vite
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Email Service**: EmailJS
- **Linting**: ESLint

## 🚀 Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/UNNuwantha/developer-portfolio.git
   cd personal-portfolio/client
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**

   Create a `.env` file in the root directory and add your EmailJS configuration:
   ```env
   VITE_EMAILJS_SERVICE_ID=your_service_id
   VITE_EMAILJS_TEMPLATE_ID=your_template_id
   VITE_EMAILJS_PUBLIC_KEY=your_public_key
   ```

4. **Start the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**

   Navigate to `http://localhost:5173` to view your portfolio.

## 📜 Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the project for production
- `npm run preview` - Preview the production build locally
- `npm run lint` - Run ESLint to check for code issues

## 📁 Project Structure

```
client/
├── public/
│   └── projects/          # Project images/assets
├── src/
│   ├── assets/            # Static assets
│   ├── components/        # Reusable UI components
│   │   ├── AnimatedBorderButton.jsx
│   │   └── Button.jsx
│   ├── layout/            # Layout components
│   │   ├── Footer.jsx
│   │   └── Navbar.jsx
│   ├── sections/          # Main page sections
│   │   ├── About.jsx
│   │   ├── Contact.jsx
│   │   ├── Experience.jsx
│   │   ├── Hero.jsx
│   │   ├── Projects.jsx
│   │   └── Testimonials.jsx
│   ├── App.jsx            # Main app component
│   ├── index.css          # Global styles
│   └── main.jsx           # App entry point
├── package.json
├── vite.config.js
└── README.md
```

## 🎨 Customization

### Personal Information
- Update the content in each section component (`src/sections/`)
- Replace placeholder images in `public/projects/`
- Modify the color scheme in `src/index.css`

### Styling
- Customize Tailwind CSS classes in component files
- Adjust animations and transitions as needed
- Modify responsive breakpoints for different screen sizes

## 📧 Contact Form Setup

To enable the contact form functionality:

1. Sign up for a free account at [EmailJS](https://www.emailjs.com/)
2. Create an email service and template
3. Add your service ID, template ID, and public key to the `.env` file

## 🚀 Deployment

### Build for Production

```bash
npm run build
```

The built files will be in the `dist/` directory, ready for deployment to any static hosting service like Vercel, Netlify, or GitHub Pages.

### Recommended Deployment Platforms

- [Vercel](https://vercel.com/) - Great for React apps with automatic deployments
- [Netlify](https://netlify.com/) - Excellent for static sites with form handling
- [GitHub Pages](https://pages.github.com/) - Free hosting for public repositories

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

⭐ **Star this repo** if you found it helpful!
