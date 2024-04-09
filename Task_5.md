![Screenshot 2024-04-09 223904](https://github.com/Arbaaz-Tanveer/Awesome_Robotics_Club_Arbaaz-Tanveer_230184/assets/153709169/b9e1bd01-1b40-4359-873b-813cdc243992)
open the tinkercad file here https://www.tinkercad.com/things/a2FsJBpVQdy-robo-task?sharecode=zoyJ9b3e0B_KzIOrjOC-FK98Qo9wwMJlII1VBttrDYs

heres how the code works
the code first initializes two arrays with 1 and 0 ,1 for thh stars and 0 for empty space ,each array for each row and
then as in the loop everytime each element of the array is getting replaced with the next element with the last element
becoming zero.teh game ends when the row number of bird coincides with the 1 value(if any row at that position has it) 
an infinite loop is initiated at that point to terminate the game also if the score reaches a max score a winning statement 
is shown and the game ends here also.The display is updated using the liquid crystal library .a delay is added at end to slow
down the game.The potentimeter makes the A0 pin read the value between 0 to 1023 on the bases of which the row of the bird
is decided.
