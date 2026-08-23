# Lure design

Implement against this file, not folklore.

## Identity

- Product: **Lure**
- Repo: `computerpets-lure`
- Idea: Pet Fishing Hole
- Genre: Cozy minigame
- Engine: Phaser.js
- Surface: `8080`

## Loop

Feed is a care verb. Lure is how treats get made: Paint the clownfish fishes a reef, Rui fishes a river. Catch goes to inventory, then to feed.

## Play beats

- Cast on a biome matching the active pet.
- Timing bar + patience stat.
- Rare splash = companion item, not a new species.
- Trash can be recycled in Quarry later.

## Neighbors

- computerpets (feed inventory)
- computerpets-ledger (sell extra)
- computerpets-quests
- computerpets-lore (biome)

## Failure doctrine

Tab-out → pause the bite window. No wallet → local fish still feed Rui. Never catch another player's pet.

## Hard rules

1. Minigames cannot mint or burn NFTs by themselves (Minter is the write path).
2. Stats come from lived overlay care + Dojo caps, not cash shop.
3. Species kits stay inside Lore. Illegal hybrids never spawn.
4. Fail soft: the desktop overlay process is not this process.
