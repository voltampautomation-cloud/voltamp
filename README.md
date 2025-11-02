# VoltAmp Automation - Next.js site (Ready for Vercel)

## What is included
- Next.js app (pages directory)
- Tailwind CSS configured
- Framer Motion installed
- Contact form wired to Formspree endpoint (https://formspree.io/f/mqagwodg)
- Logo placed at `/public/VA-logo.png`

## To run locally
1. Install dependencies:
   ```
   npm install
   ```
2. Run the dev server:
   ```
   npm run dev
   ```
3. Open http://localhost:3000

## To deploy to Vercel
1. Push this project to a GitHub repository.
2. Login to https://vercel.com and import the GitHub repo.
3. Vercel will detect Next.js and deploy automatically.
4. (Optional) Set your custom domain in Vercel dashboard.

## Notes about Formspree file uploads
- Formspree supports file uploads; ensure your Formspree form settings allow attachments.
- Emails will be sent to the email associated with the Formspree form.
