HUNGER STATION CAFE - DIGITAL MENU (FREE HOSTING ON GITHUB PAGES)
==================================================================
Files
- index.html  = the customer menu (this is what the QR code opens)
- admin.html  = your private admin page (edit prices, items, photos)
- menu.json   = the menu data (the admin page edits this file)
- images/     = logo and item photos

PART 1 - PUT THE MENU ONLINE (about 10 minutes, once)
1. Create a free account at github.com and sign in.
2. Click the + icon (top right) > New repository.
   - Repository name: hungerstation   (short and simple; this becomes part of your link)
   - Choose Public. Click Create repository.
3. On the new repository page click "uploading an existing file".
4. Unzip this package on your computer. Drag index.html, admin.html, menu.json AND the whole
   images folder into the GitHub upload box. Wait until all files finish uploading,
   then click Commit changes.
5. Go to Settings > Pages. Under "Build and deployment": Source = "Deploy from a branch",
   Branch = main, Folder = / (root). Click Save.
6. Wait 1-2 minutes. Your menu link will be:
      https://YOUR-USERNAME.github.io/hungerstation/
   Open it on your phone in Chrome to check. Anyone can open it, no login needed.

PART 2 - SET UP THE ADMIN (once)
1. On GitHub: click your profile picture > Settings > Developer settings (bottom of left list)
   > Personal access tokens > Fine-grained tokens > Generate new token.
2. Name: menu-admin. Expiration: choose the longest allowed (or No expiration).
3. Repository access: "Only select repositories" > choose hungerstation.
4. Permissions > Repository permissions > Contents: Read and write.
5. Generate token and COPY it (you will not see it again). Keep it private - it is your admin password.
6. Open https://YOUR-USERNAME.github.io/hungerstation/admin.html
   Enter your GitHub username, repository name (hungerstation), branch (main) and the token.
   Click Connect. The token is saved only on that device/browser.

USING THE ADMIN
- Edit names, descriptions, prices, emoji; add/delete/reorder items and categories; mark Sold out;
  add photos (Choose photo). Then press Save & Publish.
- The live menu updates in about 1 minute (GitHub rebuilds the page).
- Use "Disconnect" on shared devices.

WHATSAPP NUMBER
Change it in Admin > Cafe settings (country code, digits only, e.g. 923313335187).

QR CODE
Once your link works, send it to Claude to make the printed QR card with the new link,
or use any free QR generator. The link never changes when you edit the menu.

SECURITY NOTES
- Anyone can read menu.json (it is the public menu). Only someone with your token can change it.
- If the token is lost or shared by mistake, delete it in GitHub settings and create a new one.
