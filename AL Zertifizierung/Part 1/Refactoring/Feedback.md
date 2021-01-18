# Remakers
* Very good analysis of current situation.
* Treating Requirements serious, this will help you by every decision making in the source code.
* Using a Keyboard Eclipse Plugin, would help to see your Keystrokes.
* When creating Tests, always start with the ‘ASSERT’-Part
* Don’t use Comments for showing Structure, f.e. the ‘GIVEN WHEN THEN’ Parts
* Especially when using a Design Pattern, it should be mentioned what other Design Pattern could be used or which Variation inside a used Design Pattern is possible...

## Part 1 - Creating initial Test
* Don’t use your personal Naming by creating Repository-Objects [08:19] either use a Name that you will for sure Change like ‘YIF_XYZ’.
* GIVEN WHEN THEN Comments is a smell, instead separate the Methods with a blank line between the parts.

## Part 2 - Quality Interface
* Nice explanations what is used, f.e. [14:00 -16:30].
* It’s good to rely on intuition, f.e. ‘Ich habe das Gefühl, dass wird später wichtig...’
* Good use of extract Method [22:40]
* Naming should have a comment, that you follow the Company Rules for Naming. In General I would suggest Naming without prefixing
* The Public Methods of Quality Interface, I would add the ABAP Doc Comments at the finish... It could be, that you will completely change the Interface (er even get rid of them)

## Part 3 - Sell In
* Observer Pattern Identified [30:00] for ‘separation of concerns’, why not use the Composit Pattern here with ‘Quality and Sell In’?
* Good forward driven creation of objects [32:30]
* Testname ‘substract_sell_in’ could be named ‘substract_with_any_sell_in’, try to find more meaningful names
* Babysteps in Testing and Implementation is good [36:40]
* Using Optional Parameters in Constructor is ok, it’s not a good approach like mentioned to comment Unit-Tests! [40:25]
* MAGIC Numbers in Production Code: 10, 50, 12 etc..
* Confused by implementing ‘notify’ Method, you should more often use your ‘Sketch’ Notes.. [51:00]
* Honest to explain why you switched from test double to self written mock.. [1:00:00]

## Part 4 - Finishing
* Using ALIASES was a good intuition, why not finishing the Refactoring? At the end you know if its useful or useless
* Using the Outline View could help you to see if you have used proper Names for Classes and Methods...
* Good Explanation at the End what is the status quo and what could follow [1:10:00]

## Summary
In summary the result is nice and clean. You showed that you know how to use ABAP in Eclipse very well for effective refactoring. 
Therefore, you passed this part of the certification.
Well done!
