WGAR GITHUB PAGES WEBSITE
=========================

WHAT'S INCLUDED
- index.html                Main WGAR site
- laws.html                 Full WGAR lawbook
- styles.css                All styling
- script.js                 Mobile menu behavior
- assets/backgrounds/       Large background GFX
- assets/divisions/         Division card GFX

GITHUB PAGES INSTALLATION
1. Go to https://github.com and sign in.
2. Click the + button in the top-right -> New repository.
3. Name it something like: WGAR
4. Choose Public, then Create repository.
5. EXTRACT this ZIP on your computer first.
6. In the empty GitHub repo, choose:
   Add file -> Upload files
7. Drag ALL FILES AND FOLDERS from inside WGAR_GitHub_Site into the upload page.
   IMPORTANT: index.html must be at the top level of the repository.
8. Click Commit changes.
9. Open Settings in the repository.
10. In the left sidebar click Pages.
11. Under Build and deployment:
    Source: Deploy from a branch
    Branch: main
    Folder: / (root)
12. Click Save.
13. Wait about 1-3 minutes and refresh the Pages settings screen.
14. GitHub will show your live link, normally:
    https://YOUR-USERNAME.github.io/WGAR/

UPDATING THE SITE LATER
1. Open your GitHub repository.
2. Click the file you want to change.
3. Click the pencil/edit icon.
4. Make the change and click Commit changes.
5. GitHub Pages automatically updates the website.

CHANGING IMAGES
- Backgrounds are in assets/backgrounds/
- Division images are in assets/divisions/
You can upload a replacement image with the SAME filename to replace it without editing HTML.

IMPORTANT ABOUT DIVISION NAMES
Some supplied GFX use fan-made/stylized markings. The site uses the most likely Star Wars unit labels based on visible color/armor themes.
If your WGAR uses different official division names, edit the text in index.html or send the correct mapping and it can be updated.


FIXED VERSION NOTES
===================
- Converted WEBP site assets to PNG for better compatibility.
- Republic Special Operations -> Republic Intelligence
- 187th Battalion -> 187th Legion
- Shadow Troopers -> Red Guards (Guarding Division)
- Mandalorian Auxiliaries -> Advanced Recon Commandos (Combat Division)
- Improved division card layout/readability.

HOW TO UPDATE YOUR EXISTING GITHUB SITE
1. Open your GARwebsite repository.
2. Delete the OLD website files/folders or replace them with this version.
3. Upload:
   index.html
   laws.html
   styles.css
   script.js
   assets/
4. Commit changes.
5. GitHub Pages will redeploy automatically after a short wait.

IMPORTANT:
The entire assets folder must be uploaded, including:
assets/backgrounds/
assets/divisions/
If images still do not appear, check that those folders are visible in your GitHub repository.

DIVISION UPDATE
===============
The Divisions section now uses the 13 exact images supplied by the site owner:
41st Elite Corps, Advanced Recon Commandos (ARC), 187th Legion, 212th Attack Battalion,
327th Star Corps, 501st Legion, The Bad Batch / Clone Force 99, Coruscant Guard,
Jedi Order, Senate Guard, Red Guard, Republic Intelligence, and Republic Commandos.

Upload/replace index.html and the full assets/divisions folder on GitHub, then commit.
