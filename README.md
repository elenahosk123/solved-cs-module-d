Download Link: https://assignmentchef.com/product/solved-cs-module-d
<br>
You will modify your program to add a new Critter: Doodlebug.   You can start by copying Ant and make necessary changes.  Both will inherit from Critter.

You will change your array(s) back to point to Critter.  <strong>That should be the only change to the main program.   </strong>




Modify your class hierarchy and review your algorithms.  What must you change?  What new algorithms do you require?




Critter will have a virtual function Breed().  Doodlebug will still use Breed().  Doodlebugs breed after 8 steps.  They (obviously?) create a new Doodlebug and not an Ant.  Are any other changes needed?




Critter will have a virtual function Eat().  If a Doodlebug moves into a grid with an Ant it will eat the ant.  An Ant will not eat another Ant.  A Doodlebug will not eat another Doodlebug.




The Doodlebug will have a function Starve() which counts the steps taken by that Doodlebug.  If it moves 3 steps and hasn’t eaten it will die.  Do you need any new member variables to support this?




Is there anything else you need?  Then finish modifying your inheritance hierarchy.  Make sure you write out, develop and test any new algorithms.  Please don’t tell me that you still start coding rather than designing first. JJ


