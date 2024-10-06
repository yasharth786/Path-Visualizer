Here's the revised version without concising the content:

---

# Path-Visualiser  
A web application to visualize various pathfinding algorithms on a Grid.

### Installation  
**Cloning the repository:**  
Clone the repository using:  
`git clone (https://github.com/yasharth786/Path-Visualizer)`

**Installing dependencies:**  
Run:  
`npm install`

**Starting the server:**  
Run:  
`npm start`  
Then open [http://localhost:3000](http://localhost:3000) in your browser.

### Features

**Positioning the Start and End Node:**  
You can move the start and end node to whichever cell you want by dragging and dropping.

**Adding Walls:**  
Make sure to toggle the node type to “Wall” using the rightmost yellow button (Node Type = Wall). You can add walls by clicking and dragging the mouse across cells, and remove them the same way. You can toggle between a wall cell and a normal cell.

**Adding Weighted Nodes:**  
Ensure the node type is set to "Weighted (6)" using the rightmost yellow button. You can add weighted nodes by clicking and dragging the mouse over cells, and remove them in the same manner. You can also toggle between wall and normal cells.

**Auto Calculation of Shortest Path:**  
The shortest path is automatically recalculated whenever you move the start or end node, so you don't need to press the "Calculate Shortest Path" button.

**Visualization of Path:**  
Click the “Visualize Path” button to visualize the path found by the algorithm.

**Clear Grid:**  
This button clears the entire grid, removing all weighted nodes and walls.

**Clear Visualization:**  
This option clears the algorithm's visualization, making every visited and shortest path node an unvisited node.

**After Visualization:**  
Once the path is visualized, you can reposition the start and end nodes, add or delete walls, and re-visualize using any algorithm without reloading the page.

### Developers  
This project was built by Yasharth Singh.
