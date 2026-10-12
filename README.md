# BEYOND THE GAME — DEMO 1 (NOT FINAL)

Interactive 2026 Hoa Sen University ELL1 survey website demo for Group 04. This is a **review draft** and not an approved final presentation.

## Contents

- `index.html` — entry point
- `styles.css` — presentation styling and mobile layout
- `app.js` — slide data, charts, navigation and quiz controls
- `assets/` — player photos selected by the group for DEMO 1
- `vercel.json` — deploy settings for a static site

## Preview locally

In this folder run `python3 -m http.server 8000` and open http://localhost:8000. Alternatively open `index.html` directly; depending on browser settings some features may prefer a local server. No NPM or build is required.

## Controls

- Left/right arrows or Space — navigate scenes
- `F` — request fullscreen (browser support required)
- Top-left identity — open scene navigation
- EN/VI — switch between English and Vietnamese
- Mobile: swipe horizontally or tap next/previous
- Mini game: show the clear photograph, have students guess aloud; add confirmed answer with the input, Save, then Reveal Answer. Saved only in that browser/device.

## Data and outstanding items

Statistics represent 50 actual CSV respondents received October 2026. Multi-select sports totals can exceed 100%. Score averages exclude 'Not aware', whereas 4–5 percentages use all 50 respondents. The international ranking excludes two multi-name entries, merges Ronaldo/CR7/Cristiano Ronaldo, and omits Rooney only **visually** by the group's instruction, not from the CSV.

- **HSU official logo:** placeholder letters, official logo NOT supplied.
- **Tournament official logos:** visual placeholders pending properly sourced 2026/27 assets.
- **Team members:** names, roles and photo pending. Four roster lines demonstrate a *layout*, not the team size.
- **Vietnam 2026 achievements:** awaiting independently checked sources.
- **Current player clubs:** Vietnamese clubs checked using VOV, Thanh Nien, VTC News October 2026; Neymar's Santos club checked via October 2026 reports. Review again when finalizing: https://vov.vn/the-thao/nam-dinh-cap-nhat-tinh-hinh-chan-thuong-cua-xuan-son-post1339439.vov , https://thanhnien.vn/dinh-bac-bi-dung-dap-co-phut-905-tran-clb-cahn-thang-tai-singapre-hlv-polking-phai-tinh-toan-185261008222906211.htm , https://vtcnews.vn/thong-tin-moi-nhat-ve-chan-thuong-cua-hoang-duc-ar1038246.html .
- **Quiz answers:** group has supplied only photos, not the names. Enter approved answers in the demo UI per device or set code when confirmed.
- **QR:** is intentionally just a placeholder; add real QR only when deployed URL is confirmed.
- **Image permissions:** player photos supplied by Group 04 for internal review; before public release check their origins, credits and permission to republish.

## Fastest Vercel DEMO 1 deployment — Vercel Drop

1. Visit https://vercel.com/drop and sign in. Vercel Drop accepts this .zip directly.
2. Upload the **whole ZIP**, enter a fresh name (e.g. `beyond-the-game-ell1-group4-demo1`, if available), choose your account/team, click **Deploy**.
3. Vercel will create a *new* Vercel project and give a `.vercel.app` URL. Test on laptop and phone.
4. Each Vercel Drop upload makes a **new project**. For revising the same URL later, connect GitHub for automatic updates.

## Vercel via GitHub (better for continued revisions)

1. Create a new GitHub repository (`beyond-the-game-ell1-group4` or another available name).
2. Unzip this archive on your computer. In the new repo use **Add file → Upload files**. Upload `index.html`, `app.js`, `styles.css`, `vercel.json` and the **whole `assets` folder**. Commit the changes. (Do not upload the ZIP as the only file.)
3. Sign in to https://vercel.com with GitHub; click **Add New → Project**, select/import the repository, approve permissions if asked.
4. Framework Preset: **Other**; Root Directory: repository root `./`; **no build command**; Output Directory: `.` if requested; deploy.
5. Open the assigned `.vercel.app` link, check images and use arrow keys; add your own domain only if needed. Vercel name availability is not guaranteed.

To modify the site after deployment, commit changed files to GitHub and Vercel should automatically redeploy.


## Vercel Drop — fastest deployment for Demo 1

1. Open https://vercel.com/drop on a computer and sign in.
2. Drag the provided `BEYOND_THE_GAME_ELL1_GROUP04_DEMO_1_VERCEL.zip` onto the upload area.
3. Select your account/team, enter an available project name, and Deploy.
4. Check the generated URL. This creates a **new Vercel project**, no GitHub necessary.
5. For long-term updates and version history, prefer the GitHub integration instructions above.

Official Vercel references: https://vercel.com/i/deploy-to-vercel-without-git and https://vercel.com/docs/git
