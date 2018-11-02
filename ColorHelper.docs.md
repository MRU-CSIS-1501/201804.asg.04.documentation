# ColorHelper Docs

## Preamble

This class contains methods that will help you deal with generating colored Strings.

The coloredString method code is being used by the ParadeDisplayHelper to display the cards with colors. You **might** want to use it in your code as well.

## Public Methods

### String coloredString(String colorName, String s)
> <pre>
> /**
>  * Returns a string that will print in color in a terminal that
>  * can display ANSI colors.
>  *
>  * For example, coloredString("green", "foo") returns a
>  * green "foo".
>  *
>  * Recognized colors (case insensitive) are:
>  *
>  * "BLACK"
>  * "RED"
>  * "GREEN"
>  * "YELLOW"
>  * "BLUE"
>  * "PURPLE"
>  * "CYAN"
>  * "WHITE"
>  * "GRAY"
>  * "LIGHTBLUE"
>  * "PINK"
>  *
>  * If an unknown color string is passed, WHITE is applied.
>  */
> </pre>