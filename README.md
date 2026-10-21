# Dinesh Karthik — Portfolio

A responsive, static portfolio built with semantic HTML, CSS, and vanilla JavaScript. It includes your stated software, AI development, data analytics skills and language proficiencies. The design follows the supplied reference: a quiet light palette, generous spacing, rounded panels, a centered profile portrait, and direct contact actions. There is no package install or build step.

## Run locally

Open `index.html` in a browser, or run `npx serve .` from this folder for a local web server.

## Before sharing

- Replace the Google Drive resume URL in the header, hero, and contact panel if you upload a new resume.
- Update the LinkedIn URL if your profile address changes.
- Add verification links for certificates if you want visitors to verify them.
- Update the IEEE paper URL if the publication link changes.
- Add live demos for the projects if they become available.
- Confirm the visible contact details and certificate wording.

The portfolio includes your email, phone number, and city from the supplied resume so recruiters can contact you directly. Remove or change the phone number if you do not want it public. The resume button opens the Google Drive file you supplied; the PDF itself is not copied into this website.

The credentials section uses titles transcribed from the supplied resume and certificate PDFs. The CodeChef SQL and Python items are marked as needing confirmation because individual verification details were not available in the supplied files. The internship certificate informs the Clobas role summary. The student leadership entry uses the dates and title already provided in the conversation.

The IoT project summary comes from its GitHub README. Its preliminary outcome is not quoted as a verified metric. Plant Disease Recognition and Text Emotion Detection have been removed from the featured project list as requested.

## Deploy on Vercel

This is a static website, so it does not need React, Next.js, or a build command. Import the GitHub repository in Vercel and set the root directory to the project folder if needed. Choose **Other** as the framework preset, leave the build command blank, and set the output directory to `.`. Vercel will serve `index.html` as the site homepage. The included `vercel.json` keeps URLs clean.

## Files

- `index.html` — portfolio sections, content, and project drawings
- `styles.css` — responsive layout and accessibility states
- `script.js` — accessible mobile navigation
- `assets/dinesh-portrait.webp` — square grayscale portrait cutout with transparency, displayed as a circle
- `favicon.svg` — DK monogram
- `vercel.json` — clean URL settings
