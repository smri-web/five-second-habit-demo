# 5·4·3·2·1 — Habit Tracker (prototype)

Interactive web prototype of an ADHD-focused habit tracker. A faithful, clickable
stand-in for the native iOS app — used to test the experience before the real build.

**Live:** https://smri-web.github.io/five-second-habit-demo/

## What it demonstrates
- The **5·4·3·2·1** (Mel Robbins) countdown ritual before each habit.
- A fixed **1→30 strike-off calendar** with a backward count ("29 more days to become a habit").
- **Miss-penalty:** a missed day un-strikes your last done day (`struck = clamp(done − miss, 0…30)`).
- **Up to 3 habits** (hard cap — an over-commitment guardrail).
- A **soft focus screen** with leave-detection ("welcome back — finish it").
- A locked **"Block distracting apps"** teaser (a paid native feature).

Use the **time-travel controls** below the phone to fast-forward days and watch the
strikes and miss-penalty without waiting 30 real days.

> Prototype only: it cannot send real notifications or block apps — those require the
> native iOS build.
