# Ootu — Kerala Diet Dashboard

A single-page web app that sets daily calorie and protein targets and helps you plan meals around **Kerala home cooking**.

**Live app:** https://samsulukk.github.io/ootu-kerala-diet-dashboard/

## What it does

- **Personal targets.** Enter height, weight, age, sex and activity level, choose a goal (weight loss, maintain or weight gain), and get:
  - BMI with its category
  - a daily calorie target, using the Mifflin-St Jeor equation (−500 kcal/day for loss, +500 kcal/day for gain)
  - a daily protein target (2.0 g/kg for loss, 1.6 g/kg to maintain, 1.8 g/kg for gain)
- **123 foods** in 13 categories: Kerala breakfasts (puttu, appam, idiyappam), curries, thorans, biriyanis, snacks and payasams, plus common supermarket protein foods.
- **Meal builder.** Tap dishes to add them. Progress bars track calories and protein against your targets and turn orange when you go over.
- **Smart tags.** Dishes are labelled automatically:
  - *Loss pick:* 200 kcal or less, with at least 28% of calories from protein
  - *Gain pick:* 280 kcal or more
- **Search and filters** by dish name, category, goal tag, or supermarket items only.
- Light and dark mode, and a responsive layout that works on phones.

## Tech

Plain HTML, CSS and JavaScript in one file (`index.html`), with no build step and no dependencies. It's hosted on GitHub Pages.

## Run locally

Open `index.html` in any browser.

## Disclaimer

Nutrition values are typical per-serving estimates for home-style Kerala cooking. Real values vary with recipe, oil and portion size. Targets are estimates, not medical advice.
