1. run simulation with any of the config files
..\..\bin\FLIP_simulator\FLIP_simulator.exe config.yaml

2. visualize the result with "buckling.hipnc"

It is also possible to change the liquid source geometry in Houdini.


Caution:
1. use the houdini to generate the fluid source. The name of sdf field must be "source"

2. the grid size of vdb must match the config.yaml