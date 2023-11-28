# TerrainGen
Terrain Generation Script in Unity Engine based on the tutorial from [@SebastianLague](https://www.youtube.com/playlist?list=PLFt_AvWsXl0eBW2EiBtl_sxmDtSgZBxB3) on YouTube.
## General Concept:
1. Points are generated within a 2D Plane in the horizontal orientation
2. The vertical position of each point can be varied according to a perlin noise map so that the gradients (hills in terrain) are not too steep
3. The script iterates through the points, connects 3 neighbouring points and makes a triangular face (mesh)
4. The Mesh for each triangle gets assigned a different colour based on it's vertical position. Lower get blue (=water) and higher ones get brown/red (=mountains)

