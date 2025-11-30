# BootstrapForm

Small Bootstrap-based form project.

How to upload to GitHub

1. Initialize a local repo, add files, and commit:

```powershell
cd 'c:\Users\cscot\OneDrive\Desktop\MyCode\BootstrapForm'
git init
git add .
git commit -m "Initial commit"
```

2. Create a GitHub repository:
- Option A (recommended): Install and authenticate the GitHub CLI (`gh`), then run:

```powershell
gh auth login
gh repo create <repo-name> --public --source=. --push
```

- Option B: Create a new repository at https://github.com/new and follow the instructions to add a remote and push:

```powershell
git remote add origin https://github.com/<your-username>/<repo-name>.git
git branch -M main
git push -u origin main
```

3. After pushing, set repository description, license and visibility on GitHub.

If you want, I can run the git initialization and attempt to create the repo using `gh` now.
