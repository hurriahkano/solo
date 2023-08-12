# Boolean logic exercise 

## part I

 Write down what the following statement wiil return. Try to figure this out before putting the commands in the chrome console. 
 1. ## 2 == "2";
true 
2. ## 2 === 2;
true 
3. ## 10 % 3;
 1
4. ## 10 % 3 === 1;
 true 
5. ## true && false;
false 
6. ## false || true;
true 
7. ## true || false;
true 

## part II 

Answer the following questions about this code block:

## (a)

let isLearning = true;
if(isLearning){
    console.log("Keep it up!");
} else {
    console.log("Pretty sure you are learning....");
}

1. ## what should the abiove code console.log?
The code will be in console.log ;keep it up! Because the islearning variable is the truthy .
2. ## Why do we not need to specify if(isLearning === true)? Why does if(isLearning) work on its own?
since the true is a the truthy vlaue 

## (b)

let firstvariable;
let secondvariable = "";
let thirdvariable = 1;
let secretMessage = "Shh!";

if(firstvariable){
    console.log("first");
} else if(firstvariable || secondvariable){
    console.log("second");
} else if(firstvariable || thirdvariable){
    console.log("third");
} else {
    console.log("fourth");
}

1. ## What should the above code console.log? Why?
The codde should console.log "third" because the third variable is truthy .
2. ## What is the value of firstvariable when it is initialized?
The value of the firstvariable is undefined. 
3. ## Is the value of firstvariable a “truthy” value? Why?
No, it is undefined 
4. ## Is the value of secondvariable a “truthy” value? Why?
No, it is empty value 
5. ## Is the value of thirdvariable a “truthy” value? Why?
yes it is , since all number except for zero number are truthy 

## Part III 

1. ## Research Math.random here and write an if statement that console.log’s “Over 0.5” if Math.random returns a number greater than 0.5. Otherwise console.log “Under 0.5”.
if(Math.random() > 0.5){
  console.log("Over 0.5");
} else {
  console.log("Under 0.5");
}

2. ## What is a falsey value? List all the falsey values in JavaScript.
falsely values are the value that evaluate to false in the boolean context.
list of them are: 
Null 
Undefined 
Nans
J