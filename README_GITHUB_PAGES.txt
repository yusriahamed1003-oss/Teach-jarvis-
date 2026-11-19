TEACH JARVIS — GITHUB PAGES STARTER

This package is prepared for GitHub Pages. It contains the existing Teach Jarvis front-end prototype, PWA manifest, offline service worker, icons, and an automated GitHub Pages deployment workflow.

IMPORTANT CURRENT LIMITATIONS
- This is still a front-end prototype, not a complete production student platform.
- AI Teacher replies are examples; no real AI backend is connected.
- Library entries are placeholders; add only official or properly licensed materials.
- There is no real student registration, PIN authentication, account recovery, cloud database, or cloud backup.
- Do not enter real student names, dates of birth, PINs, or other sensitive information.
- GitHub Pages hosts static public files. Anyone can view the site's source code in a public repository. Never put passwords, API keys, student records, or private data in this repository.
- Offline timetable/homework data is stored in the browser on that device only. It does not sync to other devices.

PUBLISH ON GITHUB PAGES (Chromebook)
1. With a parent/guardian's help, sign in to GitHub and create a NEW repository named: teach-jarvis
2. Choose Public only if you are comfortable with the website source being visible. Do not upload personal information.
3. In the new repository, choose Add file > Upload files.
4. Open this ZIP on your Chromebook, then upload the CONTENTS of this folder (index.html, manifest.webmanifest, service-worker.js, icons folder, and .github folder). Keep the folder structure exactly as shown. Do not upload this ZIP as a single file.
5. Commit the files to the main branch.
6. Open the repository's Settings > Pages. If asked for a source, select GitHub Actions.
7. Open the Actions tab and wait for “Deploy Teach Jarvis to GitHub Pages” to finish successfully.
8. The public address will appear in Settings > Pages and in the workflow deployment result. It usually looks like https://YOUR-USERNAME.github.io/teach-jarvis/ .
9. Open that address in Chrome while online once. Then use Chrome's menu > Install app (if offered) or Create shortcut > Open as window.

If the workflow does not start, check that the files including .github/workflows/pages.yml were uploaded with their folders intact.

PWA / OFFLINE TEST
1. Visit the GitHub Pages address while online and wait for it to finish loading.
2. Add a homework item and a timetable session.
3. Turn off Wi-Fi and reload. The app shell and browser-local data should remain available after the first successful online visit.
4. Turn Wi-Fi back on.

ANDROID APK
GitHub Pages does not create an APK. Android packaging/signing is a separate later step and needs an Android build environment. The Chromebook may not support every Android packaging tool.


BRANDING UPDATE
The app icons are now the new futuristic Teach Jarvis TJ logo.
The manifest points to icons/icon-192.png and icons/icon-512.png.
Upload the contents of this folder to the repository root, keeping the icons folder.
