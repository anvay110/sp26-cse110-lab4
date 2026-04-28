1. Line 12 prints `3`. Since `i` is declared with `var`, it can be accessed outside the for loop. When the loop ends, `i` is equal to `3`.
2. Line 13 prints `150`. Since `discountedPrice` is declared with `var`, it can be accessed outside the for loop. After the last iteration, `300 * (1 - 0.5) = 150`.
3. Line 14 prints `150`. Since `finalPrice` is declared with `var` outside the loop on line 4, it is always accessible. After the last iteration, its value is `150`.
4. The function returns `[50, 100, 150]`. Each price is multiplied by `(1 - 0.5)`, rounded to 2 decimal places, and pushed into `discounted`, which is then returned.
5. Line 12 returns an error. Since `i` is declared with `let`, it cannot be accessed outside the for loop.
6. Line 13 returns an error. Since `discountedPrice` is declared with `let`, it cannot be accessed outside the for loop.
7. Line 14 prints `150`. Since `finalPrice` is declared with `let` outside the loop on line 4, it remains accessible. After the last iteration, its value is `150`.
8. The function returns `[50, 100, 150]`. Switching to `let` doesn't affect the return value, only the scoping of variables inside the function.
9. Line 11 returns an error. Since `i` is declared with `let`, it cannot be accessed outside the for loop.
10. Line 12 prints `3`. Since `length` is declared with `const` outside the loop on line 4, it is accessible here. `prices.length` equals `3`.
11. The function returns `[50, 100, 150]`. Using `const` for `discounted` doesn't prevent `.push()`, since that modifies the array's contents, not the variable itself.
12. A. `student.name`, B. `student['Grad Year']`, C. `student.greeting()`, D. `student['Favorite Teacher'].name`, E. `student.courseLoad[0]`
13. A. '3' + 2 = '32' — 2 is converted to a string, resulting in string concatenation. B. '3' - 2 = 1 — '3' is converted to a number, resulting in subtraction. C. 3 + null = 3 — null converts to 0. D. '3' + null = '3null' — null converts to the string 'null', resulting in string concatenation. E. true + 3 = 4 — true converts to 1. F. false + null = 0 — false converts to 0 and null converts to 0. G. '3' + undefined = '3undefined' — undefined converts to the string 'undefined', resulting in string concatenation. H. '3' - undefined = NaN — undefined converts to NaN, and any arithmetic with NaN returns NaN.
14. A. '2' > 1 = true — '2' is converted to a number, and 2 > 1. B. '2' < '12' = false — both are strings, so they are compared character by character. '2' > '1', so '2' < '12' is false. C. 2 == '2' = true — '2' is converted to a number before comparing. D. 2 === '2' = false — no conversion occurs; a number and a string are never strictly equal. E. true == 2 = false — true converts to 1, and 1 != 2. F. true === Boolean(2) = true — Boolean(2) is true since any non-zero number converts to true, and true === true.
15. == converts types before comparing; === does not, so both the value and type must match.
16. response in `part2-question16.js`
17. `modifyArray([1,2,3], doSomething)` returns `[2,4,6]`. For each element in the array, `doSomething` is called as the callback, multiplying it by 2 and pushing the result into `newArr`, which is then returned.
18. response in `part2-question18.js`
19. 1, 4, 3, 2