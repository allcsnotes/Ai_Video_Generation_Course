# M03-L05 · Fixing Failed Clips

> Video: Module 3, Lesson 5. Watch it first, then use this page to revise and practise.

We asked Kling for one clip of our chai stall (Kling 4.0 Flash, 5 seconds). The hand vanishes from the spice bowl. Glasses appear from nowhere. And the camera never stops spinning.

The tool is not broken. The prompt is. It asked for five things in five seconds. This lesson shows how to spot problems like this, and fix them.

## What you'll learn

- The difference between an image prompt and a video prompt
- How to read a failed prompt like a director: five problems
- How to ask Claude to find the problems and rewrite the prompt
- What a negative prompt is, and when to use it
- The before and after in Kling, and what is still not perfect
- A first-fix table for the failures you will see most

## Key ideas

### Image prompt vs video prompt

| Image prompt | Video prompt |
|---|---|
| One frozen moment | What happens over time |
| Who is there, where, what light, which style | What moves, how the camera moves, what we hear |
| Nothing moves, no sound | From the first second to the last |
| = what it looks like | = what happens |

When you start a video from an image, the image already shows the face, the place and the light. So the video prompt only needs the motion.

### Read it like a director

The failed prompt:

```text
A chai seller makes masala chai, crushes spices, pours tea from high, serves many customers who laugh, drink and clap, fast spinning camera around everything, beautiful cinematic amazing 4K
```

| # | Problem | Why it breaks |
|---|---|---|
| 1 | Too many actions | Making chai, crushing spices, pouring, serving and a crowd: 5 actions in 5 seconds. One clip holds one action. |
| 2 | Spinning camera | The model has to invent a new angle in every frame, so things melt and change. |
| 3 | Too many people | Every extra face and hand is one more thing that can go wrong. |
| 4 | Hype words | Beautiful, cinematic, amazing, 4K show the model nothing. 4K comes from your export settings. |
| 5 | No character | The man can look different in every clip. |

The fix: one action, a slow camera, few people, real details, the same man.

### Fix it with Claude

You do not have to find all this alone. Go back to Claude and open your chai stall chat. Paste the prompt, say which tool and length you used, describe what went wrong, and ask for a rewrite for one shot.

Claude finds the same five problems and explains each one in plain words. Then it rewrites shot 3 (the high pour): the same man, one action, a slow push in, slow motion.

### Negative prompts

A **negative prompt** is a list of things you do not want, like extra hands or a spinning camera. If your tool has a box for it, paste it there. The Kling model used in the video (Kling 4.0 Flash) has none, so the video skips it.

### Common failures, first fix

| What went wrong | Try this first | Fix type |
|---|---|---|
| Warped hands, extra fingers | One simple job for the hands, slow motion | Change prompt |
| A face that changes | Same character words, or start from an image | Change image |
| A wild camera | One slow move, or a still camera | Change prompt |
| Messy letters | Write "no text", add text in the edit | Change prompt |
| Nothing moves | A clear action and a camera move | Change prompt |
| Right idea, one small glitch | Just generate again | Generate again |

Download this as a checklist: [fix-a-failed-clip.md](../../downloads/fix-a-failed-clip.md).

## Worked example

### Step 1 · Ask Claude

In the chai stall chat, the video typed:

```text
I tried this prompt in Kling 4.0 Flash (5 seconds, 9:16): "A chai seller makes masala chai, crushes spices, pours tea from high, serves many customers who laugh, drink and clap, fast spinning camera around everything, beautiful cinematic amazing 4K". The clip rushes through everything: the hand vanishes from the mortar, glasses appear from nowhere, and the camera never settles. What went wrong? Rewrite it as one prompt for shot 3 (the high pour) that will work.
```

### Step 2 · Claude's rewrite

Shot 3, rewritten (5 seconds):

```text
A friendly Indian man in his mid-50s, short salt-and-pepper beard, thin black-rimmed glasses, cream cotton half-sleeve kurta, red-and-white checked cotton towel on his left shoulder. He pours one long stream of chai from high into a glass. Chai stall at sunrise. Medium close-up, slow push-in. Golden light through steam. Slow motion, realistic, 9:16, no text. Sound: chai pouring.
```

The negative prompt Claude offered (only for tools with a negative prompt box; Kling 4.0 Flash has none):

```text
fast motion, spinning camera, shaky camera, extra hands, extra glasses, objects appearing, morphing, blurry face, text, logo
```

Two tips: **start from an image** (make the shot 3 image in ChatGPT first, then use image to video, so the prompt only describes motion), and **leave the smile for another shot** (in 5 seconds, the pour is enough).

### Step 3 · Paste the fix into Kling

Same model, same 5 seconds, 9:16. 30 credits. Before and after:

| | Before · 5 actions | After · 1 action |
|---|---|---|
| Action | Rushes through everything | One long stream of chai |
| Hands and objects | The hand vanishes, glasses appear | The glass stays in place |
| Camera | Never stops spinning | Moves slowly |

It is not perfect. Near the end, the steam covers his face. The next fix is not a longer prompt. It is Claude's tip: start from an image, so his face is locked. Module 4 starts exactly there.

## Common mistakes

| Mistake | Bad | Better |
|---|---|---|
| Endless rerolls | Same prompt, Generate 5 times = 150 credits | Failed twice? Change the prompt. |
| Changing everything | New action, camera, light and model, all at once | Change one thing per try, so you know what fixed it. |
| Losing what worked | A great clip, but the prompt is gone | Save it in your project, next to the clip. |

One change per try, and save what works.

## Try it yourself

1. The video's task: take one clip that went wrong, ask Claude what failed, and make a fixed version, changing one thing at a time.
2. Find the problems in this prompt: "a dancer spins, jumps and claps with ten friends, crazy fast camera, stunning 8K".
3. Your clip's idea is right, but one cup flickers for a moment. What is the first fix?

## Next

[M04-L01 · Your First Image](../../m04-chatgpt-images-start-frames/m04-l01-your-first-image/)

## Answers

1. What good looks like: a short note of what failed, a rewritten prompt with one action and one slow camera move, and a second try where only one thing changed. Save the working prompt next to the clip.
2. Too many actions (spins, jumps, claps), too many people (ten friends), a fast camera, and hype words (stunning, 8K). No character description either.
3. The idea is right and only a small part broke, so just generate again.
