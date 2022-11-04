# Gaussian-curvature-calculation
Calculating vertex-wise Gaussian curvature of a given 3D triangular mesh in Python. The Curvature roughly describes how convex or concave a certain point is.


The formula for calculating Gaussian curvature on triangular meshes is:

kg=2π−∑θjAi



Triangular meshes are normally stored as two arrays. One nx3 array containing the 3D vertex coordinates (normally double) and one mx3 array
containing the triangles (normally integers). Each triangle is represented by three integer values, and these denote the indices of the vertices that
are connected by the triangle. So the triangle [2, 17, 4] has its corner points at the 3D coordinates stored in vertices[2], vertices[17] and vertices[4].
