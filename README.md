# Ruby Bug: Direct Instance Variable Modification

This repository demonstrates a common, yet subtle, bug in Ruby code: directly modifying instance variables using `instance_variable_set` or `instance_variable_get` instead of using accessor methods. This can lead to unexpected behavior and reduced code maintainability. 

The `bug.rb` file showcases the problematic code. The `bugSolution.rb` file provides a corrected version using accessor methods.