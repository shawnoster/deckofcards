---
tags: [deck]
---

# Shuffle the Cards

```
https://deckofcardsapi.com/api/deck/new/shuffle/?deck_count=1
```

Add deck_count as a GET or POST parameter to define the number of Decks you want to use. Blackjack typically uses 6 decks. The default is 1.

## Response

```json
{
    "success": true,
    "deck_id": "3p40paa87x90",
    "shuffled": true,
    "remaining": 52
}
```