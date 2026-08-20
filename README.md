# Badminton Tournament Dashboard

A viewer-only badminton tournament dashboard for **Royal Chola Warriors vs Supreme Pandya Titans**.

## Repository structure

```text
.
├── index.html
├── 404.html
├── assets/
│   └── images/
│       ├── royal-chola-warriors-logo.png
│       ├── supreme-pandya-titans-logo.png
│       └── supreme-pandya-titans-shark-shield.webp
├── README.md
├── LICENSE.txt
├── .gitignore
└── .nojekyll
```

## Features

- Schedule and match points
- Pair standings
- Team standings
- Players directory with search and category filter
- Insights and analytics
- Responsive viewer-only interface
- Team logos stored as separate image assets

## Run locally

Run the following command from the repository root:

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000`. Running a local server is recommended because the HTML references files in `assets/images/`.

## Publish with GitHub Pages

1. Upload all extracted files and folders to the repository root.
2. Open **Settings > Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select the `main` branch and `/ (root)`.
5. Save the settings.

Do not rename or move the `assets/images` folder unless the image paths in `index.html` and `404.html` are updated too.
