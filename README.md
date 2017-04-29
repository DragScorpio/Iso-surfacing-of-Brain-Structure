# Iso-surfacing-of-Brain-Structure

Project - Isosurfaces
We have provided 3D scalar data sets in the file head.120.vtk. These are binary files of a CT scan of a human head, from the Visible Man dataset. Actually, the datasets we are providing have been resampled from the original scan, in order to lower the resolution (making it faster to visualize).
The head.120.vtk file contains the data for a 120x120x130 grid. Each sampled data value is an ``unsigned char'': an unsigned 8-bit integer value between 0 and 255.
head_6.tcl - This TCL script will read the given data and visualize it using the iso- surfaces. The given data is a CT scan of human head. A contour filter is used to visualize the voxels that correspond to specific isovalues. The iso values are chosen to highlight the Skin and the Bone data in the CT scan. By setting the transparency (or alpha value) in the color maps we can visualize more than one isosurface. This gives us the ability to see through the physical outer layer.
In order to visualize both the iso surfaces two pipelines were used. The data is read from a common source head.120.vtk, but two similar pipelines were used for the two isosurfaces. The structure of both the pipelines were same.
Your work:
1. Read the TCL code. And rewrite it to Python code and run it.
2. Try different iso-values, and try to change the color and opacity of the isosurfaces.
3. Save some interesting pictures you find in this process and put them inside a report.
4. Compare (Hue, Saturation, and Luminance) and (Red, Green, Blue) by google the internet. And write into the report.
5. (Required for graduate students, Optional for undergraduate students) Please write a report for all the vtk filters used in the code. You need to discuss the purpose for those vtk filters. And whether we can remove those filters or substitute those filters using other filters.
