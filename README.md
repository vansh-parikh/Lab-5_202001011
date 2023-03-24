# Lab-5_202001011

**Software Engineering**

```
Name: Vansh Ashish Parikh
ID: 202001011
Lab 5
```

**Github tool and selected repository**

Here, i am using pylint tool for static analysis.

Link: https://github.com/rishabh1005/Algorithmic-Toolbox

## Installing required tools

![image](https://user-images.githubusercontent.com/124344810/227472512-40f2c0b5-a9f5-4f3e-ab1e-c3016f1345b4.png)

**Performing static Analysis and error understanding**

(1) https://github.com/rishabh1005/Algorithmic-Toolbox/blob/master/week3_greedy_algorithms/2_maximum_value_of_the_loot/fractional_knapsack.py

Tool Output:

![image](https://user-images.githubusercontent.com/124344810/227474539-7ab777f9-a1da-4b80-9d08-51ec76e58051.png)

(2) https://github.com/rishabh1005/Algorithmic-Toolbox/blob/master/week4_divide_and_conquer/6_closest_points/closest.py

Tool Output:

![image](https://user-images.githubusercontent.com/124344810/227474929-7432f555-eb1f-401a-b92c-654bee7569bd.png)

(3) https://github.com/rishabh1005/Algorithmic-Toolbox/blob/master/week4_divide_and_conquer/4_number_of_inversions/inversions.py

Tool Output:

![image](https://user-images.githubusercontent.com/124344810/227475730-4332fb82-6aaf-4e77-95ab-de048f44ee10.png)

(4) https://github.com/rishabh1005/Algorithmic-Toolbox/blob/master/week5_dynamic_programming1/3_edit_distance/edit_distance.py

Tool Output:

![image](https://user-images.githubusercontent.com/124344810/227476017-984459f4-88df-4dff-8c56-e7b27255e1e4.png)

(5) https://github.com/rishabh1005/Algorithmic-Toolbox/blob/master/week4_divide_and_conquer/3_improving_quicksort/sorting.py

Tool Output:

![image](https://user-images.githubusercontent.com/124344810/227477009-3368bb75-4f23-47f7-bdaa-44f880dbe9ca.png)

**Understanding Errors:**
```
    (1) C0321: More than one statement on a single line: This error tells that there is an on statement are found on the same line.

    (2) W0622: Redefining built-in 'input' (redefined-builtin): Used when a built-in is overridden by a variable or method.

    (3) C0114/C0ll6: Missing module docstring/function docstring:   This indicates that neither the modules nor the functions have a docstring defined. The docstring functions as a kind of comment or text explanation that the compiler ignores but which aids in explaining the function's or module's intended use to others. Writing docstrings is a wise move.

    (4) C0103:The variable doesn't match the snake_case naming style. The defined variable is not named using the snake_case convention, as indicated by this error.

    (5) R1705: Unnecessary "else" after "return", remove the "else" and de-indent the code inside it (no-else-return): This occurs when an else line is added following a "return" statement that is never actually executed.

    (6) C0305: Trailing newlines (trailing-newlines): This error tells that there are trailing blank lines in a file.

    (7) W0621: Redifining name from outerscope: This mistake indicates that a global variable with the same name as a local variable. By doing this, the global version of the variable is hidden and the local scope is changed to use the local version of the variable.

    (8) C0303: Trailing whitespace (trailing-whitespace): Used when there is whitespace between the end of a line and the newline.

    (9) W0611: Unused import sys (unused-import): Indicates that importeed module remains unused.

    (10) R1705: Unnecessary "else" after "return", remove the "else" and de-indent the code inside it (no-else-return) : Indicates unnecessary use of else after return statement.
```


