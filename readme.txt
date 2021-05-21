21.05.2021 - Destroyable Meshes


The asset is designed as part of a 3D-PS1-Style Horrorgame, but the implementation of this feature is mostly self-contained.

The Asset lays 2DGrids over the surfaces of the IDestructible and 3D Grids to order the whole IDestructible-Object. 
IDestructor's can create Hits on IDestructible's, which creates/expands Holes and cracks on and in the IDestructible.
A Hit can also break out a part of the Wall (SupportPolygon), depending on the strength of the Hit, the size of the Part and the type of mesh.

This project is still in its conceptualization-phase.

I am currently working on:
- The Refining of the UML Diagram
- The Listing of independent testable features and according testcases
- Dependency of different features and an according implementation order.

Stay tuned!