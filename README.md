# Advance_JavaScript

/*console.log("I love Pizza!");

console.log("Its realy good!");

window.alert("I realy like Pizza!");
*/

// This is a comment

/*  This
    Is
    A
    Multiline
    Comment
*/
// --------------------------------------------- 


// ---------------------------------------- VARIABLES IN JS --------------------------------------------
// A variable is a container for storing data
// A variable behaves as if it was the value that it contains

// Two steps:
// 1. Declaration (var, let, const)
// 2. Assignment ( = assignment operator)

// let user = "Salma Khan \"Django\""
// console.log(user)
/*
let user1 = "Admin \nSite"
console.log(user1)
let user2 = "Dell\tLaptop"
console.log(user2)
let user3 = "Del\bll\tLaptop"
console.log(user3)
*/
/*
let firstName = "Bro"; //strings
let age = 21; //number
let student = true; //booleans

console.log("Hello", firstName);
console.log("You are", age, "years old");
console.log("Enrolled:", student);

document.getElementById("p1").innerHTML = "Hello "+ firstName;
document.getElementById("p2").innerHTML = "You are "+ age + " years old";
document.getElementById("p3").innerHTML = "Enrolled "+ student;
*/

// --------------------------------------------- 

/* 
 -----------------------------  arithmetic expression is a combination of...  -------------------------------------
   operands (values, variables, etc.)
   operators (+ - * / %)
   that can be evaluated to a value
   ex. y = x + 5; {where x and 5 are the operans and + is the operator}
*/


/*let students = 20;

//let extraStudents = students % 2;
//students = students ** 2;


//students += 1;
//students -= 1;
//students *= 2;
//students /= 2;

console.log(students);

let result1 = 1 + 2 * (4 + 3);
let result2 = (1 + 2)* (4 + 3);

console.log(result1)
console.log(result2)
*/

// --------------------------------------------- 

// ------------------ type conversion = change the datatype of a value to another -------------------------------------
//                                 (strings, numbers, booleans)


/*let age = window.prompt("How old are you?");

console.log(typeof age);
age = Number(age);
age += 1;

console.log("Happy Birthday! You are", age, "years old");


let x;
let y;
let z;

x = Number("Name");
y = String(3.14);
z = Boolean("pizza");

console.log(x, typeof x);
console.log(y, typeof y);
console.log(z, typeof z);
*/

// --------------------------------------------- 

// const = a variable that can't be changed
/*
const PI = 3.14;
let radius;
let circumference;

radius  = window.prompt("Enter the radius of the circle: ");
radius = Number(radius);

circumference = 2 * PI * radius;

console.log("The circumference of the circle is", circumference);
*/


// --------------------------------------------- 


// ---------------- Math =  an intrinsic object that provides basic mathematics functionality and constants -----------------------
/*
let x = 3.14;
let y = 5;
let z = 9;
let maximum;
let minimum;

//x = Math.round(x);
//x = Math.floor(x);
//x = Math.ceil(x);
//x = Math.pow(x, 2);
//x = Math.sqrt(x);
//x = Math.abs(x);
//maximum = Math.max(x, y, z);
//minimum = Math.min(x, y, z);
//x = Math.PI;

console.log(x);
*/

// --------------------------------------------- 

//------------------- Calculating Hypotenuse of right angle triangle: -------------------------------------

/*
let a;
let b;
let c;

a = window.prompt("Enter Side A: ");
a = Number(a);

b = window.prompt("Enter Side B: ");
b = Number(b);

c = Math.pow(a, 2) + Math.pow(b, 2);
c = Math.sqrt(c);

console.log("Side C is: "+c);
*/
/*
document.getElementById("submmit").onclick = function(){
    a = document.getElementById("atextbox").value;
    a = Number(a);

    b = document.getElementById("btextbox").value;
    b = Number(b);

    c = Math.pow(a, 2) + Math.pow(b, 2);
    c = Math.sqrt(c);

    document.getElementById("clable").innerHTML = "Side C: "+ c;
}

*/

