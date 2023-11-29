# WritingTests
## Unit Tests
### (A function "multiplication")
Expect Multiplication(2, 3) to be 6; aka expect the 2 input integers to be to multiplied and return an output integer

Expect Multiplication(5, 6) to be a number

Expect Multiplication(x, 10) to read as error 
### (function "concatOdds") 
Expect concatOdds([-9,-3,0,2,5,7,8,10], [1,5,5,7,13,16,2]) to be [-9,-3,1,5,7,13]

Expect concatOdds([-2,-2,-100,5,3], [5,9,7,8]) to be [3,5,7,9]

Expect concatOdds([-3,-5,-5,17], [2,6,15]) to be [-5,-3,15,17]

Expect to take in 2 or more arrays of integers as arguements, and should return 1 array that only contains the odd numbers, in ascending order, from all of the intial arrays. 
multiples of the same odd integer should only be listed/ displayed once in the new array. 
## Functional Tests
-Guest checkout gets create account option: Should test that when a user chooses to check out as a guest, they are presented with an option to create an account. Within this route, step by step process for user should be able to: Add items to the cart-> proceed to checkout as a guest-> Verify that there is an option to create an account ->  complete the checkout process by filling appropipate payment, billing and shipping information without creating an account-> verify that the order is processed successfully, and no account is created.

-user opts to create an account during checkout: should test that user can create an account with valid data during the checkout process. For this, step by step process for user should be that: Adding items to cart-> Then proceed to checkout as a guest -> There should be option to create an account -> User hooses to create an account -> User provides valid information for account creation -> Then user contiunes to complete the checkout process -> Finally verify that the order is processed successfully, and a new account is created for users. 

-no login prompt for logged in user checkout: Should test that when a logged in user proceeds to checkout, they are not prompted to log in again. This process should look like: user logs in with existing  credentials -> Then items are added to the cart -> proceed to checkout -> Test verifies that there is no prompt to log in -> complete checkout process. 
