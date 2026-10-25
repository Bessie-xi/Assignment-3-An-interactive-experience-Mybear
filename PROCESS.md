# Development Process

## Starting Idea

I wanted to make a website with a 3D teddy bear that users could rotate and touch. At first, I considered a dress-up feature, but I decided to focus on touch interactions instead.

## Working with AI Step by Step

I used Codex to help check the model, write code, and fix problems. I added one feature at a time, tested it, and gave more specific feedback.

1. **Simplify the page:** Remove the fabric panel, put the bear in the centre, and keep rotation without zooming or moving it sideways.
2. **Make the bear feel alive:** Add blinking, gentle movement, and breathing.
3. **Add touch reactions:** Give each body part a different animation. The arm movement looked too stretched, so I asked AI to reduce it but keep the quick lift and slow return.
4. **Add dialogue:** Replace page instructions with a pixel speech bubble. Give each body part three messages and show the text one character at a time.
5. **Adjust the sound:** Add piano music, touch sounds, and a quiet talking sound. After testing, I lowered the music, raised the talking sound, and removed the “NO” voice.

I learned to give clear instructions about speed, size, timing, and click counts instead of only saying “make it more natural.”

## How the Idea Changed

The bear started as a cute toy. Later, I wanted it to react when users treated it roughly.

The first version showed a scary image after rapid clicking. This felt repetitive, so I changed it into a short story:

- The first time, the bear cries and asks the user to be gentle.
- Choosing **Yes** gives the user another chance. Choosing **No** triggers the scary image.
- If the user keeps clicking roughly after the surprise, the bear gets angry, fades away, and ends the interaction.

This gives the user’s actions a clear consequence.

## Testing and Changes

I tested the website many times and asked a friend to try it.

During my friend’s test, the bear said the scary picture was not ready. This was a loading message, not something the character should say, so I removed it.

In my own tests, the crying scene did not move on to the choices. I asked AI to show the Yes / No buttons separately at the bottom of the screen. I also removed the raised-arm movement from the crying scene.

The hover-to-front feature also caused problems. Automatic rotation and the camera reset interrupted each other. I gave AI the full code to help combine the controls and remove conflicting logic.

## Suggestions I Kept or Changed

I kept the pixel speech bubble, body-part dialogue, and sound button because they made the feedback clearer.

I dropped the “I feel dizzy” reaction during fast dragging because it did not work reliably. I also left out dress-up features so I could improve the existing interactions.

## Tools and My Role

- **Codex:** Helped write and organise code, create model animations, explain code, and fix problems.
- **OpenAI image generation:** Made the scary bear image. I asked for darker lighting, a tilted head, hollow eyes, and a wider smile.
- **Runway:** Generated the piano music and the “NO” voice, which I later removed.
- **My role:** I chose the idea and assets, wrote the dialogue, tested the experience, and decided what to keep, change, or remove.

The project developed through repeated testing and small changes, rather than one AI-generated result.
