# Northstar Studio — Business Landing Page

A responsive, minimal business landing page built with plain HTML, CSS and JavaScript.

## Run locally
1. Extract the ZIP file.
2. Open `index.html` in a browser.

You can also use the **Live Server** extension in Visual Studio Code:
1. Open this folder in VS Code.
2. Install the Live Server extension if needed.
3. Right-click `index.html` and choose **Open with Live Server**.

## Customize before publishing
- In `index.html`, replace `Northstar Studio` / `northstar.` with your business name.
- Replace the sample service descriptions with your actual services.
- Replace `hello@yourbusiness.com` in both `index.html` and `js/script.js` with your real business email.
- Update the page title and meta description in the `<head>` section.
- Adjust colors in the `:root` section at the top of `css/style.css`.

## Contact form note
The contact form uses a `mailto:` link. It opens the visitor's default email app and prepares an email; it does not store or send submissions to a database. For a production form that sends messages directly, connect a form service or backend.

## Deploy
Upload the project folder to a static hosting provider such as GitHub Pages, Netlify or Vercel. Keep the folder structure unchanged:
- `index.html`
- `css/style.css`
- `js/script.js`
