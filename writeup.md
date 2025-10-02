# Assignment 3 - Write UP

## Description
This assignment completes our movie chatbot system by implementing action functions that query our movie database and building a natural language interface. You implemented functions to search for movies by year, director, and actors, as well as the core search system that matches user queries to appropriate database operations. This builds directly on the pattern matching work from Assignment 2 to create a functional conversational AI system.

## What to complete
1. Complete all action functions in `a3.py` (title_by_year, title_by_year_range, etc.)
2. Implement the `search_pa_list` function to handle pattern matching and responses  
3. Add at least one new movie to the database with proper formatting
4. Create a new pattern/action pair and add it to the pa_list
5. Ensure all provided assert statements pass
6. Complete the reflection questions below
7. Push your code to github for grading

## Reflection Questions

1. What are some key programming concepts or techniques that you learned while completing this assignment?

One key programming conept that I learned while completing this assignment is list iteration. I had somewhat of an idea due to know Java but this new format was a little confusing at first. Taking the list and adding them together while iterating confused me at te beginning. After I got that concept down the rest was easier to do. 

2. How does the overall movie chatbot system work? Explain the flow from when a user types a query to when they receive an answer.

The overall movie chatbpt system works by taking user input and itterating through pre-written lists. Once it finds a match it then finds that item. An example is matching "actors, in, Jaws" It matches these terms from the input to these pre-written lines and returns an answer which then iterates through a different list until it finds jaws. It then returns this list and once again iterates through a seperate list with these actors and finally returns the list of actors.

3. What are some real-world applications where this type of pattern-matching chatbot system could be useful? How might you extend or improve this system for practical use?

Some real world applications for this type of pattern matching chatbot system that I see being useful is using it for search engines. It makes it easier to find what the user needs through these predictions. I might extnd or improve this system for practical use by extending it to not only pre-written answers but taking the suggestions and searches from previous users. This would make it easier to find user inputs.