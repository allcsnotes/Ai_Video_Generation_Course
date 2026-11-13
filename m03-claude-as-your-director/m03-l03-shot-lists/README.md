# M03-L03 · Shot Lists

> Video: Module 3, Lesson 3. Watch it first, then use this page to revise and practise.

Our chai stall Reel now has a script. But a video model cannot make the whole Reel in one go. It makes one short clip at a time, about 5 seconds long.

For our 30 second script, how many clips do we need to make? Five. One clip for each shot. And the list of those shots, in order, is called a **shot list**.

## What you'll learn

- What a shot list is: one table, one row per shot
- The five things to write for every shot
- How long each shot should be, and how to save credits on 6 second shots
- Why you change the shot size from one shot to the next
- How to ask your AI Video Director in Claude for a shot list
- Four checks before you spend any credits

## Key ideas

### A shot list is one table

Each row is one shot. For every shot you write five things: the **number**, the **length** in seconds, the **shot size**, the **camera move**, and **what we see**.

| No. | Length | Shot size | Camera move | What we see |
|---|---|---|---|---|
| 1 | 0–6 s | Extreme close-up | Static, slow push in | A match strikes, a blue flame bursts |
| 2 | 6–12 s | Close-up | Slow tilt down | Ginger and cardamom, crushed |
| 3 | 12–18 s | Medium close-up | Slow motion, tilt up | The high pour, first sunlight |
| 4 | 18–24 s | Medium shot | Slow dolly sideways | The first customers arrive |
| 5 | 24–30 s | Wide shot | Slow pull back | The whole stall glows, a toast |

- 1 row of the shot list = 1 prompt (next lesson) = 1 clip in Kling. The shot list is your to do list for Kling.
- The numbers matter too. Name every clip with its number, like `shot01_flame.mp4`, `shot02_spices.mp4`, `shot03_pour.mp4`, so nothing gets lost when you edit.

Download a blank version with these columns (and the video's five rows as an example): [shot-list-template.csv](../../downloads/shot-list-template.csv).

### How long is each shot?

- On a Reel, most shots last 3 to 6 seconds. Any longer, and people get bored.
- Add them up, and they must fit your length: 6 + 6 + 6 + 6 + 6 = 30 seconds.
- Kling makes clips of 5 or 10 seconds. A 10 second clip costs double the credits.

| Kling clip | Credits |
|---|---|
| 5 s | 30 |
| 10 s | 60 (double) |

So for a 6 second shot, make a 5 second clip, and slow it down a little when you edit. That saves credits. Plan around 5 second clips, and stretch a little in the edit.

### Change the size every shot

The sizes from Module 2, used in order:

| Shot | Size | Short name | Camera |
|---|---|---|---|
| 1 | Extreme close-up | ECU | Static, slow push in |
| 2 | Close-up | CU | Slow tilt down |
| 3 | Medium close-up | MCU | Slow tilt up |
| 4 | Medium shot | MS | Slow dolly sideways |
| 5 | Wide shot | WS | Slow pull back |

- From close to wide: the world gets bigger as the story grows.
- Two shots of the same size in a row can look like a mistake. A new size feels like a new moment.
- Give every shot just one slow camera move: one push in, one tilt, or one pull back.

### Check it before you spend credits

Four checks:

1. **One action per shot.** One thing happens.
2. **One camera move per shot.** Slow and simple.
3. **The size changes** from shot to shot.
4. **The lengths add up** to your total: 6 + 6 + 6 + 6 + 6 = 30 s.

Then count the cost: 5 clips × 30 credits = 150 credits. That is more than two months of free credits (the free plan gives 66 a month, and they expire after a month). Check the credits in your own account, and plan before you generate.

## Worked example

Asking the AI Video Director in Claude, in the same chai stall chat:

1. Open the chai stall chat in your AI Video Director project.
2. Pick a hook and ask for the shot list in one table, then press Enter:

```text
I pick Hook 1. Turn the 30-second script into a numbered shot list. For each shot give the shot number, length in seconds, shot size, camera move and what we see. Make it one table. No prompts yet.
```

What came back:

- One clean table: 5 shots × 6 seconds = 30 seconds.
- Shot 1 is the hook: an extreme close-up, almost black, then a match strikes and a blue flame bursts under the big dented kettle.
- The size column goes ECU, CU, MCU, MS, WS: close to wide, as planned.
- The camera column gives one slow move per shot: push in, tilt, tilt, dolly, pull back.
- A tip: keep shot 1 dark for the first second (the flame bursts at about the 1 second mark). Next, Claude can write the prompts.

## Common mistakes

| Mistake | Bad | Better |
|---|---|---|
| Too much in one shot | Shot 2: crush the spices, pour the chai, serve customers | 3 shots: crush · pour · serve |
| Every shot the same size | MS · MS · MS · MS · MS (feels flat) | ECU · CU · MCU · MS · WS |
| Shots too long | 10 s of the same cup · 60 credits | 5 s, slowed a little · 30 credits |

One action, a new size, and short shots.

## Try it yourself

1. The video's task: turn your own 30 second script into a shot list with Claude, and run the four checks. Still no credits needed.
2. Fix this shot list: shot 1 MS, shot 2 MS, shot 3 MS, each "he cooks, serves and waves", 10 seconds each.
3. You need a 6 second shot. Which Kling clip length do you make, and how many credits does it cost?

## Next

[M03-L04 · The Prompt Formula](../m03-l04-the-prompt-formula/)

## Answers

1. What good looks like: a table with No., Length, Shot size, Camera move and What we see; each row passes all four checks; the lengths add up to 30 s.
2. Split each "cooks, serves and waves" into separate shots (one action each), change the sizes (for example CU, MS, WS), and make each shot 3 to 6 seconds with one slow move.
3. A 5 second clip (30 credits), slowed down a little in the edit.
