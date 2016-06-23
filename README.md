# Program-Structure-Eloquent-JavaScript-Exercises
Exercise from Chapter 2

//Exercise 1:

var note = "";
for (var i = 0; i < 7; i++) {
console.log(note += "#");
}

//Exercise 2:

for (var i = 0; i < 100; i++) {
  if (i % 15 == 0) {
    console.log("FizzBuzz");
    }
    else if (i % 3 == 0) {
    console.log("Fizz");
    }
    else if (i % 5 == 0) {
    console.log("Buzz");
    }
    else {
    console.log(i);
    }
};

//Exercise 3:

var size = 8;
for (var i = 0; i < size; i++) {
  var s='';
  for (var j = 0; j < size; j++) {
    if ((i+j)%2 === 0) {
      s += '#';
    } 
    else {
      s += ' ';
    }
  }
  console.log(s);
};
