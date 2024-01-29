
# Dungeon Deck
tabletop dungeon crawler using only d6 and standard deck of cards

### Card Types
- Treasure _given to player_
- Battle _given to player_
- Spent Stack
- Draw From Stack
- In Play

---

### World Tiles and Encounters
- **Spades**: Encounters or fights
- **Clubs**: Dungeons with challenges based on card value
- **Diamonds**: Secrets or treasures
- **Hearts**: Friendly or safe areas
  - Fully heal outside dungeons

- Players can choose to skip cards, shuffling them back into the deck.

### Special Cards
- **Aces**: Critical plot point
- **Face Cards (Kings, Queens, Jacks)**: Opportunities for leveling up
- **Jokers**:
  - draw 5 cards, player with highest roll chooses card
  - stories below told in drawn card environment
  - **Red Joker**: Positive and humorous event
  - **Black Joker**: Funny but slightly dangerous situation

### Leveling Up
- when successfully overcoming challenges presented by face cards
- Each level gained adds +1 to attack rolls and +1 to max health
- Players start with 6hp and 1d6 attack
- returns health to full
- Player can exchange 10 Battle cards for level up on next Heart
  - shuffle those 10 battle cards into Draw From

### Card World Content
_skip this section (and jokers) for a simpler non-storytelling game_
- Drawn cards alternate between day and night
- Roll a d6 to determine the biome for an adventure setting:
  1. Forest/Jungle
  2. Desert/Barren
  3. Mountainous/Tundra
  4. Plains/Grasslands
  5. Aquatic/Coastal
  6. Urban/Ruins

### Conquering a Card
- Hearts cards do not require conquering, as they are safe
- Dungeons must be finished
- Enemies must be defeated
- Treasure must be found

---

### Clubs - Dungeon Generation
- Divide the card value in half, rounding down
- Draw as many cards, these are the dungeon content
- Players can leave dungeon at any point
  - reshuffle the dungeon card
  - reshuffle any card drawn for inside dungeon
  
- Hearts drawn:
  - player can heal half of card value
  - if healing:
    - card spent
    - player(s) heal for 1/2 of card value
  - if skipped:
    - heart reshuffled into Draw From
    - draw another card
  
- Hearts face card drawn:
  - treat as treasure
  - if conquered, players level up

- Clubs drawn: 
  - place card to the side, begin a new inner dungeon
  - take half of card value, rounded down
  - draw that many new dungeon rooms

### Diamonds - Puzzle/Treasure
- Roll 1d6
- Player must match DM's roll within 14 - card value
- If completed, player gets gold equal to card value
- every crit fail takes 1d6 damage

### Spades - Fight
- Card health is value / 2, + player modifier
- Every failed player roll, the DM rolls 1d6 for player damage
- Every player must:
  - roll same or higher than card health 
  - within x rolls, where x is card value

### Hearts - Safe Area
- player can spend gold equal to their max health to level up
