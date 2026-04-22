DEMANDEM READY-TO-UPLOAD SITE

WHAT THIS ZIP INCLUDES
- A simple static website you can upload to GitHub and deploy on Vercel for free.
- Product images already placed in the correct folder.
- Scroll reveal animation, subtle image hover zoom, and the hidden "111" detail.
- A countdown date you can change in script.js.

HOW TO PREVIEW LOCALLY
Option 1:
- Open index.html in your browser.

Option 2:
- In VS Code, install the "Live Server" extension.
- Right-click index.html and choose "Open with Live Server".

HOW TO PUT IT LIVE FOR FREE WITH VERCEL
1. Create a GitHub account if you do not have one.
2. Create a new repository called demandem-site.
3. Upload every file from this folder to that repository.
4. Go to Vercel.com and sign in with GitHub.
5. Click Add New Project.
6. Import the demandem-site repository.
7. Click Deploy.
8. Vercel will give you a free live link.

HOW TO CHANGE THE COUNTDOWN DATE
- Open script.js
- Change this line:
  const launchDate = new Date('2026-06-15T12:00:00');

HOW TO COLLECT REAL EMAILS
Right now the form points to a placeholder Formspree link:
  https://formspree.io/f/your-form-id

To make the waitlist form work:
1. Go to Formspree.io
2. Create a free form
3. Copy your form endpoint
4. Open index.html
5. Find this line in the form tag:
   action="https://formspree.io/f/your-form-id"
6. Replace it with your real Formspree link
7. Redeploy on Vercel

HOW THE IMAGES ARE ORGANIZED
- images/front-back.png
- images/front.png
- images/back.png
- images/detail1.png
- images/detail2.png

If you want to swap any image later:
- Put the new file inside the images folder
- Keep the same filename OR update the matching img src in index.html