// --------------------------------------------- 

// ---------------------------- COUNTER PROGRM IN JAVA SCRIPT --------------------------------


let count = 0;

document.getElementById("decreasebtn").onclick = function (){
    count -= 1;
    document.getElementById("countlabel").innerHTML= count;
}

document.getElementById("resetbtn").onclick = function (){
    count = 0;
    document.getElementById("countlabel").innerHTML= count;
}
document.getElementById("increasebtn").onclick = function (){
    count += 1;
    document.getElementById("countlabel").innerHTML= count;
}


// -------------------------------------- RANDOM NUMBER GENERATOR --------------------------------------------

/*
let a;
let f;
let g;

document.getElementById("randomBtn1").onclick = function() {

    a = (Math.floor(Math.random()* 6)+1);
    
    document.getElementById("alabel").innerHTML = a;

}

document.getElementById("randomBtn2").onclick = function(){

    f = (Math.floor(Math.random()* 7)+1);

    document.getElementById("flabel").innerHTML = f;


}

document.getElementById("randomBtn3").onclick = function(){

    g = (Math.floor(Math.random()* 8)+1);

    document.getElementById("glabel").innerHTML = g;

}

/*
console.log(a);
console.log(f);
console.log(g);
*/


// ---------------------------------------- useful string properties & methods --------------------------------------

/*
let userName = "Abu Bakar";
let myname = "   Yumna   "
let phoneNumber = "123-456-7890";

console.log(userName.length);
console.log(userName.charAt(0));                 // used to find the character at the specified index value of the String
console.log(userName.indexOf("b"));
console.log(userName.lastIndexOf("a"));
myname = myname.trim();
console.log(myname)
userName = userName.toUpperCase();
userName = userName.toLowerCase();
console.log(userName);
phoneNumber = phoneNumber.replaceAll("-", "");

console.log(phoneNumber);
*/

// --------------------------------------- SLICING IN JAVA SCRIPT ----------------------------------------------

// slice() extracts a section of a string 
//             and returns it as a new string, 
//             without modifying the original string

/*
let fullName = "Salma Khan";
let FullName = "Hafiza Nida";
let firstName;
let FirstName;
let lastName;
let LastName;

firstName = fullName.slice(0, 5);
lastName = fullName.slice(6);

console.log(fullName);
console.log(firstName);
console.log(lastName);

FirstName = FullName.slice(0, FullName.indexOf(" "));
LastName = FullName.slice(FullName.indexOf(" ")+ 1);

console.log(FullName);
console.log(FirstName);
console.log(LastName);
*/

// -------------------------------- METHOD CHAINING ------------------------------- 

// method chaining = calling one method after another
//                   in one continuous line of code
/*
let User = "someone";

let letter = User.charAt(0).toUpperCase().trim();

console.log(letter);
*/


// -------------------------------------- IF STATEMENT IN JAVA SCRIPT -------------------------------------------------
// if statement = a basic form of decision making
//                           if a condition is true, then do something
//                           if not, then don't do it!
/*
let userage = 21;

if(userage >= 65){
    console.log("You are a senior citizen!");
}
else if(userage >= 18){
    console.log("You are an adult!");
}
else if(userage < 0){
    console.log("YOU HAVEN'T BEEN BORN YET!");
}
else{
    console.log("You are a child!");
}


let online = true;

if(online){
    console.log("You are online!");
}
else{
    console.log("You are offline!");
}
*/
// ------------------------------------------------

// ------------------------------------ TERNARY OPERATOR ----------------------------------
// ternary operator = Shortcut for an 'if/else statement'
//                    Takes 3 operands
 
//                    1. a condition with ?
//                    2. expression if True :
//                    3. expression if False
// Syntax:
//        condition ? exprIfTrue : exprIfFalse

