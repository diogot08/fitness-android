# Figma import instructions for FitTrack prototype

This folder contains SVG mockups for mobile (360x800) representing the main screens of the FitTrack app. Follow the steps below to import them into your Figma file and create a clickable prototype.

1) Create a new Figma file and set the frame size to 360x800 (Mobile) for each screen.
2) Import the SVG files: In Figma, File → Place image, select the SVGs in the `design/` folder. They will be imported as vector layers (editable).
3) Arrange frames in the order: onboarding.svg, login.svg, home.svg, workouts.svg, workout_detail.svg, session.svg, history.svg, profile.svg.
4) Convert each imported SVG to a Frame (if not already): Right-click → Frame selection.
5) Create a prototype flow:
   - Onboarding `Entrar / Registrar` button → link to login frame.
   - Login `Entrar` button → link to home frame.
   - Home `Iniciar` button (next workout) → link to workout_detail frame.
   - Workout Detail `Iniciar sessão` → link to session frame.
   - From session frame, add link on `Encerrar sessão` (or use `Registrar set` to simulate progression) → link to history or home.
   - Bottom nav texts can be linked to respective frames (Home, Treinos => workouts, Perfil => profile).
6) Prototype settings: choose "On Tap" for triggers and "Navigate To" for actions. Use "Smart Animate" for smoother transitions (optional).
7) Export assets: select icons or any vector and export as PNG/SVG as needed for Play Store.

Hotspot mapping (use this to add click areas in Figma): See `hotspots.json` for coordinates relative to each frame (x, y, width, height, target).

If you want, I can also create a Figma import-ready .fig file and provide it; tell me and I'll add an exported .fig to the repo.
