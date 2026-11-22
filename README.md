# Renovation Budget

A simple, free budgeting app for home renovations. Add projects, set a budget for each one, and record what you've spent or plan to spend. All amounts are in pounds (£).

## Features

- Add projects (Kitchen, Roof, Bathroom...) each with its own budget
- Record items as **Spent** or **Planned**, and switch between the two as bills get paid
- See budget, spent, planned and remaining for each project and across everything
- Works on phones and desktops, with light and dark mode
- No account, no server, no tracking

## Your data

Everything is saved in your browser's local storage on the device you use. It is never sent anywhere. That also means it doesn't sync between devices, and clearing your browser data will erase it.

## Run it

It's a single file with no build step. Either:

- Open `index.html` in your browser, or
- Host it on GitHub Pages: go to **Settings > Pages**, choose your main branch and the root folder, then save.

## Customise

All the code lives in `index.html`. To change the currency, edit the `gbp()` function and the `£` labels.

## Licence

MIT. See [LICENSE](LICENSE).
