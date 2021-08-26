Imagine an infinite two-dimensional orthogonal grid of square cells, each of which is in one of two possible states, live or dead. Every cell interacts with its eight neighbors, which are the cells that are directly horizontally, vertically, or diagonally adjacent.  At each step in time (tick), the following transitions occur:
1. Any live cell with fewer than two live neighbors dies, as if by loneliness.
2. Any live cell with more than three live neighbors dies, as if by overcrowding. 
3. Any live cell with two or three live neighbors lives, unchanged, to the next generation. 
4. Any dead cell with exactly three live neighbors comes to life.  

The initial pattern constitutes the 'seed' (randomly placed 500 cells) of the system. The first generation is created by applying the above rules simultaneously to every cell in the seed — births and deaths happen simultaneously, and the discrete moment at which this happens is called a tick. (In other words, each generation is a pure function of the one before.) 

Few things could not got then answer like you asked for 500 cells and user input for min 100 cells which little bit confused me so I made it for all input acceptance. And a case like there are only 2 live cells and rest are dead. The live cell is form l where the intersection of l is dead so which rule will be appalied first.. for the deadd cell having two live cells or for live cell surrounded with all dead cells.
