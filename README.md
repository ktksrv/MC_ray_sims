# Stochastic View Factor Calculation of Radiation View Factor for Perpendicular Plates with One Common Edge
The repo contains a MATLAB code to implement an element-based Monte Carlo algorithm to compute the view factor of perpendicular square plates having one common edge
## Finite Element Monte Carlo Methodology for Estimating Radiation View Factor
1. Mesh the involved  geometries through   a preferred type of element
2. From a random point inside each element, generate a random ray obeying Knudsen's cosine law
3. To find the view factor of an element-1 w.r.t to element-2 (i.e F<sub>12</sub>), find the fraction of rays emanating from element-1 and intersecting element-2 to the total number of rays generated from element-1
4. Following this procedure you will obtain  F<sub>12</sub> for each element of the meshed geometry-1, now average element-wise  F<sub>12</sub> values to get an estimation of  F<sub>12</sub> for the involved geometries
