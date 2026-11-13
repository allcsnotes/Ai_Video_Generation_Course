# M13-L02 · Build 6: A Music Video on the Beat

> Video: Module 13, Build 6. Watch it first, then use this page to revise and practise.

Build 6 is a **music video** called **From Leaf to Glass**: the journey of chai, in six art styles. Six clips made in **Google Flow**, one free song, and every cut placed **on the beat** in **Shotcut**.

## What you'll build

- A 35-second music video in full HD (1080p, 24 fps), 16:9
- Six AI clips, each in its own art style
- Ten cuts that each land on the beat (16 bars of music)
- A title at the end, and the picture and the song fading out together

## Before you start

- **Google Flow** with credits (Module 7).
- A free song you are allowed to use. The video uses **Rhythms of India** (by khemrajdotin) from **Pixabay**. It is **not in YouTube's Content ID** system (YouTube's tool that matches music and makes copyright claims), so the video will not get a copyright claim. Module 10 covers free music.
- **Shotcut** installed (free).
- **Credits:** each clip is 5 seconds at 720p: **15 credits a clip**, **90 credits** for all six. Prices and plans change: check the current price before you buy.
- Plan it with the [build plan template](../../downloads/build-plan-template.md).

## Plan

### An idea that moves

A music video needs an idea that moves. Ours follows chai, from a leaf on a hill to a glass in your hand. A new look on every cut keeps the eye busy.

| Clip | Scene | Art style |
|---|---|---|
| 1 | The tea garden | Watercolour |
| 2 | Picking the leaves | Paper cut-out |
| 3 | The kettle | Clay |
| 4 | The stall at dawn | Anime |
| 5 | The stall at night | Neon |
| 6 | A toast | Old film (vintage 16mm) |

### Find the beat

Listen, and tap along. Each tap is one **beat**.

| Unit | Maths | Result |
|---|---|---|
| One beat | 60 ÷ 109 (the song has 109 beats a minute, or BPM) | about **0.55 s**, half a second |
| One bar | 4 beats | about **2.2 s**. Music changes on the bars, so that is where the cuts go. |
| In frames | at 24 frames a second | 1 bar ≈ **53 frames**, 2 bars = **106 frames** |

### The 16-bar plan (about 35 seconds)

| Cut | Clip | Bars | Frames |
|---|---|---|---|
| 1 | 1 garden | 2 | 106 |
| 2 | 2 picking | 2 | 106 |
| 3 | 3 kettle | 2 | 106 |
| 4 | 4 dawn | 2 | 106 |
| 5 | 1 garden (quick cut) | 1 | 53 |
| 6 | 2 picking (quick cut) | 1 | 53 |
| 7 | 3 kettle (quick cut) | 1 | 53 |
| 8 | 4 dawn (quick cut) | 1 | 53 |
| 9 | 6 toast | 2 | 106 |
| 10 | 5 neon (the end) | 2 | 106 |
| | **Total** | **16 bars** | **35.2 s** |

## Build it step by step

### Step 1 · The clips, in Flow

1. In the settings, choose **Video**, **16:9**, the **Omni 1.2 Flash** model, and **720p**. Leave **Length** at **5 seconds**. Flow shows the cost: **15 credits**.
2. Every prompt starts with **the number and the style**: "Shot 1. Watercolour painting style", with loose brush strokes and soft colours bleeding into textured paper.
3. Then **the scene and the motion**: a misty tea garden at sunrise, and a camera that glides fast. Fast motion looks great with quick cuts.
4. End with **two rules**: `No music. No text.` We add our own song later, and AI letters often come out broken.
5. Shot 6 uses the same pattern, in a **vintage 16mm film style**, with hands raising glasses of chai in a toast.
6. Make all six, then download each one in **720p**, and number the files 1 to 6 (`1 garden.mp4` to `6 toast.mp4`).

### Step 2 · Cut on the beat, in Shotcut

