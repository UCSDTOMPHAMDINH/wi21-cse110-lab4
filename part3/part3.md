# Part 1
## The Bug
The bug was that num1 and num2 are both strings so that when we create the result it ends up doing concat instead of addition and we end up with a concatanation of num1 and num2 instead of addition.
## The Fix
The fix was to con