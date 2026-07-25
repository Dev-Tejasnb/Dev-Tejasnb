<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Space+Grotesk&weight=700&size=32&duration=3000&pause=500&color=3B82F6&center=true&vCenter=true&width=600&height=70&lines=Tejas+N+B;Full+Stack+Developer;Open+Source+Enthusiast" alt="Typing SVG" />
  <br />
  <p>
    <a href="https://portfolio-tejas.vercel.app" target="_blank">
      <img src="https://img.shields.io/badge/Live%20Demo-3B82F6?style=for-the-badge&logo=vercel&logoColor=white" />
    </a>
    <a href="https://linkedin.com/in/tejas-n-b" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
    </a>
    <a href="mailto:tejasnb03@gmail.com">
      <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
    </a>
  </p>
</div>

---

## Portfolio Website

An interactive developer portfolio built with **Next.js 16**, **React 19**, **TypeScript**, and **Tailwind CSS**. Features a cyberpunk-inspired dark theme with glassmorphism, particle animations, Three.js 3D scenes, AI chatbot, terminal emulator, and real-time GitHub integration.

### Tech Stack

| Category | Technologies |
|---|---|
| **Framework** | Next.js 16.2.11 (Turbopack) |
| **UI Library** | React 19, TypeScript |
| **Styling** | Tailwind CSS v3 |
| **Animation** | Framer Motion 11, GSAP 3 |
| **3D Graphics** | Three.js, @react-three/fiber 9, @react-three/drei 10 |
| **Icons** | Lucide React |
| **Fonts** | Space Grotesk (display), Inter (body), JetBrains Mono (mono) |
| **Email** | EmailJS |

### Features

- **Animated Background** — Real-time canvas particle system with animated grid overlay
- **3D Scene** — Interactive Three.js particle field with floating geometry
- **Typewriter Effect** — Dynamic headline cycling with configurable speed
- **AI Chatbot** — Context-aware assistant that answers questions about skills, projects, and experience
- **Terminal Emulator** — In-browser CLI with custom commands (`about`, `projects`, `skills`, `contact`, etc.)
- **GitHub Integration** — Contribution graph and stats via GitHub GraphQL API
- **Scroll Animations** — Framer Motion `whileInView` reveals with staggered children
- **Loading Screen** — Animated intro with smooth transition
- **Fully Responsive** — Mobile-first layout with glassmorphism cards

### Sections

1. Hero — Animated intro with typewriter headlines
2. About — Bio, social links, and personal info
3. Skills — Categorized skill bars with proficiency levels
4. Projects — Filterable project cards with tech tags
5. Timeline — Experience, education, and certifications
6. GitHub — Contribution calendar widget and stats
7. AI Chatbot — Floating assistant (bottom-right)
8. Terminal — Interactive CLI (bottom-left)
9. Footer — Links and attribution

### Getting Started

```bash
# Clone the repository
git clone https://github.com/dev-tejasnb/portfolio.git
cd portfolio

# Install dependencies
npm install --legacy-peer-deps

# Set up environment variables
cp .env.example .env.local
# Edit .env.local with your credentials

# Run development server
npm run dev
```

Visit [http://localhost:3000](http://localhost:3000).

### Environment Variables

Create `.env.local`:

| Variable | Description |
|---|---|
| `NEXT_PUBLIC_EMAILJS_SERVICE_ID` | EmailJS service ID |
| `NEXT_PUBLIC_EMAILJS_TEMPLATE_ID` | EmailJS template ID |
| `NEXT_PUBLIC_EMAILJS_PUBLIC_KEY` | EmailJS public key |
| `NEXT_PUBLIC_GITHUB_TOKEN` | GitHub personal access token (for contribution graph) |

### Scripts

| Command | Description |
|---|---|
| `npm run dev` | Start Turbopack dev server on `0.0.0.0:3000` |
| `npm run build` | Production build |
| `npm run start` | Start production server |
| `npm run lint` | Run Next.js ESLint |

### Build

```bash
npm run build
```

Output is a fully static export in `.next/`.

### License

MIT © Tejas N B
