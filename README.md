var prompt = require('prompt-sync')();
let num1 =  parseInt(prompt("Enter your First Number:"));
let num2 = parseInt(prompt("Enter Your Second Number:"));
let Opretor = prompt("Write any 1 opration from the following:(+,-,*,/):");


if(Opretor == "+"){
    console.log(`Your Answer is ${num1} ${Opretor} ${num2} = ${num1 + num2}`)
}else if(Opretor == "-"){
    console.log(`Your Answer is ${num1} ${Opretor} ${num2} = ${num1 - num2}`)
}else if(Opretor == "*"){
    console.log(`Your Answer is ${num1} ${Opretor} ${num2} = ${num1 * num2}`)
}else if(Opretor == "/"){
    console.log(`Your Answer is ${num1} ${Opretor} ${num2} = ${num1 / num2}`)
}else{

}console.log(`Invlid Opreter`)



export{}
in this repository we are creating a mini calculator
