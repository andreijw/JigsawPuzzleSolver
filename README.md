# JigsawPuzzleSolver
A solver program that can correctly assemble any jigsaw puzzle

The main idea behind this tool is to allow users to input a picture of their Jig saw puzzle pices
and the puzzle will solved correctly in a very efficient manner

Phase 1 - 06/05/2022
*	This will inlcude a heuristic / brute force naive but optimized approach to solve the pieces
*	The main idea behind this approach will be to use some computer vision techniques to cut out the
*	puzzle pices from the picutre. This will involve some image segmentation and filtering, probably a canny filter
*	and some thresholding. Then the border of the puzzle will be constructed by identifying the border pieces. I then
*	plan to slowly work on building the rest of the puzzle from the outside in

Phase 2 - TBD
*	Phase 2 will start once phase 1 is adequately implemented, this will involve some machine learning ideas. I think an
*	evolutionary network that will correctly learn to solve puzzles.