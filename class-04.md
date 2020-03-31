# Welcome 301d4

## CSS Grid
CSS Grid Layout, is a two-dimensional grid-based layout system

To get started you have to
* define a container element as a grid with 'display: grid'
* set the column and row sizes with 'grid-template-columns' and 'grid-template-rows', 
* then place its child elements into the grid with 'grid-column' and 'grid-row'

## some Properties for the Grid Container
* 'display'
* grid-template-columns
* grid-template-rows
* grid-template-areas
* grid-template
* grid-column-gap
* grid-row-gap

## Some Properties for the Grid Items
* grid-column-start
* grid-column-end
* grid-row-start
* grid-row-end

## Common Responsive Layouts with CSS Grid
CSS grid lets us not only arrange elements in a row or a column, but in multiple rows and columns.

The smaller images (in a grid!) are in the perfect layout to get you started with CSS grid.Grid gives us control over how wide or narrow each of the ‘grid cells’ get. This allows us to maintain a sensible aspect ratio to their height.
using 'grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));'

when we put images in a responsive grid layout like this we come across the problem of the images stretching out of proportion. so we Use 'object-fit: cover;'

 grid-gap property. This defines the size of the space between the columns and the rows.

## Regular Expressions
Regular Expression are usefull in extracting informations from any text

## Character classes
* '.'	any character except newline
* '\w\d\s'	word, digit, whitespace
* '\W\D\S'	not word, digit, whitespace
* '[abc]'	any of a, b, or c
* '[^abc]'	not a, b, or c
* '[a-g]'	character between a & g

## Anchors
* '^abc$'	start / end of the string
* '\b\B'	word, not-word boundary

## Escaped characters
* '\.\*\\'	escaped special characters
* '\t\n\r'	tab, linefeed, carriage return

## Groups & Lookaround
* '(abc)'	capture group
* '\1'	backreference to group #1
* '(?:abc)'	non-capturing group
* '(?=abc)'	positive lookahead
* '(?!abc)'	negative lookahead