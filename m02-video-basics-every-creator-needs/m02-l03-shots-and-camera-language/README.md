# M02-L03 · Shots and Camera Language

> Video: Module 2, Lesson 3. Watch it first, then use this page to revise and practise.

One woman, holding a sign in her chai shop. Show her from far away, and it feels calm. Show her face up close, and it feels personal. Same person, same moment. Only the camera changed.

If you type "close-up" or "slow pan" into a prompt, does the AI understand it? Yes. Video models learned from millions of real videos and their descriptions, so camera words work like buttons.

## What you'll learn

- The four shot sizes: wide, medium, close-up, extreme close-up
- Five camera moves: pan, tilt, dolly, orbit and handheld
- The feeling each move gives, and why a static shot is safest
- The order to write camera words in a prompt
- Three camera mistakes

## Key ideas

### Shot size: how much fits in the frame

| Shot size | What it shows | What it does |
|---|---|---|
| Wide | The whole place; the person is small | Tells you where we are |
| Medium | The person from the waist up | The everyday shot for talking |
| Close-up | The face fills the frame | Shows feeling |
| Extreme close-up | One small detail, like the steam on the chai | Draws the eye to one thing |

### Camera moves: each has a name

| Move | What the camera does | Like |
|---|---|---|
| Pan | Turns left or right | Turning your head |
| Tilt | Turns up or down | Looking from the floor to the sky |
| Dolly | Moves the whole camera forward or back: push in to get closer, pull out to show more | Walking toward or away |
| Orbit | Circles around the subject | Walking around a table |
| Handheld | Adds a small, natural shake | A phone in your hand |

### Every move gives a feeling

| Move | Feeling |
|---|---|
| Push in (slowly, closer and closer) | Builds focus and emotion |
| Pan | Reveals a place, bit by bit |
| Orbit | Makes a product, or a hero, look important |
| Handheld | Feels real, like someone is there, filming |
| Static (no camera move) | Feels calm, and is the easiest for AI to get right |

A static shot is the safest choice for beginners.

### Write it in the prompt

Put the **shot size** first, then the **subject**, then the **camera move**.

| 1 · Shot size | 2 · Subject | 3 · Camera move |
|---|---|---|
| close-up | a clay cup of chai, steam rising | slow push in |

```text
close-up of a clay cup of chai, steam rising, slow push in
```

Use one move per shot. Ask for a pan, a tilt and an orbit together, and the AI gets confused.

## Worked example

The opening prompt of the video asks two questions at once:

```text
a woman holds a sign in her chai shop, close-up, slow pan
```

The AI understands both camera words. But following the lesson, a cleaner version puts the size first and keeps one move:

```text
close-up of a woman holding a sign in her chai shop, slow push in
```

The same woman as a wide view would feel calm and show the whole shop; as a close-up it feels personal.

## Common mistakes

- **No camera words at all.** The AI picks a random move. Always name the shot and the move.
- **Too many moves in one 5 second clip.** Pick one.
- **Fast moves.** Quick spins and fast zooms often warp the picture. Slow is safer.

Safe default: one slow move per shot.

## Try it yourself

1. The video's task: watch any movie scene, and name each shot and each camera move you see.
2. Write a prompt for an extreme close-up of a match being struck, with no camera move.
3. Which move would you use to make a new phone look important? Write the full prompt in the right order.

## Next

[M02-L04 · Light, Mood and Style](../m02-l04-light-mood-and-style/)

## Answers

1. What good looks like: a list such as "wide, static · medium, pan · close-up, slow push in", one line per shot.
2. One possible answer: `extreme close-up of a match head striking into a flame, static camera`.
3. An orbit. For example: `close-up of a new phone on a white table, slow orbit`.
