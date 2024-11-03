# REBCO-SCS
[HTS Modeling] Electro-Mechanical Coupled Model for REBCO Cylindrical Coils

This is a coupled electro-mechanical model for cylindrical REBCO coils. 
The electromagnetic component is based on $T-A$ formulations for the 1-D array of REBCO layers in the coil. 
The mechanical component is based on a classic elastic solid model, considering the discrete contact boundary conditions between REBCO turns. 
Multiple General Extrusion units are set to extract the Lorenz force and displacement between the electromagnetic and mechanical components. 
The excitation process of this model is defined by the interpolation functions, enabling changes to the background field and operational current individually. 

# Authors Information
This numerical method was first proposed by Yufan Yan.
She was with the Department of Mechanical Engineering, Tsinghua University, Beijing 100084, China, and is now with Lawrence Berkeley National Laboratory, Berkeley, CA 94720, USA.

The shared model file, 'SCS_coupled_comsol62.mph,' was created by Liangjun Shao using COMSOL Multiphysics 6.2 at Tsinghua University, Beijing 100084, China.

# Reference
The model was also shared at <https://htsmodelling.com/model-files/electro-mechanical-coupled-model-for-rebco-cylindrical-coils>.

Please kindly refer to the following papers: <br>
[1] Yan Y, Song P, Xin C, Guan M, Li Y, Liu H and Qu T 2021 Screening-current induced mechanical strains in REBCO insert coils Supercond. Sci. Technol. 34, 085012 <br>
[2] Shao L et al 2024 Experimental study on screening-current induced strain in REBCO insert coils: under critical current control and operation current cycles Supercond. Sci. Technol. 37, 065014
