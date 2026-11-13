# M13-L01 · Build 5: A One-Minute Short Film

> Video: Module 13, Build 5. Watch it first, then use this page to revise and practise.

Build 5 is a **one-minute short film** with two characters who speak. It is called **The Last Glass**: eight shots made in **Google Flow**, two characters with their own saved voices, and one edit in **Shotcut**.

## What you'll build

- A 55-second film in full HD (1080p, 24 fps), 16:9
- Two characters, **Meera** and **Ravi**, who look and sound the same in every shot
- Eight shots with six spoken lines, made with Flow's Omni model using ingredients
- Soft music under the voices, a title on the first shot, and a fade to black at the end

## Before you start

- **Google Flow** with a paid plan and enough credits (Module 7), and the **Meera** character from Module 9.
- A picture of the **Chai Corner stall**, used as an ingredient so the place stays the same.
- A soft music track you are allowed to use (Module 10).
- **Shotcut** installed (free).
- **Credits:** at 720p, Flow costs **about 3 credits for each second**. All eight shots cost **165 credits**. Fixing two shots cost **39 more credits** in the video. Ravi's portrait is **free**. Prices and plans change: check the current price before you buy.
- Plan it with the [build plan template](../../downloads/build-plan-template.md).

## Plan

### A tiny story in three beats

Every short film starts with a tiny story.

1. **Beat 1:** after sunset, Meera is closing her chai stall. Ravi, her oldest customer, arrives late, and asks for one last glass.
2. **Beat 2:** she pours it. He says his wife made chai just like this. And Meera says: "I know. She taught me this recipe."
3. **Beat 3:** they part with a promise: "Same time tomorrow."

### The shot list

Eight shots, each six to ten seconds long, about 55 seconds in all.

| Shot | Length | What happens | Line |
|---|---|---|---|
| 1 | 7 s | Meera closes up | (no line) |
| 2 | 6 s | Ravi arrives | Ravi: "Am I too late for chai?" |
| 3 | 6 s | One last glass | Meera: "For you? Never. One last glass." |
| 4 | 6 s | The pour | (no line) |
| 5 | 8 s | Ravi takes the glass | Ravi: "My wife made chai just like this." |
| 6 | 6 s | She taught me | Meera: "I know. She taught me this recipe." |
| 7 | 6 s | He sips | (no line) |
| 8 | 10 s | Same time tomorrow | Ravi: "Same time tomorrow?" Meera: "Same time tomorrow." |

## Build it step by step

### Step 1 · The cast, in Flow Characters

**Meera gets a saved voice**

1. In Flow, open **Characters**. Meera is already here from Module 9. This time, we give her a voice of her own.
2. Click **Select a voice**, and pick one close to her. In **Customize performance**, describe how she speaks: warm and kind, calm and gentle.
3. Name it **Meera voice**, click **Save new voice**, then **Add to character**. Now every shot with Meera uses the same voice.

**A new character: Ravi**

4. Click **New character** and describe Ravi in a few lines: about 70, grey hair, round glasses, and a brown wool shawl. Flow makes his portrait for **free**.
5. Add his **Character info**. Then click **Create body**, and describe him standing, with his walking stick.
6. Give Ravi a saved voice too: an old man, slow, soft and kind. Now the cast has two characters, each with a face and a voice.

### Step 2 · The shots, in Flow

1. In the settings, choose **Video**, **Ingredients**, **16:9**, and **720p**. Then drag **Length** to fit the shot: **7 seconds** for the first one.
2. Click the **+** button, filter by **Characters**, pick **Meera**, and click **Add to prompt**. The stall picture is a second ingredient, so the place stays the same.
3. Every prompt follows one pattern: **the shot number and its framing › the time and the place › the action › the look › the sound**.
4. When someone speaks, write the word **says**, and put the exact words **in quotes**. Flow speaks them in that character's saved voice.
5. Shot 5 has **three ingredients**: Meera, Ravi, and the stall. Two people can share one shot.
6. Generate the shots one at a time. Download each one in **720p**, and put its number in the file name (`1 wide.mp4` to `8 end.mp4`), so the order is clear.

### Step 3 · Check every shot before the edit

Play all eight shots, one by one, with the sound on. Check four things.

| Check | What the video found |
|---|---|
| 1 · Words | Play each line and listen to every word. All six lines came out exactly as written. |
| 2 · Voices | Ravi always sounds like Ravi (a low voice), and Meera always sounds like Meera (a higher voice), because each one has a saved voice. |
| 3 · Faces | Put the shots side by side: the same Meera, the same Ravi, and the same clothes in every shot. |
| 4 · Light | A problem: shots 1 and 2 looked like late afternoon, but the rest were after sunset. |

**The fix:** change the prompt: after sunset, the sky is dark blue, and the string lights glow brightly. Make both shots again (**39 more credits**). Now every shot is in the evening, with the string lights on, so the cuts feel like one scene.

### Step 4 · Edit in Shotcut

