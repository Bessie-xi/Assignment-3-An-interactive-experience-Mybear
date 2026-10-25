# MyBear

MyBear is an interactive 3D teddy bear website for people who enjoy cute characters and a little horror. The bear responds to your touch with movements, words, and sounds.

## Play Online

[\[https://bessie-xi.github.io/Assignment-3-An-interactive-experience-Mybear/\]](https://bessie-xi.github.io/Assignment-3-An-interactive-experience-Mybear/)

## How to Play

- Click the bear’s head, ears, nose, belly, hands, or legs to see different movements and messages.
- Click and drag the bear to rotate it.
- Click the bear 5 times within 2 seconds, and it will cry, shake, and ask you to be gentle.
- Choose **Yes**, and it will smile and thank you. Clicking too much again will trigger a scary surprise.
- Choose **No**, and the scary surprise appears right away.
- If you keep clicking too much after the surprise, the bear gets angry and leaves.
- Refresh the page to start again. Use the music button in the bottom-right corner to turn sound on or off.

**This experience includes a brief scary image and fast shaking.**

## Run Locally

Install Node.js and connect to the internet. Open a terminal in the project folder and run:

```bash
npx --yes http-server . -p 8080
```

Then open this address in your browser:

```text
http://localhost:8080
```

## Tools Used

- HTML, CSS, and JavaScript
- Google `model-viewer`, loaded from a CDN, to show the 3D bear
- Web Audio API for touch sounds and the bear’s voice
- An MP3 file for the piano background music

## Known Limits

- Sound starts after your first click.
- Refreshing the page resets the story.
- An internet connection is needed to load `model-viewer`.
- On small screens, the speech bubble may cover part of the bear.

## Screenshot

![MyBear screenshot](./assets/screenshot.png)

## Demo Video

[Watch the demo video](./assets/video.mp4)

## Credits

- Bear model: [Add the creator, source link, and license]
- Plaid background: [Add the source and license]
- Scary image: Made with OpenAI’s image generation tool.
- Piano music: Generated with Runway.
- See [PROCESS.md](./PROCESS.md) for how AI helped with the project.
