# Blackjack Trainer

Hole-card strategy drill, live table, and variance lab. One HTML file per tool, no build step, no dependencies.

- **index.html** — the trainer (drill, play table, charts, stats, rules)
- **variance-lab.html** — bankroll variance calculator with misread modelling
- **install.html** — the page to send people: how to put it on a phone

Everything runs in the browser. Stats and bankroll are saved in your own browser's local storage; nothing leaves your device.

## Use it

Open the site, or on a phone use *Add to Home Screen* — it installs as an app and works offline.

## Host your own copy

1. Fork or download this repo.
2. Settings → Pages → Source: *Deploy from a branch* → `main` / root.
3. Your copy is live at `https://<you>.github.io/<repo>/`.

Or just download `index.html` and open it. It works from a file on disk too.

## Model

Infinite-deck expectations from exact dynamic programming; split values computed live from the rule set;
variance and cross-spot covariance from Monte Carlo. Read fidelity, dealer rules, doubling and splitting
rules are all configurable, and the charts recompute as you change them.
