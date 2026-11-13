# M05-L04 · Start and End Frames

> Video: Module 5, Lesson 4. Watch it first, then use this page to revise and practise.

Two pictures of Meera. In the first, she pours the chai. In the last, she laughs with the glass. Give Kling both pictures, and it makes the movement in between. The clip starts exactly on one, and ends exactly on the other.

## What you'll learn

- Why Keyframes gives you more control than Omni reference
- Which model you need for an end frame, and what it costs
- How to add a first frame and a last frame, and why they must match
- How to prompt only the change between the two pictures
- How to check both ends and the whole middle of the clip
- Three start and end frame mistakes

## Before you start

- **Account:** your free Kling account.
- **Two pictures** of your character that match: same person, same clothes, same place, same light. The video uses Meera pouring chai (first frame) and Meera laughing with the glass (last frame), both made in the same ChatGPT chat as her character sheet in M04-L04.
- **Cost:** this lesson spends credits once, and more than before. An end frame needs **Kling 4.0**, which costs **50 credits** for 5 seconds, not 30. On the free plan (66 credits a month) that is most of your month. In the video, the balance went from 552 to 502.
- Prices change: read the number on the Generate button before you press it.

### Why use two frames?

| | Omni reference (last lesson) | Keyframes (this lesson) |
|---|---|---|
| Your picture is | a guide | the exact frame |
| First frame | close, not exact | exactly your first picture |
| Last frame | Kling decides | exactly your last picture |

So you choose where the shot begins, and where it ends. Kling only fills the middle.

## Follow along

### Step 1 · Pick Keyframes

In the prompt box, click **Omni reference**, and pick **Keyframes**.

What you should see with **Kling 4.0 Flash**: only one box, **First frame**. Flash cannot take an end frame.

### Step 2 · Switch the model to Kling 4.0

Open the model menu. This time, the model you want is **Kling 4.0**.

What you should see: a second box appears, **Last frame**. Look at the button: Kling 4.0 costs **50 credits**, not 30.

### Step 3 · Add your two pictures

1. Click **First frame**, pick **Upload**, and choose the pouring picture.
2. Click **Last frame**, and choose the laughing picture.

The two pictures must match: same woman, same clothes, same place, same light. Make them in the same ChatGPT chat, like the character sheet in Module 4.

### Step 4 · Prompt the change

Kling already sees both pictures, so describe only what happens between them:

- **Action:** she finishes pouring and puts the kettle down. Then she lifts the glass and laughs.
- **Camera:** the last picture is a close-up, so the camera slowly pushes in from a medium shot to a close-up.
- **Protect her:** keep her face, hair and clothes the same. No text.

The full prompt is in "Prompts used" below.

### Step 5 · Settings, then Generate

Open the settings.

- The ratio says **Adaptive**. Kling uses the shape of your pictures, so the clip stays 9:16.
- Keep **5 seconds** and **one output**. The button says **50 credits**.

Press **Generate** once. **This spends 50 credits.** Kling warns that the end frame takes more time, so this one waits a little longer. When it is done, the balance went from 552 to 502.

Click path: `Generate > Video Generation > Kling 4.0 > Keyframes > First frame + Last frame > 720p · 5 s · Adaptive > Generate`

### Step 6 · Check the ends, then the whole clip

| Check | The video's clip |
|---|---|
| First frame | Exactly the pouring picture |
| Last frame | Exactly the laughing picture |
| The middle | She puts the kettle down, lifts the glass, and the camera moves in. The same woman all the way |
| Anything you did not ask for? | Near the end, the steam drifts across her face for a moment |

So watch the whole clip, not only the ends.

Omni reference was close, but not exact. Keyframes is exact at both ends. That control costs 20 more credits.

## Prompts used

```text
She finishes pouring and puts the kettle down. Then she lifts the glass of chai and laughs warmly. The camera slowly pushes in from a medium shot to a close-up. Keep her face, hair and clothes the same. Smooth, natural motion. No text.
```

The pattern:

```text
[What happens between the two pictures, in order]. The camera [move] from [first shot size] to [last shot size]. Keep [her / his] face, hair and clothes the same. Smooth, natural motion. No text.
```

## Common mistakes

1. **Two pictures that do not match.** A different face or a different place, and Kling has to morph one into the other. It looks strange.
2. **Too big a jump.** From the street outside to a close-up in 5 seconds is too much. Keep the two pictures close.
3. **The wrong model.** Flash has no Last frame box. Check that it says Kling 4.0, and 50 credits, before you press Generate.

The fix: two matching pictures, a small change, and Kling 4.0.

## Try it yourself

1. The video's task: make a start picture and an end picture of your character, and turn them into one 5 second shot with Keyframes.
2. Before you spend 50 credits, put your two pictures side by side. Same face, clothes, place and light?
3. Is "she stands outside the stall" to "a close-up of her laughing" a good pair for 5 seconds?

## Recap

- Keyframes locks the exact first frame and the exact last frame. Kling fills the middle.
- Pick Keyframes and Kling 4.0, then add your two pictures. Make them in the same chat so they match.
- In the prompt, describe what happens between them, and the camera move.

## Next

[M05-L05 · Camera Control and Motion Strength](../m05-l05-camera-control-and-motion-strength/)

## Answers

1. What good looks like: one 5 second clip for 50 credits whose first frame is exactly your start picture and whose last frame is exactly your end picture, with a smooth middle and the same person all the way. Watch it all for small surprises, like the steam across Meera's face.
2. If any of the four differ, fix the picture in ChatGPT first. Pictures are cheap to fix; 50 credits are not.
3. No. That is too big a jump for 5 seconds. Keep the two pictures close.
