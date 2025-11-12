# Resilience Kit

Action-first kit to reduce crypto market contagion and help users, venues, and policymakers choose **resilience > roulette**.

## What’s inside
- **posts/**: Copy‑paste posts for X/Twitter, Reddit, LinkedIn, and a 120‑word open note.
- **policy/**: A one-page *Resilience Pledge* and a policymaker letter template.
- **checklists/**: Individual risk checklist + an If/Then trigger sheet.
- **tools/**: Sirens to watch and quick operational guidance.

## Quickstart
1) Drop this folder into any repo (or make it the repo).  
2) Post from **posts/**, adopt **policy/**, and follow **checklists/**.  
3) Share the pledge; PR it into infra repos you depend on.

## Upload to a NEW repo (CLI)
```bash
unzip resilience-kit.zip
cd resilience-kit
git init
git add .
git commit -m "Add Resilience Kit"
git branch -M main
git remote add origin git@github.com:<your-username>/<new-repo>.git
git push -u origin main
```

## Add to an EXISTING repo (CLI)
```bash
git clone git@github.com:<your-username>/<existing-repo>.git
cd <existing-repo>
mkdir -p resilience-kit
unzip ../resilience-kit.zip -d ./resilience-kit
git add resilience-kit
git commit -m "Add resilience kit assets"
git push
```

## License
MIT — copy, modify, and redistribute freely.