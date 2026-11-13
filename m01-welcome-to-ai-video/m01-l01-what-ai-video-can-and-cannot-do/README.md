# M01-L01 · What AI Video Can and Cannot Do

> Video: Module 1, Lesson 1. Watch it first, then use this page to revise and practise.

The video opens on a cup of chai that does not exist. No camera, no cafe, no actor. A computer made it in about one minute, from one sentence:

```text
a clay cup of masala chai, steam rising, warm morning light, and a slow camera push in.
```

The clip on screen is labelled "AI generated · Kling 4.0 Flash · 5 seconds". So if AI can make this, can it make anything you ask for? Not quite. It is brilliant at some things and still weak at others. Knowing the difference is your first real skill.

## What you'll learn

- What AI video is: a prompt goes into a model, and a short clip comes out
- Why the model does not copy videos from the internet
- The six things AI video is good at today
- The six weak spots, and which module fixes each one
- Why you plan a video like a film director, with a crew of four tools
- Three beginner mistakes and one pro habit

## Key ideas

### What exactly is AI video?

You give the computer a description in words. That description is called a **prompt**.

The prompt goes into an **AI video model**: a program that has learned what real videos look like. Out comes a short **clip**, usually 5 to 10 seconds long.

| Step | What it is |
|---|---|
| 1 · Prompt | Words you type |
| 2 · AI video model | A program that has learned what real videos look like |
| 3 · Clip | 5 to 10 seconds |

### A video is many pictures

A video is many still pictures shown fast, one after another. Each picture is called a **frame**.

- Most videos show about 30 frames every second, so a 5 second clip is around 150 pictures (5 × 30 = 150).
- The Kling clip in the video uses 24 a second: 121 pictures in 5 seconds.
- The model paints every one of those pictures and makes them flow smoothly, like a real camera shot.

### It does not copy

This is the part most beginners get wrong.

| Myth | Truth |
|---|---|
| It searches the internet and copies a video | It paints brand new frames, made fresh for your prompt |

While it was being built, the model studied a huge number of videos, each with a description ("rain on a street", "pouring coffee", "sunset at sea" and so on). From them it learned patterns: how steam moves, how light falls on a face, how a camera glides forward.

Think of a painter who has seen ten thousand sunsets. Ask for a sunset, and they paint a brand new one from memory. That is also why you get a different result every time you press generate, even with the same prompt.

### What AI video is good at today

1. **Short single shots.** One place, one idea, 5 to 10 seconds.
2. **Light, weather and mood.** Sunlight, rain, fog, golden hour. These often look stunning.
3. **Camera moves.** A push in, a pan, an orbit or a drone shot that would need expensive gear in real life.
4. **Nature, food and products.** Steam, water, cloth, or a bottle turning on a table.
5. **Any style you can name.** Real looking, cartoon, 3D, anime or old film.
6. **Sound, in some tools.** Veo can make voices, footsteps, birds and rain.

### The weak spots

The video asked for a woman holding a chalkboard sign:

```text
…holds a chalkboard sign that reads CHAI CORNER OPEN 7 AM …
```

This time the words came out right: new models are much better with a few short words. But the sign changes size. It is small at second 0.2, huge at second 1.3 and small again at second 4.3. A real sign never does that.

| # | Weak spot | What goes wrong | The fix (and where you learn it) |
|---|---|---|---|
| 1 | Text | Long text, small labels and screens come out jumbled | Add text in CapCut · M11 |
| 2 | Hands and fingers | Missing, extra or melting | Better start frame · M05 |
| 3 | Long videos | One prompt = one short clip | Many shots, then edit · M11 |
| 4 | The same face | Changes from clip to clip | Consistency tricks · M09 |
| 5 | Exact numbers | Ask for 7 birds, get 5 or 9 | Keep it simple · M03 |
| 6 | Fast, busy movement | Dancing, fights and crowds warp | Slower, simpler motion · M05 |

Even when text works, always check it.

### You are the director

A shop owner asks you for a 30 second ad. Can you type one prompt and get the whole ad? No. You plan it like a film director and break it into small shots:

| Shot | What we see |
|---|---|
| 1 | The shop from outside |
| 2 | Chai being poured |
| 3 | A happy customer |
| 4 | The logo |

You make each shot as its own clip, then join them in an editor with music and text. You are not just pressing a button.

### Your film crew

| Crew job | Tool | What it does |
|---|---|---|
| Writer | Claude | Idea → script, shots, prompts |
| Photographer | ChatGPT | The first picture of each shot |
| Camera | Kling · Veo | Words and pictures → moving clips |
| Editing room | CapCut | Clips → one finished video |

## Worked example

The opening chai clip, split into the parts of its prompt:

| Part | Words in the prompt |
|---|---|
| Subject | a clay cup of masala chai |
| Motion | steam rising |
| Light | warm morning light |
| Camera | a slow camera push in |

Tool and settings shown: Kling 4.0 Flash, 5 seconds. It took about one minute. The result is a strong example of what AI video does well: one short shot, food, steam, warm light and one slow camera move.

The sign clip shows the other side. The text was right, but the sign kept growing and shrinking. Pausing at seconds 0.2, 1.3 and 4.3 is how the problem was spotted.

## Common mistakes

- **Expecting perfection on the first try.** Professionals make a few versions and keep the best one.
- **A vague prompt, like "a nice cafe video".** The model then guesses everything. Say the subject, action, light and camera.
- **Pressing generate just to see.** Every clip costs credits (one clip costs 30 credits in the video's example), so plan your prompt first.
- **Pro habit:** pause your clip and check it frame by frame. Small mistakes hide in motion.

## Try it yourself

1. The video's task: watch 5 AI videos online and spot one mistake in each. A hand, some text, or a face that changes.
2. For each mistake you find, write which weak spot from the table it belongs to.
3. A client wants a 30 second ad for a bakery. Write the 4 shots you would plan, one line each.
4. Turn "a nice cafe video" into a better prompt with a subject, an action, a light and a camera move.

## Next

[M01-L02 · How a Video Model Works](../m01-l02-how-a-video-model-works/)

## Answers

1. What good looks like: 5 lines, each with the video, the second where it happens and the mistake ("0:03, the hand has six fingers").
2. For example: a jumbled shop sign is weak spot 1 (text); a face that changes between clips is weak spot 4.
3. One possible plan: the bakery from outside; bread coming out of the oven; a customer taking a bite; the logo. Each is its own clip, joined in the editor.
4. One possible answer: `a clay cup of masala chai on a wooden cafe table, steam rising, warm morning light, slow camera push in`.
