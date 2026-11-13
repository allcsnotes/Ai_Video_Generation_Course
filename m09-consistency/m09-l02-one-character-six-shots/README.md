# M09-L02 · One Character, Six Shots

> Video: Module 9, Lesson 2. Watch it first, then use this page to revise and practise.

Six shots: a wide, a medium, two close-ups, a customer, and a goodbye at dusk. One Meera in all of them: same face, same hair, same earrings, same apron. And it all came from one setup: a **character** in Google Flow.

## What you'll learn

- Why a start picture is not enough for six shots in six places
- What a Flow **character** keeps together: her picture, her full body and her description
- What a **seed** is, and why Flow locks the character instead
- How to build a character (Characters > New character), give her a body, and save her
- How to use her in a shot with **Ingredients** mode, and the prompt pattern
- How to check six shots like a viewer, and why you should pick a voice

## Before you start

- Flow with Omni 1.2 Flash, and a close-up picture of your character in the project (the video uses Meera's ChatGPT close-up).
- The video shows no credit cost for building the character. If Flow shows a cost line, read it before you click.
- Each shot is **360p · 5 s · x1 = 5 credits**. Six shots = **30 credits** in all.

## Follow along

### Why a character?

In the last lesson the fix was a start picture. It works, but it only sets the first frame of one shot. For six shots in six places, Flow has a better tool: **Characters**.

| A character keeps | What it gives the model |
|---|---|
| Her picture | the face |
| Her full body | head to toe |
| Her description | the words |

You build it once, and reuse it in every shot.

Some tools also let you lock a **seed**: a number for the random start. Flow does not show one, so you lock the character instead.

### 1 · Open Characters

In your Flow project, click **Characters** in the left menu. A **New character** page opens.

### 2 · Add her picture

Click **Add from project**, and pick Meera's close-up picture.

### 3 · Name her

Click the **pencil**, and type **Meera**.

### 4 · Character info

Under **Character info**, paste her fixed description: her age, her hair, her earrings, her shirt and her apron (text below).

### 5 · Create body

Her picture only shows her face and chest. So click **Create body**, and describe the outfit (text below).

What you should see: Flow draws her from head to toe, with the same face. Now the model also knows how she looks from far away.

### 6 · Save

Click **Done**. Meera is saved in your project.

### 7 · Use her in a shot

Open the settings, and switch from **Frames** to **Ingredients**. Click the **+**, filter by **Characters**, pick **Meera**, and click **Add to prompt**.

### 8 · Write the shot

The prompt pattern:

| # | Part | Shot 2, the real prompt |
|---|---|---|
| 1 | Shot type + action | Medium shot. Meera pours hot chai from a steel kettle into three small glasses on her stall counter, steam rising. |
| 2 | The same description | Meera: shoulder-length wavy dark hair, small gold hoop earrings, white shirt with rolled sleeves, mustard yellow apron. |
| 3 | Place + light | Warm morning light. No text. |

One small catch: Meera comes **off the prompt after every shot**. So add her again each time.

### 9 · The six shots (5 credits each)

| Shot | Type | What happens |
|---|---|---|
| 1 | Wide | Opens the stall at sunrise |
| 2 | Medium | Pours chai into three glasses |
| 3 | Close-up | Her glass of chai |
| 4 | Customer | Hands chai to a customer |
| 5 | Close-up | Stirs the pot and laughs |
| 6 | Dusk | Waves goodbye |

Morning light, evening light, near and far, and she is still Meera.

### 10 · Check, like a viewer would

Put the faces side by side.

- Hair, earrings, shirt and apron match in all six.
- The face matches too, but in the wide shot she is far away and her face is tiny, so the details are softer: still her, just less sharp.

One surprise: in three shots she spoke on her own. Nobody wrote these words:

| Shot | What she said |
|---|---|
| 3 | "There's nothing quite like a warm cup of chai..." |
| 4 | "Here is your chai!" |
| 6 | "Bye, take care." |

To keep her voice the same in every shot, pick a voice in her character (**Select a voice**). Voices are covered in Module 10.

## Prompts used

Character info (her fixed description):

```text
Meera, 28, runs the Chai Corner stall. Shoulder-length wavy dark hair, small gold hoop earrings, white shirt with rolled sleeves, mustard yellow apron. Warm, friendly, smiles easily.
```

Create body:

```text
Full body, standing, front view. White shirt with rolled sleeves, mustard yellow apron, dark blue jeans, brown sandals. Plain light background.
```

Shot 2 (Ingredients: Meera; 9:16, 360p, 5 s, x1):

```text
Medium shot. Meera pours hot chai from a steel kettle into three small glasses on her stall counter, steam rising. Meera: shoulder-length wavy dark hair, small gold hoop earrings, white shirt with rolled sleeves, mustard yellow apron. Warm morning light. No text.
```

## Common mistakes

1. **Using only a start picture for many shots.** It sets one first frame; a character works in every shot.
2. **Skipping Create body.** Without it, the model does not know how she looks from far away.
3. **Forgetting to add her again.** The character comes off the prompt after every shot.
4. **Writing the description fresh each time.** Paste the same words into every prompt.
5. **No voice in the character.** She may speak on her own, in a different voice each shot.

## Your task

Build your own character, and make three shots of them: a wide shot, a medium shot and a close-up. Is it the same person in all three?

## Next

[M09-L03 · Same Place, Same Look](../m09-l03-same-place-same-look/)
