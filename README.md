Credit Card Checker
===================

A simple card validator that uses the Luhn algorithm to check for invalid cards.

#How does it work?
1. An array of numbers of a credit card is passed into a function
2. Starting from the last digit, every second one is doubled
3. If the value of the digit is larger than 9 after multiplication, 9 is subtracted
4. The final values of the array are all added together
5. If modulo of the sum is 0, the card is valid

#Commands to test out
+ console.log(validateCred(mystery5));
+ console.log(findInvalidCards(batch));
+ console.log(invalidCardCompanies(batch));