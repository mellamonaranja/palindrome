## palindrome

Even if a number is not a palindrome, one of its children may be. We call a child of a number if it is created by adding each pair of adjacent digits to create the digits of the next number.
For instance, 123312 is not a palindrome, but its next child 363 is, where: 3 = 1 + 2; 6 = 3 + 3; 3 = 1 + 2.
Write a program that tells whether the number or any of its descendants down to 2 digits is a palindrome (a 1-digit number is trivially a palindrome).
Examples:
palindromedescendant(11211230) ➞ true
// 11211230 ➞ 2333 ➞ 56 ➞ 11
palindromeDescendant(23336014) ➞ true
// 23336014 ➞ 5665
palindromeDescendant(11) ➞ true
// Number itself is a palindrome.
Etc.
