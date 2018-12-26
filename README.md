# Online Class: Loops
<pre>
/*
+---+
| 1 |
+---+
Use while-loop to print the numbers 1 to 10.
*/




/*
+---+
| 2 |
+---+
Use the PHP function <strong><em>range(start, end, step)</em></strong> 
to create array of numbers 5 to 100 with the step 5 
(example: 5, 10, 15, ...)
*/

/*
Use for-loop and if-statement to print all odd numbers.

How to check if a number is odd or even? 
Divide it by 2, and if there is a remainder, the number is odd. 
Use modulus operator (outputs the remainder after division), 
for example: 
1 % 2 = 1 -> odd number
2 % 2 = 0 -> even number
3 % 2 = 1 -> odd number
4 % 2 = 0 -> even number
*/




/*
+---+
| 3 |
+---+
Declare and assign the indexed array with your favourite food 
(at least 4 array elements). Name the array food.
*/

/*
Use while-loop to print array elements (every food in a new row).
*/

/*
Use for-loop to print array elements (every food in a new row).
*/

/*
Use foreach-loop to print array elements (every food in a new row).
*/




/*
+---+
| 4 |
+---+
Print the array from task 3 as unordered list. Printing has to be done inside the for-loop.

Before looping, you need to print the opening list-tag &lt;ul&gt;
After looping, you need to print the closing list-tag &lt;/ul&gt;
*/




/*
+---+
| 5 |
+---+
The array from task 3 is turned into associative array. 
The meal courses are broken down based on the type (salad, main course, dessert, ...) 
and country of origin (Italy, Spain, India, ...)
<strong>
$food_assoc = [
  "pizza" => [
    "type" => "main course",
    "origin" => "Italy"
  ],
  "cheesesake" => [
    "type" => "desert",
    "origin" => "Greece"
  ]
]
</strong>
So, food_assoc is an associative array. 
Every key of food_assoc (pizza, cheesecake) will now have the value that is associative array itself 
and carries the information about the type and origin.
*/

/*
Loop through $food_assoc and use print_r() to print the entire meal course 
(entire array that includes type and origin).
*/
</pre>

## The final printing should look like this: 

### My favourite meals
+ pizza
  + type: main course
  + origin: Italy
+ cheesesake
  + type: desert
  + origin: Greece
