POCKET BUDGET — IPHONE / GITHUB PAGES SETUP

This is an offline-first PWA. Budget data is stored locally in the browser on each device.

GITHUB PAGES
1. Create a new GitHub repository (for example: pocket-budget).
2. Upload ALL files/folders from this ZIP to the repository root. index.html must be at the root.
3. In the repository, open Settings > Pages.
4. Under Build and deployment, choose Deploy from a branch.
5. Choose the main branch and /(root), then Save.
6. Wait for GitHub Pages to publish the HTTPS site.

IPHONE INSTALL
1. Open the published HTTPS address in Safari.
2. Wait a few seconds on the first load so the offline cache installs.
3. Tap Share > Add to Home Screen > Add.
4. Open Pocket Budget from the new Home Screen icon.
5. In the app, use "Check cached app". It should report Ready for offline use.
6. You can test by enabling Airplane Mode and reopening the Home Screen app.

DATA SAFETY
- Transactions are NOT stored in GitHub. They remain in local browser storage on the device.
- Deleting Safari website data or deleting app/browser data can erase local records.
- Use Export backup regularly. Import that JSON backup to restore or move records.
- Automatic syncing between devices is not possible while staying completely offline.

DEFAULT WEEKLY PLAN
Dates: PHP 700
Electric + Water: PHP 700
MariBank Savings: PHP 400
Laundry: PHP 150
Food & Daily Expenses: PHP 450
Emergency / Extra: PHP 100
Total: PHP 2,500
