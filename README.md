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
In JS 