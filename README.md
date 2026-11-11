# Arch Atlas

A static, interactive cloud architecture workspace for architects and engineering teams. The site turns the repository's architecture overview into a browsable system map.

## Run locally

No build step or package installation is required. Open `index.html` in a browser, or serve the repository root with any static web server, for example:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Features

- Color-coded architecture layers for edge, application, data, and platform operations.
- Clickable components with responsibilities and design notes.
- Azure, AWS, and Google Cloud service mapping selector.
- Component search, architecture layer navigation, zoom controls, and text export.
- Responsive layout for desktop and mobile.

## Publish as a website

This is a static site and can be hosted on GitHub Pages or another static web host. In GitHub, configure Pages to deploy from the `main` branch and the repository root.

The diagram is a reference design. Validate service selection, security controls, availability, capacity, and recovery requirements for your workload before using it as a production plan.
