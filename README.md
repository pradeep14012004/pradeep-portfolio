# Pradeep M. Doddakaragi — Portfolio

Plain HTML/CSS/JS. No build step, no npm.

## Run in VS Code
1. Unzip and open the folder in VS Code (File → Open Folder).
2. Install the **Live Server** extension (Ritwick Dey), right-click `index.html` → **Open with Live Server**.
   Or in the VS Code terminal: `python -m http.server 5500`, then open http://localhost:5500
3. You need an internet connection for the Google Fonts.

## Edit
- Content lives in `index.html` (projects, skills and timeline are the arrays in the `<script>` near the bottom).
- Photos and résumé are in `assets/`. Replace them with files of the same name.
- The résumé PDF contains your phone number; remove the download links (marked `<!--zip-->`) if you don't want it public.

## Deploy
Drag the folder onto Netlify/Vercel, or push to GitHub Pages. It is a static site.
