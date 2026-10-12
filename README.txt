Login Motion Lab — starter

Use Node 24.12+ (24.x) or 22.18+ (22.x).
Open this folder in your editor.
Run npm ci, then npm run dev. Open the Local URL.
Keep the same host and port when testing saved data.

Edit src/motion.css for checkpoints 01–06.
Edit src/storage.js for checkpoints 07–09.
App.vue and base.css are provided.
First sign up with a name, demo email, password and matching confirmation.
Then sign in with that email and any 4+ made-up password characters.
Demo accounts store name/email; the current session stores email. Sign-out removes only the session. Passwords are never saved or checked. This is a UI simulation, not real authentication.

Build: npm run build
Preview: npm run preview
Do not double-click dist/index.html to test localStorage.

--- GitHub Pages (login-motion-lab-final) ---
1. Create the repo "login-motion-lab-final" on GitHub and push this folder to branch main.
2. Settings > Pages > Source: "GitHub Actions".
3. The workflow in .github/workflows/deploy.yml builds and publishes automatically.
Live URL: https://<your-user>.github.io/login-motion-lab-final/
