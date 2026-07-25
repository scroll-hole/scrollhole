# Scrollhole — Gentle Screen Time

*When you go past a limit you set, a black hole quietly opens over the app.*

Scrollhole is an Android screen-time app that doesn't nag, lock you out, or
shame you. You pick the apps you overuse and a daily budget for each. Stay under
it and Scrollhole stays invisible. Go past it and a small black hole appears over
that app — a calm, hard-to-ignore signal that it's time to put the phone down.
Need another minute? Snooze it. The point is a moment of awareness, not a wall.

## What it does

- **Per-app daily budgets** — watch only the apps you choose, each with its own limit.
- **The black hole** — a gravitational-lensing overlay bends the screen around a
  void once you're over budget, instead of a jarring block screen.
- **Per-app snooze** — grant yourself a few more minutes when you genuinely need them.
- **A puzzle to continue** — an optional small friction (a riddle or bit of math)
  before the snooze, so the choice to keep scrolling is a deliberate one.
- **Weekly recap** — an optional local summary of how your week went.

## Privacy

Everything happens on your device. **Nothing leaves your phone.**

Scrollhole has no servers, no accounts, no sign-in, no analytics, and no ads. Your
usage data, app list, and budgets never leave the device and are deleted when you
uninstall. Read the full policy: **[Privacy Policy](https://github.com/YOUR_USERNAME/scrollhole)**
*(replace with your GitHub Pages URL once live)*.

## Permissions, and why

| Permission | Why |
|---|---|
| Usage Access | To see which app is in the foreground and for how long, so budgets can be tracked. Read on-device only. |
| Display over other apps | To draw the black-hole overlay above a watched app. Draws pixels; cannot read the screen. |
| Notifications | Tracking-status notification, optional weekly recap, and alerts if tracking stops. |
| Foreground service | Keeps tracking reliable while the app runs in the background. |

## Availability

Coming to the Google Play Store. Requires Android 8.0 (API 26) or newer.

## Built with

Kotlin · Jetpack Compose · Room · WorkManager · AGSL (gravitational-lensing shader on Android 13+)
