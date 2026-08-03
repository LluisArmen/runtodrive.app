# RunToDrive

The landing page for **RunToDrive**, a fitness-powered racing career game for iPhone
and Apple Watch.

## About the app

RunToDrive turns real-world effort into racing progression. Instead of levelling up an
avatar, you develop a car.

- **Train.** Running, walking and cycling workouts arrive automatically from Apple Health.
- **Convert.** Distance, pace, effort and consistency become driver XP and resource points.
- **Develop.** Spend them across Engine, Aerodynamics, Chassis, Braking and Reliability in
  a branching R&D tree. Upgrades move through engineering, simulation and manufacturing,
  so the car evolves visibly over a season rather than in an afternoon.
- **Recover.** An energy system rewards rest instead of overtraining.
- **Race.** Race day simulates everything you built, then feeds the result into the next
  round of the season.

Real-world effort is the only way to progress. One-time purchase, no subscriptions, no
premium currency, no loot boxes, no pay-to-win. The app is offline-first: your training is
captured and stored on device, with or without signal.

## This repository

A static site — plain HTML and CSS, no build step, no dependencies, no framework.

```
index.html      Landing page
privacy.html    Privacy Policy
terms.html      Terms & Conditions
feedback.html   Anonymous feedback form
style.css       Shared styles
img/            App screenshots
```


## Feedback

`feedback.html` posts anonymously to PostHog. It sets no cookies, requires no account or
email address, and generates a fresh random identifier per submission, so messages cannot
be linked to each other or back to a sender.

## Deployment

GitHub Pages serves the `main` branch root directly. Push to `main` and the site updates.
