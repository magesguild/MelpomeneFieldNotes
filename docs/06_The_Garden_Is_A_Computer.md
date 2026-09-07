# The Garden Is a Computer

## Tactile computing with Magic: The Gathering

**Basin Game Studios**

> *Hey. We noticed something.*
> *A card moved, a token appeared, and the table remembered.*
> *Isn't that interesting?*

This began with questions raised by material computation, including the khipu:
how memory, calculation, hierarchy, and responsibility can be carried by
relationships among materials, bodies, specialists, and communities.

The khipu are an inspiration, not a template to copy. Numerical and
administrative uses are strongly documented, while the full range of khipu
meaning remains an active scholarly and community-linked field of study. We
acknowledge the Andean traditions, communities, scholars, and archives whose
work makes that understanding possible. We do not claim to reproduce, decode,
own, or substitute for khipu.

Magic is a different substrate. We carry forward one modest lesson:

> A physical arrangement can be a medium for computation and play.

## What We Noticed

Magic seems to contain a computer.

Cards are instructions and data. Decks are programs. Mana is energy. The hand is
working memory. The library is protected future state. The battlefield is active
process space. The graveyard is history and compost. The stack is a LIFO event
processor. Triggers are interrupts. Tokens are processes. Turns are clocks.

The Tableau is one way of touching that possibility and asking it to answer. It
is the generic card substrate: visible arrangements, zones, stacks, tokens,
counters, and relationships that can carry state and computation. Magic is one
Tableau host; the host's own card law remains authoritative.

Nothing here replaces Magic's card law or Comprehensive Rules. We are placing a
small lens beside the game and seeing what becomes easier to notice: machines
made from the collections already in our hands.

<figure class="visual architecture-figure">
<figcaption><span class="figure-kicker">System map</span><strong>The card table already computes</strong></figcaption>
<div class="architecture-flow">
<section class="architecture-card"><div class="figure-kicker">01 · Program</div><h3>Deck</h3><p>Genome, instruction set, and chosen redundancy.</p></section>
<section class="architecture-card"><div class="figure-kicker">02 · Active tissue</div><h3>Battlefield</h3><p>Cells, tokens, attachments, counters, and local state.</p></section>
<section class="architecture-card"><div class="figure-kicker">03 · Event processor</div><h3>Stack</h3><p>Actions, triggers, priority, and LIFO resolution.</p></section>
<section class="architecture-card"><div class="figure-kicker">04 · Memory</div><h3>Zones</h3><p>Hand, library, graveyard, exile, and the return paths between them.</p></section>
</div>
</figure>

## A Small Vocabulary

### Cells

A permanent or token can be looked at as a cell: identity, location, state,
counters, attachments, tap state, and lineage. Its printed text remains its
local law. The word is an invitation to look, not a new type line.

### Memory

| Magic zone | Tableau interpretation |
|---|---|
| Library | Protected genome or future state |
| Hand | Working memory and input buffer |
| Battlefield | Active process space |
| Stack | Event stack |
| Graveyard | Compost and event history |
| Exile | Sealed or cold memory |
| Command zone | Optional persistent kernel |

### Energy and events

Mana is an obvious place to begin looking for energy. A spell, activated ability,
triggered ability, zone change, or declared input can be treated as an event.
The ordinary Magic stack and priority system already know how to carry it.

### Look at one step

```text
declare legal action
-> pay costs
-> place event on stack
-> resolve event
-> resolve resulting triggers
-> record the new state
```

### Rest

A machine reaches Rest when the stack is empty, all triggers are resolved, no
mandatory event remains pending, and someone has taken the time to notice what
state it is in.

Rest is a valid result. A machine does not need to continue acting forever to be
interesting.

## The Rooms Magic Already Has

