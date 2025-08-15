# ===== File Tree =====
ai-agency-site/
├─ app/
│  ├─ globals.css
│  ├─ layout.tsx
│  ├─ page.tsx
├─ components/
│  ├─ Navbar.tsx
│  ├─ Footer.tsx
│  ├─ Hero.tsx
│  ├─ ServiceCards.tsx
│  ├─ CTA.tsx
├─ public/
│  ├─ logo.svg
├─ package.json
├─ tsconfig.json
├─ tailwind.config.ts
├─ postcss.config.js
├─ next.config.mjs
└─ README.md

# ===== package.json =====
{
  "name": "ai-agency-site",
  "version": "1.0.0",
  "private": true,
  "scripts": {
    "dev": "next dev",
    "build": "next build",
    "start": "next start",
    "lint": "next lint"
  },
  "dependencies": {
    "framer-motion": "^11.0.0",
    "next": "14.0.0",
    "react": "18.2.0",
    "react-dom": "18.2.0"
  },
  "devDependencies": {
    "autoprefixer": "^10.4.0",
    "postcss": "^8.4.0",
    "tailwindcss": "^3.4.0",
    "typescript": "^5.0.0"
  }
}

# ===== tsconfig.json =====
{
  "compilerOptions": {
    "target": "es5",
    "lib": ["dom", "dom.iterable", "esnext"],
    "allowJs": true,
    "skipLibCheck": true,
    "strict": true,
    "forceConsistentCasingInFileNames": true,
    "noEmit": true,
    "esModuleInterop": true,
    "module": "esnext",
    "moduleResolution": "node",
    "resolveJsonModule": true,
    "isolatedModules": true,
    "jsx": "preserve",
    "incremental": true
  },
  "include": ["next-env.d.ts", "**/*.ts", "**/*.tsx"],
  "exclude": ["node_modules"]
}

# ===== next.config.mjs =====
/** @type {import('next').NextConfig} */
const nextConfig = {};
export default nextConfig;

# ===== postcss.config.js =====
module.exports = {
  plugins: {
    tailwindcss: {},
    autoprefixer: {},
  },
};

# ===== tailwind.config.ts =====
import type { Config } from "tailwindcss";

const config: Config = {
  content: [
    "./app/**/*.{js,ts,jsx,tsx}",
    "./components/**/*.{js,ts,jsx,tsx}",
  ],
  theme: {
    extend: {},
  },
  plugins: [],
};

export default config;

# ===== app/globals.css =====
@tailwind base;
@tailwind components;
@tailwind utilities;

body {
  background-color: #0B0F14;
  color: white;
}

# ===== app/layout.tsx =====
import "./globals.css";
import type { Metadata } from "next";
import { Inter } from "next/font/google";
import Navbar from "@/components/Navbar";
import Footer from "@/components/Footer";

const inter = Inter({ subsets: ["latin"] });

export const metadata: Metadata = {
  title: "Aurora AI | Premium AI Agency",
  description: "AI Systems, Chatbots, Automation & Consulting",
};

export default function RootLayout({
  children,
}: {
  children: React.ReactNode;
}) {
  return (
    <html lang="en">
      <body className={`${inter.className} bg-[#0B0F14] text-white`}>
        <Navbar />
        {children}
        <Footer />
      </body>
    </html>
  );
}

# ===== app/page.tsx =====
import Hero from "@/components/Hero";
import ServiceCards from "@/components/ServiceCards";
import CTA from "@/components/CTA";

export default function Home() {
  return (
    <main>
      <Hero />
      <ServiceCards />
      <CTA />
    </main>
  );
}

# ===== components/Navbar.tsx =====
export default function Navbar() {
  return (
    <nav className="p-4 flex justify-between items-center border-b border-gray-800">
      <div className="font-bold text-xl text-white">Aurora AI</div>
      <div className="space-x-6">
        <a href="#services" className="hover:text-gray-300">Services</a>
        <a href="#about" className="hover:text-gray-300">About</a>
        <a href="#contact" className="hover:text-gray-300">Contact</a>
      </div>
    </nav>
  );
}

# ===== components/Footer.tsx =====
export default function Footer() {
  return (
    <footer className="p-6 text-center border-t border-gray-800 text-gray-400 text-sm">
      © {new Date().getFullYear()} Aurora AI. All rights reserved.
    </footer>
  );
}

# ===== components/Hero.tsx =====
import { motion } from "framer-motion";

export default function Hero() {
  return (
    <section className="relative h-[80vh] flex items-center justify-center text-center bg-gradient-to-br from-[#0D1B2A] to-[#1B263B]">
      <motion.div
        initial={{ opacity: 0, y: 40 }}
        animate={{ opacity: 1, y: 0 }}
        transition={{ duration: 0.8 }}
      >
        <h1 className="text-5xl font-bold mb-4">Systems that Scale</h1>
        <p className="text-lg mb-6">AI that drives results and compounds growth</p>
        <a href="#services" className="bg-blue-600 px-6 py-3 rounded-full hover:bg-blue-700">
          View Services
        </a>
      </motion.div>
    </section>
  );
}

# ===== components/ServiceCards.tsx =====
const services = [
  { title: "AI Systems", description: "Custom AI solutions to transform your business." },
  { title: "Full Stack Apps", description: "Scalable web & mobile applications." },
  { title: "AI Chatbots", description: "Conversational agents for 24/7 engagement." },
  { title: "Voice Assistants", description: "Voice-driven customer experiences." },
  { title: "Workflow Automations", description: "Streamlined operations with automation." },
  { title: "AI Consulting", description: "Expert guidance to adopt AI effectively." },
];

export default function ServiceCards() {
  return (
    <section id="services" className="py-16 px-6 grid gap-8 md:grid-cols-3">
      {services.map((s) => (
        <div key={s.title} className="bg-gray-900 p-6 rounded-lg shadow-lg hover:shadow-xl transition">
          <h3 className="text-xl font-semibold mb-2">{s.title}</h3>
          <p className="text-gray-400">{s.description}</p>
        </div>
      ))}
    </section>
  );
}

# ===== components/CTA.tsx =====
export default function CTA() {
  return (
    <section className="py-16 bg-blue-700 text-center">
      <h2 className="text-3xl font-bold mb-4">Ready to Transform Your Business?</h2>
      <p className="mb-6">Book a free consultation with our AI experts today.</p>
      <a href="#contact" className="bg-black px-6 py-3 rounded-full hover:bg-gray-900">
        Book Consultation
      </a>
    </section>
  );
}

# ===== public/logo.svg =====
<svg xmlns="http://www.w3.org/2000/svg" width="100" height="100" fill="#ffffff" viewBox="0 0 24 24">
  <circle cx="12" cy="12" r="10" stroke="#ffffff" stroke-width="2" fill="none"/>
  <path d="M12 6v6l4 2" stroke="#ffffff" stroke-width="2" fill="none"/>
</svg>

# ===== README.md =====
# Aurora AI Agency Site

## Install & Run
```bash
npm install
npm run dev
