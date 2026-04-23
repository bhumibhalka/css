# css

box : -> includes content, padding, margin , border 

margin -> use to seprate two things (clear area outside the border)
padding -> inside the box the soace between border and content

margin collapse means two box , box 1 have margin of 5px and 2nd box have margin of 7px the margin between them is gonna be 7px

box-size border box : hieght and width includes padding and margin.

inset-0

types of css 
inline css we write it using style attribute <br>
internal css we write it in head using style tag <br>
external css a separate css file with .css and linked using link tag in head

class = multiple elements can have same class

id = unique identifier there can only be one id 

selectors : universal *

group : h1, h2 , p {}

element: div {}

class : .dn {}

id : #hg {}
div b {}
div > b {} b should be the direct child of div

li.red {} -> only li's who have class of red
li.red.green ->li ony with these two classes
div span {} -> span inside the div
p:focus {},  psudeo classes
div::after,
ul li {} -> only li's that are inside ul

li:first-child {}
 last child

span: only-child {}

li: only-child {} -> li child 
span: only-child

li: last-of-type {} last li
li: nth-last-of-type(2){}
span:not(.green) -> li thats doesnt have a class of green

 ul:nth-child(2n) {}
 
 siblings: li.red ~ li {} -> li next to the li.red not before it just after it 

 li.red + 1 {} -> just one li next to the li who have class of red
  li.red +  li.green -> only check the nect li but it should also have a class of green

  input: required {} -> who have required ,aslo disabled