| Host format | What becomes visible |
|---|---|
| Constructed / Legacy | Redundancy, fault tolerance, and a deep historical instruction set |
| Limited | Runtime compilation under scarcity |
| Commander | Singleton biodiversity and a persistent kernel |
| Jumpstart | Module linking |
| Cube | A curated instruction set selected by draft |
| Planechase | A changing environmental layer |
| Archenemy | A privileged interrupt stream |
| Team formats | Shared memory and distributed operators |

The Tableau does not replace these rooms. A player chooses one, then writes down what
they want to notice.

## A Few Experiments

### Pure Compute

Begin without combat, story, or ecology:

```text
boot
-> accept input
-> perform legal transitions
-> produce output
-> reach Rest
```

Try giving Pack Rat discarded cards and watching copies appear. Its population
is already a small visible number. An Altar of Dementia can turn that number into
a library event. Record what happened without asking the machine to tell you
what it means yet.

### Exchange Duel

Let two machines ask one another questions. A packet may be a token, card, spell,
discard event, mana pulse, graveyard event, or combat-like signal. What does the
receiving machine do with it? What does its prior state change?

### Traditional Battle

Normal Magic combat remains available. Perhaps combat is one kind of exchange,
one way that a machine asks another machine to answer.

## Flow and Root

In ecological modes, we might read printed power as **Flow**, outward capacity to
share energy, memory, material, or signal.

We might read printed toughness as **Root**, capacity to remain stable under load,
scarcity, interruption, or environmental pressure.

Power and toughness remain the actual Magic values. Flow and Root are optional
readings, useful when they make something interesting easier to see.

## Favorite Card Incubation

A player can begin with any card they love and ask what kind of machine wants it.

<figure class="visual table-figure">
<figcaption><span class="figure-kicker">Incubation card</span><strong>Ask the favorite card</strong></figcaption>
<div class="table-scroll"><table class="data-table"><tbody>
<tr><th>Favorite card</th><td></td></tr>
<tr><th>Host format</th><td></td></tr>
<tr><th>Boot condition</th><td></td></tr>
<tr><th>Consumes</th><td></td></tr>
<tr><th>Produces</th><td></td></tr>
<tr><th>Observes</th><td></td></tr>
<tr><th>Memory touched</th><td></td></tr>
<tr><th>Possible companions</th><td></td></tr>
<tr><th>Failure mode</th><td></td></tr>
<tr><th>Output</th><td></td></tr>
<tr><th>Rest condition</th><td></td></tr>
</tbody></table></div>
</figure>

Perhaps the card becomes a kernel, memory organ, signal source, boundary,
environmental law, dormant reserve, macro-instruction, or puzzle condition. It
does not need to fit every design. The point is to see what it does here.

## Rat Garden

Rat Garden is our first little world: a black-centered ecology in which every
creature card is a Rat. Pack Rat is the founding species, not the king.

### The population

```text
4 Pack Rat
2 Rat Colony
2 Relentless Rats
2 Marrow-Gnawer
2 Ratcatcher
2 Crypt Rats
2 Nezumi Bone-Reader
2 Nezumi Graverobber
2 Nezumi Shortfang
2 Rotting Rats
1 Chittering Rats
1 Dirty Wererat
```

### The organs

```text
2 Skullclamp
2 Ashnod's Altar
1 Altar of Dementia
2 Bag of Holding
2 Dark Prophecy
4 Dark Ritual
1 Unearth
1 Buried Alive
1 Living Death
```

### The habitat

```text
3 Cabal Coffers
2 Urborg, Tomb of Yawgmoth
2 Bojuka Bog
2 Barren Moor
11 Swamp
```

<figure class="visual table-figure">
<figcaption><span class="figure-kicker">Ecology map</span><strong>One burrow, many niches</strong></figcaption>
<div class="comparison-grid">
<section class="component-card"><h3>Growth</h3><p>Pack Rat replicates. Marrow-Gnawer produces bloom. Rat Colony reads the wider population.</p></section>
<section class="component-card"><h3>Memory</h3><p>Graverobber returns. Skullclamp turns death into cards. Bag of Holding keeps discarded material available.</p></section>
<section class="component-card"><h3>Signal</h3><p>Crypt Rats creates an output pulse. Chittering Rats routes the next input. Shortfang senses a threshold.</p></section>
<section class="component-card"><h3>Lineage</h3><p>Pet-imprinted tokens carry Magic role and Hearth identity. The image carries biography; the marker carries characteristics.</p></section>
</div>
</figure>