/*
let marks = Checkmarks(55);

console.log(marks);
function Checkmarks(marks){
    return marks >= 60 ? true : false;
}

checkGame(false);

function checkGame(win){
    win? console.log("You Win!") : console.log("You Lose!");
}
// ------------------------------------------

//  ------------------------------- CHECKED PROPERTY -------------------------------------------- 
/*
document.getElementById("mybutton").onclick = function () {

    const mycheckbox = document.getElementById("mycheckbox");
    const visabtn = document.getElementById("visabtn");
    const mastercardbtn = document.getElementById("mastercardbtn");
    const paypalbtn = document.getElementById("paypalbtn");


    if(mycheckbox.checked){
        console.log("You are Subscribed!");
    }
    else{
        console.log("You are not Subscribed!");

    }

    if(visabtn.checked){
        console.log("You are paying with Visa");
    }
    else if(mastercardbtn.checked){
        console.log("You are paying with Master Card");
    }
    if(paypalbtn.checked){
        console.log("You are paying with Paypal");
    }
    else{
        console.log("You must select a payment type")
    }

};
*/

// ------------------------------- JAVA SCRIPT SWITCHES ---------------------------------------

// switch = statement that examines a value 
//                 for a match against many case clauses.
//                 More efficient that many "else if" statements

/*
let gradebyltrs = "A";

switch(gradebyltrs){
 
    case "A":
      console.log("You did great!");
      break;
   
    case "B":
      console.log("You did good!");
      break;
 
    case "C":
      console.log("You did okay!");
      break;
 
    case "D":
      console.log("You passed ... barely");
      break;
 
    case "F":
      console.log("YOU FAILED!");
      break;
 
    default:
      console.log(gradebyltrs, "is not a letter grade");
}


let gradebyno = 95;

switch(true){

    case gradebyno >= 90:
        console.log("You did great!");
        break;

    case gradebyno >= 80:
        console.log("You did good!");
        break;

    case gradebyno >= 70:
        console.log("You did okay!");
        break;

    case gradebyno >= 60:
        console.log("You passed ... barely");
        break;

    case gradebyno > 60:
        console.log("You FAILED:( Ediot!");
        break;

    default:
        console.log(gradebyno, "is not a letter grade!");
}
*/

// ---------------------------- Without JavaScript Switches
/*
let day = "Thursday";

if(day === "Monday"){
    document.write("7:00 am")
}
else if(day === "Tuesday"|| day ==="Wednesday"|| day === "Thursday"){
    document.write("4:00 am")
}
else if(day === "Friday"){
    document.write("9:00 am")
}
else{
    document.write("8:00 am")
}
*/

// -------------------------------------- With JavaScript Switches

/*
let Day = "Monday"

switch (Day) {
    case "Monday":
        console.log("7:00 am")
        break;

    case "Tuesday":
        console.log("4:00 am")
        break;

    case "Wednesday":
        console.log("4:00 am")
        break;

    case "Thursday":
        console.log("4:00 am")
        break;

    case "Friday":
        console.log("9:00 am")
        break;

    case "Saturday":
        console.log("8:00 am")
        break;

    case "Sunday":
        console.log("8:00 am")
}
*/

// -------------------------- STRICT EQUALITY OPERATOR ------------------------
// = assignment operator
// == comparison operator
// === strict equality operator { is used for comparing two variables, but this operator also checks datatype and compares two values}
/*
let x = "3.14";

if(x === 3.14){
    console.log("That is pi");
}
else{
    console.log("That is NOT pi");
}
*/

// --------------------------- AND & OR LOGICAL OPERATORS ------------------------------------------
// Gives us the ability to check more than 1 condition concurrently
// && AND (BOTH conditions must be true)
// || OR (Either condition can be true)
/*
let temp1 = 15;
let temp2 = 20;
let sunny = false;

if(temp1 > 0 && temp1 < 30 ){
    console.log('The weather is good!');
}
else{
    console.log('The weather is bad!');
}

if(temp2 > 0 && temp2 < 30 || sunny){
    console.log('The weather is good!');
}
else{
    console.log('The weather is bad!');
}
*/

