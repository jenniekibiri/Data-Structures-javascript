# Data-Structures-javascript
check what centuary an is in 
palindrome 
``` Javascript
function checkPalindrome(inputString) {
const len =inputString.length;
//get the length of the string
// strings in javascript have a length propety like those of javascript arrays
// loop through the first half the string and check if the first letter matches the last letter and so on
for (let i =0;i<len/2;i++){
    if(inputString[i]!==inputString[len-1-i]){
    //break from the loop if they don't match
        return false
    }
}
return true

}


```

```Javascript
Given an array of integers, find the pair of adjacent elements that has the largest product and return that product.
function adjacentElementsProduct(inputArray) {
let num1=0 ,num2=0,product=-Infinity;
for(let i=0;i<inputArray.length;i++){
    num1=inputArray[i]
    num2=inputArray[i+1];
    if(num1*num2>product){
         product =num1 * num2;
    }
}
return  product

}


```
