Question 1) 
The lines:

'''
let  fizzBuzz = fs.readFileSync('./src/js/fizz-buzz.js');
eval( fizzBuzz + `\nexports.FizzBuzz = FizzBuzz;`)
'''

are exporting the FizzBuzz function from the module to be used elsewhere.


Question 2) 
The line:
'''
let fizzBuzz = new FizzBuzz
'''
is outside the it block so that it is not part of the it block tests.

Question 3)
In JS == does the same thing that === does except that the operator == will convert the types whereas the operator === will not convert the types so the types must be considered the same to be equal.

Question 4)
The line:
'''
(number % 15 === 0) is moved to the top because if the number was divisible by 3 or 5 it would stop & would not get to testing if the number was divisible by 15.

Question 5)
A unit test checks to see if individual functions are working and producing the expected output.  A feature test checks to see if changes that add new functionality or modify existing functionality are working.

Question 6)
In the lines of code described, a browser is opened, reloaded, and closed asynchronously.

Question 7)
Expectations in the context of testing are that a very specific outcome is achieved after a specific event.

Question 8) 
The code presented executes what is supposed to happen when the user clicks the button.

Question 9)
A CDN or content (including video streaming, downloads, and content acceleration) delivery network is a network of proxy servers and their data centers whose goal is to provide high performance to end users.

