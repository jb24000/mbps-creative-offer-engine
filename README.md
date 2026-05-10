[README.md](https://github.com/user-attachments/files/27562410/README.md)
# MBPS Creative Offer Engine

A GitHub-ready PWA for generating MB Property Solutions-style creative real estate offers.

## Features

- Subject-to offer generator
- Seller finance offer generator
- Hybrid subject-to + seller finance offer generator
- Cash / wholesale offer generator
- Dynamic seller email language based on selected exit strategy
- Agent commission logic included in buyer-paid costs
- Seller closing costs included
- Installable PWA with offline support
- Copy email, open email client, save/load local deal, print/PDF

## Deploy on GitHub Pages

1. Create a new GitHub repository.
2. Upload all files in this folder.
3. Go to Settings > Pages.
4. Choose Branch: `main` and folder: `/root`.
5. Open the published GitHub Pages URL.

## PWA Install Prompt

The app includes `beforeinstallprompt` logic. The Install App button appears when the browser allows installation. On iPhone, use Safari Share > Add to Home Screen.

## Automatic Email Sending

The current app opens the device mail client using `mailto:`. For true automatic sending, connect a backend email service such as SendGrid, Mailgun, Gmail API, or GoHighLevel webhook.
