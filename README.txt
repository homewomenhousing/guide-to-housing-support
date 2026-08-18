BEFORE IT GETS HARD — SPLASH PAGE

This folder is a complete static website. You do not need to install anything.

FILES
- index.html = page content
- style.css = design
- assets/images = all website images
- assets/files = place for the downloadable guide PDF

TO ADD THE FINAL GUIDE PDF
1. Put the PDF in assets/files/
2. Rename it: before-it-gets-hard-guide.pdf
3. In index.html, find: <span class="pill disabled" ...>PDF coming soon</span>
4. Replace that line with:
   <a class="pill" href="assets/files/before-it-gets-hard-guide.pdf" download>Download PDF ↓</a>
5. You can also remove the sentence saying the downloadable PDF can be added later.

TO PUBLISH ON GITHUB PAGES
1. Create a public GitHub repository.
2. Upload EVERYTHING inside this folder, keeping the folder structure.
3. Open Settings > Pages.
4. Under Build and deployment choose "Deploy from a branch".
5. Choose branch "main" and folder "/ (root)", then Save.

The site is responsive for desktop and mobile.
