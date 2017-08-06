# SSSI
Seismic Simulation, Survey, and Imaging (Matlab, C, MPI)

The S3I is designed to provide a package for numerical simulations in explo- ration geophysics. It targets students as well as professionals in exploration geophysics. The most important purpose is to provide an easy, well or- ganized library to the interested users to learn some popular algorithms and numerical schemes in exploration geophysics rather than the high per- formance of the computation. Thus, MATLAB is adopted as the coding platform for the readability of the code, ease of data visualization, etc. It is well known that nested for-loops in MATLAB is much slower than the complied languages. In order to make the S3I efficient, we use C to gener- ate MEX-files for some frequently invoked functions. Currently, the major functions have been implemented in S3I are as follows:
• Acoustic wave simulation for 2D/3D
• Elastic wave simulation for 2D
• Kirchhoff’s migration
• Reverse Time Migration (RTM)
• Least Square RTM (LSRTM)
• Full Waveform Inversion (FWI)
With this user guide, the user may easily and quickly start using the S3I for appropriate applications. An exhaustive review of numerical simulation of wave equation and seismic imaging is out of the scope of this user guide. Therefore, only necessary equations are showed and explained to keep the contents concise. The Interested user is referred to the references for more details.
