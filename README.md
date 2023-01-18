# Analysis-of-Point-Net-Architecture-

Deep Learning on Point Sets for 3D Classification is revolutionized by PointNet architecture. PointNet architecture is evaluated as the state of the art method in 3d
classification. In this Studienarbeit, PointNet architecture is applied to 2D image data and evaluated. PointNet is highly efficient and effective on 2D data. Empirically, it shows strong performance on par or even better than the usual three layered Convolutional classification network. In this project, it is explained theoritically why the network performs relatively very well.

Real world is 3 dimensional rather than most Computer Vision represented in 2 dimensions. three dimensions consists of three coordinates in a reference coordinate
axis considered. A random point in 3 dimension can be mathematically represented as:
                                                                P = (a, b, c)
A 3d object is a random combination of many three dimensional points like p in equation. There are multiple data representations of three dimensional data.
Point Cloud, 3D Mesh, Voxel Grid, Group of 2D images are mostly used. 

Point cloud is a group of points in 3D space. usually point cloud has three coordinate points and sometimes also has RGB values and intensity. Point cloud represents a
shape in 3D or a 3D object. Point clouds are produced by many sources like Lidar, Depth Sensor, Time of Flight sensor and many more 3D scanners. There are multiple
fields in which point clouds are used like to create CAD models, quality inspection, rendering and mass customization.

Point Cloud is unlike an image, an ordered set of 3 dimensional points in a reference frame of Cartesian coordinate system on the surface of objects.
Mathematically Point Cloud can be represented as:
                                                                 P = {(ax, bx, cx) | x ∈ M}
where a,b and c are the coordinates and it contains M number of points. Sometimes addition to point coordinates, we also have RGB color information for
every point. 
In Other representation like mesh, we have vertices and edges.
                                                                 Prgb = {(ax, bx, cx, Rx, Gx, Bx) | x ∈ M}
