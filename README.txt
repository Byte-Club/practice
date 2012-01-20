jQuery Project

Start with the included index.html. 
You will be modifying the <script> tag inside of the body. 
There are 4 divs already included, which we will be modifying with jQuery. 


Basic Styling
=============
http://api.jquery.com/category/selectors/
http://api.jquery.com/category/css/ 
https://developer.mozilla.org/en/CSS/CSS_Reference
Use this documentation to help you with the following tasks:
(note that the jquery .css function can be used to apply any of the styles in the MDN reference)

Use jQuery to add a border and background color to each of the divs.
Use jQuery to make each of the divs a different size.
Use jQuery to position the divs in the corners of the screen like so:
1      2

4      3
(hint- use position: absolute, and change the distances from the sides of the screen)


Some additional jQuery practice:
Change the font, font size and color of the "awesome" divs (using only one selector).


Basic Logic
===========
https://developer.mozilla.org/en/JavaScript/Reference/Statements/if...else
Use this documentation to help you with the following tasks:

Copy and paste the following html inside the body tag:
<input id='theNumber' type='text' style='position: absolute; top: 50%; left: 50%' value='0'></input>

Copy and paste the following javascript inside the script tag:
var numberInput = $('#theNumber');
numberInput.change(function(){
  var theNumber = parseInt(numberInput.attr('value'));
  //your code goes here
});

theNumber will correspond to the number in the input box.
Under the "your code goes here" comment:
Use basic if/else conditionals to compare theNumber to the different box numbers.
If theNumber matches one of the boxes (ie- 1, 2, 3 or 4), change it's background color. 

You will want to test out your logic by entering a number into the input box and hitting enter.



