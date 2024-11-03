# REBCO-SCS
[HTS Modeling] Electro-Mechanical Coupled Model for REBCO Cylindrical Coils

This is a coupled electro-mechanical model for cylindrical REBCO coils. 
The electromagnetic component is based on T-A formulations for the 1-D array of REBCO layers in the coil. 
The mechanical component is based on a classic elastic solid model, considering the discrete contact boundary conditions between REBCO turns. 
Multiple General Extrusion units are set to extract the Lorenz force and displacement between the electromagnetic and mechanical components. 
The excitation process of this model is defined by the interpolation functions, enabling changes to the background field and operational current individually. 
