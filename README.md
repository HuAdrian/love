# Flight to Nine

An IELTS practice game. Open `index.html` in a browser; there is nothing to install or build.

Every question arrives as a row of gates in the sky, one gate per answer. Steer your plane into the
right one before it reaches you. Lock in early for more points, and chain right answers to build a
multiplier and speed.

## Modes

- **Full flight.** Six legs of five gates in IELTS order, ending in a band score. Your destination
  sets the speed and the band you need to land there: Dublin 5.5, Toronto 6.5, Sydney 7.0, London 7.5.
- **Endless jetstream.** Gates from every skill, faster and faster, until you lose three shields.
- **Training.** Ten gates of one skill.

| Leg | Skill | Gates |
| --- | --- | --- |
| 1 | Listening | Hear a caller and pick the detail they gave. The wrong gates are real IELTS traps |
| 2 | Reading | True, False or Not Given |
| 3 | Vocabulary | The academic paraphrase of an everyday word |
| 4 | Writing Task 1 | The graph a trend sentence describes |
| 5 | Writing Task 2 | The one marked word that is wrong |
| 6 | Cohesion | The linking word that fits the gap |

## Controls

- **Steer:** ← → or A D, the number keys, a swipe, or a tap on a gate or an answer card.
- **Lock in early:** Space, Enter or ↑, a swipe up, or a second tap on your card.
- **Pause:** Esc or P.

"Gates wait for me" on the boarding pass stops each gate short of the plane until you lock in.

## Scoring and rewards

A right answer is worth 100 points plus up to 200 for locking in early. Every three in a row raises
the multiplier, up to ×5. Right answers also release a trail of air-mile coins to steer through.
Air miles raise your pilot rank, and there are nine passport stamps to collect. Questions you get
wrong come back later as retakes.

The band uses the IELTS Listening raw-score table, scaled from 40 questions to 30. It is a game
score, not a prediction of a real result. Progress is kept in the browser's local storage.

## Sound

The Listening leg plays 56 recorded lines embedded in `index.html`, so it needs no network and no
speech engine on the device. They were synthesised with the Piper voice `en_GB-cori-medium`, which
was trained on public-domain LibriVox recordings.
