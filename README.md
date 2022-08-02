# Precision-tool
Python script and plugin that displays extended information on selected geometry to the Maya viewport.

This tool displays to users the mesh components and their positions to the maya viewport above the 
selected mesh. Decimal point precision and the selection of component display is handled through the 
custom maya window when the script is executed.

Displayable information:
1) vtx positions for every vertex on the selected mesh (with adjustable precision)
2) e positions of every edge on the selected mesh (with adjustable precision)
3) f positions of every face on the selected mesh (with adjustable precision)
4) individual component position displays for individually selected components on the mesh (with adjustable 
   precision)

A rename option is also available if a user decides to change the name of the geometry or a certain 
annotation.

//WARNING//

This tool is compatible with Python 2.7.7 and Maya 2019, 2020
