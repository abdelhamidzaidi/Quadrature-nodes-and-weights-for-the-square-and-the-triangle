# Quadrature-nodes-and-weights-for-the-square-and-the-triangle
The subfolder Triangle contains the nodes and the weights for positive interior symmetric quadrature rules for the triangle T0= [(0,0);(1,0);(0,1)]
The subfolder Square contains the nodes and the weights for positive interior symmetric quadrature rules for the square S0=[-1,1]^2
Example
NodSqD2 is a matrix 2x4, which contains the nodes of the quadrature rule for S0 of strenghth 2. 
NodSqD2(:,i) represents the coordinates of the i-th node
WSqD2 is a vector 1x4, which contains the weights of the quadrature rule for S0 of strenghth 2.
WSqD2(i) is the weight of NodSqD2(:,i)
type load -mat NodSqD2 to load the matrix NodSqD2 in the workspace
type load -mat WSqD2 to load the matrix NodSqD2 in the workspace
It is the same for the triangle
