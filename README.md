Most important topic:

match statements are like switch statements that return a value. They are great for error handling when assigning values that could result in an error depending on user input.

some functions return Ok() and Err() values that either contain the type you expect, or an error. If you place an underscore in the Err() "Err(_)" it becomes a catch all for all Err() objects that could return from a function.
