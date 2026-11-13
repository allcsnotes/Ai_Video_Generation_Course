# M13-L03 · Build 7: An Explainer Video

> Video: Module 13, Build 7. Watch it first, then use this page to revise and practise.

Build 7 is an **explainer video**: how a green leaf becomes black tea. A calm voice explains it, real-looking clips show each step, and a simple diagram ties it all together. A free AI voice, four clips from **Google Flow**, one diagram, and captions, all put together in **Shotcut**.

## What you'll build

- A 46-second explainer, **Green Leaf to Black Tea**, in full HD (1080p, 24 fps), 16:9
- A free 45-second voiceover from **Google AI Studio**
- Four documentary-style clips (wither, roll, oxidise, dry) and one diagram with no text in it
- Labels you type yourself, and captions burned in with a dark background

## Before you start

- **Google AI Studio** (free) for the voice.
- **Google Flow** with credits, for four clips and one diagram image (Module 7).
- **Shotcut** installed (free).
- **Credits:** the voice and the diagram are **free**. The four clips cost **15 credits each**, so **60 credits** in all. Prices and plans change: check the current price before you buy.
- Plan it with the [build plan template](../../downloads/build-plan-template.md).

## Plan

### Start with the script

An explainer starts with the **script**, not the pictures. The voice is the backbone, and every picture follows it.

The topic has four steps: **wither, roll, oxidise, and dry**. So the script says each step out loud, with its number.

### One picture for each part

| Part | Picture | Length on the timeline |
|---|---|---|
| Intro | the diagram | 9 s |
| 1 · Wither | clip 1 | 7.2 s |
| 2 · Roll | clip 2 | 7.2 s |
| 3 · Oxidise | clip 3 | 7.2 s |
| 4 · Dry | clip 4 | 7.2 s |
| Recap | the diagram again, with labels | 8.3 s |

| Item | Cost |
|---|---|
| Voice (AI Studio) | free |
| Diagram (Flow, Image) | free |
| 4 clips × 15 credits | 60 credits |

## Build it step by step

### Step 1 · The voice, in Google AI Studio

1. Open **Google AI Studio**, go to **Generate speech**, start a **new dialog**, and paste the script.
2. Write it the way people talk: **short sentences, with one idea each**. Say the **number before each step**, so viewers always know where they are.
3. Open **Style**, and describe the voice: clear and calm, like a friendly documentary narrator, with a short pause after each step.
4. Click **Run**. The voice comes out **45 seconds** long. Then download it with the **arrow icon**, as a **WAV** file.
5. Listen to it once, all the way through. If a word sounds wrong, change the spelling and run it again.

### Step 2 · The pictures, in Flow

1. Choose **Video**, **16:9**, the **Omni 1.2 Flash** model, **720p**, and **5 seconds**. Each clip costs **15 credits**.
2. Each prompt starts with **the number and the style**: realistic documentary style. Then **the place, the action, and a slow camera move**.
3. Clip 1 shows fresh leaves withering on long racks. Clip 4 shows dark, crisp leaves pouring out of a hot-air dryer.
4. Every prompt ends the same way: `No music. No text.` Our own voice does the talking.
5. For the diagram, switch to **Image**. Ask for four leaves in a row, joined by arrows, from bright green to almost black.
6. And say: **no text, no letters, no numbers**. AI pictures often break letters, so we leave empty space, and type the labels ourselves.
7. Download the four clips in **720p**, and the diagram in **2K**.

### Step 3 · Fit it to the voice, in Shotcut

1. New project called **Green Leaf to Black Tea**, in **HD 1080p 24 fps**.
2. Open the diagram, the voice, and all four video clips. They land in the **Playlist**.
3. Open the diagram. A picture lasts **4 seconds** at first, so in **Properties**, set its **Duration** to **9 seconds**, the length of the intro. Then press **A**.
4. Each step in the voice takes about 7 seconds, but each clip is only 5. So set **Speed** to **0.7**, and click **Apply**. Now the clip lasts **7.2 seconds**, in calm slow motion.
5. Add all four clips this way. Then add the diagram again at the end, for the recap.
6. Mute the clip sound on **V1**, and add an audio track. Then select **A1**, press **Home**, and press **B**. The voice drops in at the start.
7. On the last diagram, add **Text: Simple**. Type the word **Wither**, pick a dark colour, and place the box above the first leaf.
8. Add three more for **Roll**, **Oxidise**, and **Dry**. Now every word is sharp and spelled right, because we typed it.

