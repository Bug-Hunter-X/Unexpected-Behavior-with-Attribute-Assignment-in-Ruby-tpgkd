# Unexpected Behavior with Attribute Assignment in Ruby

This repository demonstrates a subtle but common error in Ruby related to assigning values to attributes.  The code in `bug.rb` shows an attempt to modify an object's attribute through the getter method, which unexpectedly fails to change the internal state.  The solution in `bugSolution.rb` provides the correct way to modify the attribute.