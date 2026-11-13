# M03-L04 · The Prompt Formula

> Video: Module 3, Lesson 4. Watch it first, then use this page to revise and practise.

Two prompts for the same shot:

- **Prompt A:** chai being made.
- **Prompt B:** a man strikes a match, and a blue flame bursts under a kettle. Extreme close-up, slow push in. Blue dawn light.

Which one gives you the shot you planned? Prompt B. The AI only knows what you write. Anything you leave out, it guesses: who, doing what, where, which shot, what light, what style. Every guess can be wrong.

## What you'll learn

- The seven parts of a good video prompt, as seven questions
- Why the order matters, and how long a prompt should be
- How to keep the same man in every clip with the same character words
- How to ask your AI Video Director in Claude for one prompt per shot
- How to swap vague words for words a camera can see
- Three prompt mistakes

## Key ideas

### Seven parts, seven questions

| # | Part | Question | Chai · shot 1 |
|---|---|---|---|
| 1 | Subject | Who or what? | the chai man |
| 2 | Action | What happens? | strikes a match, a blue flame bursts |
| 3 | Setting | Where are we? | a dark roadside chai stall |
| 4 | Camera | Shot size + move | extreme close-up, slow push in |
| 5 | Light | Time and mood | blue dawn, orange glow |
| 6 | Style | Real, cartoon, clay? | photorealistic, 9:16, no text |
| 7 | Sound | What do we hear? | match strike, whoosh |

Write the answers in this order, as short sentences, and you have a prompt:

```text
The chai man. He strikes a match. A blue flame bursts under the kettle. Dark roadside chai stall. Extreme close-up, slow push in. Blue dawn light, orange flame glow. Photorealistic, 9:16, no text. Sound: match strike, whoosh.
```

Download the formula with this example and a fill-in template: [prompt-formula.md](../../downloads/prompt-formula.md).

### Why this order?