1. New project called **From Leaf to Glass**, in **HD 1080p 24 fps**.
2. Open all six clips and the song at once. They land in the **Playlist**.
3. Double-click the first clip. In the time box under the player, type `00:00:04:09` (4 seconds and 9 frames), and press **Enter**. Then press **O** to set the **out point** (where the clip ends).
4. The clip is now exactly **106 frames: two bars**. Press **A** to add it to the timeline. Then do the same for clips 2, 3 and 4.
5. For the quick cuts, set the start as well. Type `00:00:02:12` (2 seconds and 12 frames), and press **I** for the **in point** (where the clip starts). Then set the end one bar later, with **O**. Each quick cut is **53 frames**.
6. Ten cuts in all make **35.208 seconds**: exactly **16 bars**.
7. Mute the sound of the clips with the **speaker icon on track V1**. Then add an audio track: `Timeline menu > Track Operations > Add Audio Track`.
8. Load the song, and start it at **1 minute 53** (in point 1:53.25), where a strong part starts. Its length is the same 35.208 seconds.
9. Select track **A1**, press **Home**, then press **B**. The song drops onto A1, lined up with the first cut.
10. On the song, add **Fade Out Audio**, for **2 seconds**.
11. On the last clip, add **Text: Simple** with the title **From Leaf to Glass**. Then add **Fade Out Video**, for **1 second**.
12. Export with the **YouTube** preset (`Export Video/Audio`). The music video is 35 seconds long, in full HD.

### Step 3 · Check the cuts

1. **Play it, and tap along.** Every cut should land on a tap, never between two taps.
2. The video measured it: **all ten cuts land within 30 milliseconds of a beat**, far too close to notice.
3. **Check the looks:** six art styles, no broken text, and smooth motion in every clip.
4. **Check the end:** the title shows, then the picture and the song fade out together.

## Prompts used

Settings for every clip: `Video · 16:9 · Omni 1.2 Flash · 720p · 5 s · x1` (15 credits).

Shot 1, watercolour:

```text
Shot 1. Watercolour painting style: loose brush strokes, soft colours bleeding into textured paper. A misty tea garden on green hills at sunrise. The camera glides fast over rows of tea bushes toward the rising sun. Lively, energetic motion. Sound: birds and wind. No music. No text.
```

Shot 6, vintage 16mm film:

```text
Shot 6. Vintage 16mm film style: warm faded colours, film grain, soft light flicker. Close-up of several hands raising small glasses of chai in a cheerful toast. The glasses clink together in slow motion. Sound: glasses clinking. No music. No text.
```

Shots 2 to 5 follow the same pattern: `Shot N. <style> style: <what the style looks like>. <scene>. <camera motion>. Sound: <...>. No music. No text.`

## Check your work

- [ ] Six clips, six different art styles, no broken text, smooth motion
- [ ] Every clip on the timeline is a whole number of bars (106 or 53 frames)
- [ ] Ten cuts, 16 bars, 35.2 seconds
- [ ] Clip sound muted; the song starts with the first cut
- [ ] Tapping along, every cut lands on a tap
- [ ] The title shows at the end; picture and song fade out together
- [ ] The song is free to use and not in Content ID

## Common mistakes

- **Cutting by eye.** Work out the beat and the bar first (60 ÷ BPM), then cut by frames.
- **Clips that are not a whole number of bars.** The next cut lands between beats.
- **Leaving the clip sound on.** Each clip has its own sound; mute V1.
- **A song that is in Content ID.** Your video can get a copyright claim. Use a free song that is not in it.
- **Asking for text in the clips.** AI letters often come out broken. End every prompt with No text.
- **Song not lined up.** Select A1, press Home, then B, so it starts with the first cut.

## Your task

Make a 20-second music video, with five cuts on the beat, using a free song: count its beats, and make every clip a whole number of bars.

What good looks like: you found the BPM, worked out one beat (60 ÷ BPM) and one bar (4 beats), turned a bar into frames, gave every clip a whole number of bars, and tapping along shows every cut on a beat.

## Recap

1. A music video needs an idea that moves, and one style for each clip.
2. Find the beat: 60 divided by the BPM gives one beat, and four beats make one bar.
3. Make every clip a whole number of bars long, and cut on the bars.
4. Mute the clips, line the song up with the first cut, and fade both out at the end.

## Next

[M13-L03 · Build 7: An Explainer Video](../m13-l03-build-7-an-explainer-video/)
