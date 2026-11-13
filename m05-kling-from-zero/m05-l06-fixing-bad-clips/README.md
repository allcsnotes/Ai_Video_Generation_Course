# M05-L06 · Fixing Bad Clips

> Video: Module 5, Lesson 6. Watch it first, then use this page to revise and practise.

Last lesson, the calm clip was almost perfect. But near the end, steam drifts over Meera's face. You can fix a bad clip in three ways: change the words, try again, or change the picture. Pick the right one first, and you save credits.

## What you'll learn

- How to find the cause of a bad clip with three questions
- How to fix the words with one clear line, when Kling has no negative prompt box
- When trying again (rerolling) makes sense, and the once-more rule
- How to fix the picture in ChatGPT when the problem starts in the first frame
- Why "no steam" can still put steam in the clip
- Three fixing mistakes

## Before you start

- **Account:** your free Kling account, and ChatGPT for the picture fix.
- **The clip:** the calm clip from M05-L05 (Kling 4.0 Flash, the pouring picture as the first frame).
- **Cost:** every new Kling clip costs **30 credits** (Kling 4.0 Flash, 5 seconds). The video makes three new clips in this lesson: the words fix, the new picture, and the new picture with new words. A new picture in ChatGPT costs no credits.
- On the free plan, 30 credits a try is two clips a month. Prices change: read the number on the Generate button before you press it.

### Find the cause first: three questions

| # | Question | If yes |
|---|---|---|
| 1 | Did my words ask for it? | Change the words |
| 2 | Is the problem already in the picture? | Change the picture |
| 3 | Neither? | It was bad luck. Try once more |

Here, the prompt never asked for steam on her face. So we start with the words.

## Follow along

### Step 1 · Fix the words

1. Click **Edit** on the clip. Kling puts back the same prompt, the same first frame and the same settings.
2. Some tools have a box for things you do not want. It is called a **negative prompt**. Kling does not have one here.
3. So write it inside your prompt: say what you want, then say what you do not want. Add one line:

```text
The steam stays low, just above the glass. No steam over her face.
```

Change only this one line. Keep everything else the same, so you know what made the difference. Press **Generate**. **This spends 30 credits.**

The full prompt for this try:

```text
She slowly lifts the glass of chai and smiles. The camera slowly pushes in. One gentle move only. Subtle, natural motion. Keep her face, hands and clothes the same. The steam stays low, just above the glass. No steam over her face. No text.
```

### Step 2 · Check the fix

What you see in the video:

- At the start, her face is clear.
- But near the end, the steam rises even higher. It covers more of her face than before.

So the words did not fix it. When one clear line fails, the cause is somewhere else. Two fixes are left: try again, or change the picture.

### Step 3 · Know when to try again

Press Generate with the same prompt, and Kling makes a brand new clip. Every try comes out a little different.

Sometimes that is all you need. A hand that bent, or a face that changed for one moment, can be fine on the next try.

But every roll costs 30 credits. On the free plan, that is two clips a month.

The rule:

```text
Try 1 > fails > Try 2 > fails again > Change something
```

Try the same prompt once more, at most. If it fails again, the luck is not the problem. Change something.

### Step 4 · Change the picture

Look closely at the first frame. There is already steam, rising from the hot chai, just below her face.

Kling continues what it sees. The steam keeps rising, so it drifts up over her face. If the picture starts the problem, the prompt alone may not stop it.

So fix the picture first. In ChatGPT, edit the picture (Module 4, Lesson 3):

```text
Keep everything exactly the same. Only remove the steam.
```

Then use the new picture as the first frame, with the same prompt, and press **Generate**. **This spends 30 credits.**

What you should see: with the new picture, there is less steam. But a little still drifts up, near the end.

### Step 5 · Take the word out of the prompt

Change one more thing: take the word **steam** out of the prompt. Even "no steam" puts steam in Kling's mind. Say what you want instead: the air stays clear and still.

```text
She slowly lifts the glass of chai and smiles. The camera slowly pushes in. One gentle move only. Subtle, natural motion. Keep her face, hands and clothes the same. The air stays clear and still. No text.
```

Press **Generate**. **This spends 30 credits.**

What you should see: her face stays clear, right to the end. One change at a time: the picture, then the words.

A new picture is free on ChatGPT. A new clip costs credits. So fix the picture before you spend.

## Prompts used

The one-line words fix (did not work):

```text
The steam stays low, just above the glass. No steam over her face.
```

The ChatGPT picture edit:

```text
Keep everything exactly the same. Only remove the steam.
```

The final prompt, with the steam word taken out (worked, with the new picture):

```text
She slowly lifts the glass of chai and smiles. The camera slowly pushes in. One gentle move only. Subtle, natural motion. Keep her face, hands and clothes the same. The air stays clear and still. No text.
```

## Common mistakes

1. **Pressing Generate again and again.** Same prompt, same problem, credits gone.
2. **Changing everything at once.** Then you never learn what fixed it.
3. **Fixing the words, when the problem is in the picture.** Words cannot fix a problem in the picture. Look at the first frame first.

The fix: find the cause, then change one thing.

You can also use the Module 3 checklist, [fix-a-failed-clip.md](../../downloads/fix-a-failed-clip.md), before you spend credits on a retry.

## Try it yourself

1. The video's task: take a clip with one problem. Find the cause, change one thing, and generate again.
2. Rewrite "No people in the background" as what you want to see instead.
3. Your character's hand bent for one moment, and nothing in the words or the picture asked for it. What do you do?

## Recap

- Find the cause first: the words, the picture, or bad luck.
- Fix the words with one clear line. Say what you want to see, not the thing you want gone.
- Try the same prompt once more, at most. And fix the picture before you spend credits.

That is the end of Module 5.

## Next

[M06-L01 · Lip Sync](../../m06-kling-power-features/m06-l01-lip-sync/)

## Answers

1. What good looks like: you answered the three questions, changed only one thing (the words, the picture, or a single retry), and the problem is gone in the new clip.
2. For example: "The background stays empty and softly blurred." Say what you want, so the unwanted thing never enters Kling's mind.
3. Neither the words nor the picture caused it, so it was bad luck. Try the same prompt once more, at most.
