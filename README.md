# val-day-site 💌

A simple Valentine's Day website I wanted to try out. The whole thing is just one `index.html` file — no frameworks, no build tools, no dependencies.

## What it does

- Opens with a fake **404 page** that transitions into the actual site
- **Image carousel** you can swipe/drag through
- A **"will you be my Valentine?"** prompt with a runaway "no" button that dodges your cursor
- Popups, confetti, fireworks, and a chime when you (inevitably) click yes
- A hidden **love letter** you can tap to read
- Remembers if you've visited before

## ⚠️For dramatic effect, The page is one-time use i.e. after making a choice, the page now displays an emoji, based on the choice, on a blank page. You can use the dev flag "?dev=true" for building or testing [?dev=true].

## The process

Took me a couple minutes of prompting to get the base up, and then for some reason an unreasonably long time tweaking absolutely unnecessary stuff. You know how it goes — *"let me just fix this one thing"* x47.

First version. Hope to take it up a notch next year.

## Live link

**[val-day-site.vercel.app](https://val-day-site.vercel.app)**

## Dev (testing/building) link

**[val-day-site.vercel.app?dev=true](https://val-day-site.vercel.app?dev=true)**

## Personalize it

Everything is in `index.html`. Swap out:
- The images in the `media` array
- The letter text in the paper popup
- The button labels and popup messages
- The masthead branding

No setup required. Just edit and deploy.

## Tech

HTML + CSS + vanilla JS. That's it.
