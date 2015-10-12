# Evaluation
I feel that overall, my success criteria has been met. The first point in my success criteria was to make sure that the user was asked 10 questions. This criteria has been met and the user does indeed get asked 10 questions. This is important because it confirms that all the code is correctly inside the loop and I haven’t incremented the counter too many times. I have made sure the criteria is met by setting a counter variable to start as 1 and every time a question is asked the variable had one added to it. Once the variable reaches 10, one last question is asked and then the loop stops.

The next criteria I said my program had to meet was to make sure that all the numbers were randomly generated.in my quiz. I ran the quiz a few times, and I couldn’t notice a pattern between the numbers. It’s important that this criteria is met because it’s an important part of the design specification and it provides reusability for the quiz. This would help it in a real life setting.   I have achieved this by using Python’s random module which allows me to select numbers within a specific range.
	
Another criteria I felt my quiz had to meet was that it only produced the (+),(-) and (*) operators. I ran the quiz multiple times and they were definitely the only operators used in the questions. I feel it’s important that this criteria was met because it’s one of the big parts of the design specification and for younger children, divides can be challenging. It also makes sure that no decimals can be created from the questions and that would cause Python to error when a decimal was entered. I achieved this by only defining the add, subtract and multiply functions.
	
The final criteria I said my quiz had to meet was to make sure the score is counted correctly and displayed at the end. I ran the quiz quite a few times and the score was correctly counted each time. The score also printed correctly every time. I feel it’s important to meet this criteria to help give feedback to the user. I achieved this by adding one to the score each time the user got a question right and called the score variable in the final print.