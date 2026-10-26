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
| Psych-Soc › 6A Sensing the Environment | 298 | MrPankow (204 notes), MileDown (28 notes), Bouras (17 notes) |
| Psych-Soc › 6B Making Sense of the Environment | 496 | MrPankow (325 notes), MileDown (27 notes), Bouras (23 notes), Tsunami (2 notes) |
| Psych-Soc › 6C Responding to the World | 123 | MrPankow (64 notes), MileDown (18 notes), Bouras (11 notes) |
| Psych-Soc › 7A Individual Influences on Behavior | 619 | MrPankow (375 notes), MileDown (48 notes), Bouras (29 notes) |
| Psych-Soc › 7B Social Processes and Behavior | 101 | MrPankow (66 notes), MileDown (3 notes), Bouras (2 notes) |
| Psych-Soc › 7C Attitude and Behavior Change | 129 | MrPankow (79 notes), Bouras (7 notes) |
| Psych-Soc › 8A-8B Self-Identity and Social Thinking | 179 | MrPankow (113 notes), MileDown (9 notes), Bouras (5 notes) |
| Psych-Soc › 8C Social Interactions | 149 | Bouras (121 notes), MileDown (28 notes) |
| Psych-Soc › 9A Social Structure and Culture | 116 | Bouras (98 notes), MileDown (18 notes) |
| Psych-Soc › 9B-10A Demographics and Social Inequality | 128 | Bouras (106 notes), MileDown (21 notes) |
| Psych-Soc › Research Methods and Statistics | 107 | Bouras (104 notes), MrPankow (2 notes) |

The psych/soc subdecks follow the AAMC content categories, 6A (sensing the environment) through 10A (social inequality), plus research methods.

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
- **One consistent style.** Questions ("What is X?") became statements, long passages were trimmed with the extra detail
  moved to the back, typos and broken formatting were fixed, and formulas use proper sub- and superscripts. All cards
  share one note type (`Tsunami`) with a clean light and dark theme. Khan Academy and YouTube links sit in their own
  row on the back.

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