### The small golden seed

```text
1 Pack Rat
3 Swamps
1 input card
1 Rat token or physical child-body
```

The seed can receive input, spend energy, reproduce, expose population, and
reach Rest. It is almost comically small. The deck is the grown body; the seed
is the first living beginning.

## Two other seeds

### Hope-Bloom

```text
Bishop of Wings
Angelic Accord
Giada, Font of Hope
```

```text
Angel enters
-> gain 4 life
-> delayed Angel creation
-> population growth
-> inherited counters
-> another Angel enters
```

Giada notices population. Bishop notices arrival. Angelic Accord waits, then
answers. The three cards become a small ecology of anticipation.

### The Meek Foundry

```text
Thopter Foundry
Sword of the Meek
Disciple of the Vault
```

```text
mana
-> artifact sacrifice
-> Thopter child
-> life output
-> graveyard event
-> Sword return
```

`Emry, Lurker of the Loch` can join later as an archive and recovery organ.

## When machines meet

Two decks can do more than fight. They can ask one another questions, exchange
packets, discover compatible words, and sometimes produce a small child seed.

Before a meeting, each machine declares:

```text
input ports
output ports
active words
resources it can share
resources it can receive
refusal conditions
Rest condition
```

If both players consent, they may compose witnessed words, exchange one organ
and one word, or let a token bud into a new scenario. Parent decks remain
unchanged. The child still obeys the host format, deck size, copy limits,
resource costs, and card law.

No machine is required to accept inheritance. A meeting that preserves two
distinct, healthy systems is a successful meeting.

## Games that can grow from the Core

### The First Burrow

Wake the golden seed, receive three inputs, grow three named descendants, compost
one body, recover one memory, produce one output, and reach Rest without
exhausting the habitat.

### Two Hearths

A Rat Garden sends a population packet to a Meek Foundry. The Foundry archives or
transforms it and returns an artifact signal. The Rat Garden may adopt,
quarantine, or refuse the signal.

### The Mailbox Game

One player places a facedown card into an input mailbox. The other machine decides
whether to open it, archive it, transform it, return it, or leave it unanswered.
The card is a message whose meaning depends on the receiver's state.

## A practical computation

The smallest Rat machine can serve as a physical tally and allocation tool. Each
sample is represented by one input card:

```text
discard one sample card
-> pay 2B
-> activate Pack Rat
-> create one Rat token
-> record the population
```

The Rat population is a visible unary register. `Rat Colony` can provide a
second population-scaled readout, while `Altar of Dementia` can turn the final
value into a recorded library event.

This is not proposed for safety-critical accounting, medicine, or navigation. It
is a bounded field calculation for allocation puzzles, teaching, and play: a
pocket-sized counter that keeps each input, cost, and result visible.

<figure class="visual equation-figure">
<figcaption><span class="figure-kicker">Generated word</span><strong>A first portable operation</strong></figcaption>
<div class="equation"><code>KINDLE-RAT</code> <span>(sample → population + 1)</span></div>
<p class="figure-note">The word names a witnessed card sequence. It does not create new card text or bypass its costs.</p>
</figure>

## Tactile apparatus

All we need to begin is a deck, tokens, counters, a surface, input and output
markers, a cycle tracker, and somewhere to write what the machine answered. A
4x4 cell mat is useful but optional.

Software may verify a replay later. It cannot replace moving the cards, resolving
the stack, paying costs, updating counters, and recording the answer.

## Hey

Take a card you love. Give it energy, memory, neighbors, and somewhere to rest.
Watch what it becomes.

Then ask someone else:

> Hey. We noticed something. What do you notice?
