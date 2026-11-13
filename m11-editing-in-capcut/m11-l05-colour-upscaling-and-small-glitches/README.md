# M11-L05 · Colour, Upscaling and Small Glitches

> Video: Module 11, Lesson 5. Watch it first, then use this page to revise and practise.

The video opens with our pour shot straight from the AI. It looks a little flat and grey. Then the same shot after a few small fixes: warmer, brighter colour, a tighter frame, and big enough for a phone screen.

**Note:** this module is called "Editing in CapCut", but CapCut's colour tools need its online servers, and they do not work on every computer. So this lesson is done in **Shotcut**, a free editor that works fully offline. The ideas are the same in any editor.

## What you'll learn

- How to set up a vertical project in Shotcut
- What a filter is, and why every fix in this lesson is one
- How to fix flat colour with Brightness and Saturation, gently
- How to zoom a small glitch out of the frame, and what to do when it is in the middle
- What upscaling is, and how to upscale on export with Lanczos

## Before you start

- **Shotcut:** free, works fully offline, on Windows, Mac and Linux. No account.
- Nothing in this lesson spends credits.
- One AI clip to fix. The video uses `1_pour.mp4`, which came out of the AI at 360 × 640.

## Follow along

### Step 1 · Set up the project

1. Open Shotcut. Name the project.
2. Set **Video mode** to **Vertical HD 30 fps**. That is 1080 × 1920, standing up.
3. Click **Start**, then drag your clip onto the timeline.

### Step 2 · Open Filters

Click the clip, and open **Filters**. Every fix in this lesson is a **filter**: a small setting you add to a clip, and can switch off at any time.

### Step 3 · Brightness

AI clips often look a little flat. Two filters fix most of it.

Click **+**, and pick **Brightness**. Raise the **Level** a little. The video used **112%**.

### Step 4 · Saturation

Click **+** again, search for `saturation`, and pick **Saturation**. The video raised it to **125**. The apron and the sign get richer, without looking fake.

Go gently. Push too far, and:

- skin turns orange
- bright parts turn pure white

### Step 5 · Zoom a glitch out of the frame

AI clips sometimes have a small glitch near the edge of the frame: a warped hand, or a half made object. If it sits near the edge, zoom in a little to push it out of the frame.

1. Click **+**, and add **Size, Position & Rotate**.
2. Set **Zoom** from 100% to **112%**. The picture grows, and the edges move outside the frame.

Keep it small. Every bit of zoom also makes the picture a little softer.

If the glitch is in the **middle**, you cannot crop it away. Cut those frames out (Lesson 2), or cover the spot with text or a sticker.

Zoom is for glitches only. Never use it, or anything else, to hide an AI watermark or label.

### Step 6 · Upscale on export

Our clips came out of the AI at **360 × 640**. A phone screen shows **1080 × 1920**: three times as wide. **Upscaling** means making the video bigger, to fit that size.

1. Click **Export**, then **Advanced**.
2. **Resolution** already says 1080 × 1920, from the project. So Shotcut scales every clip up to fit.
3. Set **Interpolation** to **Lanczos**. It fills in the new pixels more carefully, so edges stay clean.

| Interpolation | In the video |
|---|---|
| Nearest Neighbor | fast |
| Bilinear | good |
| Bicubic | better |
| Lanczos | best |

But upscaling cannot add detail that was never there. Always make your clips at the **highest resolution your AI tool allows**. Upscaling is only the backup plan.

## Prompts used

No AI prompts in this lesson. Settings used:

```text
Video mode: Vertical HD 30 fps (1080 × 1920)
Filter Brightness: Level 112%
Filter Saturation: 125
Filter Size, Position & Rotate: Zoom 112%
Export > Advanced: Resolution 1080 × 1920, Interpolation Lanczos
```

## Try it yourself

1. The video's task: warm up your pour shot, zoom out one glitch, and export it at full HD.
2. Push Saturation far too high on purpose, look at the skin and the bright parts, then bring it back down.
3. Check your AI tool's settings: what is the highest resolution it lets you make?

What good looks like: richer colour that still looks natural, no glitch at the edge, and a 1080 × 1920 file that stays clean at the edges.

## Common mistakes

- **Pushing colour too far.** Skin turns orange and bright parts turn white.
- **Zooming a lot.** Every bit of zoom makes the picture softer. Keep it small.
- **Trying to crop a glitch in the middle.** Cut those frames or cover the spot instead.
- **Thinking upscaling adds detail.** It does not. Make clips at the highest resolution you can.
- **Forgetting the project Video mode.** Set Vertical HD 30 fps at the start, so export is 1080 × 1920.

## Next

[M11-L06 · Export Settings and Quality Checks](../m11-l06-export-settings-and-quality-checks/)
