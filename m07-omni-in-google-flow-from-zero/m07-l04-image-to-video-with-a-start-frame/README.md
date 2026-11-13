# M07-L04 · Image to Video with a Start Frame

> Video: Module 7, Lesson 4. Watch it first, then use this page to revise and practise.

With text only, Omni draws a new face every time: two of our text clips show two different women. But a brand needs the same person in every clip. For the course, that is **Meera**. The fix is a **start frame**: a picture that becomes the first frame of the video.

## What you'll learn

- Why text-only prompts give a new face every time
- How to add a ChatGPT picture as the start frame in Flow (Frames > Start > Upload media > Add to prompt)
- What the picture gives (the look) and what the text gives (what happens)
- What goes wrong when the text asks for a new look
- Four rules for a start frame

## Before you start

- Flow with Omni 1.2 Flash, Agent off.
- A picture of your character. The video uses Meera, the close-up made in ChatGPT in Module 4: tall (9:16), a clear face, a glass of chai.
- Each test is **9:16 · 360p · 8 s · x1 = 8 credits**. The video makes two tests, so **16 credits**. Uploading the picture is free.

## Follow along

### 1 · Pick Frames

Open the settings and pick **Frames**.

What you should see: the prompt box now shows a **Start** box and an **End** box.

### 2 · Open the Start box

Click **Start**. A new project has no pictures yet, so click **Upload media** and choose the file.

### 3 · Add it to the prompt

Click **Add to prompt**.

What you should see: Meera sits in the **Start** box. She is now the first frame of the video.

### 4 · Write only what happens

The picture already shows her face, her clothes and the place. So the text only says **what happens**: what she does, what she says, and what you hear.

She smiles and says, in a warm, friendly voice: "Welcome to Chai Corner. Fresh chai, every morning!" Then she takes a small sip. The camera stays still. No music, no subtitles.

| The picture gives the look | The text gives what happens |
|---|---|
| her face | what she does |
| her clothes | what she says |
| the place | what we hear |

### 5 · Generate (spends 8 credits)

Settings: 9:16 · 360p · 8 s · x1 = 8 credits. Click the **arrow**.

What you should see: it is Meera. The same face, the same hair, the same yellow apron as the picture. She says the line word for word, and then she takes the sip.

| Seconds (about) | What she does |
|---|---|
| 0 to 1 | smiles |
| 1 to 5 | says the line |
| 5 to 7 | takes a sip |

The picture gave the look. The prompt gave the action and the voice.

### 6 · A mistake to learn from (spends 8 credits)

Same start frame, but this prompt asks for a new look: a green saree, at a busy night market.

What you see: the first frame is Meera. Then, in less than a second, the video jumps: new clothes, a new place, and it is night. She even says "every morning", at night. The text fought the picture, and the text won.

So with a start frame, do not ask for a new look. Write only what happens.

## Prompts used

The start frame prompt (Start = the Meera picture):

```text
She looks at the camera, smiles and says in a warm, friendly voice with a light Indian accent: "Welcome to Chai Corner. Fresh chai, every morning!" Then she lifts the glass a little and takes a small sip. The camera stays still. Background: a quiet street in the morning, birds far away. No music. No subtitles. No text.
```

The clashing prompt (same start frame; do not copy this one, it shows the mistake):

```text
A woman in a green saree stands at a busy night market full of people and lights. She says in a warm voice: "Welcome to Chai Corner. Fresh chai, every morning!" No music. No subtitles. No text.
```

## Four rules for a start frame

1. **The same shape as the video.** Tall for a phone: a 9:16 picture for a 9:16 video. Make it in ChatGPT at 9:16.
2. **The picture sets the look.** Do not change her clothes or the place in the text.
3. **Write what happens:** the action, the exact line and the sound (smiles, says "...", takes a sip).
4. **One clear action is enough for 8 seconds.** More actions make a rushed clip.

## Common mistakes

1. **Describing a new look in the text.** The video jumps away from your picture in under a second.
2. **A wide picture for a tall video** (or the other way round). Match the shapes.
3. **Too many actions.** One smile, one line, one sip is plenty for 8 seconds.
4. **Text only for a brand character.** Every clip draws a new face. Start from the same picture.

## Your task

Turn one of your ChatGPT pictures into an 8 second talking clip: 360p, one line and one action. Good looks like: the same face and clothes as your picture all the way through, and your line word for word.

## Next

[M07-L05 · Flow Basics](../m07-l05-flow-basics/)
