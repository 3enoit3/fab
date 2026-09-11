fab
===
# Deck building
* hand structure (4 cards) -> deck structure (roles)
* structure/role > individual card
* questions for all decks
  * how to kill? is average turn
  * what is a broken turn?
* attack vs arcane
* when discovering a new hero, build a keyword pool
  * hero + weapons -> pool
  * cards <-> pool

# Deck playing
* life is a resource
* theoretical value -> real value: attack + real block - lost life
* card value
  * card modes
    * damage + effect + condition vs cost
    * block
    * pitch
  * card value = f(mode, deck/synergies), where deck = f(value)...
  * realized value
    * hit: attack > block, arcane damage > arcane barrier...
    * protect: block, gain life, disrupt...
    * store: arsenal, resource, ally/aura (board presence)...
  * integration
    * value over several turns: keep clock in mind (strong early, weak later) 
  * influence on the opponent
    * low life -> force: protect
    * hit -> life (-> high hit) or protect (-> low hit)
    * low hit -> low force: higher chance of high hit
    * high hit -> higher dilemma: higher chance of low hit
  * pitch costs one card: 3 value
* arsenal is very important
  * combo
  * key card types (ex. lightning)
  * defense reaction
  * save from a weak 1-card turn (ex. because blocked on-hit) to a big 5-cards turn
* equipment
  * head: hand/deck
  * chest: resources
  * arms: offensive (ex. buff, on-hit)
  * legs: action points (ex. go again)
* deck value
  * synergy is key: enablers and consumers
  * consistency is next
* deck vs opponent deck
  * who wants to accelerate / shorter game? flatter/consistent hands, weaker blocks
  * who wants to decelerate / longer game? stronger/peak hands (breakpoints, on-hit, disrupt)
* clock
  * tick is defined by the decrease of the lowest life
  * keep track of turns for stored value: may not have time to realize it
  * Sage is a short game -> luck is higher

# Checklist
## Start
1. Who is the sprinter?
2. What is my life danger zone? f(opp hero)
## Loading to RAM: CPP
1. Clock
2. Puzzle
3. Prediction
### Clock
* track
  * life: delta for speed + absolute for time left
  * turns: opportunities in both decks
 
1. me
2. ?
3. musketeers
4. daltons
5. lucky luke !mid-game!
6. ?
7. dwarfs
8. snow white
9. ?
10. ? !full cycle!

# Improvement
* Beginner
  * mechanics
  * decklist
  * hand conversion
  * game plan identification
    * what powerful cards
    * how archetypes win: proactive, reactive, combo
* Intermediate
  * matchup
  * side board
  * armor
  * ratios/deck building
* Advanced
  * gamestate adaptation: pivot to attack or to fatigue
  * implied value
  * outs
  * meta

# Terminology
* permission (MTG): counter spell
* agency: capacity to make impactful choices
* value trade: value vs opponent value
  * attack vs defense (generally defense > attack because no pitch: mid-range > aggro)
* evasive damage: escape traditional block
  * arcane damage -> wizard/runeblade
  * dominate (1 block) -> guardian
  * intimidate (banish for a turn) -> brute
* outs: remaining cards in the deck allowing to save a desperate situation - taking a riskier path hoping for a great reward
* drawing dead: no more outs in the deck
* gamestate: snapshot of the game (life, counters, cards, effects...)
* floor/ceiling: ?
* inorganic synergy: named/typed cards working together (vs organic: draw any cards)
* solved hero: meta compression (only one version of it) + stagnant design

