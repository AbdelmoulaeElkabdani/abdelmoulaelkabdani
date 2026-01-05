ProMan - Personal Portfolio (customized)

This is a customized copy of the ProMan personal portfolio template. Changes made:
- Theme adjusted to black/white.
- Header profile image cropped and focused on face.
- Contact form wired to open WhatsApp with a prefilled message (edit `WA_NUMBER` in `index.html`).

How to preview locally:

```powershell
cd 'C:\Users\SIMO\Downloads\proman-1.0.0\proman-1.0.0'
python -m http.server 8000
# Open http://localhost:8000
```

How to publish to GitHub Pages (summary):
1. Create a new GitHub repository (e.g. `proman-1.0.0`).
2. Add the remote and push:

```powershell
git remote add origin https://github.com/<your-username>/<repo>.git
git push -u origin main
```

3. Enable GitHub Pages in repository settings (use branch `main` and folder `/ (root)`).

Replace `WA_NUMBER` in `index.html` with your WhatsApp number in international format (e.g. `2126XXXXXXXX`).
