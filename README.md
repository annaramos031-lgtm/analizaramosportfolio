# Analiza De Torres Ramos — Portfolio Website

A responsive personal portfolio with a soft pink palette, elegant typography, subtle motion, and a portrait placeholder.

## Open in VS Code
1. Extract `analiza_ramos_portfolio.zip`.
2. Open the extracted `analiza_ramos_portfolio` folder in Visual Studio Code.
3. Open `index.html` in a browser. Recommended: install the **Live Server** extension in VS Code, right-click `index.html`, then choose **Open with Live Server**.

## Add Analiza's photo
The hero portrait is currently a designed placeholder. To use a real photo:
1. Put the image in the `assets` folder, for example `analiza.jpg`.
2. In `index.html`, find `<div class="portrait-placeholder"> ... </div>` inside `.portrait-frame`.
3. Replace that block with:
   ```html
   <div class="portrait-placeholder actual-photo">
     <img src="assets/analiza.jpg" alt="Portrait of Analiza De Torres Ramos">
   </div>
   ```
4. Add this to the end of `style.css`:
   ```css
   .portrait-placeholder.actual-photo { padding: 0; background: #f6dce7; }
   .portrait-placeholder.actual-photo img { width: 100%; height: 100%; object-fit: cover; }
   ```

## Personalize the content
- Edit the About section with Analiza's real background and goals.
- Replace sample skills and project cards with accurate details.
- Change `annaramos031@gmail.com` in `index.html` to her email.
- Update the page title and description if needed.

## Notes
- Google Fonts are loaded online. System fallback fonts are included for offline use.
- No build step or package installation is required.


## Resume / CV and Certificates
The `assets/documents` folder contains temporary placeholder PDFs so the Preview and Download buttons work immediately:
- `analiza-resume-placeholder.pdf`
- `analiza-certificates-placeholder.pdf`

Replace these with Analiza's official documents, keeping the same filenames to avoid changing the website links. The placeholders are not official credentials.

## Contact form
The form prepares a message addressed to `annaramos031@gmail.com` in the visitor's default email app. The visitor must confirm sending from that app. A static HTML website cannot securely deliver email directly without a backend or a form service.


## Profile photo
Analiza’s professional portrait is included at `assets/analiza-professional-portrait.png` and displayed in the homepage hero section.


## Portfolio positioning
The profile is written to welcome a broad range of online and remote opportunities, including virtual assistance, administrative support, data entry, customer support, online research, and other suitable work. Keep listed skills and experience accurate to Analiza's actual background.


## CV uploaded to portfolio
Analiza's current CV is available at `assets/documents/Analiza-De-Torres-Ramos-CV.pdf`.
The Resume/CV Preview and Download links point to this file. The certificates PDF remains a clearly labeled placeholder until official certificates are available.