- Video models pay the most attention to the **start** of a prompt. So put the most important things first: who it is, and what they do.
- Camera, light and style come next. They shape how the shot looks.
- Sound goes last. Some tools, like Veo, make sound with the video. Others ignore it. So sound is a bonus.
- Keep it short: about **40 to 60 words**. A very long prompt can confuse the model. (Claude's prompts in this lesson are 56 to 58 words.)

### Keep the same man in every clip

Make five clips and the man can look different in every one. The fix: describe him once, in detail, and copy the same words into every prompt.

| # | Detail | Words |
|---|---|---|
| 1 | Age | mid-50s |
| 2 | Beard | short salt-and-pepper |
| 3 | Glasses | thin black rims |
| 4 | Clothes | cream half-sleeve kurta |
| 5 | One special detail | red and white towel on his shoulder |

The same 25 words start all 5 prompts. New words in each prompt give you 5 different men; the same words give you a similar man every time. It is not perfect, but it helps a lot. Module 9 locks the character fully.

### Use words a camera can see

| Vague | Specific | Part |
|---|---|---|
| a nice morning | golden sunrise light through steam | Light |
| a moving camera | a slow push in | Camera |
| good quality | photorealistic | Style |
| a sign that says OPEN | no text (add it later in the edit) | Style |

AI video often writes messy letters, so ask for no text, and add text later in the edit.

## Worked example

In the same chai stall chat in your AI Video Director project:

1. Open the chai stall chat.
2. Ask for one prompt per shot, using the 7 parts in order, then press Enter:

```text
Now write one video prompt for each of the 5 shots. Use this formula, in this order: subject, action, setting, camera, light, style, sound. Keep each prompt under 60 words, and put each one in its own code block so I can copy it.
```

Claude wrote 5 prompts, 56 to 58 words each, every one starting with the same description of the man. Shot 1, part by part: the man, then the action (he strikes a match, a blue flame bursts), the setting (a dark roadside chai stall), the camera (extreme close-up, slow push-in), the light (pre-dawn blue with an orange flame glow), the style (photorealistic, 9:16, no text), and last the sound (a match strike and a whoosh).

Claude's tip: the character description takes up 25 of the words. If you make the clips from images, Kling or Veo will see the face and the stall in the image, so you can cut the description down to "the chai man" and use the extra words for more action.

All five prompts are below.

## Prompts used

Shot 1 · The flame (6 s):

```text
A friendly Indian man in his mid-50s, short salt-and-pepper beard, thin black-rimmed glasses, cream cotton half-sleeve kurta, red-and-white checked cotton towel on his left shoulder. He strikes a match. A blue flame bursts under the kettle. Dark roadside chai stall. Extreme close-up, slow push-in. Pre-dawn blue, orange flame glow. Photorealistic, 9:16, no text. Sound: match strike, whoosh.
```

Shot 2 · The spices (6 s):

```text
A friendly Indian man in his mid-50s, short salt-and-pepper beard, thin black-rimmed glasses, cream cotton half-sleeve kurta, red-and-white checked cotton towel on his left shoulder. He crushes spices and drops them into bubbling chai. Roadside chai stall counter. Close-up, tilt from mortar to kettle. Blue dawn, warm flame glow. Photorealistic, 9:16, no text. Sound: pestle thuds, bubbling.
```

Shot 3 · The high pour (6 s):

```text
A friendly Indian man in his mid-50s, short salt-and-pepper beard, thin black-rimmed glasses, cream cotton half-sleeve kurta, red-and-white checked cotton towel on his left shoulder. He pours chai from high into a glass, smiling. Chai stall at sunrise. Slow-motion medium close-up, tilt up to his face. Golden rays through steam. Photorealistic, 9:16, no text. Sound: chai pouring, birds.
```

Shot 4 · First customers (6 s):

```text
A friendly Indian man in his mid-50s, short salt-and-pepper beard, thin black-rimmed glasses, cream cotton half-sleeve kurta, red-and-white checked cotton towel on his left shoulder. He hands chai to a jogger, auto driver and office worker. Morning chai stall. Medium shot, slow sideways dolly. Soft golden sun, long shadows. Photorealistic, 9:16, no text. Sound: chatter, glass clinks.
```

Shot 5 · Cheers (6 s):

```text
A friendly Indian man in his mid-50s, short salt-and-pepper beard, thin black-rimmed glasses, cream cotton half-sleeve kurta, red-and-white checked cotton towel on his left shoulder. He smiles at the camera and raises his glass. Chai stall, customers chatting behind. Wide shot, slow pull-back. Warm golden morning sun. Photorealistic, 9:16, no text. Sound: soft chatter, music fades.
```

### Want more ready prompts?

The course's prompt library has 50 ready video prompts, 5 for each of 10 shot types (extreme close-up, close-up, medium close-up, medium shot, wide shot, aerial and establishing, product shot, first-person POV, tracking shot, slow-motion moment). Every one follows the same order: subject, action, setting, camera, light, style, sound.

[AI Video Prompt Library · 50 prompts (PDF)](../../downloads/ai-video-prompt-library-50-prompts.pdf)

## Common mistakes

| Mistake | Bad | Better |
|---|---|---|
| A pile of keywords | chai, morning, beautiful, cinematic, 4K | A man pours chai at sunrise. Slow push in. |
| Two actions in one prompt | He pours chai, then serves customers | Clip 3: he pours. Clip 4: he serves. |
| A new man every prompt | Shot 1: an old man. Shot 2: a chai seller. | The same 25 words in every prompt |

Short sentences, one action, the same man.

## Try it yourself

1. The video's task: ask Claude for one prompt for each shot of your own shot list, and check that every prompt has all seven parts.
2. Label the seven parts in Claude's Shot 4 prompt above.
3. Rewrite "a girl, park, nice day, cinematic, amazing, 4K" with the formula.

## Next

[M03-L05 · Fixing Failed Clips](../m03-l05-fixing-failed-clips/)

## Answers

1. What good looks like: one prompt per shot, each 40 to 60 words, each with subject, action, setting, camera, light, style and sound in that order, and the same character words at the start.
2. Subject: the 25 character words. Action: he hands chai to a jogger, auto driver and office worker. Setting: morning chai stall. Camera: medium shot, slow sideways dolly. Light: soft golden sun, long shadows. Style: photorealistic, 9:16, no text. Sound: chatter, glass clinks.
3. One possible answer: `A young girl in a yellow dress. She blows a dandelion and laughs. A green park. Medium close-up, slow push in. Soft late afternoon sun. Photorealistic, 9:16, no text. Sound: birds, light wind.`
