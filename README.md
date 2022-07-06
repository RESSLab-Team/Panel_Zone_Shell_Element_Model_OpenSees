# Panel_Zone_Shell_Element_Model_OpenSees
In this repository, the FourNodeQuad2D3DOF element is provided.

This element was modified by Skiadopoulos and Lignos at EPFL. More details are found in:

https://onlinelibrary.wiley.com/doi/abs/10.1002/eqe.3629

Both .cpp and .h file formats are included for one to integrate to the OpenSees environment.

An example is also provided that utilizes the developed FourNodeQuad2D3DOF element: Interior_Subassembly_Shell_Panel_Example.tcl

In this example the highly inelastic panel zone is modeled with the developed element and the interior beam-to-column subassembly is imposed to cyclic symmetric loading protocol. 

An OpenSees executable that includes the developed element is also provided. 

However, it is higly recommended to keep the newest updates of OpenSees by explicitly compiling the FourNodeQuad2D3DOF element. Instructions for this are found in the following link: 

https://github.com/RESSLab-Team/OpenSees-Instructions
