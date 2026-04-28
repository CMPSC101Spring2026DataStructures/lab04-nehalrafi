# Reflection: Rock, Paper, Scissors Lab

Name: Md. Nehal Uddin Rafin
Date: April 27, 2025

Please answer the following questions after you have completed the programming lab. Write your answers in complete sentences and provide thoughtful responses.

## Comprehension Questions

1. What is the purpose of breaking a program into functions? How did this help you in completing the lab?

Your Response:

Breaking a program into functions helps keep everything organized and easier to understand. Instead of having one long messy code, each function does one specific job. For this lab, it really helped me because I could focus on one part at a time, like input or deciding the winner, instead of getting confused by everything together. It also made fixing errors a lot easier.


2. Describe how you validated user input in your version of the Rock, Paper, Scissors game. Why is input validation important?

Your Response:

I used a loop that keeps asking the user for input until they enter something valid. I allowed both numbers (1, 2, 3) and words (rock, paper, scissors), and checked if the input matches the valid options. If not, it shows an error and asks again. Input validation is important because it prevents the program from breaking or giving wrong results when the user types something random.

3. How did you use comments and docstrings in your code? Give an example of a helpful comment or docstring you wrote.

Your Response:

I used comments to explain what certain parts of the code are doing, especially where the logic could be confusing. I also added docstrings for each function to describe what it does. For example, in the function that determines the winner, I explained that it returns "user", "computer", or "tie" based on the choices. This makes the code easier to read and understand later.

4. Explain how the computer's move is generated in your program. What Python features did you use to accomplish this?

Your Response:

The computer’s move is generated randomly using Python’s random module. I used random.choice() to pick one option from the list of choices. This makes the game fair and unpredictable since the computer doesn’t follow a fixed pattern.

5. What was the most challenging part of refactoring the spaghetti code into a more structured program? How did you overcome this challenge?

Your Response:

The hardest part was turning the messy code into separate functions. At first it wasn’t clear how to divide everything. I solved this by going step by step and grouping similar tasks together, like input handling, game logic, and output. Once I broke it down, it started to make more sense.

## Ethical Reflection Questions

1. Why is it important to write code that is easy for others to read and maintain? How does this relate to your responsibilities as a programmer?

Your Response:

It’s important because other people might need to read or work on your code later. If it’s messy, it becomes hard to understand and can cause mistakes. As a programmer, I think it’s my responsibility to write clean and clear code so others can easily follow it and build on it if needed.

2. Consider the use of open source code (like the spaghetti code provided). What are some ethical considerations when using, modifying, or sharing code written by others?

Your Response:

When using open source code, you should not just copy it and claim it as your own. You should understand it, make your own changes, and give credit if needed. It’s also important to follow any rules or licenses. Basically, you should respect the original work and be honest about what you did.

---

(Did you remember to add your name and date at the top of your reflection file?)
Yes