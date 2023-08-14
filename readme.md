# part 1
1. true
2. true
3. 1
4. true
5. false
6. true
7. true

# part 2 (A)
## What should the above code console.log?
The provided code block console.log the message:"Keep it up!"he variable isLearning is assigned the value true. When the if statement is encountered, the condition isLearning is evaluated. Since isLearning is true, which is a truthy value, the code block inside the if statement is executed. Therefore, "Keep it up!" will be logged to the console.

## Why do we not need to specify if(isLearning === true)? Why does if(isLearning) work on its own?
 JavaScript automatically coerces it into a boolean value. In the case of conditions like if(isLearning), JavaScript checks if isLearning is a truthy value (in this case, it's true). If it were false, it would be considered a falsy value.

 

## (B)
## 1. What should the above code console.log? Why?
The reason it logs "Keep it up!" is that the variable isLearning is assigned the value true. When the if statement is encountered, the condition isLearning is evaluated. Since isLearning is true, the code block inside the if statement is executed, leading to the message "Keep it up!" being logged to the console.

## 2. What is the value of firstvariable when it is initialized?
 It seems   undefined that the code or context where firstvariableis defined or initialized is missing.

 ## 3. Is the value of firstvariable a “truthy” value? Why?
 A "truthy" value is a value that is considered true when used in a boolean context; For example, if firstvariable were initialized with a non-empty string, a number other than 0, or an object, then its value would be considered "truthy."

 ## 4. Is the value of secondvariable a “truthy” value? Why?
  As a general guideline, values that are not explicitly "falsy" (such as false, 0, null, undefined, NaN, and an empty string) are considered "truthy."

  ## 5. Is the value of thirdvariable a “truthy” value? Why?
  results in True, then value is truthy.

  # part (3)
 # (2)
 1. false: The boolean value false.
2. 0: The number zero (numeric zero).
3. "" (empty string): An empty string.
4. null: A special value representing the absence of any value.
5. undefined: A value representing an uninitialized or non-existent variable.
6. NaN: Stands for "Not-a-Number" and represents an undefined or unrepresentable value resulting from certain arithmetic operations.