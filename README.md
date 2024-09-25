# Fizzi 3D Website

Welcome to the **Fizzi 3D Website** project! This is a creative personal portfolio built using a modern tech stack including **Next.js**, **Prismic CMS**, **Three.js**, **Tailwind CSS**, and **GSAP** for smooth animations. The portfolio features a vibrant soda-themed design, interactive 3D elements, and dynamic content management.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup & Installation](#setup--installation)
- [Customization](#customization)
- [Deployment](#deployment)
- [Resources](#resources)
- [Troubleshooting](#troubleshooting)

---

## Introduction

This project is designed as a creative personal portfolio with a focus on modern, responsive web design and 3D interactions. The use of **Next.js** for the frontend, **Prismic CMS** for content management, and **Three.js** for 3D models allows for a rich, interactive experience.

### Project Goal

To build a visually stunning and interactive personal portfolio website using cutting-edge web technologies. The final result will showcase your work in a unique way with animations, 3D models, and dynamic content.

---

## Features

- **Interactive 3D Soda Can:** Using Three.js, a 3D model of a soda can is rendered, providing a playful and engaging centerpiece for the site.
- **Custom Animations:** GSAP is utilized for smooth, professional-grade animations across the website.
- **Content Management:** Integrated with Prismic CMS for easy content updates without needing to modify code.
- **Responsive Design:** Built with Tailwind CSS to ensure a mobile-friendly, responsive layout.
- **Dynamic Sections:** Includes sections for showcasing text, work experience, and project galleries, all easily customizable through Prismic.

---

## Technologies Used

- **Next.js**: React-based framework for fast, server-side rendered applications.
- **Prismic CMS**: Headless CMS used to manage dynamic content.
- **Three.js**: 3D JavaScript library to render the soda can and other 3D elements.
- **Tailwind CSS**: Utility-first CSS framework for responsive design.
- **GSAP (GreenSock Animation Platform)**: High-performance animations for smooth transitions and interactions.
- **Zustand**: Lightweight state management for React.
- **Vercel**: Deployment platform optimized for Next.js applications.

---

## Setup & Installation

### Prerequisites

Before you begin, ensure you have the following installed:

- Node.js (version 16 or above)
- Git
- Prismic account

### Steps

1. **Clone the repository:**

   ```bash
   git clone https://github.com/codedalex/fizzi-3d-website.git
   cd fizzi-3d-website
   ```

2. **Install dependencies:**

   ```bash
   npm install
   ```

3. **Create a `.env.local` file:**

   Set up your environment variables for Prismic and Vercel:

   ```bash
   NEXT_PUBLIC_PRISMIC_ENDPOINT=<Your Prismic API URL>
   PRISMIC_ACCESS_TOKEN=<Your Prismic Access Token>
   ```

4. **Start the development server:**

   ```bash
   npm run dev
   ```

5. **Access the site:**

   Visit `http://localhost:3000` in your browser to see the site live.

---

## Customization

You can customize the design and content in a few simple steps:

1. **3D Soda Can Customization:**
   The 3D soda can model can be edited in **Blender**. Update the texture or 3D object in the `SodaCan.tsx` file.

2. **Text and Content:**
   Update the text content directly in Prismic CMS. Head to your Prismic repository and modify the document fields as required.

3. **Styling:**
   Modify Tailwind CSS utility classes within components to adjust styling or customize the `tailwind.config.js` file for deeper changes.

4. **Assets:**
   Replace image assets in the `public/` directory or update them via Prismic for dynamic images.

---

## Deployment

The easiest way to deploy your project is via **Vercel**:

1. **Create a Vercel account** and link it to your GitHub repository.
2. **Deploy:**
   Simply push your changes to the `main` branch and Vercel will automatically build and deploy the project.
3. **Set Up Prismic Webhooks:**
   Follow the instructions [here](https://prismic.io/docs/webhooks) to set up Prismic webhooks for automatic redeployment on content changes.

---

## Resources

- [Next.js Documentation](https://nextjs.org/docs)
- [Prismic CMS Documentation](https://prismic.io/docs)
- [Three.js Documentation](https://threejs.org/docs/)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [GSAP Documentation](https://greensock.com/docs)
- [Zustand Documentation](https://zustand.docs.pmnd.rs)

---

## Troubleshooting

### Common Issue: "No Documents Returned" Error

If you encounter the error `No documents were returned`, follow these steps:

1. In Prismic, ensure that the documents are uploaded in the correct locale (e.g., `en-us`).
2. Set the appropriate locale as the master in the **Translations & Locales** settings in Prismic.

For more detailed help, visit the [Prismic community forum](https://community.prismic.io/latest).

---

## License

This project is open-source and available under the [MIT License](LICENSE).
```

This README provides a clear overview of the project, setup instructions, and customization options, giving future users all the information they need to get started.