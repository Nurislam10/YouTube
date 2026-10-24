# Car YouTube

A YouTube player page built for car screens (`index.html`).

- Steering wheel buttons work: play/pause, **next / previous**, seek forward/back
  (Media Session API, plus a silent background track so the page itself receives the media keys).
- Large buttons for the touch screen; layout fits landscape (wide) and portrait screens.
- Paste a video or playlist link to add it to the queue. The queue and your position are saved.

## Setup

Turn on GitHub Pages: Settings → Pages → Branch: `main` / root.
Then open `https://<username>.github.io/youtube/` in the car's browser.

## Test mode

Open `.../youtube/?test` and press the steering wheel buttons: a panel shows which
signals the browser receives (Media Session actions or key events).

## Open a playlist directly

`https://nurislam10.github.io/YouTube/?list=<playlist id>` opens that playlist right away
(it continues where it stopped). The playlist must be Public or Unlisted.
