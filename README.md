
# Windows Sense – Prototype (Vite + React + Tailwind)

An animated Windows 11–style prototype with Dashboard, User Management, and Copilot panes.

## Local Run

```bash
npm i
npm run dev
```

## Build

```bash
npm run build
npm run preview
```

## Deploy to Vercel (Recommended)

1. Create a free account at vercel.com and install the **Vercel CLI** (optional).
2. Push this folder to a **new GitHub repo** or use the Vercel “Import Project” button and pick this folder.
3. Framework preset: **Vite**
   - Build command: `npm run build`
   - Output dir: `dist`
4. Click **Deploy**. You’ll get a public URL like `https://windows-sense.vercel.app`.

## Tech

- React 18 + TypeScript
- Vite
- TailwindCSS
- framer-motion, recharts
