# Git / GitHub setup (Windows PowerShell)

```powershell
cd path\to\ai-tools-lab
git init
git add .
git commit -m "Initial commit: AI tools knowledge base"
git branch -M main
```

GitHub par naya empty repo banao (name: ai-tools-lab, README/gitignore mat add karo), phir:

```powershell
git remote add origin https://github.com/<your-username>/ai-tools-lab.git
git push -u origin main
```

Ya GitHub CLI se:
```powershell
gh repo create ai-tools-lab --public --source=. --push
```

Dhyan: API keys / .env kabhi commit mat karo (.gitignore me covered hai).
