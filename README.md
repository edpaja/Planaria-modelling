# Planaria-modelling
UFBA planaria modelling for 3D printing and molding

Planarians are a type of flatworm that can be found in marine, freshwater, or terrestrial environments. In this project, we were most interested by the locomotion of planarians in water. My main contribution to studying this biolocomotion was in designing 3D-printable molds to form shapes that may recreate this motion.

You will find in this repository the python codes written to model any surface in 3 dimension and also some that model Enneper surfaces. In these scripts I use various packages that use either Delaunay triangulation algorithms or more specific mesh creation algorithms. I also added the stl files that were used for the 3d printing. It is important to note that to use the python files you need to adapt the file path at the end of the script to your computer.

The difficulty in this project wasn't actually just modelling the right shapes, it was to find the right mesh forming algorithms so that the stl files could be read properly by the 3D printing softwares. Since we were molding using very fragile polymer materials, the mold had to be very precise and smooth. This is why I didn't just use blender or FreeCAD to model the shapes. Additionally, these scripts give much more liberty with the parameters for the mesh creation.
