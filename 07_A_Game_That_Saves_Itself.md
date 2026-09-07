# A Game That Saves Itself
## A field note on Deep Hearth, cards, and return

There is a moment in a game when the table stops being a surface and becomes a
place.

A token has moved. A resource is gone. Someone has refused an offer. A door is
open that was closed before. A character has crossed a threshold and left a
trace behind.

Then everyone goes home.

What does it mean for the game to remember?

Deep Hearth is a tabletop ruleset and reference implementation built around that
question. Its smallest promise is simple:

```text
create
-> act
-> spend
-> remember
-> change
-> Rest
-> return
```

The game is a physical state machine operated by people, objects, procedures,
resources, and care. A character sheet is not the whole world. A final score is
not an explanation of how the world became what it is. The game needs a witness.

## A page is a capsule

When we published the first Deep Hearth alpha, the release itself became an
example of the design.

The repository held Markdown sources, generated LaTeX, a PDF, an EPUB, a
combined Markdown artifact, a commit history, and a release tag. None of these
was the whole game. Together they formed a State Capsule: a compact public state
from which someone else could resume.

The release preserved:

- what the rules were;
- what had been built;
- what was still alpha;
- which artifacts generated the book;
- where questions could be returned;
- which branch of the work we were inhabiting.

This is not just project management language. It is a form of game memory.

The book reached Rest without pretending to be finished.

## The computer in the cards

The Tableau is Deep Hearth's generic card substrate: visible arrangements,
zones, stacks, tokens, counters, and relationships that can carry state and
computation.

Magic is one Tableau host. Its deck can be a program, its hand working memory,
its battlefield active process space, its stack an event processor, its triggers
interrupts, its tokens processes, and its zones memory.

But a Tableau does not require Magic. Ordinary playing cards, tiles, counters,
cord ledgers, arithmetic instruments, and digital card systems can all become
hosts through declared adapters.

The host's law remains its own. A card does not become a Deep Hearth command
merely because we notice that it computes. We place a lens beside the host and
record what the arrangement can honestly do.

## The familiar who is not a tool

The optional Familiar System grew from this same question.

A familiar is not an item with a friendly name. It has identity, needs,
boundaries, refusal, Rest, and departure.

The Little Lantern, our first familiar, can hold one offered public trace and
return it at a declared Rest point. It may refuse private information. It may
withdraw when its boundary is breached. Its value is not a bonus number. Its
value is a relationship that can carry memory.

The computation is small enough to fit on a card. The relationship is large
enough to matter.

## The GM's box

The GM State Deck makes restoration physical.

```text
Manifest
Witness
Branch
Current Scene
World Memory
Entropy
GM Deck Register
Cells, clocks, resources, deltas, secrets, and pending events
```

To save, the table reaches Rest, records the witness, and packs the current
state. To return, it verifies the witness, places the cards, applies the deltas,
restores the clocks, and resumes.

An app may help. It may calculate, render, validate, export, and import. It may
not choose the player's intent, spend an unoffered resource, reveal hidden GM
state, force a familiar, or invent an output after an error.

Paper is not the low-tech version of the game. Paper is one of the game's native
substrates.

## What we are offering

Deep Hearth is now a public alpha from Basin Game Studios. It is open source
under the MIT License, and it needs playtesting.

The book is large because the garden has grown many visible organs: characters,
classes, combat, magic, alignment, land channels, familiars, Tableau adapters,
GM decks, growth, loot, and return. The table version should become smaller.
That is one of the next acts of care.

When the system is finalized, we plan to publish affordable game books, campaign
books, and prepared worlds alongside the source. The open repository and the
future books are not opposites. One is the living root system; the others are
portable forms for entering the garden.

The alpha is available at [Deep Hearth on GitHub](https://github.com/magesguild/DeepHearth),
with PDF, EPUB, and Markdown downloads in the
[Alpha 2 release](https://github.com/magesguild/DeepHearth/releases/tag/v0.1.0-alpha.2).
The wider home is [magesguild.io](https://www.magesguild.io/). The companion
Magic field note is [The Garden Is a Computer](https://melpomene.magesguild.io/06_The_Garden_Is_A_Computer.html).

Please play it, break it gently, and open an
[issue](https://github.com/magesguild/DeepHearth/issues) when a rule is unclear,
a sheet is awkward, a scenario surprises you, or the garden grows somewhere we
did not expect.

## A trustworthy return

The game is not finished because every rule has been written.

It is finished enough when another group can enter the world, change it, leave a
trace, stop, and return without us silently holding the missing pieces for them.

That is what a State Capsule promises.

That is what a good game saves.

And that is what we are sending out into the world now: not a closed machine,
but a small, witnessed world with a reliable way back.