1. New project called **The Last Glass**, video mode **HD 1080p 24 fps**.
2. Open each shot, and press **A** to add it to the timeline. All eight shots, in order, make **55 seconds**.
3. **Keep the sound of these clips** this time. The dialogue lives inside them.
4. Add an audio track, and add soft music. Set its **Gain** to **-18 dB**, so it sits quietly under the voices.
5. Add **Fade In Audio** for **1 second**, and **Fade Out Audio** for **3 seconds**. (After you add a fade, check that its box is ticked.)
6. On the first shot, add the **Text: Simple** filter, with the title **The Last Glass**, in the lower third.
7. On the last shot, add **Fade Out Video**, so the film ends on black.
8. Open **Export**, choose the **YouTube** preset, and click **Export Video/Audio**. The film is 55 seconds long, in full HD.

## Prompts used

Ravi, new character (Flow Characters, the portrait is free):

```text
Ravi, a kind retired school teacher, about 70, Indian. Short grey hair, neat grey moustache, round wire glasses, beige cotton kurta under a brown wool shawl. Gentle eyes, slow smile. Realistic photo portrait, soft warm evening light, plain background.
```

Ravi, Character info:

```text
Ravi, about 70, a retired school teacher and Meera's oldest customer. Short grey hair, grey moustache, round wire glasses, beige kurta, brown wool shawl. Gentle, slow, a little shy.
```

Ravi, Create body:

```text
Full body, standing. Beige cotton kurta and loose white pyjama trousers, brown wool shawl over his shoulders, brown leather sandals. Holds a wooden walking stick. Plain background.
```

Shot 1 (first version, 7 s; ingredients: Meera + the stall). This one came out too bright:

```text
Shot 1, wide. Evening at dusk. Meera stands alone behind the counter of her Chai Corner stall and slowly wipes the counter with a cloth. Warm string lights glow over the stall. The street is almost empty. The camera is still. Look: realistic film, soft warm light. Sound: a quiet evening street, a few birds. She does not speak. No music. No captions.
```

Shot 1 (fixed version, 7 s):

```text
Shot 1, wide. After sunset: the sky is dark blue and the street is in shadow. Warm string lights are switched on over the Chai Corner stall and glow brightly. Meera stands alone behind the counter and slowly wipes it with a cloth. The street is almost empty. The camera is still. Look: realistic film, warm string light on her face, the same evening light in every shot. Sound: a quiet evening street, a few birds. She does not speak. No music. No captions.
```

Shot 2 (6 s; ingredients: Ravi + the stall):

```text
Shot 2, medium. Evening at dusk at the Chai Corner stall, warm string lights. Ravi walks slowly into the frame from the left with his walking stick and stops at the counter, a little out of breath. He smiles shyly and says: "Am I too late for chai?" The camera is still. Look: realistic film, soft warm light. Sound: a quiet evening street, his stick taps the ground. No music. No captions.
```

Shot 5 (8 s; three ingredients: Meera, Ravi + the stall):

```text
Shot 5, medium two-shot from the side. Evening at dusk at the Chai Corner stall, warm string lights. Meera stands behind the counter on the right and hands a small glass of chai across to Ravi on the left. He takes it with both hands, looks at it, and says quietly: "My wife made chai just like this." Meera listens and smiles. The camera is still. Look: realistic film, soft warm light. Sound: a quiet evening street. Only Ravi speaks. No music. No captions.
```

Shot 8 (10 s; ingredients: Ravi, Meera + the stall):

```text
Shot 8, wide two-shot. Evening at dusk at the Chai Corner stall, warm string lights glow over them. Ravi stands at the counter on the left holding his glass, Meera stands behind the counter on the right. Ravi raises his glass a little and asks: "Same time tomorrow?" Meera smiles and answers: "Same time tomorrow." They both laugh softly. The camera slowly pulls back. Look: realistic film, soft warm light. Sound: a quiet evening street. No music. No captions.
```

Settings for every shot: `Video · Ingredients · 16:9 · 720p · Length to fit the shot · x1`.

## Check your work

- [ ] Every one of the six lines is spoken word for word
- [ ] Each character has the same voice in every shot
- [ ] The same faces and clothes in every shot
- [ ] Every shot has the same time of day (after sunset, string lights on)
- [ ] Clip sound kept (the dialogue), music at -18 dB under it, 1 s fade in, 3 s fade out
- [ ] Title on shot 1 in the lower third, the film ends on black
- [ ] The file is 55 seconds, full HD (1080p, 24 fps)

## Common mistakes

- **No saved voice.** Without one, a character can sound different in every shot.
- **Dialogue not in quotes after says.** Flow may change the words or give them to the wrong person.
- **Different light between shots.** One bright shot breaks the scene. Write the same time of day in every prompt, and fix the shot before you edit.
- **Muting the clips.** In this film the dialogue lives inside the clips. Keep their sound.
- **Music too loud.** -18 dB keeps it quietly under the voices.
- **A fade that is added but not switched on.** Check the box after adding a fade filter.

## Your task

Make your own 30-second scene, with two characters and one line each: a saved voice each, then check all four.

What good looks like: a tiny story in beats, a shot list with lengths, two characters each with a face and a saved voice, lines in quotes after says, and shots that pass words, voices, faces and light.

## Recap

1. A short film starts with a tiny story in three beats, and a list of shots.
2. Give every character a face and a saved voice, in Flow Characters.
3. Add the characters as ingredients, and write each line in quotes, after says.
4. Check the words, the voices, the faces and the light, and fix a shot before you edit.

## Next

[M13-L02 · Build 6: A Music Video on the Beat](../m13-l02-build-6-a-music-video-on-the-beat/)
