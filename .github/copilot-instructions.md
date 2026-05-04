# Next.js Project Setup

## Project: site-postpops
A Next.js website ready for Vercel deployment with TypeScript, Tailwind CSS, and ESLint.

## Development Server
Run the development server:
```bash
npm run dev
```

The app will open at http://localhost:3000

## Building for Production
```bash
npm run build
npm run start
```

## Vercel Deployment
This project is configured for automatic deployment on Vercel:
1. Connect your Git repository to Vercel
2. Vercel will automatically detect the Next.js configuration
3. Deploy with `git push` to your main branch

No additional configuration needed - Vercel handles everything automatically.

## Project Structure
- `src/app/` - App Router pages and layouts
- `src/components/` - React components
- `public/` - Static assets
- `node_modules/` - Dependencies

## Key Files
- `next.config.ts` - Next.js configuration
- `tsconfig.json` - TypeScript configuration
- `tailwind.config.ts` - Tailwind CSS configuration
- `eslint.config.mjs` - ESLint rules

## Dependencies
- Next.js 16
- React 19
- TypeScript
- Tailwind CSS
- ESLint

## Available Scripts
- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint
