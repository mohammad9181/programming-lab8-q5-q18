Questions:

9. The keySet method in HashMap displays a set containing all keys in
the in the HashMap. It's backed by the same HashMap, so when there is 
a change, it automatically updates the set.

13. currentRoom changes, and the description aswell. When going in a
certain direction, currentRoom and the description change in order for
the next go command to work properly.

17. We no longer need to change Game class. because it is done automatilly
in the CommandWords class. We are only calling the method that does so
in Game class. In the CommandWors class, the showAll method creates a loop
that, when creating a local string attribute, does the process of printing
each item in the validCommands collection and adding them to that String.

18. Changing each method to static has its goods and bads. The good thing
is, static helps with optimization and simplification because we're deleting
potentially multiple lines of useless code. However, this makes the code less
flexible when wanting each Game class to have its own command set, it's a 
little harder to do so with static. Using static can maybe make it harder to
expand code and testing it.