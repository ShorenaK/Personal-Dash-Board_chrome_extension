# Resolved promises quiz

1. What is a promise (in your own words)?
A promise that an operation that normally takes a bit of time will eventually finish running. I.O.U (I owe you)

2. Which part of the code we have so far is a promise?
The fetch req returns a promise object

3. What are the three states a promise can be in?
(1)pending , (2) resolved (fulfilled), (3) rejected

4. What does it mean when a promise is "resolved" (or fulfilled)?
The task we watned to perfom finished successfully.

5. How do we tell the code to do something only AFTER a
   promise is resolved?
.then() when is set to resulve state .then will run after fetching

6. Rejection:
a promise becomes rejected if an error thrown inside any of the .then() block or if a prgoramemer manuallu calls Promise.reject()