// ------------------------------- ! NOT logical operator ---------------------------------
// typically used to reverse a condition's boolean value
// true -> false  false -> true
/*
let percent = 70;
let pass = true;

if(!(percent > 50)){
    console.log("Its okay!")
}
else{
    console.log("You did greate!")
};

if(!(pass)){
    console.log("You failed!")
}
else{
    console.log("Congratulatins! You are pass:)")
}
*/

// ------------------------------- WHILE LOOP IN JS ---------------------------
// while loop = repeat some code 
//              while some condition is true
//              potentially infinite
//              intialize, condition, increment
/*

let i = 1;                                      //initialize
while (i <= 5) {                                //condition
    console.log("Hello");
    i++                                         //increment
}

let username = "";

while(username == "" || username == null){
    username = window.prompt("Enter your name: ")
}

console.log("Hello "+ username);
*/

// ---------------------------- DO WHILE LOOP -----------------------------

// do while loop = do something,
// then check the condition,
// repeat if condition is true
/*
let h = 20;

do{
    console.log(h);
    h++
}while(h < 10)

let username = "";

do{
    username = window.prompt("Enter your name: ")
}while(username == "" || username == null)

console.log("Hello "+ username);
*/

// ---------------------- FOR LOOP ------------------------------
// for loop = repeat some code a 
//            certain amount of times

/*
for(let i = 1; i <= 10; i += 1){
    console.log(i);
}
for(let hny = 1; hny <= 10; hny += 1){
    console.log(hny);
}
console.log("Happy New Year:)!")
*/

// --------------------------- BREAK AND CONTINOUS ------------------------------- 
// break = breaks out of a loop entirely
// continue = skip an iteration of a loop

/*
for(let i = 1; i <= 20; i+=1){
    if(i == 13){
        continue;
    }
    if(i == 17){
        break;
    }
    console.log(i);
}
*/

// -------------------------------------- Functions -----------------------------------------
//function = Define code once, and use it many times.
//           To perform some code, call the function name.

/*
startProgram();

function startProgram(){
    let Name = "Abu Bakar";
    let age = 2;
    
    happyBirthday(Name, age);
}

function happyBirthday(Name, age){
    console.log("Happy birthday to you!");
    console.log("Happy birthday to you!");
    console.log("Happy birthday dear", Name);
    console.log("Happy birthday to you!");
    console.log("You are", age,"years old!");
}
*/

// ----------------------------------- RETURN STATEMENT --------------------------
// return = returns a value back to the place 
//    

/*
let area ;
let width;
let height;

width = window.prompt("Enter Width: ");
height = window.prompt("Enter Height: ");

area = getArea(width, height);
console.log(area);

function getArea (width, height){
    return width * height;
}
*/



// ----------------------------- Varibles ------------------------------------
// variable scope = where a variable is accessible

// let = variables are limited to block scope {}
// var = variables are limited to a function(){}
// you should always use let keyword

/*
for(let q = 1; q <= 3; q+=1){
    console.log(q);
}
for(var w = 1; w <= 3; w+=1){
    console.log(w);
}

console.log(q);
console.log(w);
*/

// ------------------------------- TEMPLATE LITERALS -------------------------------
// Template literals = delimited with (`)
//                                   instead of double or single quotes
//                                   allows embedded variables and expressions

/*
let userName = "Khan";
let items = 3;
let total = 75;

//console.log("Hello", userName);
//console.log("You have", items, "items in your cart");
//console.log("Your total is $", total);

//console.log(`Hello ${userName}`);
//console.log(`You have ${items} items in your cart`);
//console.log(`Your total is $${total}`);

let text = 
`Hello ${userName}<br>
You have ${items} items in your cart<br>
Your total is $${total}<br>`;

//console.log(text);
document.getElementById("myliteral").innerHTML = text;

// With the help of Backlite(``)we can write string in new line as follows:

console.log(`My name is 
Salma Khan`)

*/

