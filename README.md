# Sixfold

A single-page dice game: roll six digits and collect badges based on
conditions you define yourself — divisibility, patterns, straights,
exact numbers, and more.

## Running it

No build step, no dependencies. Just open `index.html` in a browser,
or serve the folder with any static file server:

```bash
npx serve .
```

## Deploying

This is a static site, so it works on any static host. For Cloudflare
Pages:

1. Push this repo to GitHub.
2. In the Cloudflare dashboard, go to **Workers & Pages → Create →
   Pages → Connect to Git**, pick this repo.
3. Build settings: leave the build command empty and set the output
   directory to `/` (the repo root) — there's nothing to build.
4. Deploy.

## Features

- Roll six digits, one at a time, with sound
- A badge catalog you fully control: add, edit, duplicate, reorder,
  and delete conditions (divisible-by, contains/starts/ends-with a
  sequence, straights, repeating patterns, ascending/descending, and
  more), each with its own icon, rarity, and EP reward
- A number tester to check any digit sequence against your catalog
  without rolling
- A small shared leaderboard
- Progress is stored per-browser (localStorage) — nothing is sent to
  a server

## License

Personal project — no license specified.
