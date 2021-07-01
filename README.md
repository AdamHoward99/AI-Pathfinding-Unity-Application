<h1 align="center">AI Pathfinding Unity Application</h1>
<p align="center">This is a Unity application to highlight comparisons between various methods of AI pathfinding used in the video game industry. The methods are tested on a map of nodes visualized with coloured quads in a 3D Unity scene, tests of the methods aim to find the time it takes to find the goal node from the start node, the amount of nodes required in the search, the memory capacity used during the search and the total nodes in the shortest path found by the method.</p>
 
<p align="center">The methods tested in this application are common pathfinding algorithms like BFS, DFS, A* in addition to various optimization techniques to improve upon these algorithms such as Binary Heaps, Fibonacci Heaps, HPA* (Hierarchical Pathfinding A*), Floyd-Warshall Algorithm and various Distance Heuristics. This application also servers as the deliverable to my dissertation.</p>

## Screenshots
<p align="center">
  <img hspace = "10" alt ="Map 1 with A*" src = "https://user-images.githubusercontent.com/74617187/124136771-fb30a080-da7c-11eb-8f97-bec6e51579f1.png" height = "500" width = "650"/>
  <img alt ="3D Map 1 HPA*" src = "https://user-images.githubusercontent.com/74617187/124137278-6e3a1700-da7d-11eb-9113-fee947c0518c.png" height = "500" width = "650"/>
</p>
  
## How To Use
The application consists of 6 maps to test methods on, these maps are split into 2D maps and 3D maps. In 2D maps, the scene camera remains static and will portray an overhead view of the map. In 3D maps, the camera is moveable via the WASD keys and mouse to direct where you want the camera to move to; additional controls for the camera movement are given in the 3D map scenes.

In each scene the UI will contain dropdown lists featuring the different pathfinding algorithms; to select an algorithm to test, you simply need to select the algorithm from the top dropdown menu. If you are wanting to apply an optimization technique or a heuristic (A* only) to the algorithm; you can select those options in the following dropdowns. Users if they wish can also edit the positioning of the start and goal node positions; this can be done by entering the coordinates into the input boxes in the UI menu; if the entered coordinates contain a wall/blocked node then the node position will not change.

Once users are happy with the settings, they can press the start button on the right side of the UI menu to allow the test to begin, results will be displayed in colouring on the maps. To reset and try another test, you MUST press the reset button underneath the start button, otherwise no changes will happen. 

## Built With
- C#
- Unity Engine

## Contributors

**Adam Howard**
- [Profile] (https://github.com/AdamHoward99)

## Future Work
- Due to time constraints, many algorithms and pathfinding methods were scrapped (Bidirectional Search, D* Lite). I would like to include these in addition to further expanding the list of algorithms you can test in the application.
