# M02-L02 · Aspect Ratios

> Video: Module 2, Lesson 2. Watch it first, then use this page to revise and practise.

Open Instagram Reels, and every video is tall. Open YouTube on a laptop, and every video is wide. Same kind of content, a different shape. That shape is called the **aspect ratio**.

What happens if you make a wide clip and then post it as a Reel? You lose most of the picture. The sides get cut off, or you get big black bars. So you choose the shape before you generate.

## What you'll learn

- What an aspect ratio is: 16:9, 9:16 and 1:1
- Which shape each platform uses
- Why cropping a wide clip for Reels wastes most of it
- Where to set the shape in Kling, Veo and ChatGPT
- The safe zone on tall videos
- Three shape mistakes

## Key ideas

### Width compared to height

An aspect ratio is just the width compared to the height.

| Ratio | Shape | Like |
|---|---|---|
| 16:9 | 16 parts wide for every 9 parts tall | Wide, like a TV |
| 9:16 | 9 parts wide, 16 parts tall | Tall, like a phone held upright |
| 1:1 | Same width and height | A square |

The ratio is only the shape, not the quality. 1080p can be any shape:

| Shape | 1080p size |
|---|---|
| 16:9 | 1920 × 1080 |
| 9:16 | 1080 × 1920 |
| 1:1 | 1080 × 1080 |

### Each platform has a favourite shape

| Ratio | Where | Why |
|---|---|---|
| 9:16 | Reels, YouTube Shorts, TikTok | Tall, full screen on a phone |
| 16:9 | Normal YouTube videos, websites, presentations (slides) | Wide, for big screens |
| 1:1 | Feed posts, ads | A square takes more space in a feed than a wide video |

So ask one question first: where will people watch this?

### Why choose before you generate?

The video cuts a tall video out of the wide chai clip:

- The tall frame keeps only the middle, about one third. About two thirds of the picture is thrown away.
- What is left looks softer, because a small piece of the frame is stretched to fill the whole phone screen.
- If you generate in 9:16 from the start, the model plans the whole picture for that tall shape. Nothing is wasted.

### Set the shape before you generate

- In Kling and Veo, the aspect ratio is a simple setting next to the prompt. Pick it before you press **Generate**. 16:9 and 9:16 are almost always there.
- When you make a start image in ChatGPT, ask for the same shape (a tall 9:16 image for a tall video). A wide image will not turn into a tall video.
- Keep every shot in one video the same shape (shot 1, 2 and 3 all 9:16). Mixing shapes gives you black bars in the edit.

The create screen shown in the video (Kling or Veo):

```text
Prompt:        close-up of a clay cup of chai, steam rising, warm morning light
Aspect ratio:  16:9 · 9:16 · 1:1
Generate
```

### The safe zone on tall videos

On Reels and Shorts, the app puts its buttons on the right side, and the caption at the bottom.

| Part of the screen | What sits there |
|---|---|
| The right side | App buttons: like, comment, share |
| The bottom | Caption: your name and the text |
| The middle | Your face and text: the **safe zone** |

Keep the face and any important text in the middle, away from the edges. You can even write it in the prompt:

```text
…a woman with a sign, subject in the centre of the frame
```

## Worked example

A Chai Corner Reel, planned the right way:

1. Where will people watch it? On Instagram Reels, so the shape is 9:16.
2. Start image in ChatGPT: ask for a tall 9:16 image.
3. In Kling, set the aspect ratio to 9:16 before pressing Generate.
4. In the prompt, add "subject in the centre of the frame" so the buttons and caption do not cover her face or sign.
5. Make every other shot 9:16 too, so the edit has no black bars.

The wrong way: generate a 16:9 clip and crop it. You keep about a third of the picture, and it looks softer on the phone.

## Common mistakes

- **Making a wide clip, then cropping it for Reels.** Generate it tall from the start.
- **Using a wide start image for a tall video.** Make the image the same shape first.
- **Putting the face near the edge of a tall frame.** The buttons cover it. Keep it in the middle.

Safe default: pick the shape first, and keep it the same.

## Try it yourself

1. The video's task: open Reels, then open YouTube Shorts, and notice where the buttons and captions sit on a tall video.
2. Pick the ratio: (a) a 10 minute YouTube tutorial; (b) a 30 second Reel; (c) a product post in the Instagram feed.
3. Add one phrase to this prompt so it is safe for Reels: "a man pours chai at his stall, slow push in".

## Next

[M02-L03 · Shots and Camera Language](../m02-l03-shots-and-camera-language/)

## Answers

1. What good looks like: buttons (like, comment, share) on the right, the caption and name at the bottom, on both apps. Your important content belongs in the middle.
2. (a) 16:9. (b) 9:16. (c) 1:1.
3. Add `subject in the centre of the frame`, and set 9:16 in the tool before you generate.
