# Put the Permit Portal Online — Click-by-Click (about 15 minutes)

You'll end up with a real web address like **https://projectpermitportal.github.io/portal/** that works on any phone — that's the address the QR codes will use.

## Part 1 — Create the account (you must do this part yourself)
1. Go to **github.com** and click **Sign up**.
2. Email: use one you control (bdiaz8448@gmail.com works).
3. Username: try **projectpermitportal** (if taken: **project-permit-portal** or **permitportalpro**).
4. Create a password, verify the puzzle, then enter the code GitHub emails you.
5. Skip all the personalization questions (choose Free plan).

## Part 2 — Create the repository
1. Click the **+** in the top-right corner → **New repository**.
2. Repository name: **portal**
3. Set it to **Public** (required for free hosting).
4. Do NOT check any of the "initialize" boxes. Click **Create repository**.

## Part 3 — Upload the website
1. On the new repo page, click the link that says **"uploading an existing file"**.
2. Open your **Daily Permit Numbering Website** folder on your Desktop.
3. Drag in: **index.html**, **HANDOFF.md**, the whole **assets** folder, and the whole **w4rw4** folder.
   - Tip: if folder-dragging misbehaves, drag index.html first, commit, then drag each folder separately.
   - You can skip the two big .xlsx master files — they're your private records, not part of the website.
   - The floor plans PDF ("DSM4 floor plans and walkable ceiling plain.pdf") IS used by the "Open full PDF" button — upload it too if it's under GitHub's 100 MB limit (it is).
4. Scroll down, click **Commit changes**. Wait for the upload bar to finish before leaving the page.

## Part 4 — Turn on the website (GitHub Pages)
1. In the repo, click **Settings** (top tab) → **Pages** (left sidebar).
2. Under "Build and deployment" → Source: **Deploy from a branch**.
3. Branch: **main**, folder: **/ (root)** → **Save**.
4. Wait 1–2 minutes, refresh the page — GitHub shows your live address at the top, like:
   **https://projectpermitportal.github.io/portal/**
5. Open it on your phone. Done.

## Part 5 — After it's live (important)
- Open the live site as Admin → **QR Codes** → print the posters. (QR codes point at the live address now.)
- Sign in with the Owner PIN (**7777** — CHANGE IT immediately in Settings).
- Remember: each device keeps its own data in this pilot. The kiosk's permits live on the kiosk. Weekly "Save Record Copy" from the main device is your official log.

## Updating the website later
Any time the index.html on your Desktop changes:
1. Go to the repo → click **index.html** → click the **pencil icon** (or just re-drag the file via Add file → Upload files).
2. Commit changes. The live site updates in about a minute.

## If you get stuck
Open a Claude session (Opus or Sonnet), point it at this folder, and say:
**"Read HANDOFF.md and GITHUB-SETUP.md. I'm stuck on Part X — walk me through it."**
It will know exactly what this project is.
