# ParadeDisplayHelper Docs

## Preamble

This class contains methods that help you display the parade visually in a terminal window.

All of these methods will be used in your code!

## Public Methods

### String theCards(ArrayList\<String> cards)
> <pre>
> /**
>  * Returns a colored display of cards from a list of
>  * card strings passed in.
>  */
> </pre>

---

### String removalLine(int numCardsInRemovalZone)
> <pre>
> /**
>  * Returns the removal line: a colored indication of which
>  * cards are evaluated for possible removal. The number of
>  * cards in this zone is passed in.
>  */
> </pre>

---

### String colorRemovalMarkers(ArrayList\<Integer> cardOrdinals)
> <pre>
> /**
>  * Returns the markers indicating which cards should be removed
>  * due to being the same color as a played card.
>  *
>  * Takes in a list of card ordinals to be removed; for example, if
>  * cardsToMark is [1,3,4], then the first, third, and fourth cards
>  * (counting from left to right) would be marked.
>  */
> </pre>

---

### String valueRemovalMarkers(ArrayList\<Integer> cardOrdinals)
> <pre>
> /**
>  * Returns the markers indicating which cards should be removed
>  * due to being the same value or less as a played card.
>  *
>  * Takes in a list of card ordinals to be removed; for example, if
>  * cardsToMark is [1,3,4], then the first, third, and fourth cards
>  * (counting from left to right) would be marked.
>  */
> </pre>