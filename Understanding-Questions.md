# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
* The event handler triggers and determines which action needs to be triggered
* The action then looks at the reducer, determines the operation that is being applied by looking in the state
* reducer then applies the changes to State, in this case adding 1 
* the function runs and the changes get rendered again
* TotalDisplay shows the total plus 1.
