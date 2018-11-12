# while-for-loops
//ascending while loop
var myArray = [];
var j = 0;
while(j < 5) {
  myArray.push(j);
  j++;
}

console.log(myArray);
//descending while loop
var ourArray = [];
var i = 5;
while(i > 0) {
  ourArray.push(i);
  i--;
}
console.log(ourArray);


// descending for loop
var ourArray = [];
for (var i = 5; i <= 1; i--) {
  ourArray.push(i);
}

// ascending for loop
var myArray = [];
for(let j = 1; j <= 5; j++){
  myArray.push(j)
}


//looping through an array using for loop
var myArray = [2,3,4,5,6]
var total = 0;
for(let i = 0; i < myArray.length; i++){
total += myArray[i]
}

//looping through a string in reverse using for loop
var myString = "esreveR";
var reverseString = "";
for(let i = myString.length -1; i >=0; i--;) {
reverseString += myString[i];
}

//looping through a string in reverse using for of in a function
function reverse(str) {
let reversed = "";
for(let char of str){
reversed = char + reversed //its needed
  }
return reversed
}
