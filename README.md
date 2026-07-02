# Roster Manager

A simple, standalone roster app. **No Google account, no setup, no internet needed.**

## How to use

**Double-click `index.html`** — it opens in your browser.

## Features

- **Team** — pick a team (BOS is preloaded with 8 members).
- **Shift** — select members + dates + a shift (Morn / LateNight / Night), click **Apply**.
- **Leave** — Leave / PL / CL / SL / Holiday / Comp-off.
- **Weekend Night** — assigns the night shift to weekend dates only.
- **Auto Weekly-Off** — a weekend **morning** shift auto-fills "Weekly Off" for the next two days.
- **Grid** — see the whole roster with colors; click a cell to erase it.
- **Export CSV** — download the roster (open in Excel/Google Sheets).
- Changes are **saved automatically** in your browser.

## Customizing

Open `index.html` in an editor and edit the data blocks near the top of the
`<script>` section:

- `TEAMS` — add teams / members.
- `SHIFTS` — shift names, timings, and colors.
- `STATUSES` — leave / status colors.
