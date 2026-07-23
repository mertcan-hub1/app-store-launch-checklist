# Before App Store Launch Checklist

An interactive, trackable checklist of **every step between a finished build and a live App Store listing** — in the order Apple actually asks for it, written for your first launch.

**Use it here → https://sweetato-nds.github.io/app-store-launch-checklist/**

No account, no install. Tick items off as you go; progress is saved in your browser and nothing is sent anywhere.

## What it covers

Seven phases, sequenced the way Apple requires them:

| Phase | | |
|---|---|---|
| **A** | Join the Apple Developer Program | entity type, 2FA, approval wait |
| **B** | Agreements, tax & banking | the step first-timers discover too late |
| **C** | Create your app record | bundle ID, name, SKU |
| **D** | In-app purchases & subscriptions | skip if your app is free |
| **E** | Store listing, privacy & assets | where most first rejections happen |
| **F** | Upload the build | Xcode → App Store Connect |
| **G** | Submit for review | demo accounts, release options, rejections |

Plus **Trap** callouts for the classic first-timer mistakes (D-U-N-S numbers, pending agreements, mismatched product IDs, dead privacy-policy links, missing demo accounts).

## Personalize it with any AI assistant

This checklist is also a **template**. Send the page link or the `index.html` source to Claude, ChatGPT, or any AI assistant and say, for example:

> Personalize this checklist for my app **Luma**, bundle ID **com.jane.luma**, SKU **LUMA001**, subscription **com.jane.luma.pro.monthly**.

A machine-readable contract embedded at the top of the source tells the assistant exactly what it may change — a single `PERSONALIZE` config block (app name, bundle ID, SKU, product ID) and the page title — and forbids touching anything else. Your values then appear in the right checklist steps automatically, and your copy tracks its progress separately from the shared template.

## Feedback

Shipped with this checklist? Spotted something wrong or missing? **Please open an issue:**
https://github.com/sweetato-nds/app-store-launch-checklist/issues

## Notes

- Independent community project — not affiliated with Apple.
- Fees, screenshot sizes, and App Store Connect layouts change over time; treat what App Store Connect shows you as the source of truth.
- One self-contained HTML file: no build step, no dependencies, works offline.

## License

[MIT](LICENSE)
