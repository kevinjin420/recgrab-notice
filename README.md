# RecGrab Privacy Policy

Static privacy policy page for the RecGrab Chrome extension.

## Local Preview

Open `index.html` in a browser, or serve the folder with any static server:

```sh
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## GitHub Pages Setup

After creating a GitHub repository and pushing this folder:

1. Open the repository on GitHub.
2. Go to **Settings -> Pages**.
3. Under **Build and deployment**, set **Source** to **GitHub Actions**.
4. Push to `main`.
5. The workflow in `.github/workflows/pages.yml` will publish the page.

Replace `YOUR_EMAIL@example.com` in `index.html` before publishing.
