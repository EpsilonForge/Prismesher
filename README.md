# Prismesher (forked from Meshwell v1.0.7)

Prismesher is a Python wrapper around [GMSH](https://gmsh.info/) that provides:

(1) a Prism class that simplifies, to the point of automating, the definition of solids from arbitrary (multi)polygons with "buffered" extrusions;

(2) a simple API where such Prisms and regular GMSH OCC objects are specified in an ordered dictionary of mesh priority, and whose keys are then used to label the mesh entities and their interfaces unambiguously;

This version is derived from [meshwell](https://github.com/simbilod/meshwell), which continued evolving to support more functionality but diverged from [gplugins](https://github.com/gdsfactory/gplugins). We created this fork to support and further extend a gplugins-compatible mesher.

### Related projects

* [meshwell](https://github.com/simbilod/meshwell): The original repository for this library. 
* [gdsfactory](https://github.com/gdsfactory/gdsfactory): open-source plugin-rich layout software; meshwell is the backend to [gplugins](https://github.com/gdsfactory/gplugins)' gmsh module
* [femwell](https://github.com/HelgeGehring/femwell): open-source scikit-fem based finite-element simulations, with emphasis on photonics
* [DEVSIM](https://github.com/devsim/devsim): open-source finite-volume simulator, with emphasis on semiconductor TCAD

### Other notable GMSH Python interfaces:

* [gmsh](https://gitlab.onelab.info/gmsh/gmsh): the gmsh Python API itself has significantly improved over the years
* [pygmsh](https://github.com/meshpro/pygmsh): manipulate Python objects instead of gmsh entity tags
* [objectgmsh](https://github.com/nemocrys/objectgmsh): class wrappers around entities
* [gyptis](https://gyptis.gitlab.io/): uses basic gmsh for photonic geometries


