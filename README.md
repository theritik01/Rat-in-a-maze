<h1 align="center" >Rat in a maze</h1>
Solve this problem using backtracking
<h4>Problem Statement</h4>
<p>A rat starts from source and has to reach the destination. The rat can move only in two directions: forward and down. In the maze matrix, 0 means the block is a dead end and 1 means the block can be used in the path from source to destination. Note that this is a simple version of the typical Maze problem.</p>
<img align="center" src="https://www.geeksforgeeks.org/wp-content/uploads/ratinmaze_filled_path1.png">
<h4>Approach</h4>
<P>Form a recursive function, which will follow a path and check if the path reaches the destination or not. If the path does not reach the destination then backtrack and try other paths.</p>
<h4>Complexity Analysis:</h4>
<ul>
<li><h5>Time Complexity: O(2^(n^2))</h5><p>The recursion can run upper-bound 2^(n^2) times.</p>
<li><h5>Space Complexity: O(n^2)</h5><p>Output matrix is required so an extra space of size n*n is needed.</p>
