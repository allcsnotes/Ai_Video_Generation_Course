# Fix a failed clip: checklist

From the AI Video Creation course, Module 3, Lesson 5 (Fixing Failed Clips). Use it every time a clip comes back wrong, before you spend more credits.

## 1. Read the failed prompt like a director

Tick every problem you find.

- [ ] **Too many actions.** One 5 second clip holds one action, not five.
- [ ] **A fast or spinning camera.** The model invents a new angle every frame, so things melt and change.
- [ ] **Too many people.** Every extra face and hand is one more thing that can break.
- [ ] **Hype words** (beautiful, cinematic, amazing, 4K). They show the model nothing. 4K is an export setting.
- [ ] **No character description.** The person can look different in every clip.

The fix in one line: one action, a slow camera, few people, real details, the same character.

## 2. Image prompt or video prompt?

- An **image prompt** is one frozen moment: who is there, where, what light, which style. Nothing moves, no sound.
- A **video prompt** is what happens over time: what moves, how the camera moves, what we hear.
- If you start from an image, the image already shows the face, the place and the light. The video prompt only needs the motion.

## 3. Ask Claude to fix it

In your AI Video Director chat, paste:

1. the prompt you used,
2. the tool and length (for example Kling 4.0 Flash, 5 seconds, 9:16),
3. what went wrong, in plain words,
4. and ask for a rewrite for one shot.

If Claude gives a negative prompt (a list of things you do not want), paste it only if your tool has a box for it.

## 4. Common failures, first fix

| What went wrong | Try this first | Fix type |
|---|---|---|
| Warped hands, extra fingers | One simple job for the hands, slow motion | Change prompt |
| A face that changes | Same character words, or start from an image | Change image |
| A wild camera | One slow move, or a still camera | Change prompt |
| Messy letters | Write "no text", add text in the edit | Change prompt |
| Nothing moves | A clear action and a camera move | Change prompt |
| Right idea, one small glitch | Just generate again | Generate again |

## 5. Before you press Generate again

- [ ] Failed twice with the same prompt? Change the prompt. Do not reroll a third time.
- [ ] Change **one thing** per try, so you know what fixed it.
- [ ] Check the credit cost (in the video: 30 credits for a 5 second Kling 4.0 Flash clip; check the current cost).
- [ ] Save the prompt that worked in your project, next to the clip.
