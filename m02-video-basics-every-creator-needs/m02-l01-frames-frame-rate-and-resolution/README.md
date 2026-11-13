# M02-L01 · Frames, Frame Rate and Resolution

> Video: Module 2, Lesson 1. Watch it first, then use this page to revise and practise.

Two cups of chai. It is the same clip, but one moves smoothly and the other stutters. Clip A shows 24 pictures a second; clip B shows 6. That is the only difference.

Which number makes a video look like a real film: 24, 30 or 60? 24. Films have used 24 pictures a second for about 100 years, and our Kling clip uses it too.

## What you'll learn

- What frame rate (FPS) is, and how 8, 24, 30 and 60 look
- How slow motion works, and why slowed AI clips stutter
- What resolution is: 720p, 1080p and 4K
- When 720p is fine and when to aim for 1080p
- Safe export settings for your final video

## Key ideas

### Frame rate: frames per second

A video is many still pictures called **frames**. **Frame rate** is how many frames are shown every second, written **FPS** (frames per second). One second of our clip holds 24 frames.

| FPS | Looks | Used for |
|---|---|---|
| 8 | Choppy: your eye sees every jump | |
| 24 | Cinema: smooth, a little natural blur | Films |
| 30 | Common online | Phones and social media |
| 60 | Extra smooth | Games and sports |

For AI video, 24 or 30 is perfect. More frames means more work, and more credits.

### How slow motion works

- A camera records 60 frames in 1 second. Play them at 30 a second, and the same 60 frames now take 2 seconds: half speed.
- Smooth slow motion needs extra frames: 60 fps gives half speed, 120 fps gives quarter speed.

### Why slowed AI clips stutter

AI clips usually have only 24 or 30 frames a second. Slow one down a lot in the editor (say to ¼ speed) and there are only about 6 new frames a second. It stutters.

So if you want slow motion, ask for it in the prompt instead:

```text
close-up of a clay cup of chai, steam rising in slow motion, warm light
```

The model then makes every frame, so the motion stays smooth.

### Resolution: pixels in each frame

**Resolution** is how many pixels make up each frame. The "p" number is the height.

| Name | Size | Pixels |
|---|---|---|
| 720p | 1280 × 720 | about 1 million |
| 1080p | 1920 × 1080 | about 2 million, more than twice the detail |
| 4K | 3840 × 2160 | about 8 million, 4 times 1080p |

More pixels means sharper detail, but also bigger files and more credits to make.

### Does 720p look bad?

It depends on the screen.

- **On a phone:** most people cannot tell 720p from 1080p. The screen is small.
- **On a laptop or TV:** the difference is easy to see. Edges look soft and small text gets blurry.

| Use | Resolution |
|---|---|
| Practice, short videos on Instagram | 720p is fine (free plans often give 720p) |
| Paying clients, YouTube | Aim for 1080p |

### Export: keep it the same

One rule when you edit: keep it simple, and keep it the same.

- If your clips are 24 fps, export at 24 or at 30. Do not mix many rates (like 24, 25 and 60 fps) in one video.
- Export at 1080p. Even when some clips are 720p, a 1080p export plays cleanly on every screen.

## Worked example

The video's chai edit:

| Clip | Frame rate | Resolution |
|---|---|---|
| `chai_shot01_v02_kling.mp4` | 24 fps | 720p |
| `chai_shot02_v01_kling.mp4` | 24 fps | 720p |
| `chai_shot03_v01_kling.mp4` | 24 fps | 720p |

Export settings: frame rate 24 or 30, resolution 1080p.

Final video: `chai_final_v1.mp4`, 24 fps, 1080p, one frame rate.

## Common mistakes

- **Slowing an AI clip down a lot.** It stutters, because there are not enough frames. Ask for slow motion in the prompt.
- **Paying for 4K when the video is only for phones.** Nobody sees the difference on a phone, but you pay for it.
- **Exporting at a low resolution.** Your clips can be sharp, and a bad export still makes them soft. Export at 1080p.

Safe default: 24 or 30 fps, 1080p export.

## Try it yourself

1. The video's task: open any YouTube video, switch the quality between 360p, 720p and 1080p, and notice when you see the difference.
2. Do it twice: once on your phone and once on a laptop. On which screen did 720p look soft?
3. Rewrite this prompt so the slow motion stays smooth: "a glass of water being poured". Then say why you should not slow it down in the editor instead.

## Next

[M02-L02 · Aspect Ratios](../m02-l02-aspect-ratios/)

## Answers

1. What good looks like: one line per quality level, for example "360p: blurry text; 720p: fine on the phone; 1080p: sharp on the laptop".
2. Most people see the difference on the laptop, not on the phone, exactly as the video says.
3. One possible answer: `close-up of water pouring into a glass in slow motion, soft daylight, still camera`. Slowing a 24 fps clip in the editor leaves too few frames, so it stutters; asking in the prompt makes the model draw every frame.
