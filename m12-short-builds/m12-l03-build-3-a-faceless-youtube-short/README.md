# M12-L03 · Build 3: A Faceless YouTube Short

> Video: Module 12, Build 3. Watch it first, then use this page to revise and practise.

Build 3 is a **faceless YouTube Short**: a short, upright video with one fun fact, a voiceover and captions. **Faceless** means there is no presenter: nobody appears on camera. The voice and the captions tell the whole story.

## What you'll build

- A vertical video (9:16) of about 19 seconds, about one fun fact: chai means tea
- A free AI voiceover from **Google AI Studio**
- Six clips, one for each part of the script: four reused, two new from **Kling**
- Captions made with Shotcut's **Speech to Text**, checked by hand, then burned in

## Before you start

You need just three things: a **short script**, a **voice**, and **one clip for each sentence**.

- **Google AI Studio** (free) for the voice. Module 10 covers voiceovers.
- **Kling** for the two new clips (Module 5).
- Four clips from earlier builds: the pour, the stall, the tin and a glass of chai.
- **Shotcut** installed (free).
- **Credits:** two new Kling clips at **30 credits** each = **60 Kling credits**. The voice is **free**. The reused clips cost **0**. Prices and plans change: check the current price before you buy.
- Plan it with the [build plan template](../../downloads/build-plan-template.md).

## Plan

**The fact:** chai tea means tea tea. The voice is about 19 seconds long (our take was 18.8 seconds).

| Clip | What it shows | What the voice says | Source |
|---|---|---|---|
| 1 | The pour | Chai tea? That means tea tea. | reused |
| 2 | The stall | In Hindi, chai is simply the word for tea. | reused |
| 3 | Tea garden (for China) | The word started in China as cha, | new in Kling |
| 4 | Camel caravan (for the old trade roads) | and travelled west on old trade roads, all the way to India. | new in Kling |
| 5 | The tin | And masala means spice. So masala chai is just spiced tea. | reused |
| 6 | A glass | Now you know! | reused |

## Build it step by step

### Step 1 · The voice, in AI Studio

1. Open **Google AI Studio** (`aistudio.google.com`), go to **Generate speech**, and click **Create new dialog**.
2. Paste the script into the speech block.
3. Open **Style**, and describe the voice: curious and lively, like a friend sharing a fun fact.
4. Click **Run**, and listen to the whole take. If a word sounds wrong, change the text and run it again.
5. Click **download**, to save the voice (a WAV file).

The video's take starts: "Chai tea? That means tea tea."

### Step 2 · Two new clips, in Kling

1. Open Kling with **Kling 4.0 Flash**, **720p**, **9:16**, and **5 s**.
2. Clip 1: a misty tea garden on hills, at sunrise. Clip 2: a camel caravan crossing golden dunes, carrying sacks of tea.
3. Both prompts say **no text**, so there are no wrong letters to fix. Each clip costs **30 credits**.

### Step 3 · Edit in Shotcut

1. New project called **Chai fact short**, in **Vertical HD 30 fps**.
2. Open the six clips one by one, and press **A** for each, so they line up on the timeline in order (V1).
3. The clips have their own sound, and we only want the voice. Click the **speaker on the V1 track** to mute it.
4. Add an audio track. Open the voice, select the new track, and press **A**. The voice starts at zero.
5. Match each clip to its sentence. Put the playhead where the next sentence starts, select the clip, and press **S** to split it.
6. Select the leftover piece, and press **X**. **Ripple delete** removes it and pulls the next clips in. Now clip 2 starts with sentence 2. Do this for every clip, so every clip ends where its sentence ends.

### Step 4 · Captions, with Speech to Text

1. Click **Subtitles**, open the menu, and pick **Speech to Text**.
2. The first time, Shotcut asks to download a speech model. Click **Yes**. It is about **60 MB**, only the first time, and it runs on your own computer.
3. Keep the language on **English**, and set the **maximum line length to 20** characters, so each caption stays short. Click **OK**.
4. In a few seconds you get **15 subtitle lines**. Now **read every one**. In the video it got the second line wrong, and it added quote marks.
5. Click a line, and fix it in the **Current** box. The video also fixed one more word, near the end.
6. Open the menu again, and click **Burn In Subtitles on Output**. This draws the captions onto the video.
7. Untick **Use font size**. Set the position to **90, 1250** and the size to **900 × 170**. Now the captions are big, and sit above the bottom.

### Step 5 · Export

1. Click **Export**, pick the **YouTube** preset, and click **Export Video/Audio**. Wait for the **green tick**.

### Step 6 · Post it as a Short

- Any vertical video **up to 3 minutes** long can go into the YouTube Shorts feed.
- When you upload it, YouTube asks about altered or synthetic content. These clips look real and are made with AI, so answer **yes**.

## Prompts used

The script (pasted into AI Studio):

```text
Chai tea? That means tea tea. In Hindi, chai is simply the word for tea. The word started in China as cha, and travelled west on old trade roads, all the way to India. And masala means spice. So masala chai is just spiced tea. Now you know!
```

Voice style (AI Studio, Style):

```text
Curious and lively, like a friend sharing a fun fact. Clear, upbeat, medium pace.
```

Kling clip 1, tea garden:

```text
Misty green tea garden on rolling hills at sunrise. Neat rows of tea bushes, soft golden light, low mist between the hills. Slow drone push forward. No people, no text. Cinematic, photo-real.
```

Kling clip 2, camel caravan:

```text
A camel caravan walks across golden desert dunes at sunset, carrying sacks of tea. Long shadows, warm orange light, dust in the air. Wide shot, slow sideways camera move. No text. Cinematic, photo-real.
```

Settings: `Kling 4.0 Flash · 720p · 9:16 · 5 s` (30 credits each).

## Check your work

- [ ] The file is **1080 × 1920**, **30 fps**, and **under 20 seconds** (ours was 19.5 s)
- [ ] Clip sound muted (V1 speaker); only the voice plays
- [ ] Every clip starts and ends with its own sentence
- [ ] Every caption line read and fixed; no extra quote marks
- [ ] Captions burned in, big, above the bottom
- [ ] Watch it with the **sound off**: the captions must tell the story alone
- [ ] On upload, you answered **yes** to altered or synthetic content

## Common mistakes

- **Trusting Speech to Text.** It gets words wrong and adds quote marks. Read every line.
- **Long caption lines.** Set the maximum line length to 20 so each caption stays short.
- **Leaving the clip sound on.** Mute V1, so only the voice plays.
- **Clips that do not match the words.** Split at each sentence (S) and ripple delete the leftover (X).
- **Asking for text in the clip.** AI letters are often wrong. Say "no text" in the prompt.
- **Not checking with the sound off.** Many people watch Shorts muted.

## Your task

Make a faceless short video about one fun fact, with a voice and captions.

What good looks like: a script of a few short sentences, a free AI voice you listened to in full, one clip per sentence (reuse what you can), clips trimmed to their sentences, captions you read and fixed, and a file that makes sense with the sound off.

## Recap

1. Faceless means a script, a voice, and one clip for each sentence.
2. The voice is free from AI Studio. Only the new clips cost credits.
3. In Shotcut, mute the clips, put the voice on its own track, and trim each clip to its sentence.
4. Speech to Text writes the captions. Read every line, fix the mistakes, then burn them in.

## Next

[M12-L04 · Build 4: A Talking Character with Lip Sync](../m12-l04-build-4-a-talking-character-with-lip-sync/)
