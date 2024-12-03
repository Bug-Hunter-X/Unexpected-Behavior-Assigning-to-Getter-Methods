# Unexpected Behavior Assigning to Getter Methods in Ruby

This example demonstrates a common pitfall in Ruby where assigning a value to a getter method doesn't modify the underlying instance variable.  This often surprises developers familiar with languages where getter methods act more like simple accessors. The code shows the problem and its solution.

## Bug
The `bug.rb` file demonstrates the problem: direct assignment to the getter (`my_object.value = 20`) fails to change the object's internal state. 

## Solution
The `bugSolution.rb` file presents the corrected approach using a setter method or modifying the instance variable directly.