### Step 4 · Captions, for sound off

Many people watch with the sound off, so captions really matter.

1. In **Subtitles**, open the menu, and choose **Speech to Text**. Set the **maximum line length** to **32 characters**, and pick track **A1** (tracks with speech), where the voice is. Click **OK**.
2. Shotcut writes every caption for you, with its times. **Read every line.** Here it spelled oxidise with a z ("oxidize"), so we fix it to match our labels.
3. Choose **Burn In Subtitles on Output**. Turn off **Use font size**, and set a wide, low box.
4. White text disappears on the cream diagram, so give it a **dark, see-through background** (padding 10). Now the captions read well on every shot.
5. Export with the **YouTube** preset. The explainer is **46 seconds** long, in full HD.

## Prompts used

The voiceover script (AI Studio, voice Fola):

```text
Every glass of chai starts as a green leaf. So how does a green leaf become black tea? In four steps. One: wither. The fresh leaves rest on long racks for many hours, until they go soft. Two: roll. Rollers twist and break the leaves, so the juice inside meets the air. Three: oxidise. In the air, the leaves slowly turn from green to copper brown, just like a cut apple. Four: dry. Hot air stops the change, and the leaves turn dark and crisp. Wither, roll, oxidise, dry. That is how a green leaf becomes black tea.
```

Voice style:

```text
Clear and calm, like a friendly documentary narrator. Steady pace, with a short pause after each step.
```

Clip 1 (Flow, `Video · 16:9 · Omni 1.2 Flash · 720p · 5 s`, 15 credits):

```text
Clip 1. Realistic documentary style: a tea factory in Assam, soft morning light. Fresh green tea leaves are spread thinly on long wire racks to wither. Slow camera push along the racks. Sound: soft fans humming. No music. No text.
```

Clip 4:

```text
Clip 4. Realistic documentary style: inside a tea factory in Assam, warm light. Dark, crisp black tea leaves pour out of a large hot-air dryer onto a metal tray, close up. Slow camera move. Sound: leaves rustling and a warm hum. No music. No text.
```

Clips 2 (roll) and 3 (oxidise) follow the same pattern: `Clip N. Realistic documentary style: <place> › <action> › <slow camera move>. Sound: <...>. No music. No text.`

The diagram (Flow, **Image**, Nano Banana 2.1, free):

```text
A clean flat illustration diagram on a plain cream background: four tea leaves in a row from left to right, joined by simple dark arrows. Leaf 1 is fresh and bright green. Leaf 2 is soft and limp. Leaf 3 is twisted and rolled, turning copper brown. Leaf 4 is dark, almost black, and crisp. Lots of empty space above each leaf. No text, no letters, no numbers.
```

## Check your work

- [ ] The script says each step with its number, in short sentences
- [ ] The voice is about 45 seconds, and you listened to all of it
- [ ] The AI clips and the diagram have no text in them
- [ ] Diagram 9 s at the start; each clip at Speed 0.7 (7.2 s); the diagram again at the end
- [ ] The four labels are typed (Text: Simple), sharp and spelled right
- [ ] Every caption line read; spelling matches the labels (oxidise)
- [ ] Captions readable on the cream diagram (dark, see-through background)
- [ ] The file is 46 seconds, full HD

## Common mistakes

- **Starting with the pictures.** Write the script first; the pictures follow the voice.
- **Text inside AI pictures.** Letters come out broken. Ask for no text, and type the labels yourself.
- **Pictures shorter than the voice.** Set the picture Duration, and slow clips down with Speed.
- **Forgetting Apply** after changing Speed.
- **Trusting Speech to Text.** It spelled oxidise with a z. Read every line.
- **White captions on a light picture.** Add a dark, see-through background.

## Your task

Make a 30-second explainer, with three steps: a free AI voice, one picture for each step, typed labels, and captions.

What good looks like: a script with a numbered step in each short sentence, a voice you listened to in full, one text-free picture per part, pictures stretched to fit the voice, typed labels, and captions you read and fixed.

## Recap

1. Write the script first. The voice is the backbone of an explainer.
2. Plan one picture for each part, and ask for no text in AI pictures.
3. Fit the pictures to the voice: set the picture duration, and slow the clips down with Speed.
4. Type the labels with Text: Simple, make captions with Speech to Text, and read every line.

## Next

[M13-L04 · Build 8: Your Own Project](../m13-l04-build-8-your-own-project/)
