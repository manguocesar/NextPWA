# Basic NextJS PWA setup

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Steps
1. npm install next-pwa
2. update next.config.mjs
3. in .env set NODE_ENV="development"
4. add [public/manifest.json](https://www.mridul.tech/tools/manifest-generator) 
5. Define the PWA Metadata
6. Build and Run PWA

### NEXT PWA includes
- Service worker generation and registration
- Caching
- Offline support
- Manifest file generation
- Head meta tags

### ADDITIONALS
- sw.js as caching, background synchronization, providing native features, and enabling offline support
- workbox caches assets