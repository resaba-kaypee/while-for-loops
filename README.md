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

