// Write a function called isNameCorrect that takes in a name as a parameter. If the name is equal to 'Megan' return true else return false.


// What is unique about using 'let' instead of 'var'?


//Is 6 == '6' true or false? Why?


//Is 4 === '4' true or false? Why?


// Write a function called ageTracker that takes in an age as the only parameter. If the age is less than 18 return 'Minor'. If the age is between 18 and 60 return 'Adult'. If the age is greater than 60 return 'Senior' else return 'Not valid age'.


//Write a basic for loop. What are the 3 parts of for loop syntax? 



//What does Truthy and Falsy mean?



//What is the basic syntax for a ternary operator?



//Write a function called colorChecker that takes in one parameter a color and returns a ternary that tests whether that color is equal to 'yellow' if it is return true else return false. 


//What does each of these methods do? 

    //.push():
    //.pop():
    //.shift():
    //.unshift():
    //.slice():
    //.splice():


//Write a function called pushNameToArr that takes in a name and the array as a parameters and pushes it to the provided array and returns it. **Be sure to console.log the original array after you invoke it to see the changes.
  var arr = ['Bamm-Bamm', 'Pebbles', 'Fred', 'Wilma', 'Betty'];



//Write a function classed sliceItUp that takes in an array and returns a copy of the array from index 2 to the end.
  var array = [1, 2, 4, 6, 2, 56, 2]


//Write a function called spliceAndReplace that takes in an array and modifies the original array and removes the 'Fred' and replaces it with 'Barney'. **Be sure to console.log the original array after you invoke it to see the changes.
  var arr = ['Bamm-Bamm', 'Pebbles', 'Fred', 'Wilma', 'Betty'];


//How do you calculate the length of the given array?
  var arr = ['Bamm-Bamm', 'Pebbles', 'Fred', 'Wilma', 'Betty'];


//Write a function called loopAndRemove that takes in an array and loops through the array and removes 'Pebbles'. **Be sure to console.log the original array after you invoke it to see the changes.
  var arr = ['Bamm-Bamm', 'Pebbles', 'Fred', 'Wilma', 'Betty'];


//What is the syntax for looping through an array backwards?


//Write a function called backwardsLooping that takes in the given array as the only parameter. Loop backwards through that array and add 1 to each of the items. **Be sure to console.log the original array after you invoke it to see the changes.
  var array = [1, 2, 4, 6, 2, 56, 2];


//Given the object below add a key of city with a value of 'Bedrock'. **Be sure to console.log the original object after you change it to see the changes.
  var obj = {
    name: 'Betty'
  }

// What is a method in it's simpliest definition?


// Are Objects and Arrays both ordered?


// **Dot notation and bracket notation are the only way to access information inside an object. If you do not reference the object first the key value will be be defined. You MUST reference the object in order to see inside of it. 

// **Anytime you are referencing a property with bracket notation you will need to use quotations so it knows you're referencing a property and not a variable. 


//Given the obj add a method called sayFavoriteFood that that alerts 'Pizza'. 

var person = {
    myName: 'Barney',
    hairColor: 'Brown',
}

// person['sayFavoriteFood']()


//How would you access and invoke the second function inside the nestedArray and invoke it?

var person = {
    myName: 'Wilma',
    hairColor: 'red',
    nestedArray: [{
        func: function() {
              console.log('Hello')
              }
        }, 
        {
          func2: function() {
            console.log('Second Hello')
          }
        }]
}


//Finish the function called buildBunnyObj that takes in a name and a color as the parameters. Return an object with a key of bunnyName which is the name passed in as a parameter and a key of bunnyColor which is the color passed in as a parameter.

function buildBunnyObj(name, color) {
  //code here.
}

var skittles = buildBunnyObj('Skittles', 'Rainbow');
// console.log(skittles)

var snowflake = buildBunnyObj('Snowflake', 'White')
// console.log(snowflake)


//**A callback in its simpliest form is a function that is passed in as an argument.

//Finish the below callback function by passing in the callBack function into the callBackHolderFunction as an argument. Then takes that function and console.logs the invokation of it inside the callBackHolderFunction.

function callBack() {
    console.log('Im a callback');
}

function callBackHolderFunction(  ) {
   

}
callBackHolderFunction(  )



//Below you are given an invocation of the function alertObjectName. Your job is to finish the function based on the invocation. You are passed in two arguments an object and a callback function. Alert the value of the name property within the callback function.

function alertObjectName() {
  
}

alertObjectName({name: 'Betty'}, function(obj) {
    alert(obj)
})



//Below you are given an invocation of the function callbackAddition. Your job is to finish the callbackAddition function based off the three arguments passed into the invocation. You will need to return the invocation of the callback function within the callbackAddition function.


function callbackAddition() {

}

callbackAddition(12, 55, function(num, num2){
    return num + num2
})
