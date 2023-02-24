# comp3270 assignment 1

question 1
input: just follow the printed instruction to input the initial state first, press "enter", then imput goal state, then press "enter" to implement to codes. For each state, continuouesly input the numbers without any space between each. 
eg. 
initial state: 
7|2|4 
5|0|6
8|3|1
just input 724506831

The output is easy to understand.


question 2:
No input.
illustration of the output:
path: [[start side],[destination]]. 
      In each sublist,i.e.[start side] and [destination]: 
      list[0]=number of missionary on this side after one travel
      l[1]=number of cannibals on this side after one travel
      l[2]: people travel from the side where l[2]=0 to the side where l[2]=1, except the initial state as there is no travel before that
