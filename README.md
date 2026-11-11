# Fieldnotes — Architecture for the real world

An editorial, responsive architecture portfolio for exploring a cloud-native commerce platform. It combines a presentation-style landing page with interactive views for system architecture, cloud service comparisons, security and operations, and deployment flow.

## Run locally

No build step or package installation is required. Open `index.html` in a browser, or serve the repository root with a static web server:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Site features

- Editorial landing page with animated, abstract system illustration.
- Architecture views in tabs: system map, cloud choices, security and operations, and delivery.
- Azure, AWS, and Google Cloud service mapping.
- Responsive layouts and motion-reduction support.
- Static HTML, CSS, and JavaScript; no build tooling required.

## Publish with GitHub Pages

In the repository settings, enable GitHub Pages and configure deployment from the `main` branch and repository root. Once Pages finishes deploying, the published site URL will appear in the Pages settings.

This is a provider-neutral reference design. Validate service availability, sizing, security, compliance, resilience, and recovery requirements against the actual workload before using it as a production plan.
