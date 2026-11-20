Santhosh R · Portfolio
A single-file personal website (crystal glassmorphism, scroll animations, built-in editor).
Everything lives in index.html: no build step, no dependencies.
Put it on GitHub Pages
Create a new repository on GitHub, e.g. santhosh-portfolio (Public).
For a URL like https://USERNAME.github.io/, name the repo exactly USERNAME.github.io.
Open the repo, tap Add file → Upload files, and upload index.html (keep the name index.html).
Tap Commit changes.
Go to Settings → Pages. Under Build and deployment, set Source: Deploy from a branch, Branch: main, folder / (root), then Save.
Wait about a minute. Your site appears at https://USERNAME.github.io/REPO-NAME/ (or https://USERNAME.github.io/ for a user site).
Tip on a phone: if the Upload option is missing, open GitHub in your browser and choose Desktop site.
Updating the site later (using the built-in editor)
Open your live site, tap the ⋯ menu in the top bar, then ✎ Edit site.
Enter the owner password, change any text, add certificates or projects, swap the photo.
Tap Save & download file. This downloads a new index.html with all your changes.
In your GitHub repo, tap Add file → Upload files, upload the new index.html (it replaces the old one), and Commit changes.
Reload the site after a minute. The changes are now permanent for everyone.
Edits are only permanent after you upload the downloaded file. Anyone can open the editor on their own screen, but nothing they change can affect your site because only you can commit to the repository.
Change the password
The password is stored as a SHA-256 hash in index.html (the PH constant near the top of the script). To change it, generate a new hash of your password at any SHA-256 tool and replace the long hex value.
Contact links
LinkedIn: https://www.linkedin.com/in/santhosh-r-a5024a414
GitHub: https://github.com/dellinspion22-commits
