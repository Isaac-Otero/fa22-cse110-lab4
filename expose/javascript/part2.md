1. Line 12 returns 3, it returns 3, because we're asking the console log to return the for loop var i, it stops at 3 iterations. Therefore it returns the number 3.
2. We get 150, because the var keyword is a function scope, so it's to go through the function and return a discounted price variable form line 7. As it gets updated through the loop, we are left with 150.
3.we also get 150, because the way the function is set up, the variable finalPrice is pushed to discounted which is returned at the end of the function. The finalPrice is what is wanted and is pushed out.
4. Discounted should return 150, as this is the final discounted price which should be returned. 
5. There is an error, because let only exists with in the block scope it was called, so for the iterator I to exist after the for loop would not be able to happen. Therefore we get an error message.
6. The same problem happems, an error occurs because the matter of the fact is still true. DiscountedPrice doesn't exist outside the block scope in which it was initialized so it can't be accessed outside of it.
7. We get 150 because finalPrice is also declared throughout the whole scope at the TOP of the function. So it exists throughout the function. So it is able to get reassigned and set to 150 which is what we get.
8. The function will return 150 because finalPrice is Let and it's declared at the top of the function it's able to get reassigned throughout the function. So in line when it the discounted price gets pushed to finalPrice, it is able to get updated. Which we should end up with 150. 
9. The same issue as before happens, we get an error because the let variable is only alive within the block scope of the for loop itself. Therefore can't be shown in the console.
10. We get 3 returned because the const Length is set with prices.length and when it's set it can't be changed. So if we just return it through the console log then it'll just return 3 because that's the size of prices.
11. I predict it will return the discountedPrice because the array is empty and discounted was never set to anything. It's just empty. So after it's initially set it'll return the right variable. Which would be 150.
12.
A: Student.name
B: Student["Grad Year"]
C: Student.getting()
D: Student["Favorite Teacher"].name
E: Student.courseLoad[0]
13.
A. The answer was 32 because it took the string 3 and combined it with the 2 to get a string 32. Since integers mapped to their exact string representation. 
B. The answer is 1 because since 3 maps to it's integer representation it is able to become an int and minus it by 2 to get 1.
C. We get a 3 because null is treated as 0.
D. We get 3null because it took the null and made it become it's string representation so that it can be concated(stitched) togeter with the string 3.
E. We get 4 because true is treated as 1 because it maps to 1 and 3 is an int so they add to get 4
F. False and null both map to 0 so, 0+0 equals 0.
G. We get 3undefined because 3 is a string and undefined maps to it's string represenation and was able to become 3undefined
H. We get NaN because they couldn't be compared so we get NaN
14.
A. The string 2 is able to be represented with an int, 2 so it returns true because the int 2 is greater than 1.
B. False, because there is a string comparison per string, so 2 is compared to the number 1 and 2 is not less than 1 so it's considered false.
C. The string 2 is compared to the integer 2 and since they're the same the answer is true 
D. Since the types are different it's immediately returned as false.
E. The answer is false because true maps to 1, so 1 does not equal 2. So the answer is false.
F. The answer is true because Boolean(2) returns true because it's true that 2 is 2 and therefore goes to 1 and since true maps to 1 then the answer is true
15. == is just a regular equality check, === is a type equality check, and it checks if the types are the same.
17. The result that there will be a newArr created, which would be [2,4,6]. What happens is that each element in the array will go through the function doSomething and multiply the number by 2. Through callback it calls the array at each element.
19. 1,4,3,2
