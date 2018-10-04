//# bankBalanceChecker
//JS output tree for checking bank balance @ an atm

/*
 * Programming Quiz - Checking Your Balance (3-5)
 */

// change the values of `balance`, `checkBalance`, and `isActive` to test your code
var balance = 0;
var checkBalance = true;
var isActive = false;

// your code goes here
//gMeta

if (checkBalance === false) {
    console.log("Thank you. Have a nice day!");
} else if (checkBalance === true && isActive === true && balance > 0) {
    console.log("Your balance is $" + balance + ".");
} else if (checkBalance === true && isActive === false && balance >= 0) {
    console.log("Your account is no longer active.");
} else if (checkBalance === true && isActive === true && balance === 0) {
    console.log("Your account is empty");
} else if (checkBalance === true && isActive === true && balance < 0) {
    console.log("Your balance is negative. Please contact bank.");
}

