Day 3 - Reading 05 - Notes
(Ch. 10 & Ch. 11)

## Design with CSS

*Imagine there is an invisible box around every HTML element.*

*Can link an external .CSS file*

'''<link href="name/name.css" type="text/css" rel="stylesheet"/>'''

**Boxes**
- Width and height
- Borders
- Background color and images
- Position in browser window

**Text**
- Typeface
- Size
- Color
- Italics, bold, uppercase, lowercase, small caps

**Specific**
- Specific ways to style certain elements like lists, tables, forms

#### CSS associates style rules with HTML elements
- **Selector**: indicates which element rule applies to
- **Declaration**: indicates how elements referred to in selector should be styled 
    - **Property**: indicate aspects of the element you want to change (can have several separated by semi colon)
    - **Values**: specify settings for chosen properties

#### Cascading Nature of CSS
- if two selectors identical, last one takes precedence
- if one selector is more specific, takes precedence
- add !important after property value to indicate should be considered more important than other rules
- **Can create generic rules that apply to whole doc and then overwrite with more specific rules*

## COLOR

- RGB
    - rgb(100,100,90)

- HEX CODES
    - #EE3E80

- COLOR NAMES
    - DarkCyan

- HSLA
    - Hue (angle between 0 and 360), saturation (percentage), lightness (percentage, 0 white 50 normal 100 black), alpha (opacity, number between 0 and 1.0, .5 50% transparency)

- CSS3- opacity and rgba (a is opacity percentage so 50% would be rgba (0,0,0,.5)

**FUN FACT**: Anything between /* stuff stuff stuffff */ will not show. It's called *commenting code*. To do this highlight + cmmd + /

**Saturation** refers to the amount of gray in color

**Brightness** refers to amount of black in color

- *Brightness* only adds black, *lightness* offers both white and black

**SEE PG 256 FOR INTERESTING WAYS TO WRITE RULES RE COLOR**


[Back to home](README.md)