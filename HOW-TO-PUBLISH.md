# 🚀 How to publish Frontend Odyssey to GitHub

Your repo is already created at:
**https://github.com/lynxiecreations-crypto/Frontend-Odyssey.git**

Below are the exact commands to push this folder into it. Run these from **your own computer**, inside the folder you downloaded (the one containing this file).

## 1. Initialize git (if this folder isn't already a repo)

```bash
cd Frontend-Odyssey
git init
git branch -M main
```

## 2. Connect it to your GitHub repo

```bash
git remote add origin https://github.com/lynxiecreations-crypto/Frontend-Odyssey.git
```

If that repo already has a README/commit in it from GitHub's "create repo" step, pull first so you don't get a rejected push:

```bash
git pull origin main --allow-unrelated-histories
```

## 3. Stage, commit, and push everything

```bash
git add .
git commit -m "Add Frontend Odyssey: 20 useful apps across 4 levels"
git push -u origin main
```

## 4. Authenticate

GitHub no longer accepts your account password over HTTPS git operations — you'll be prompted for a **Personal Access Token (PAT)** instead of a password. If you don't have one yet:

1. Go to **GitHub → Settings → Developer settings → Personal access tokens → Tokens (classic)**
2. Generate a new token with the `repo` scope
3. Copy it, and paste it in place of your password when `git push` prompts you

(Alternatively, set up SSH keys and use `git@github.com:lynxiecreations-crypto/Frontend-Odyssey.git` as your remote instead of the HTTPS URL — no token needed after that.)

## 5. Verify

Visit https://github.com/lynxiecreations-crypto/Frontend-Odyssey and confirm all four `Level-*` folders and the README show up.

---

## ⚠️ About sharing your GitHub credentials

Please don't paste your GitHub password, personal access token, or any other credential into this chat. I can't securely store or use credentials on your behalf, and pasting them here would expose them in your chat history. The commands above are the safest way to get this onto GitHub yourself — it's just three or four commands, and takes under a minute.

If you'd rather not use the command line at all, GitHub's website also lets you do this via drag-and-drop:

1. Open your repo page → click **"Add file" → "Upload files"**
2. Drag the entire `Frontend-Odyssey` folder contents in
3. Scroll down, add a commit message, click **"Commit changes"**

## 🌐 Optional: turn one app into a live demo with GitHub Pages

1. In your repo, go to **Settings → Pages**
2. Under "Source," choose the `main` branch and `/ (root)` folder
3. Save — GitHub will publish at `https://lynxiecreations-crypto.github.io/Frontend-Odyssey/`
4. Since each app is a single file, link directly to one, e.g.:
   `https://lynxiecreations-crypto.github.io/Frontend-Odyssey/Level-4-Mastermind/analytics-dashboard.html`
