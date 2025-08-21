# Sherlo README Draft (Essence of Ideas)

This file summarizes the proposed structure and content for the updated GitHub README, based on our discussion. It's in Polish as per the draft, with a note to translate to English later.

### Proposed Table of Contents

- **Logo & Subtitle** – Logo with a short tagline describing Sherlo.
- **Product GIF** – Visual demo (GIF or screenshot) showing the product's essence.
- **What is Sherlo? (with integrated catchphrase and benefits)** – Description, what it is, benefits, and catchphrase woven in naturally.
- **How Sherlo Works** – Step-by-step explanation of the process, inspired by sci-fi.
- **Web App & Demo** – Description of the web app with a demo link.
- **New to Storybook?** – Short intro for newcomers with resources.
- **Quick Start** – Simple installation steps, mentioning Storybook.
- **Documentation & Resources** – Links to docs, site, community.
- **Packages & License** – Overview of packages and license.

### Draft Content (in Polish)

````
<!-- Logo & Subtitle -->
<p align="center">
  <a href="https://sherlo.io/">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="./assets/logo-dark.svg">
      <img src="./assets/logo-light.svg" alt="Sherlo" width="200" />
    </picture>
  </a>
</p>

<p align="center">
  Narzędzie do testów wizualnych i review dla React Native Storybook
</p>

<!-- Product GIF -->
<div align="center">
  <img src="./assets/app.webp" alt="Sherlo w akcji" />
</div>

## Co to jest Sherlo? (z benefits)

Sherlo to SaaS-owe narzędzie do automatycznych testów wizualnych i review zmian UI w aplikacjach React Native, integrujące się ze Storybook. **Catchphrase: "Złap bugi wizualne zanim trafią do użytkowników – pixel-perfect testing dla React Native."**

Dlaczego warto?
- 🐛 Łap regresje wizualne wcześnie, zanim dotrą do produkcji.
- 📱 Testy na realnych symulatorach iOS/Android, nie w przeglądarce.
- ⚡ Szybki setup w kilka sekund.
- 👥 Łatwy review dla zespołów – designerzy i devy w jednym miejscu.
- 💰 Darmowe dla early users w becie!

## Jak działa Sherlo?

Wyobraź sobie sekwencję z filmu sci-fi:
1. **Uruchomienie urządzenia** – Sherlo odpala symulatory urządzeń mobilnych w chmurze.
2. **Screenshoty** – Automatycznie rejestruje zrzuty ekranu Twoich komponentów ze Storybook.
3. **Znajdowanie różnic** – Porównuje z baseline'em, highlightując zmiany (jak skan w Matrixie).
4. **Review** – Zespół przegląda i aprobuje w web appie.
5. **Ship do produkcji** – Wysyłaj z pewnością, że UI jest idealne.

## Web App & Demo

Web app Sherlo to intuicyjny dashboard do review: porównywanie diffów, komentarze, aprobaty. Sprawdź to w akcji – **[live demo](https://app.sherlo.io/demo)** (bez rejestracji)!

## New to Storybook?

Storybook to narzędzie do budowania komponentów UI w izolacji. Używa go ponad 80k devów. Z Sherlo dostajesz automatyczne testy wizualne na topie. Jeśli nie znasz, sprawdź [przewodnik React Native](https://github.com/storybookjs/react-native).

## Quick Start

Dodaj Sherlo do projektu w <2 minuty:
```bash
npx sherlo@latest init
````

CLI wykryje/setupuje Storybook, skonfiguruje skrypty i uruchomi pierwszy test. (Jeśli nowy w Storybook, CLI Cię poprowadzi.)

## Documentation & Resources

- Docs: https://docs.sherlo.io
- Strona: https://sherlo.io
- Community: https://github.com/sherlo-io/sherlo/discussions
- Bugi: https://github.com/sherlo-io/sherlo/issues
- Konkurencja: [Chromatic](https://www.chromatic.com/), [Percy](https://percy.io/)

## Packages & License

Monorepo zawiera:

- `packages/cli` – CLI do integracji.
- `packages/react-native-storybook` – Integracja ze Storybook.

Licencja: [MIT](LICENSE)

```

This captures the key ideas: marketing-oriented with benefits, sci-fi inspired how-to, integrated catchphrase, and balanced sections. Ready to translate or refine?
```
