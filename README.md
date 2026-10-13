# VeyilGuard — Heat Safety Prototype

A responsive single-page prototype for heat-safety awareness among outdoor workers in Tamil Nadu.

## Features
- Live current weather for Chennai, Madurai, and Coimbatore via Open-Meteo (falls back to clearly labelled sample data if unavailable)
- Demonstration heat-safety guidance
- Rest-break countdown timer
- English/Tamil interface toggle
- Browser text-to-speech safety tip
- Responsive layout for mobile and desktop

## Important limitations
- Live weather requires an internet connection. If the API is unavailable, the page shows sample fallback values and labels them.
- Heat guidance is illustrative and is not an official warning or medical advice.
- Weather values come from Open-Meteo; they are not an official heat warning.
- Browser voice playback depends on device/browser language support.

## Run locally
Open `index.html` in a modern browser. No build step is required.

## Publish with GitHub Pages
1. Create a public repository named `veyilguard`.
2. Upload `index.html` and `README.md` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then Save.
6. Wait for GitHub Pages to publish the site. Copy the URL shown in Settings → Pages.

Your source repository URL will look like `https://github.com/YOUR-USERNAME/veyilguard/`.
Your live demo URL will usually look like `https://YOUR-USERNAME.github.io/veyilguard/`.

Replace `YOUR-USERNAME` with your actual GitHub username. These URLs are examples until you publish the repository.


## Weather API attribution
Current weather is fetched from [Open-Meteo](https://open-meteo.com/). The public API is used without an API key for this prototype. Review its terms and attribution requirements before wider/commercial deployment.
