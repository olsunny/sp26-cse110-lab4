1. values added: 20
2. final result: 20
3. var should not be used because it can pierce through if, for, and other code 
blocks, which can cause errors when you have the same variable names that should 
represent different values or it makes catching bugs a lot harder since all var 
is processed at the function start and only assigned in place.
4. values added: 20
5. returns an error because the let variable result is declared inside a code block, 
preventing it from being accessed outside of the block.
6. returns an error because the function attempts to reassign the result in line 7, 
even though it was declared as a const variable.
7. same as previous question.