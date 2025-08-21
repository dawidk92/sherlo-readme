<p align="center">
  <a href="https://sherlo.io/">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="../assets/logo-dark.svg">
      <img src="../assets/logo-light.svg" alt="Sherlo" width="200" />
    </picture>
  </a>
</p>

<p align="center">
  <strong>Ship pixel-perfect React&nbsp;Native apps with confidence</strong>
</p>

<p align="center">
  Visual testing & review tool tailor-made for React&nbsp;Native <em>Storybook</em>
</p>

<p align="center"><em>Free for early adopters while we’re in open&nbsp;beta 🎉</em></p>

<br />

<div align="center">
    <img src="../assets/app.webp" alt="Sherlo web app screenshot" />
</div>

<br />

## Table of Contents

- [Why Sherlo?](#-why-sherlo)
- [Benefits](#-key-benefits)
- [Live Demo](#-see-it-in-action)
- [Quick Start](#-quick-start)
- [How It Works](#-how-it-works)
- [Storybook 101](#-new-to-storybook)
- [Documentation & Resources](#-documentation--resources)
- [Packages](#-packages)
- [License](#️-license)

<br />

## 🚀 Why Sherlo?

**Sherlo is the only visual testing platform built exclusively for React&nbsp;Native teams.** While other services test in web browsers, Sherlo spins up real mobile simulators so you’re catching bugs where your users actually see them.

### ✨ Key Benefits

🐛 **Catch Visual Regressions Early** – Detect pixel drift before it hits production  
📱 **Real-Device Accuracy** – iOS & Android simulators, not browser iframes  
⚡ **Setup in Seconds** – `npx sherlo init` and you’re off  
👥 **Designer-Friendly Reviews** – Share a web link, collect feedback fast  
💰 **Free While in Beta** – Zero cost for early users; help us shape the future

<br />

## ✨ See It In Action

Curious? Jump into the [**live demo**](https://app.sherlo.io/demo) – no signup required.

<br />

## ⚡ Quick Start

Add Sherlo to your project in under two minutes:

```bash
npx sherlo@latest init
```

The CLI will:

1. Detect or set up Storybook
2. Configure required scripts
3. Launch the first visual test run

<br />

## 🛠️ How It Works

1. **📸 Capture** – Sherlo renders every Storybook component on multiple device profiles
2. **🔍 Compare** – Screenshots are diffed against the baseline after each commit
3. **👀 Review** – Designers & devs approve or reject changes in the web app
4. **🚢 Ship** – Merge with confidence knowing the UI is rock-solid

<br />

## 📚 New to Storybook?

[**Storybook**](https://storybook.js.org/) lets you build UI components in isolation and see them all in one place. Over 80k developers use it daily.

When paired with **Sherlo** you get automated visual testing on top – the perfect feedback loop ⚡

- **Storybook** = component playground & documentation
- **Sherlo** = visual regression guardrail
- **Result** = Faster, safer UI development

If you’ve never installed Storybook, our CLI will guide you – or follow the [React&nbsp;Native guide](https://github.com/storybookjs/react-native).

<br />

## 📖 Documentation & Resources

- **Docs** – <https://docs.sherlo.io>
- **Website** – <https://sherlo.io>
- **Community Q&A** – <https://github.com/sherlo-io/sherlo/discussions>
- **Bug Reports** – <https://github.com/sherlo-io/sherlo/issues>

<br />

## 📦 Packages

This monorepo contains:

- [`packages/cli`](../packages/cli) – The Sherlo command-line interface
- [`packages/react-native-storybook`](../packages/react-native-storybook) – Storybook addon & utilities for React&nbsp;Native

<br />

## ©️ License

[MIT](../LICENSE)
