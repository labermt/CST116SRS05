# CST161SRS05
Life 2D  

Project Name(s):  

    - Life2D  

Purposes:  

    - Learn to program with 2D arrays.  
    - Practice stream input and output.  

Specification:  

This SRS is based on the Conway's Game of Life.  (https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life)

Create a 2 dimensional 100 x 100 array of ints.  

Initialize your data 0's and 1's of your choosing. Input from cin and output to cout.  Use file redirection to reduce typing.  

Loop over your array changing the 0's and 1's following these rules:  

- Each cell is modified based upon its 8 neighbors, vertical, horizontal, and diagonal.  
- If a cell contains a 1 and has 2 or 3 neighbors with a 1, it keeps the value of 1, otherwise it changes to a 0.  
- If a cell contains a 0 and has exactly 3 neighbors with a 1, it changes to a 1, otherwise it keeps the value of 0.  

If a cell is on the border of the array, it wraps back to the opposite end when looking at neighbors.  

Prompt the user for number of iterations and output the values of your array for each iteration. Use a row of 100 '-' characters to divide your iterations. Output the original array a iteration 0.  

Tips: 

- Use [http://web.mit.edu/jb16/www/6170/gameoflife/gol.html](http://web.mit.edu/jb16/www/6170/gameoflife/gol.html) to compare your code to actual results.  

- In the loop duplicate the array and then process it back into the original array.  

###
