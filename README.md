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
let s='madam'; let r=s.split('').reverse().join(''); console.log(s===r);
7. Count Vowels
let s='cryptography'; console.log((s.match(/[aeiou]/gi)||[]).length);
8. Table
let n=5; for(let i=1;i<=10;i++) console.log(`${n} x ${i} = ${n*i}`);
9. Count Digits
let n=12345; console.log(Math.abs(n).toString().length);
10. Caesar Cipher
let msg='HELLO'; let out=''; for(let ch of msg){let c=ch.charCodeAt(0);
out+=String.fromCharCode((c-65+3)%26+65);} console.log(out);
