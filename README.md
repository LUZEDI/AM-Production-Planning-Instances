# AM-Production-Planning-Instances
Instances of  AM Production Planning

The folder "3D models" includes 100 3D models with support structures in STL format.

The folder "Instances" contains 30 AMPP instances. Each file records the part ID of the 3D models used. M2 files use machines 3 and 4, and M4 files use all four machines.

The folder "part machine data" contains 100 parts and four machines. The parameters of parts include the width, length, and height of the minimum bounding box of the parts, the part's volume and the support structure volume. The parameters of machines include width (W), length (L), height (H) of the machines' building space, setup time (ST), part scanning speed/building speed (VT), support structure scanning/building speed (SPT), and powder coating/recoating speed (HT).

projection.txt records the coordinates of the 100-part projections derived from the 3D models. For polygon p1 with vertices (x11, y11), (x12, y12), (x13, y13) and hole vertices (x14, y14), (x15, y15), (x16, y16), coordinates are recorded as:

x11 x12 x13 NaN x14 x15 x16

y11 y12 y13 NaN y14 y15 y16

Updated on 16 Nov 2024.
