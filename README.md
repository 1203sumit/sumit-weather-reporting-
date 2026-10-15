# sumit-weather-reporting-
https://1203sumit.github.io/sumit-weather-reporting-/


# Atmosphere Weather Intelligence — Playwright Automation with TypeScript

## Project Overview

Atmosphere Weather Intelligence is a web development project that displays current weather conditions, hourly forecasts, a 5-day forecast, and other weather information.

I applied **Playwright automation using TypeScript** to test the application's key functionalities and verify their expected behavior. I used Playwright Codegen to record browser interactions, generated initial test code, and executed the test scripts through the terminal.

## Technologies Used

- **Playwright** — End-to-end browser automation
- **TypeScript** — Writing automation test scripts
- **Playwright Codegen** — Recording browser actions and generating test code
- **Node.js & npm** — Project setup and package management
- **Chromium** — Browser test execution
- **VS Code** — Code editor and integrated terminal
- **Git & GitHub** — Version control and project hosting

## Automated Test Scenarios

The automation project covers the following scenarios:

1. Website loading and verification of important UI sections.
2. Celsius and Fahrenheit temperature unit switching.
3. City search functionality and location updates.
4. Empty search validation.
5. Footer content and developer credit verification.

## Playwright Features Used

- Writing test cases using `.spec.ts` files.
- Locating elements using Playwright locators.
- Performing browser actions such as clicking, filling inputs, and submitting forms.
- Using assertions to validate expected results.
- Executing tests through terminal commands.
- Generating HTML test reports.
- Capturing screenshots when tests fail.
- Recording videos when tests fail.
- Using Trace Viewer to investigate test failures.
- Running tests in headed mode to observe browser interactions.

## Project Structure

```text
atmosphere-playwright-typescript/
├── tests/
│   └── weather.spec.ts
├── playwright.config.ts
├── package.json
├── tsconfig.json
├── .gitignore
└── README.md
```

## How to Run the Tests

Install dependencies:

```bash
npm install
```

Install the Chromium browser:

```bash
npx playwright install chromium
```

Run all test cases:

```bash
npx playwright test
```

Run tests with a visible browser:

```bash
npx playwright test --headed
```

Run a specific test file:

```bash
npx playwright test tests/weather.spec.ts
```

Open the HTML report:

```bash
npx playwright show-report
```

## Screenshots, Videos & Test Reports

Playwright is configured to capture screenshots and videos when tests fail and retain execution traces for debugging.

The generated test artifacts help investigate failures and understand what happened during browser execution.

Common output folders include:

- `test-results/` — Test artifacts such as failure screenshots, videos, and traces.
- `playwright-report/` — HTML test report.

These folders are generated when the relevant test runs produce those artifacts.

## Key Learnings

- Applying automation to an existing web development project.
- Using Playwright Codegen to generate initial automation scripts.
- Writing and executing TypeScript test cases.
- Using locators and assertions to validate application behavior.
- Understanding browser automation, screenshots, video recording, and debugging.
- Reviewing test results through Playwright's HTML report.

## Conclusion

This project provided hands-on experience in **Playwright automation with TypeScript**, from recording browser interactions and writing test scripts to executing tests and reviewing results. It helped me understand how automated UI testing can improve confidence in web application functionality.

**Sdet:** Sumit Kumar Mishra

**Live Website:** https://1203sumit.github.io/sumit-weather-reporting-/

