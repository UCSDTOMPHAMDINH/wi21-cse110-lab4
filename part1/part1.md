# LAB 2 part1

1. prints prices.length, because var goes through for blocks so the log can see it.
2. prints the last discounted price calculated, because var goes through for blocks and the last item calculated is the last object discountedPrice was set to in the last iteration of the loop.
3. prints the last rounded discounted price calculated in the for loop. var is able to go through  for loops, so we will print the last finalPrice that was calculated in the last iteration of the loop.
4. [50,100,150] it will print the array of the prices in prices lowered by the discount function iterated through the list and lowers each by discount, theres no errors.
5. There is an error, because let cannot go through the block so when we are at console.log(i) we cannot see i and we throw an error.
6. THere is an error because we cannot see discountedprice variable through the block so when we try to log we cannot see it and we get an error.
7. prints the last rounded finalPrice price from the last iteration from the loop, because we defined finalPrice outside of the block we are able to see finalPrice when we log.
8. print the array [50,100,150], although the logs will not work the functionality works the same returning the list of prices lowered by the discount.
9. There is an error, because let cant go through the block so when we log we cannot see it and there is an error.
10. There is an error, because const cant go through the for loop so we cannt see it and there is an error when we try to use log.
11. 0 if we disregard the error of trying to change a const, but because the const was declared as 0 we will log 0.
12. [0,0,0] if we disregard the error trying to change the const finalPrice, then we would be pushing finalPrice 3 times which is a const equal to 0.
13. A. student.name  
    B. student['Grad Year'] 
    C. student.greeting() 
    D. student['Favorite Teacher'].name 
    E. student.courseLoad[0]
14. A. '32', we have string '3' then we add 2 which gets converted to string to do string concat so we get '32' \\
    B. 1, we have string '3' and int 2 so when we use '-' which is a int operator so '3' changes to int and we get 1 \\
    C. 3, null gets converted to 0 \\
    D. '3null', we convert null to string to do concat because + is concat operator for string. \\
    E. 4, true is equal to 1 so we get 1 + 3 which is 4. \\
    F.  0, false and null both convert to 0 so we get 0. \\
    G. '3undefined', to concat undefined gets converted to string and we get '3undefined' \\
    H. NaN, undefined gets converted to NaN so we get a undefined answer. \\
15. A. True, dictionary comparison of "2" and "1" \\
    B. false, dictionary comparison of "2" and "12" and 2 is greater. \\
    C. True, we convert '2' to 2 and they are equal. \\
    D. false, strict equality and they are not same types. \\
    E. false, true is 1 and 1 does not equal 2 \\
    F. true, Boolean makes Boolean(2) equal to true and true === true \\
16. === is strict comparison that takes into account object type and value, and == you can convert and access value there.
17. "How are you?" 2 == true evaluates to false because true converts to 1, then we go to if(2) which is true because we convert 2 to a boolean which is true.
18. 
19. [6,8,10], So to start we make a new array newArr, then we iterate through the array we start with first element 1 then we push into newArr callback(1, function(x)) where function(x) is just x*2. out callback was just doSomething so we return (1+2) * 2 which is 6 and we push that into the array, we repeat that process for the rest of the array and we end up with [6,8,10].
20. 
21. 1 \\
    4 \\
    3 \\
    2 
