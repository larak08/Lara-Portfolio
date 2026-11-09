# Lara Koshal — Portfolio

A React + TypeScript + Vite portfolio with Home, About Me, Projects, individual project detail pages, Resume, and Contact. Includes supplied images, co-op video, and a public resume PDF with the phone number removed.

## Run locally

Install Node.js (LTS), then in this folder:

```bash
npm install
npm run dev
```

Open the local URL shown in the terminal. To check production build:

```bash
npm run build
npm run preview
```

## Deploy to Vercel

1. Create a new GitHub repository, e.g. `lara-portfolio`.
2. Upload the *contents of this folder* to the repository (not the ZIP, and not `node_modules`).
3. Visit https://vercel.com/new, sign in with GitHub, and import your repository.
4. Framework: Vite. Root: `./`. Build command: `npm run build`. Output directory: `dist`.
5. Deploy and share the generated `.vercel.app` URL.
6. Future GitHub pushes will trigger new deployments.

The `vercel.json` rewrite makes deep links such as `/projects/bridgepath` load when opened directly.

## Before publishing

- Check all written descriptions and individual contributions for accuracy.
- Verify your co-op video is suitable for public sharing and contains no confidential information.
- The AI diagram is a generic illustration, not a screenshot of the original system.
- The vehicle repository link was intentionally omitted because its public accessibility is unconfirmed. Add it to the project `links` array in `src/main.tsx` once public.
- The PDF phone number has been removed; inspect the rest of your resume before sharing.
- Large video file (~44 MB) increases repository and deployment size. If preferred, replace with a YouTube/Vimeo embed and remove `public/coop-presentation.mp4`.

## Change content

Edit `src/main.tsx` for text, links and project pages. Edit `src/style.css` for colours, fonts and layout. Replace images in `public/images/`.
