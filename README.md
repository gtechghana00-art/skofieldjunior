# SkofieldJunior Thank You Landing Page

Responsive React + TypeScript + Vite landing page using SkofieldJunior's orange, black and cream palette.

## Add your images
Place your own portrait at `public/images/profile.jpg` and your logo at `public/images/logo.png`.
The portrait and logo files are not bundled because you should use the original images you uploaded.

## Run locally
1. Install Node.js (LTS) from https://nodejs.org/
2. Extract this project folder.
3. Open the folder in VS Code or Antigravity.
4. Open a terminal in the project folder and run:
   ```bash
   npm install
   npm run dev
   ```
5. Open the local address printed in the terminal, commonly `http://localhost:5173`.

## Build for deployment
Run `npm run build`. The production files will be generated in `dist/`.

## Personalise your contact details
Edit the constants at the top of `src/App.tsx`:
- `WHATSAPP_NUMBER`: Ghana number with country code and without the first 0.
- `PHONE_DISPLAY`: number displayed on the page.
- `INSTAGRAM_HANDLE`: your social handle.

## Paystack warning
This page does not verify payments. Do not treat a visit to the page as proof of payment. Confirm payments in your Paystack dashboard. To add automated verification, implement it on a secure backend and keep your Paystack secret key out of frontend code.
