# 🥤 Fizzi — 3D Animated Soda Landing Page

A modern, high-performance 3D animated e-commerce landing page for **Fizzi**, a fictional soda brand. Built with Next.js, Three.js, GSAP animations, and integrated with Prismic CMS for dynamic content management.

![Fizzi Banner](https://img.shields.io/badge/Next.js-14-black?style=for-the-badge&logo=next.js)
![Three.js](https://img.shields.io/badge/Three.js-3D-blue?style=for-the-badge&logo=three.js)
![GSAP](https://img.shields.io/badge/GSAP-Animations-green?style=for-the-badge&logo=greensock)
![Prismic](https://img.shields.io/badge/Prismic-CMS-purple?style=for-the-badge&logo=prismic)

---

## ✨ Features

- **🎨 Interactive 3D Visuals**: Real-time 3D soda cans and dynamic scenes powered by Three.js & React Three Fiber.
- **⚡ Smooth Animations**: Immersive scroll-driven animations powered by GSAP & ScrollTrigger.
- **📱 Fully Responsive**: Seamless experience across desktop, tablet, and mobile devices.
- **🧩 Headless CMS**: Dynamic slices and page building powered by Prismic & Slice Machine.
- **🚀 Ultra Fast**: Built on Next.js 14 App Router for optimal rendering performance and SEO.

---

## 🛠️ Tech Stack

- **Framework**: [Next.js](https://nextjs.org/) (App Router)
- **Language**: [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **3D & Graphics**: [Three.js](https://threejs.org/) / [React Three Fiber](https://docs.pmnd.rs/react-three-fiber) / [Drei](https://github.com/pmndrs/drei)
- **Animations**: [GSAP](https://greensock.com/gsap/) (ScrollTrigger, Flip)
- **Content Management**: [Prismic CMS](https://prismic.io/) & [Slice Machine](https://prismic.io/docs/slice-machine)

---

## 🚀 Getting Started

Follow these steps to set up the project locally.

### Prerequisites

Ensure you have the following installed on your machine:
- **Node.js** (v18.x or higher)
- **npm** or **pnpm** / **yarn**

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/GreyNova/FIZZI-DRINKS.git
   cd FIZZI-DRINKS
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up Environment Variables:**
   Create a `.env.local` file in the root directory and configure your Prismic repository endpoint:
   ```env
   NEXT_PUBLIC_PRISMIC_ENVIRONMENT=your-prismic-repo-name
   ```

4. **Run the Development Server:**
   ```bash
   npm run dev
   ```

5. **Launch Prismic Slice Machine (Optional):**
   ```bash
   npx slicemachine
   ```

Open [http://localhost:3000](http://localhost:3000) in your browser to see the live site.

---

## 📦 Project Structure

```text
├── src/
│   ├── app/            # Next.js App Router pages & API routes
│   ├── components/     # Reusable UI components & 3D canvas components
│   ├── slices/         # Prismic Slice Machine components
│   └── lib/            # Utility functions & helpers
├── customtypes/        # Prismic custom type schemas
├── public/             # Static assets & 3D models (.gltf / .glb)
├── prismicio.ts        # Prismic client configuration
└── tailwind.config.ts  # Tailwind CSS configuration
```

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
