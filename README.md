JavaScript Practice Programs
1. Hello
console.log('Hello, Cryptography!');
2. Sum
let a=5,b=7; console.log(a+b);
3. Even/Odd
let n=10; console.log(n%2===0?'Even':'Odd');
4. Largest
let a=3,b=8,c=5; console.log(Math.max(a,b,c));
5. Reverse String
let s='hello'; console.log(s.split('').reverse().join(''));

6. Palindrome
let s = "madam";
// Reverse the string
let reversed = s.split("").reverse().join("");

// Check if both are equal
if (s === reversed) {
    console.log("Palindrome");
} else {
    console.log("Not a Palindrome");
}

7. Count Vowels
let s = "cryptography";
let count = 0;

for (let i = 0; i < s.length; i++) {
    let ch = s[i].toLowerCase();

    if (
        ch === "a" ||
        ch === "e" ||
        ch === "i" ||
        ch === "o" ||
        ch === "u"
    ) {
        count++;
    }
}

console.log("Number of vowels:", count);


8. Table
let n = 5;

for (let i = 1; i <= 10; i++) {
    console.log(n + " x " + i + " = " + (n * i));
}

9. Count Digits
let n = 12345;

// Convert number to string
let str = n.toString();

// Find length of string
console.log("Number of digits:", str.length);

10. Caesar Cipher
let msg = "HELLO";
let result = "";

for (let i = 0; i < msg.length; i++) {
    let code = msg.charCodeAt(i);

    // Shift each letter by 3
    code = code + 3;

    // If it goes beyond 'Z', start again from 'A'
    if (code > 90) {
        code = code - 26;
    }

    result = result + String.fromCharCode(code);
}

console.log(result);
