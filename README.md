# penrose
scripts to generate penrose tilings

generate-penrose3D.py: Generates a 3D penrose tiling in the bounding box of size len x len x len and prints it to a csv-file
                       one edge per row in format "x1, y1, z1, x2, y2, z2".
                       
thick-penrose3D.py:    Reads the file generated by 'generate-penrose3D.py' and creates an stl-file.

generate-penrose2D.py: Generates a 2D penrose tiling in the bounding box of size len x len and prints it to a csv-file
                       one edge per row in format "x1, y1, x2, y2".
