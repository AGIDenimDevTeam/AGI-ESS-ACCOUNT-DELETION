Account Deletion (Play Store / App Store Requirement)

Since the app allows account creation, both stores require users to be able to delete their account without needing the app installed.

1. In-App Deletion

Path: Dashboard → ⋮ (top-right menu) → Delete My Account

Permanently deletes the employee's app login/registration record.
Does not affect the official HR/payroll employment record — that is managed separately, outside this app's control.
2. Web-Based Deletion

File: docs/index.html — a static page hosted via GitHub Pages, so users can request deletion from any browser without the app installed.

Setup:

Repo → Settings → Pages → Branch: main, Folder: /docs
Before publishing, replace the placeholder support email in docs/index.html (appears in two places) with your real HR/IT contact email.

After publishing:

Copy the GitHub Pages URL.
Add it to:
Google Play Console → Data Safety → Data deletion
Apple App Store Connect → App Privacy
