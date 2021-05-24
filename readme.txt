22.05.2021 - Destroyable Meshes

	What is it about?
The asset is designed as part of a 3D-PS1-Style Horrorgame, but the implementation of this feature is mostly self-contained.


	How is it supposed to work?
The goal is an asset, that allows for procedural Destroying of Meshes. 
Therefore an Interface IDestructible and an Interface IDestructor is implemented.
The core-idea is: Hits from an IDestructor on an IDestructible create/expand cracks and holes in the IDestructor. 
By that, some parts of the IDestructor can become fully disconnected by the cracks.
Those parts will be cutted out and be new objects/meshes.
The Expansion of holes and cracks / The effect of the hit will be calculated by creating a "SupportPolygon", in other words: 
That part of the wall that is most likely to be breaken out by the Hit. 
See more about the calculations of Hits in the Situation1_Hit.png or Usecase.text.
See more about the architecture in the UML.


	What's next?
This project is still in its conceptualization-phase.

I am currently working on:
- The Refining of the UML Diagram
- The Listing of independent testable features and creation of according testcases
- Dependency of different features and an according implementation order.

Stay tuned!
