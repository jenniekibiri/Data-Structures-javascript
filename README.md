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
