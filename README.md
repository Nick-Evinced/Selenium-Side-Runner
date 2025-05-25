# NVIDIA Accessibility Test – Selenium IDE

This project contains a Selenium IDE `.side` file with automated accessibility smoke tests for [nvidia.com](https://nvidia.com).

## 🔍 What It Tests

- Presence of `<nav>` via `role="navigation"`
- Existence of `<h1>` page heading
- Visibility of the “Learn More” call-to-action button

## ▶️ How to Run

Install the Selenium SIDE runner:

```bash
npm install -g selenium-side-runner