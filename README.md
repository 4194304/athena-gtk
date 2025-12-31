# Athena GTK
Athena GTK is a GTK theme that tries to bring the flat, monochrome look of X athena widgets to GTK.

## Recommended settings
To replicate the look of X athena widgets as closely as possible, I would highly recommend setting the font to Misc Fixed SemiCondensed 10. Even though Pango 1.44 dropped support for many bitmap fonts, you can still convert BDF fonts into OTB format using FontForge or fonttosfnt and use them in GTK applications. While I have plans for a monochrome icon theme to fit this theme, SE98 fits in decently well for the time being.

## Some settings
If you'd rather use another font instead of Misc Fixed (or use the regular variant of Misc Fixed), comment out the section at the start of the CSS file (`* { font-weight:bold; }` ) and the fonts will no longer be entirely bold. You can also enable menu separators by deleting the chunk of CSS that says "If you want menu separators comment this out" before it.
