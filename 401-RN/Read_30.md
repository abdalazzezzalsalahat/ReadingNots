# whiteboards and interviews



## 1. Restate the Question

> *Restate the Question they asked to make sure that you fully understand the question.*


## 1.1 Write down the steps of the solution

> *Write down the general steps before going into code of how you woul solve the problem.*

```
1. Start at middle of array.
2. Keep variables tracking left and right boundaries of search area.
3. If value equal to search_val, return true.
4. If left and right boundaries are adjacent, return false.
5. If value bigger than search_val, go halfway towards left boundary, and move the right boundary along with us.
6. If value smaller than search_val, go halfway towards right boundary, and move the left boundary along with us.
```


## 2. Ask About Edge Cases
> *Think about the about the input and expect the out put and ask them about it.*

## 3. Ask About Test Cases

> *This is a **FREE** question so you want to take advantage of it.*


## 4. Write Pseudocode

> *Before you go to code, write the pseudocode first and aske the interviewer if it mamke sense, in the worst case they will not give you any feed back.*

```
function fizzBuzz(n) {
 // If n is not a number or not an integer greater 
 // than zero, return null
 
 // create empty array to store output
 
 // Loop through numbers from 1 to n
 
  // If number modulo 3 is zero, add ‘fizz’ 
  // to output array
  // Else If number modulo 5 is zero, 
  // add ‘buzz’ to output array
  // Else If number modulo 3 is zero and 
  // number modulo 5 is zero, add ‘fizzbuzz’ 
  // to array
  // Else add the number to the array
 
 // return output array
}
```


## 5. Write the Actual Code

> *Now its time to convert your pseudocode into an actual code, they might offer some help.*

```
function fizzBuzz(n) {
 if (isNaN(n) || !Number.isInteger(n) || n < 1) return null;
 let output = [];
 for (let i = 1; i <= n; i++) {
  if (i % 3 === 0 && i % 5 === 0) {
   output.push(“fizzbuzz”);
  } else if (i % 3 === 0) {
   output.push(“fizz”);
  } else if (i % 5 === 0) {
   output.push(“buzz”);
  } else {
   output.push(i);
  }
 }
 
 return output;
}
```


## 6. Stuck? Ask for Help!

> *if you got stuck at some point don't be afraid to ask for some help or hints.*

### We’re All Human

> **Remember thst the interviewer has been in your position and understands the stress of interviews.**