// --------------------------------------- Number Guessing Game ---------------------------------------------


let answer = Math.floor(Math.random() * 10+ 1);
let guesses = 0;

document.getElementById("subbtn").onclick = function (){
    let guess = document.getElementById("guessingfield").value;
    guesses += 1;

    if(guess == answer){
        alert(`${guess} is the number.It took you ${guesses} guesses.`)
        window.location.reload();//to reload page and restart the game, when u guess right
    }
    else if(guess < answer){
        alert("Too Small!")
    }
    else{
        alert("Too Large!")
    }
}


// ---------------------------------- JavaScript temperature conversion program -------------------------------

/*
document.getElementById("submitButton").onclick = function(){

    let temp;

    if(document.getElementById("cButton").checked){
        temp = document.getElementById("textBox").value;
        temp = Number(temp);
        temp = toCelsius(temp);
        document.getElementById("tempLabel").innerHTML = temp + "°C";
    }
    else if(document.getElementById("fButton").checked){
        temp = document.getElementById("textBox").value;
        temp = Number(temp);
        temp = toFahrenheit(temp);
        document.getElementById("tempLabel").innerHTML = temp + "°F";
    }
    else{
        document.getElementById("tempLabel").innerHTML = "Select a unit";
    }
}

function toCelsius(temp){
    return (temp - 32) * (5/9);
}

function toFahrenheit(temp){
    return temp * 9 / 5 + 32;
}
*/

// -------------------------------------- ARRAY IN JS -------------------------------
// array = think of it as a variable, 
//             that can store multiple values

/*
let fruits = ["apple", "orange", "banana"];

//fruits[2] = "coconut";

//fruits.push("lemon");   //add an element
//fruits.pop();           //removes last element
//fruits.unshift("mango");//add element to beginning
//fruits.shift();         //removes element from beginning

//let length = fruits.length;
//let index = fruits.indexOf("kiwi");

console.log(fruits);
*/

// --------------------------------- SORT ARRAY ----------------------------
/*
let fruits = ["banana", "apple", "orange", "mango"];

fruits = fruits.sort();
//fruits = fruits.sort().reverse();

for(let fruit of fruits){
    console.log(fruit);
}
*/


// -------------------------------------- 2D array = An array of arrays ------------------------

/*
let fruits = ["apples", "oranges", "bananas"];
let vegetables = ["carrots", "onions", "potatoes"];
let meats = ["eggs", "chicken", "fish"];

let groceryList = [fruits, vegetables, meats];

groceryList[2][2] = "steak";

for(let list of groceryList){
    for(let food of list){
        console.log(food);
    }
}
*/

// --------------------------- Spread Operator---------------------------------

// spread operator = allows an iterable such as an 
// ...                             array or string to be expanded 
//                                 in places where zero or more 
//                                 arguments are expected
//                                 (unpacks the elements)

/*//
let numbers = [1, 2, 3, 4, 5, 6, 7, 8, 9];
let maximum = Math.max(...numbers);
console.log(maximum);

let class1 = ["Spongebob", "Patrick", "Sandy"];
let class2 = ["Squidward", "Mr.Krabs", "Plankton"];
class1.push(...class2);
console.log(...class1);
*/

// -----------------------------------------JavaScript rest parameters ----------------------------

// rest parameters = represents an indefinite number
// ...                             of parameters
//                                (packs arguments into an array)

// let month1 = "January";
// let month2 = "Faburary";
// let month3 = "March";
// let month4 = "April";
// let month5 = "May";
// let month6 = "June";
// let month7 = "July";
// let month8 = "August";
// let month9 = "September";
// let month10 = "October";
// let month11 = "November";
// let month12 = "December";

// console.log(year(month1, month2));

// function year(...months){
//     let all_months = month;
//     for(let month of months){
//         all_months += month;
//     }
//     return all_months
// }


