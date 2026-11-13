# M11-L04 · Captions

> Video: Module 11, Lesson 4. Watch it first, then use this page to revise and practise.

Most people scroll with the sound off. The video plays our ad the way they see it: no voice, and no words. It says nothing. Then the same ad with captions: even with the sound off, the message gets through.

## What you'll learn

- What captions are, and the two ways to add them in CapCut
- What an SRT file is, and how to get Claude to write one
- How to import an SRT with Local captions
- How to style captions so they are easy to read on a phone
- How to fix wrong words and bad timing

## Before you start

- CapCut on the computer, with your ad from the last lesson.
- Your voiceover script (the words of your voice), and Claude (Module 3) to turn it into an SRT.
- Nothing in this lesson spends credits.

### Two ways to add captions

**Captions** are the words of your voiceover, on screen, in time with the voice.

| Way | How it works | Catch |
|---|---|---|
| Auto captions | CapCut listens to your voice and writes them in one click | Needs CapCut's servers, and on some computers it does not work |
| Import an SRT | A small text file with your captions, made beforehand | Works on every computer |

The video uses the second way.

### What an SRT file is

An **SRT** is a plain text file. Each caption has three parts:

| Part | Looks like |
|---|---|
| A number | 1, 2, 3 ... in order |
| Start --> end | hours:minutes:seconds,milliseconds |
| The words | What shows on screen |

Keep each caption short: **5 or 6 words**, so people can read it at a glance.

## Follow along

### Step 1 · Ask Claude for the SRT

You do not need to write it by hand. Give Claude your voiceover script, and ask:

```text
Here is my voiceover script. Turn it into an SRT, one short line every 2 or 3 seconds.
```

The SRT shown in the video, `captions.srt` (line 4 has a spelling mistake that we fix in Step 7):

```text
1
00:00:00,000 --> 00:00:02,500
Every morning at Chai Corner,

2
00:00:02,700 --> 00:00:05,600
the kettle starts before the sun.

3
00:00:06,000 --> 00:00:07,500
Fresh ginger,

4
00:00:07,600 --> 00:00:09,200
real cardamon,

5
00:00:09,300 --> 00:00:12,000
and a smile in every glass.
```

### Step 2 · Import the SRT

1. Click path: `Text > Local captions`.
2. Click **Import file**, and choose your SRT. It shows up as a card.

### Step 3 · Place it at the start

Put the playhead at the very start, then click the **+** on the card.

What you should see: the captions land on their **own track**, one block for each line, lined up with the voice. The **Captions** tab lists every line.

### Step 4 · Open the Text tab, Apply to all

Click a caption, and open the **Text** tab. **Apply to all** is ticked, so every change styles all the captions at once.

### Step 5 · Bold and size

Click **B** for bold, and drag **Font size** up until the words are easy to read on a phone. The video used **21**.

### Step 6 · Outline and position

1. Scroll down to **Preset style**, and pick white words with a dark outline. Under **Stroke**, you can see the outline is on. It keeps the words clear on any picture.
2. Under **Position**, set **Y** to **-900**. Now the captions sit in the lower middle, above the buttons that Reels and Shorts put at the bottom.

### Step 7 · Check every word

Play the video, and read each caption. Here is a mistake: **cardamon** should be **cardamom**.

1. In the **Captions** tab, double click the wrong word.
2. Type the right one, and click away.

Brand names and spices are the words that most often go wrong.

### Step 8 · Fix the timing

If a caption shows too early or too late, drag its **edges** on the timeline until it matches the voice.

## Prompts used

The Claude prompt:

```text
Here is my voiceover script. Turn it into an SRT, one short line every 2 or 3 seconds.
```

Caption style used:

```text
Text tab · Apply to all · B (bold) · Font size 21 · Preset style: white words, dark outline (Stroke on) · Position Y -900
```

## Try it yourself

1. The video's task: add captions to your ad, style them, and check every word.
2. Count the words in each of your captions. Split any line over 6 words.
3. Play your ad on a phone with the sound off. Can you follow the whole message?

What good looks like: short, bold, white captions with a dark outline in the lower middle, every word spelled right, each line in time with the voice.

## Common mistakes

- **Relying on Auto captions only.** It needs CapCut's servers; an SRT works on every computer.
- **Long caption lines.** Keep to 5 or 6 words.
- **Small, thin text with no outline.** Use bold, a bigger size and a dark outline.
- **Captions at the very bottom.** Reels and Shorts put buttons there; move them up (Y -900).
- **Not reading every caption.** Brand names and spices often come out wrong.
- **Ignoring timing.** Drag the edges so each line matches the voice.

## Next

[M11-L05 · Colour, Upscaling and Small Glitches](../m11-l05-colour-upscaling-and-small-glitches/)
