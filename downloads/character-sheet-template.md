# Character Sheet Template

From Module 4, Lesson 4 of the AI Video Creation course. One prompt used twice gives you two different people. A character sheet gives you one.

A **character sheet** is one picture that shows one character many times: three angles and three expressions. Every view is made together, so it is the same person in every view. For every new shot, you point ChatGPT to the sheet and say: use this exact person.

## 1. Write the full description (once, then never change it)

Copy this exact text into every prompt. Change one word (wavy to curly) and you get a new person.

| Part | Your character | The video's example (Meera) |
|---|---|---|
| Name | | Meera |
| Age | | 28-year-old |
| Who | | Indian woman |
| Hair | | shoulder-length wavy black hair |
| Eyes | | warm brown eyes |
| Jewellery or detail | | small gold hoop earrings |
| Clothes | | a white shirt and a mustard-yellow apron |

Your description, in one line:

```text
[Name]: a [age] [who] with [hair], [eyes], [jewellery or detail], [clothes].
```

## 2. The sheet prompt (four parts)

1. Describe the character in full.
2. List the views: top row angles, bottom row expressions.
3. One plain white background, and the same face, hair and clothes in every view.
4. The shape and no words: wide 16:9, no text, no labels.

```text
Create a character sheet for one character. [Your full description]. Show [her / him] six times on one plain white background. Top row: front view, three-quarter view, side view. Bottom row: a big smile, surprised, thinking. Same face, same hair and same clothes in every view. Soft, even studio light. Photorealistic, wide 16:9, no text, no labels.
```

The video's version:

```text
Create a character sheet for one character. Meera: a 28-year-old Indian woman with shoulder-length wavy black hair, warm brown eyes, small gold hoop earrings, a white shirt and a mustard-yellow apron. Show her six times on one plain white background. Top row: front view, three-quarter view, side view. Bottom row: a big smile, surprised, thinking. Same face, same hair and same clothes in every view. Soft, even studio light. Photorealistic, wide 16:9, no text, no labels.
```

## 3. Check the sheet

- [ ] Six big views (not twelve tiny ones).
- [ ] Top row: front, three-quarter, side. Bottom row: smile, surprised, thinking.
- [ ] Plain white background, no props.
- [ ] Same face, hair, jewellery and clothes in every view.
- [ ] No text and no labels.

## 4. Use the sheet for a new shot (same chat)

```text
Now use this exact [Name] from the sheet. Show [her / him] [the new shot]. Keep [her / his] face, hair, [jewellery or detail] and [clothes] exactly the same as in the sheet. [light], plain softly blurred background. [shot], vertical 9:16, no text.
```

The video's version:

```text
Now use this exact Meera from the sheet. Show her behind a small chai counter, pouring chai from a steel kettle into a glass. Keep her face, hair, earrings and apron exactly the same as in the sheet. Warm morning light, plain softly blurred background. Medium shot, vertical 9:16, no text.
```

## 5. Check every new shot against the sheet

| Shot | Face | Hair | Jewellery or detail | Clothes | The detail I asked for | Keep? |
|---|---|---|---|---|---|---|
| 1 | | | | | | |
| 2 | | | | | | |
| 3 | | | | | | |

Small details can change (in the video, the glass went to Meera's lips, not near her chin). Always check each shot.

## The three mistakes

- Changing the description between prompts.
- A busy background: props and colours pull the eye away from the face.
- Too many tiny views: six big views are easier to copy.
