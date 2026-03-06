[Uploading readme.md…]()
# Cable Viewer (CSV / Excel)

A lightweight, mobile-first web app to upload **CSV**, search any header, **edit rows**, and **export** back to CSV with the same headers.

## Live site (GitHub Pages)
1. Create a new repo on GitHub (e.g., `cable-viewer`).
2. Upload all files from this folder.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main` (or `master`) and **/ (root)**
   - Click **Save**
5. Your site will publish at:  
   `https://<your-username>.github.io/<repo-name>/`

> Tip: Put your working app at `/index.html`.  
> If you also upload `index_xlsx.html`, open it via:  
> `https://<your-username>.github.io/<repo-name>/index_xlsx.html`

## Usage
- **Upload CSV** (works fully offline).
- Use **Global Search** or per-column filters and click **Search**.
- **Edit** rows, **Add** rows, **Delete** rows.
- **Download CSV** to save the current data.

## Optional: Custom domain
- Edit the `CNAME` file and put your domain (e.g., `viewer.example.com`).
- Point your DNS CNAME to `<your-username>.github.io`.
- GitHub Pages → enable HTTPS.

## License
MIT — see `LICENSE`.
