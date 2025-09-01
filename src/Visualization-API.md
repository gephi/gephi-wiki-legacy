Visualization API provides means of controlling the visualization.

### Visualization controller

This is the most important interface of the API. Its implementation is available through `Lookup`.

```java
VisualizationController controller = Lookup.getDefault().lookup(VisualizationController.class);
```

The controller provides access to following components: `Camera`, `SelectionManager`, `MotionManager`, `VizEventManager`.

### Camera

Holds data related to the scene projection such as position, screen size or look-at point. In 2D it is possible to move the camera to any spot, in 3D it is possible to rotate it or use more user friendly orbiting. The camera can be zoomed and translated in both modes. To center the camera on graph or a node, use `VisualizationController.center***()` methods.

### SelectionManager

Responsible for all selection related queries and settings. Its most important methods are: `getSelectedNodes()`, `clearSelection()`, `selectNodes(Node[])`, `selectEdges(Edge[])`.

### MotionManager

Receives all user created events and sends them to the `VizEventManager` after processing for selection and navigation. It provides information about mouse position and current selection shape (rectangle, ellipse, etc.), if any exists.

### VizEventManager

Dispatches all user created events to registered listeners. To add or remove a listener, use `addListener(VizEventListener)` or `removeListener(VizEventListener)`. 