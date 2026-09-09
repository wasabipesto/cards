# Cards

This is a project for simulating, playing, and developing various card games.

The reference games for this project are currently:

- [War](https://en.wikipedia.org/wiki/War_(card_game))
- [Phase 10](https://en.wikipedia.org/wiki/Phase_10)
- North American [Euchre](https://en.wikipedia.org/wiki/Euchre)

## Features

- [ ] [Building](https://en.wikipedia.org/wiki/List_of_traditional_card_and_tile_packs) the deck
- [ ] Realistically [shuffling](https://en.wikipedia.org/wiki/Shuffling) the deck
- [ ] [Cutting](https://en.wikipedia.org/wiki/Cut_(cards)) the deck
- [ ] Measuring [randomness](https://en.wikipedia.org/wiki/Shuffling#Randomization) of the deck
- [ ] [Dealing](https://en.wikipedia.org/wiki/Card_game#Dealing) cards to players
- [ ] Per-game table state and zones
- [ ] Playing the cards (delegated to per-game strategies)
- [ ] Collecting played cards and re-shuffling

## Questions

- [ ] Which shuffling strategies are best at low iterations?
- [ ] Does cutting the deck affect hand randomness?
- [ ] Does dealing in packets of 2/3 affect hand randomness?
- [ ] Can you win War by [manipulating your hand](https://arxiv.org/abs/1007.1371)?
- [ ] How do the phases of Phase 10 scale in difficulty?
- [ ] What custom phases of Phase 10 would have a better/harder difficulty curve?
- [ ] Can we re-implement existing [Euchre AI strategies](https://portfolios.cs.earlham.edu/wp-content/uploads/2024/05/Capsone-August-final.pdf) or create better ones?
