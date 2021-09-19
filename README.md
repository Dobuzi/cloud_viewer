# Cloud Viewer

3D Viewer for Point Cloud Data with pcl

1. Put the data into data folder
```
mkdir -p build/data
```
- Move the pcd file into build/data folder

2. Edit the source file 
- Edit the file name on line 36 of src/cloud_viewer.cpp

3. Make the source
```
cd build
cmake ..
make
./cloud_viewer
```
