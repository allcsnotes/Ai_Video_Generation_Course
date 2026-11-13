# M01-L03 · Text, Image or Video to Video

> Video: Module 1, Lesson 3. Watch it first, then use this page to revise and practise.

Two clips, both "Kling 4.0 Flash · 5 seconds". Same cup, same cafe, same warm light. But the first started from words only, and the second started from a picture.

With which one do you get more control over the look? The picture. When you choose the first frame yourself, the AI has much less to guess.

## What you'll learn

- Way 1, text to video: start from words
- Way 2, image to video: start from a picture
- Way 3, video to video: start from a clip
- What each one costs in Kling, as shown in the video
- Two questions that tell you which way to use
- Why this course uses image to video for most clips

## Key ideas

### Way 1 · Text to video

You type words, and the model makes the whole clip.

```text
Close-up of a clay cup of masala chai, steam rising, warm morning light, slow push in
```

- The model decides everything you did not say: the shape of the cup, the table, the light, the people.
- In Kling you type the prompt and press **Generate**. One clip of 5 seconds costs **30 credits**.

| Good for | Weak at |
|---|---|
| Fastest way to start | Every try looks different |
| Only one step | Same cup in 5 shots? Hard |
| Testing ideas | Same face in 5 shots? Hard |

Words alone are not enough when the look must stay the same.

### Way 2 · Image to video

First you make a picture, for example in ChatGPT. Then the video model uses that picture as the **first frame** and only adds the motion.

- Frame 1 of the clip is your picture. Then the steam moves and the camera slowly pushes in (frames 41, 81, up to frame 121 at 5 s).
- In Kling: pick **Keyframes** mode, add your picture as the first frame, and describe only the motion.

Why the course loves image to video:

1. **Check the look first.** Does the picture look right? Only then spend video credits (picture in ChatGPT, then 30 Kling credits).
2. **Reuse one picture.** Use it in shot 1, shot 2 and shot 3 to keep the same cup, the same face and the same place in every shot.

### Way 3 · Video to video

You start from a clip that already exists.

- The model **keeps** the motion and the camera move, and **changes** the look. For example, it can turn a real cafe into clay animation.
- In Kling you add the video as a **reference** and describe the new style.
- Cost: **24 credits for just 3 seconds**, because Kling also counts the seconds of your input video.

Use it when you love a motion and only want a new look.

### All three, side by side

| Way | Control of the look | Steps | Cost in Kling | Best for |
|---|---|---|---|---|
| Text to video (from words) | Low | One step | 30 credits · 5 s | Testing ideas |
| Image to video (from a picture) | High | Picture, then clip | 30 credits · 5 s | Same face or product |
| Video to video (from a clip) | Medium, copies motion | Needs a clip first | 24 credits · 3 s | New style, same motion |

### How to choose

Ask two questions:

1. Do you need the same face, product or place in many shots? **Yes** → image to video.
2. Do you already have a clip with the exact motion you want? **Yes** → video to video.
3. Neither, and you are just exploring? → text to video.

### Our main way in this course

Most clips in this course use image to video:

| Step | Tool | Job |
|---|---|---|
| 1 | Claude | Writes the prompt |
| 2 | ChatGPT | Makes the picture |
| 3 | Kling or Veo | Brings it to life |

The motion prompt shown for the chai picture:

```text
Steam rises slowly from the cup of chai. Slow camera push in.
```

## Worked example

The same chai idea, made three ways in the video:

| Way | What went in | What came out | Cost shown |
|---|---|---|---|
| Text to video | The close-up chai prompt above | A 5 s clip; the model chose the cup, table and light | 30 credits |
| Image to video | A chai picture as the first frame + "steam rises, slow push in" | A 5 s clip whose frame 1 is the picture | 30 credits (plus the picture) |
| Video to video | A 3 s real cafe clip + a new style | The same motion in a clay animation look | 24 credits |

Prices and credit costs change. Check the current cost in the tool before you generate.

## Common mistakes

- **A prompt that fights the picture.** Picture of a cup, prompt asks for a dancing cat. Describe only the motion.
- **A small, low quality picture.** A tiny, blurry first frame gives a weak clip. Use a sharp, full size picture: the clip can only be as sharp as its first frame.
- **The wrong shape.** A square picture in a landscape video gets cropped or gets black bars. Make the picture in the same ratio, like 16:9.

The clip is only as good as its first frame.

## Try it yourself

1. The video's task: pick one idea. Write a text prompt for it, then describe the first frame picture you would make. No credits needed, just a notes file.
2. For each case, pick the way: (a) a 5 shot ad with the same shop owner in every shot; (b) you love the camera move in an old clip but want it as anime; (c) you just want to see if "a kite over a beach" looks nice.
3. Your picture shows a sleeping dog. Write a motion prompt that does not fight the picture.

## Next

[M01-L04 · The Full Workflow and Your Two Paths](../m01-l04-the-full-workflow-and-your-two-paths/)

## Answers

1. What good looks like: one text prompt with a subject, action, light and camera move, and one or two lines that describe the still picture (what is in it, the light, the shape such as 9:16).
2. (a) Image to video. (b) Video to video. (c) Text to video.
3. One possible answer: `The dog breathes slowly and one ear twitches. Still camera.` It only describes motion, and keeps what the picture already shows.
