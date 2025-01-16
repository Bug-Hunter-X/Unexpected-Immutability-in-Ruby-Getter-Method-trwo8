This repository showcases a subtle but important characteristic of Ruby:  the immutability of instance variables when accessed through getter methods. The `bug.rb` file demonstrates the issue, where a direct assignment to the result of a getter method fails to update the object's internal state.  The `bugSolution.rb` file provides the correct way to modify the instance variable.