# GitHub Profile README — Setup Guide

This bundle is prepared for the GitHub username **SaadQureshi002**.

## 1. Create the profile repository

Create a **public** GitHub repository named exactly:

```text
SaadQureshi002
```

The repository name must match your GitHub username exactly.

## 2. Upload this bundle

Your repository should look like this:

```text
SaadQureshi002/
├── README.md
├── SETUP.md
├── assets/
│   ├── header.svg
│   ├── footer.svg
│   └── tech-radar.svg
└── .github/
    └── workflows/
        ├── snake.yml
        └── waka-readme.yml
```

## 3. Replace your email

Open `README.md` and replace every occurrence of:

```text
YOUR_EMAIL@gmail.com
```

with your preferred professional email address.

## 4. Enable GitHub Actions write access

Go to:

**Repository → Settings → Actions → General → Workflow permissions**

Select:

**Read and write permissions**

Then save.

## 5. Generate the contribution snake

Go to:

**Actions → Generate Contribution Snake → Run workflow**

After the workflow finishes, an `output` branch will be created. The snake in your README will then load automatically.

The workflow also runs automatically every day.

## 6. Enable Weekly Coding Breakdown with WakaTime

### A. Create WakaTime account
Create a WakaTime account and install its plugin/extension in the IDEs you use (for example VS Code).

### B. Copy your WakaTime API key
From WakaTime, copy your API key.

### C. Add the secret to GitHub
Go to:

**Repository → Settings → Secrets and variables → Actions → New repository secret**

Name:

```text
WAKATIME_API_KEY
```

Value: paste your WakaTime API key.

### D. Run the workflow
Go to:

**Actions → Update WakaTime Coding Stats → Run workflow**

Your README section between these markers will be updated automatically:

```html
<!--START_SECTION:waka-->
<!--END_SECTION:waka-->
```

It will then update every day.

## 7. Check your profile

Open:

```text
https://github.com/SaadQureshi002
```

Your profile README should appear automatically.

## Notes

- GitHub stats, streak, typing text, profile views and activity graph are dynamic third-party widgets.
- They may occasionally be temporarily rate-limited even when your README is correct.
- The local `assets/` graphics will keep working because they are stored inside your own repository.
