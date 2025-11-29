# AIRLeague  All-India JEE Mains Open Test Landing Page

This repository contains a single-page landing site for **AIRLeague**, an All-India JEE Mains open test aimed at students from local coachings, self-study aspirants and droppers.

The core idea:

- Showcase participation at an All-India scale (target 50,000+ students)
- Highlight that students can see their performance on a national leaderboard
- Emphasise that the question paper is designed by a committee of IIT Delhi professors, IIT Delhi pass-outs and PhD scholars
- Make it especially relevant and aspirational for students of local coachings across India

## Tech stack

- Pure HTML + Tailwind CSS via CDN
- No build step, no bundler, no framework
- Works as a static site on any modern web host

## Run locally

- Open `index.html` directly in a modern browser (Chrome, Edge, Firefox, etc.), or
- Serve the folder using any simple static server if you prefer (for example, through your IDE or a lightweight HTTP server).

No additional setup or dependencies are required.

## Deploy

You can deploy this folder as-is to any static hosting provider:

- **Netlify**: create a new site from this folder and set the publish directory to the repo root.
- **Vercel**: create a new project, select this folder, choose a static/other preset, and let `index.html` be the entry.
- **GitHub Pages**: push this folder to a GitHub repository and enable GitHub Pages for the main branch.
- **Any static host**: upload `index.html` (and any future assets you add) to the root of your site.

## Customisation guide

You will likely want to adapt the copy to your own brand name, dates and registration flow.

- **Brand name / logo text**  
  Search for `AIRLeague` in `index.html` and update it to your preferred brand or test name.

- **Registration link (CTA button)**  
  In `index.html`, search for `https://example.com/register` and replace it with your actual Google Form link or custom signup URL.

- **Dates, fee, mode of exam**  
  Once final, update the text in the **How it works** and **FAQ** sections to reflect the exact schedule, fee, mode (online/offline) and other logistics.

- **Sections**  
  The page is structured into:
  - Hero section (headline, All-India scale, key stats)
  - For students (especially from local coachings)
  - Academic committee (IIT Delhi professors, pass-outs, PhD scholars)
  - For coaching institutes
  - How it works
  - FAQ
  - Registration call-to-action

You can rearrange, remove or add sections to match how you want to pitch the test.

## Future evolution

If you later decide to move to a framework like React or Next.js, you can reuse the same content and layout ideas from this static page and port them into components. For an initial launch, this zero-dependency static setup is intentionally simple and easy to deploy.
