# RayTracerInC
Simple Ray tracer with my own math library


## Sample Image generated by this rayTracer

### Using 256 rays per pixel and 1000 ray counts

![test](https://user-images.githubusercontent.com/56222543/217295338-0efecda9-f626-4c71-a151-8e24dd177460.jpg)

### Using 500 rays per pixel and using multi-threading support
![test](https://user-images.githubusercontent.com/56222543/233251704-b224f793-3128-4b61-a501-f288edb8c9fa.jpg)


## Build Instructions for windows

For building the project in windows, you need to have Visual studio installed in your machine. Although having a cpp compiler and gnu make will work fine.

Open the project in cmd prompt, then type the following commands, 

This will show you the various types of actions you can take for setup the project in your machine.
```batch
.\generate_project.bat --help
```

This will generate the visual studio 2022 files for your machine. 
```batch
.\generate_project.bat vs2022
```

Now navigate to RayTracer from your file explorer and open the .sln file.

After that you can build and run the project using visual studio editor.
