Palidator
=========

Palidator is a param validator, Yes as it sounds. 
This module will validate a set of multiple conditions sent to it with its corrsponding param(s) and it will return an array with the corresponding results. 

The returned Array has the next format: 
  - Array Dimensions: 2  (n+1 * 2)
  - results[0][0]= True if all validations were True otherwise False
  - results[0][1]= If Any validation was False then this will be the sum of the 
 validations did not pass.
  - results[index][0]= The result of index validation (True | False)
  - results[index][1]= If results[index][0] was False then this position will have the result (could be an exception catched) otherwise empty (True).


The most common validations for this will be:

  - is integer 
  - is string
  - is char
  - betwen (for numerical comparitions)
  - greater than 
  - smaller than
  - equal
  - is hash

  And many others... (for more details go to documentation) 

Phase
----

Development


Tech
------

Python


License
-----
"Para el pueblo"
Yes that means MIT :)


Contributors Welcome
----
> If you want to contribute to this project feel free to 
> put in contact with me (lmaciasm10@gmail.com) and lets discuss
> your ideas :)
