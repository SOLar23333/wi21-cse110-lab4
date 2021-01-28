1. prices.length - 1 will be printed, because var i is a global var (in this function) and will stop at prices.length -1.

2. discountedPrice of the last item will be printed, which is prices[prices.length - 1] * (1 - discount), because var tolerates redeclarations, thus the discountedPrice declared at the last time will be printed.

3. The final price of the last item will be printed. The finalPrice is a global var (in this function).

4. [50, 100, 150]. During each loop, the price is discounted by 50%, and multiplied by 100, rounded, then divided by 100. Thus 100 became 50, then 5000, then 50. 200 Became 100, then 10000, then 100. 300 became 150, then 15000, then 150. And each of them was pushed into the finalPrice array.

5. ReferenceError, i is only declared inside the loop.

6. ReferenceError, discountedPrice is only declared inside the loop.

7. The final price of the last item will be printed. The finalPrice is a global variable in this function.

8. [50, 100, 150]. During each loop, the price is discounted by 50%, and multiplied by 100, rounded, then divided by 100. Thus 100 became 50, then 5000, then 50. 200 Became 100, then 10000, then 100. 300 became 150, then 15000, then 150. And each of them was pushed into the finalPrice array.

9. ReferenceError, i is only declared inside the loop.

10. ReferenceError, discountedPrice is only declared inside the loop, and it's a const.

11. Should be 0 since finalPrice is a const inside this function. However, attempt to reassign finalPrice inside the loop will cause an type error. 

12. Error, as soon as we attempt to reassign finalPrice inside the loop, it will cause an error. 

13. 
- A. student.name
- B. student["Grad Year"]
- C. student.greeting()
- D. student["Favorite Teacher"].name
- E. student.courseLoad[0]

14. 
- A. '32', number 2 is converted to a string and concatenated with '3'.
- B. 1, string '3' is converted to number 3.
- C. 3, null is converted to 0
- D. '3null', null is converted to a string 'null' 
- E. 4, true is converted to number 1
- F. 0, false is converted to number 0, null is converted to number 0
- G. '3undefined', undefined is converted to a string "undefined" and concatenated with "3"
- H. NaN, undefined is converted to NaN, and 

15. 
- A. true, string '2' is converted to number 2
- B. false, dictionary comparison, first char "2" is greater than "1"
- C. true, string '2' is converted to number 2
- D. false, strict equality check, 2 and "2" have different type
- E. false, true is converted to number 1
- F. true, Boolean(2) is true 

16. === is strict equality operator, which checks the equality without type conversion, while == is regular equality check, will perform type conversion before compare the value.

17. 'How are you?' In the first comparison, true will be converted to 1, which is not equal to 2. In the second comparison, 2 will be converted to true since numbers other than 0 are true.

19 . [6, 8, 10]. Inside the loop, if array[i] == x, then we call doSomething on x, which add the element by 2. Inside function(x), we then multiply the element by 2. Then, we push the result, which is (x + 2) * 2, into the newArr.

21 . 1 4 3 2