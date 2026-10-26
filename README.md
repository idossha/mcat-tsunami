# Tsunami: an MCAT Anki deck

Tsunami is one MCAT Anki deck built from the two most-used free community decks, with every card checked for errors
and restyled to one consistent layout. **3,988 notes, 4,485 cards** covering biochemistry, biology, general and
organic chemistry, physics and math, and psychology/sociology.

**Download:** [`tsunami.apkg`](https://github.com/idossha/mcat-tsunami/releases/latest/download/tsunami.apkg) (326 MB, includes the images). In Anki: File › Import, then pick the
file. Cards import as new, with no review history.

## What's inside

| Subdeck | Cards | From |
|---|---:|---|
| Biochemistry | 512 | MileDown |
| Biology | 601 | MileDown |
| Essential Equations | 91 | MileDown |
| General Chemistry | 248 | MileDown |
| Organic Chemistry | 283 | MileDown |
| Physics and Math | 305 | MileDown (301 notes), Tsunami (2 notes) |
| Psych-Soc › Sensation and Perception (6A) | 298 | MrPankow (204 notes), MileDown (28 notes), Bouras (17 notes) |
| Psych-Soc › Cognition and Consciousness (6B) | 496 | MrPankow (325 notes), MileDown (27 notes), Bouras (23 notes), Tsunami (2 notes) |
| Psych-Soc › Emotion and Stress (6C) | 123 | MrPankow (64 notes), MileDown (18 notes), Bouras (11 notes) |
| Psych-Soc › Brain, Personality and Disorders (7A) | 619 | MrPankow (375 notes), MileDown (48 notes), Bouras (29 notes) |
| Psych-Soc › Social Influence (7B) | 101 | MrPankow (66 notes), MileDown (3 notes), Bouras (2 notes) |
| Psych-Soc › Learning and Attitude Change (7C) | 129 | MrPankow (79 notes), Bouras (7 notes) |
| Psych-Soc › Identity and Social Perception (8A–8B) | 179 | MrPankow (113 notes), MileDown (9 notes), Bouras (5 notes) |
| Psych-Soc › Social Interactions (8C) | 149 | Bouras (121 notes), MileDown (28 notes) |
| Psych-Soc › Social Structure and Culture (9A) | 116 | Bouras (98 notes), MileDown (18 notes) |
| Psych-Soc › Demographics and Inequality (9B–10A) | 128 | Bouras (106 notes), MileDown (21 notes) |
| Psych-Soc › Research Methods and Statistics | 107 | Bouras (104 notes), MrPankow (2 notes) |

The psych/soc subdecks are named by topic. The AAMC content category of each is in brackets, and every psych/soc card also
carries it as the tag `Tsunami::Psych_Soc::<category>`.

## How it was made

- **Sources.** The sciences come from [MileDown's MCAT deck](https://www.reddit.com/r/Mcat/comments/cckw41/my_anki_deck/)
  (2019). Psych/soc comes from [MrPankow's P/S deck](https://www.reddit.com/r/Mcat/comments/insg2k/mrpankows_guide_to_a_510_for_the_average_human/)
  (2020), whose later chapters (8C onward) are the [Bouras deck](https://www.reddit.com/r/AnkiMCAT/comments/h0yi2a/the_bouras_deck/)
  by u/a_dawg98. Neither deck has been updated by its author since 2020.
- **Overlap removed.** MileDown's Behavioral subdeck repeats the P/S deck. Each of its 827 cards was compared with
  the P/S deck: 627 were already covered and were dropped, and the 200 that added something were moved into
  the matching psych/soc category.
- **Errors fixed.** Two full content passes compared every card with the AAMC content outline and standard MCAT prep
  (Kaplan, Princeton Review, Khan Academy). A change was made only when the card was certainly wrong and a second,
  independent check agreed. 180 cards were corrected; each one is listed in [CORRECTIONS.md](CORRECTIONS.md) with its
  before and after text and the reason. 30 cards where the check was unsure are tagged `Tsunami::flagged` and left
  as they were.
- **Duplicates removed.** 34 cards that repeated another card word for word were deleted.
- **An example on every card.** 3,757 cards have a short, concrete example on the back, in its own row, that shows
  the idea in action (a named study, a number, a molecule, an everyday scene). Each was written for this deck and
  accepted by a second, independent check; the rest already give an example in their explanation.
- **One consistent style.** Questions ("What is X?") became statements, long passages were trimmed with the extra detail
  moved to the back, typos and broken formatting were fixed, and formulas use proper sub- and superscripts. A card that
  lists points shows the question on its own line and the points as a list underneath. All cards share one note type
  (`Tsunami`: Text, Extra, Links, Example) with a clean light and dark theme. Khan Academy and YouTube links sit in their
  own row on the back.

## Tags

- `Tsunami::<Subject>::<Topic>` — topic tags inherited from MileDown (for example `Tsunami::Biology::Immune_System`).
- `Tsunami::Psych_Soc::<category>` — AAMC category of each psych/soc card (`6A` … `9B_10A`, `Research`).
- `source::MileDown`, `source::MrPankow`, `source::Bouras` — which deck the card came from; `source::Tsunami` — the few cards written new for this deck.
- `Tsunami::corrected` marks the 255 cards changed by a content or spelling correction; `Tsunami::flagged` marks the 30 doubtful ones.

## Files

- [`deck/tsunami.jsonl`](deck/tsunami.jsonl): every note as text (one JSON object per line), so changes show up in diffs.
- [`CORRECTIONS.md`](CORRECTIONS.md): every content correction, with the reason.

## Found a mistake?

Open an issue with the card's text and what is wrong.

## Credits

The cards are the work of MileDown, MrPankow and u/a_dawg98 (the Bouras deck), who shared their decks for free on
Reddit. The images come with those decks and many are from Khan Academy, Wikimedia Commons and other sites; their
rights stay with their owners. This repository adds the corrections, the merge and the styling, and shares the result
the same way the original decks were shared: free, for personal study.

Flashcards build recall, not passage reasoning: pair the deck with AAMC and UWorld practice passages.
