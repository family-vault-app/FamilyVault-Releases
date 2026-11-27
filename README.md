# Family Vault and Estate Planner

**A private place on your own PC for your family's passwords and accounts, and a guided estate plan for the people you love.**

Family Vault and Estate Planner is a free Windows app for households. Everything stays on your computer: there is no cloud account, no tracking, and nothing is sent anywhere.

## What it does

- **Keeps your passwords and accounts safe.** Each family member has their own vault. You can share an entry with someone else in the family, and the app reminds you about renewals and recurring payments.
- **Helps you plan for the unexpected.** A step-by-step questionnaire walks you through your will, insurance, bank accounts, bills, digital accounts, your employer, who to contact, and your wishes. Couples can work on one plan together.
- **Prints a binder for your safe.** Print the whole plan, with revision numbers, so a paper copy is ready when it's needed. The app tells you when the printed copy is out of date.
- **Gives your family a way in.** Emergency contacts can ask for access after a waiting period you choose, and an executor checklist helps work through what needs to be cancelled, transferred or claimed.

## Download

1. Open the [latest release](https://github.com/family-vault-app/FamilyVault-Releases/releases/latest).
2. Download **FamilyVaultEstatePlanner-Setup-*version*.exe** (the installer).
   - Prefer not to install? Download the **.zip** instead, and unzip it into a folder you own (for example in your Documents), not into Program Files.
3. Read the **[User Manual (PDF)](Family-Vault-User-Manual.pdf)**. It walks you through everything with pictures.

You'll need Windows 10 or 11 (64-bit). The app uses Microsoft's free WebView2 runtime, which most PCs already have; if yours doesn't, the installer tells you where to get it.

## Installing

1. Run the installer. It installs just for you, so no administrator password is needed.
2. Windows may show **"Windows protected your PC"**. That's because the app isn't signed by a big publisher. Click **More info**, then **Run anyway**.
3. Start **Family Vault and Estate Planner** from the Start menu. A short **Before you start** note explains how the app works. Then you create the first account and print your **recovery code**: keep it with your important papers.

## Updates

The app checks for new versions by itself once a day. When one is out, the **About** page shows **Update available** with a download link. Run the new installer: your passwords, plans and backups are kept.

## Your information

- Your information is stored encrypted on your own PC, in the app's `data` folder.
- Back it up: the app makes automatic backups, and can also copy them to a USB stick or another folder you choose.
- Keep your printed recovery code safe. Without it, a forgotten administrator password can't be recovered.
- This app is a personal organizer. It is not legal, financial or tax advice.

## Checking your download (optional)

Each release lists **SHA256SUMS.txt**. To check a file, open PowerShell in your Downloads folder and run:

```powershell
Get-FileHash .\FamilyVaultEstatePlanner-Setup-1.0.0.exe -Algorithm SHA256
```

The value should match the one in SHA256SUMS.txt.

## Licence

Free for personal and household use, and free to share with friends: please pass it on unchanged and never sell it. It comes as is, without warranty. The full licence is in `LICENSE.txt`, inside the app's folder and on the app's **About** page.

Copyright (c) 2026 Benji Kidmose.

## Help

Questions? Ask the person who gave you the app. Inside the app, the **?** button on each screen explains that screen.
