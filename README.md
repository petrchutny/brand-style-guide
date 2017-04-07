# brand-style-guide
Template for a print-ready brand style guide, using CSS grid, SASS stylesheet.

## Printin
Best works in Safari on OS X. As browsers have problems respecting the page breaking, you have to add a margin big enough under a cell (.grid-item) to push lower rows to next page. See _print.scss for the example.

## Cell width
Cells can span 6, 4 or 3 columns. Use the classes `.span-6 .span-4 .span-3` accordingly.
		
## Cell height
Cells defaultly span over 2 rows. Use the class `.span-1-row` to half its height, so that you can stack two cells on top of each other.

## Adding more colour swatches
Find the `.colours` div and add the class coresponding to the number of swatches you want. From no class to `.five`	
