### How does this sudoku solver works?
The core of the solver is the backtracking algorithm. I implemented a classic backtracking approach to solve the Sudoku. The pruning involves checking the validity of the Sudoku at each step, ensuring the efficiency of the solver. Nothing too fancy.
### Computer Vision and Image Processing:
I implemented computer vision and image processing techniques to capture the Sudoku puzzle directly from the screen. This way, users can simply display the puzzle on their screen, and the solver will recognize it automatically.
### Machine Learning:
To recognize the digits within the Sudoku puzzle, there is employed a simple K-Nearest Neighbors (KNN) model. This model allows the solver to read the digits from the captured image with accuracy.
### GUI Automation:
The project also utilizes GUI automation to interact with the Sudoku.com website. The solver automatically clicks on each cell and inputs the correct digit using the computer vision and machine learning components.
### Why i did it?
I just wanted to test python cv2 and fill my github repository
