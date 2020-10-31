---
tags: [card]
---

# Draw a Card

```
https://deckofcardsapi.com/api/deck/{deck-id}/draw/?count=2
```

The count variable defines how many cards to draw from the deck. Be sure to replace `deck-id` with a valid `deck-id`. We use the deck_id as an identifier so we know who is playing with what deck. After two weeks, if no actions have been made on the deck then we throw it away.

> TIP: replace `{deck_id}` with "new" to create a shuffled deck and draw cards from that deck in the same request.

## Response

```json
{
    "success": true,
    "cards": [
        {
            "image": "https://deckofcardsapi.com/static/img/KH.png",
            "value": "KING",
            "suit": "HEARTS",
            "code": "KH"
        },
        {
            "image": "https://deckofcardsapi.com/static/img/8C.png",
            "value": "8",
            "suit": "CLUBS",
            "code": "8C"
        }
    ],
    "deck_id":"3p40paa87x90",
    "remaining": 50
}
```
