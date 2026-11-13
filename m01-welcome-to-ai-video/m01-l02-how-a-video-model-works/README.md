# M01-L02 · How a Video Model Works

> Video: Module 1, Lesson 2. Watch it first, then use this page to revise and practise.

Every AI video you have ever seen started as pure static: no picture at all, just random coloured dots. Then, step by step, the dots get cleaned up and a cup of chai appears.

Does the model draw the cup line by line, like an artist with a pencil? No. It starts with noise and removes a little of it at a time, until only a picture is left. No maths needed: this page explains how.

## What you'll learn

- What a picture is to a computer: pixels
- What noise is, and why every AI video starts from it
- The training game: add noise, then guess it away
- How a new picture is made in 20 to 50 cleaning steps, steered by your prompt
- What a seed is, and why the same prompt gives a different clip
- Why a video model cleans all frames together, and why longer, sharper clips cost more

## Key ideas

### Pixels: a picture is a grid of coloured squares

Zoom into any image and you find a grid of tiny coloured squares. Each square is a **pixel**.

- One frame of the chai video is 1280 pixels wide and 720 tall: 1280 × 720 = 921,600 pixels, almost one million.
- Each pixel is just one colour: warm brown for the cup, gold for the light, dark for the shadows.

### Noise

Give every pixel a random colour and you get **noise**. It looks like the static on an old TV.

| A picture | Noise |
|---|---|
| Every pixel has a reason | Every pixel is random, like old TV static |

Noise has no picture hidden in it at all. Keep that in mind, because every AI video starts from it.

### The training game

How does a model learn to turn noise into a picture? With a simple game.

Part 1, add noise:

| Step | Noise | What you see |
|---|---|---|
| 0 | 0% | The real photo |
| 1 | 30% | A little grainy |
| 2 | 55% | More |
| 3 | 80% | More |
| 4 | 100% | Only noise, the photo is gone |

Part 2, guess the noise:

1. Show the model a noisy photo and ask: which part of this is noise? Take it away.
2. At first its guesses are bad. It checks the real answer and adjusts itself a tiny bit.
3. Repeat this millions of times, with millions of photos and video clips, each with a description.

This is called **training**. In the end the model is very good at one job: cleaning a little noise out of any picture.

### Making a brand new picture

1. Start with pure noise. No photo is hidden inside.
2. The model cleans a little, then a little more.
3. First rough shapes appear (big blobs of light and dark), then colours (brown cup, golden light), then fine details (steam, wood grain, edges).

This usually takes 20 to 50 small steps. Each step is one cleaning pass.

### Your prompt steers every step

Noise could become anything: a car, a tree, a face. Your prompt decides. At every step the model reads your words and cleans toward a picture that matches them.

| Same starting noise + prompt | Result |
|---|---|
| "a clay cup of masala chai…" | Chai, as asked |
| "a woman holding a sign…" | The woman, as asked |

Same noise, different prompt, different picture.

### The seed: a dice roll

Every time you press generate, the tool picks a new random noise to start from. The number behind that pick is the **seed**. Think of it as a dice roll.

- New seed, new starting noise, new result. That is why the same prompt gives a different clip every time.
- Some tools let you keep the same seed. Same seed + same prompt = almost the same result again.

### Frames are cleaned together

A video is many frames. The 5 second Kling clip has 121 frames.

- If the model cleaned each frame on its own, they would not match: the cup would jump around and the light would flicker.
- So a video model cleans **all the frames together, as one stack**. At every step each frame looks at its neighbours.
- That is how the steam keeps rising one way and the cup stays put.
- When the frames do not agree well enough, you see the weak spots: a sign that grows then shrinks, a face that slowly turns into someone else.

### Longer and sharper costs more

| Clip | Frames | Pixels in each frame | Pixels to clean, about |
|---|---|---|---|
| 5 seconds · 720p | 121 | 0.9 million | 110 million |
| 10 seconds · 1080p | 241 | 2.1 million | 500 million |

More work for the computer means more credits: about 4.5 times the work for the longer, sharper clip.

## Worked example

The chai frame, step by step:

1. A 1280 × 720 frame starts as random coloured dots ("step 0 of 30" on screen).
2. Early passes: big blobs of light and dark.
3. Middle passes: a brown cup and golden light.
4. Late passes: steam, wood grain and sharp edges.
5. The prompt "a clay cup of masala chai…" steered every pass toward chai.

The seed scene shows three tries of one prompt with seeds 4821, 1307 and 9264. Each seed gives a new result (the video draws these as different framings, as an illustration).

## Common mistakes

- **Rerolling, hoping the problem goes away.** Each try is only new noise. If a problem keeps coming back, change the prompt.
- **One long clip to save time.** More frames means more chances to drift. Make short clips and join them later.
- **Ten ideas in one prompt.** At every step all those words pull in different directions. Keep one clear subject and one clear action.

Now you know why: every try is new noise. Keep it short, simple and clear.

## Try it yourself

1. The video's task: in ChatGPT, ask for the same picture twice and spot what changes between the two results.
2. Work out the pixels in one 1080p frame (1920 × 1080).
3. A clip keeps showing a melting hand after three tries. What should you do next?

## Next

[M01-L03 · Text, Image or Video to Video](../m01-l03-text-image-or-video-to-video/)

## Answers

1. What good looks like: a short list such as "the cup moved left, the light is warmer, the table is different". Those changes come from a different starting noise, which is the seed at work.
2. 1920 × 1080 = 2,073,600 pixels, about 2.1 million, the number in the table above.
3. Stop pressing generate with the same prompt. Change the prompt, for example give the hands one simple job.
