# Wellness Buddy

A wearable-free wellness check-in prototype, built by [Mindy Wu](https://mindy-portfolio.vercel.app/) as a portfolio project.

Buddy brings your classes, meals and sleep into one place, writes a monthly "what's working for you" report, and gives you a crew to keep you going.

## What's in it

- **Today**: a 10-second check-in (sleep, energy, mood), a workout log, and an interactive meal-photo estimate where you tap each item to correct the portion.
- **Week**: movement, sleep and energy by day.
- **Report**: a monthly summary with what's working and what's not, likely nutrient gaps with foods that help, and a recipe.
- **Crew**: a weekly challenge, class meetups, and a photo feed with kudos and comments.

## About this demo

- It makes **no API calls**. Every insight is pre-written sample data, so it costs nothing to run or demo.
- State (check-ins, logged workouts, kudos, posts) is saved in your browser's `localStorage` only. Nothing is uploaded.
- Estimates are for general wellness, not medical advice. Photo-based calorie estimates tend to run low.
- The Crew is simulated, with fictional friends. A real version needs accounts and a backend.

## Run it

It is one static file with no build step:

```bash
python3 -m http.server 8080
```

Then open http://localhost:8080.

Product scope and the plan for testing the idea are in [`docs/MVP-scope.md`](docs/MVP-scope.md).
