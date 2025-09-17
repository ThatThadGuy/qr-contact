# QR Contact Landing Page

This is a minimal, self-contained landing page that provides a vCard for download, suitable for hosting on services like GitHub Pages. When a user visits the page, it attempts to automatically trigger a download of the `.vcf` contact file. If the browser blocks this, a fallback button is available.

## How to Deploy on GitHub Pages

1.  **Create a new public repository** on GitHub (e.g., `qr-contact`).

2.  **Add the files** from this project (`index.html` and `JRBorders.vcf`) to the root of your new repository.

3.  **Configure GitHub Pages:**
    *   In your repository, go to `Settings` > `Pages`.
    *   Under "Build and deployment", select `Deploy from a branch` as the source.
    *   Choose the `main` branch and the `/(root)` folder.
    *   Click `Save`.

4.  **Wait for deployment:** GitHub will build and deploy your site. After a minute or two, your landing page will be live at `https://USERNAME.github.io/your-repo-name/` (e.g., `https://johndoe.github.io/qr-contact/`).

## Generating the QR Code

Once your page is live, you need to generate a QR code that points to its URL.

*   **Use a QR Code Generator:** Use any online tool or local software to generate a QR code for your live URL.
*   **Update the URL:** If you ever change the repository name or use a custom domain, you **must** generate a new QR code pointing to the new URL.

This repository includes a placeholder `qr-code.png` that points to `https://USERNAME.github.io/qr-contact/`. Remember to replace `USERNAME` with your GitHub username and `qr-contact` with your repository name before using it, or generate a new one pointing to your final URL.
