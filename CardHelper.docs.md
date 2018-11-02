# CardHelper Docs

## Preamble

This class contains methods that will help you deal with Cards.

Just because a method is being used here, doesn't mean **your** code needs to use it: some of these methods exist for other Helper classes to use!

## Public Methods

### public static String validSymbols()
> <pre>
> /**
>  * Returns all allowable symbols from the cards in a Parade deck.
>  */
> </pre>

---

### public static String colorOf(String card)
> <pre>
> /**
>  * Returns the color of a given Parade card.
>  * Invalid cards are given a color of INVALID_CARD_COLOR.
>  */
> </pre>

---

### char symbolOf(String card)
> <pre>
> /**
>  * Returns the sybmol (R,Y,B,P,A,G, or U) of a given card.
>  *  If card isn't valid, returns INVALID_CARD_SYMBOL.
>  */
> </pre>

---

### int valueOf(String card)
> <pre>
> /**
>  *  Returns the value (0-10) of a given card.
>  *  If card is invalid, returns INVALID_CARD_VAL.
>  */
> </pre>

---

### boolean haveSameColor(String cardA, String cardB)
> <pre>
> /**
>  *  Returns true if cardA and cardB have the same color.
>  */
> </pre>

---

### boolean valid(String card)
> <pre>
> /**
>  *  Returns true if card has a valid format.
>  *  [Color Symbol]-[Value 0 thru 10]
>  */
> </pre>
