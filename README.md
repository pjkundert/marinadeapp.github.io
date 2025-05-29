# Marinade Bible Meditation App

This is the official website for the Marinade Bible Meditation App - a platform for audio-guided Bible meditations, curated scripture collections, daily meditation reminders, and personal prayer journaling.

## Website

The website is published at [marinadeapp.com](https://marinadeapp.com) using GitHub Pages.

## Development

This is a static website built with HTML and CSS.

### Local Development

To run the website locally:

1. Clone this repository
2. Navigate to the project directory
3. Start a local server (e.g., `python -m http.server`)
4. Open your browser at `localhost:8000`

## Custom Domain Setup

This website is configured to use the custom domain `marinadeapp.com`. The following steps are needed to complete the setup:

1. The `CNAME` file in this repository is already configured with the domain
2. In your domain registrar:
   - Create an `A` record pointing to `185.199.108.153`
   - Create an `A` record pointing to `185.199.109.153`
   - Create an `A` record pointing to `185.199.110.153`
   - Create an `A` record pointing to `185.199.111.153`
   - Create a `CNAME` record for `www` pointing to `marinadeapp.github.io`

3. In the GitHub repository settings:
   - Go to "Pages" section
   - Under "Custom domain", enter `marinadeapp.com`
   - Check "Enforce HTTPS" once the domain is verified

## License

© 2025 Marinade App. All rights reserved.
