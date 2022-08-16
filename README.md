# Python-Defining-and-calling-Functions
Define the word_dict() function that analyzes the input text file.

Place the insertion point on line 12.

Type def words_dict():

This creates a function that takes no arguments. Later, the function will take an argument that passes in the path of the user's input file.

Highlight the code in lines 13 through 35.

Press Tab.

This places all of the code that compares the input file to the wordlist under the function. Now this code is no longer in scope of the whole program, but in scope of the words_dict function.

Provide a return value.

Place the insertion point on line 37, and press Tab to indent beneath the words_dict function.

Type return word_count

When the function completes, it will now pass the result (contents of the word_count dictionary) back to the statement that called the words_dict() function.

Document the function.

Position the insertion point at the end of line 12, and press Enter.

In line 13, type a docstring that describes what the function does.

Define the function print_top_words that prints the results to the console.

Place the insertion point on line 39 and press Enter.

Type def print_top_words(choice):

This creates a new function. The function accepts one argument, choice, which will identify whether common words should be suppressed.

Indent lines 41 through 54 beneath the function.

As before, this places the block of code under the scope of the newly defined function.

Place the insertion point on line 56, and press Tab.

Type return results_list

Now, when you call the print_top_words() function elsewhere in your program, it will return results_list back to the calling statement.

Write a docstring below the function definition as shown:

Do some cleanup and call both the words_dict() and print_top_words() functions.

In line 43, delete the choice = "n" statement, leaving an empty line as shown.

Since you're going to pass in the user's choice as a parameter, you no longer need to define it here.

In line 43, type word_count = words_dict()

This calls the function and assigns the returned dictionary to words_count.

Position the insertion point in line 78, and press Enter.

Press Tab twice to indent even with the user_output line below.

Type print_top_words(common_word) and press Enter.

This calls the function print_top_words() while passing in the user's answer to suppressing words as the parameter.

Test the program.

Run the program.

Provide any value for the first prompt.

At the second prompt, enter n

Verify that the results printed to the console.

Rerun the program, this time entering y at the suppression question. Verify that the results are accurate:


