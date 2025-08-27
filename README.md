<br />

<p align="center">
  <a href="https://sherlo.io/">
    <picture>
      <source media="(prefers-color-scheme: dark) and (max-width: 480px)" srcset="./assets/logo-dark.svg" width="140">
      <source media="(prefers-color-scheme: dark)" srcset="./assets/logo-dark.svg" width="176">
      <source media="(max-width: 480px)" srcset="./assets/logo-light.svg" width="140">
      <img src="./assets/logo-light.svg" alt="Sherlo logo" width="176" />
    </picture>
  </a>
</p>

<p align="center">Visual Testing & Review Tool for React Native Storybook</p>

<br />

<!-- TODO: ogarnac gif pod mobile -->
<div align="center">
  <img src="./assets/sherlo.gif" alt="Sherlo visual testing tool demo showing UI comparison and review workflow" width="780" />
</div>

# Sherlo

Test your UI on iOS and Android automatically in the cloud. Built for React Native Storybook.

### Key Benefits

- **🖼️ Ensure Pixel Perfection** - Your UI, exactly as designed
- **📱 Real Mobile Testing** - Native iOS & Android testing - not web-based solutions like React Native Web
- **☁️ Visual Testing Cloud** - You build, we test - on infrastructure built specifically for mobile UI testing
- **🤝 Team-Friendly Review** - One web app for your whole team
- **✅ Ship with Confidence** - Merge with peace of mind - see exactly what changed
- **⏱️ Save Manual QA Hours** - Forget device-by-device checks - every UI update caught automatically

<br />

## Web App + Demo

Review visual changes across devices in one web app as a team - from developers to designers.

### Features

- **📸 Visual Diff Comparison** - Compare before/after screenshots with highlighted changes
- **💬 Team Feedback** - Approve or reject changes with comments
- **🔍 Code Inspector** - Inspect React Native styles directly in the browser
- **🎨 Figma Integration** - Compare UI with Figma designs side-by-side
- **…and more**

**🚀 [Try the Demo](https://app.sherlo.io/demo)** to see these features in action

<br />

<!-- TODO: opakowac w frame z "przegladarki" jak na LP -->
<div align="center">
  <img src="./assets/app.webp" alt="Sherlo - podgląd aplikacji" />
</div>

<br />

## Quick Start

1. Install Sherlo:

```bash
npx sherlo@latest init
```

<br />

2. _Optionally_ change your [test devices](https://docs.sherlo.io/setup/config#devices) (example):

```json
[
  { "id": "iphone.15.pro", "osVersion": "17" },
  { "id": "pixel.7", "osVersion": "13", "osTheme": "dark", "osLocale": "en_GB" }
]
```

<br />

3. Run a [testing command](https://docs.sherlo.io/setup/testing#testing-commands) - that's it!

<br />

[Full documentation →](https://docs.sherlo.io/setup/integration)

<br />

## How It Works

1. **📸 Capture** - Sherlo runs your Storybook stories on iOS and Android simulators

2. **🔍 Compare** - Screenshots are compared against previous versions to detect visual changes

3. **👀 Review** - Your team reviews visual changes before they go live

4. **🚢 Ship** - Deploy with confidence knowing your UI is rock-solid
