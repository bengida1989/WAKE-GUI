WAKE-GUI Toolbox
+++++++++++++++++++++++++++++++++++++++++++++++++
.. image:: WAKE-GUI_capabilities.JPG

What is it?
------------

+ WAKE-GUI (v1.6) is a collection of Matlab subroutines and GUI for post-processing of wake data measured using Particle Image Velocimetry (PIV), and analyzed by OpenPIV (or other) software. 

+ WAKE-GUI accepts PIV wake data as .mat files extracted from the OpenPIV-spatial-analysis-toolbox. Future version of the code will also support .vec files. 

+ WAKE-GUI allows the user to re-construct a full unsteady wake image from a set of PIV images recorded behind bodies/birds using a cross-correlation algorithm, which overlaps consecutive images. 

+ WAKE-GUI allows the estimation of drag and cumulative circulatory lift forces from the wake data, thus enabling the user to estimate the loads exerted on the body generating the wake.


How to cite this work?
------------

Ben-Gida, Hadar; Gurka, Roi; Liberzon, Alex (2020): OpenPIV - WAKE-GUI Matlab Toolbox. figshare. Software. https://figshare.com/articles/OpenPIV_-_WAKE-GUI_Matlab_ToolBox/12331007


Support
------------

+ Please note that the current WAKE-GUI version (1.6) supports Matlab 2015a-2020a versions.

+ source code for the project is maintained at
  `<https://github.com/OpenPIV/WAKE-GUI>`_
  `<https://github.com/bengida1989/WAKE-GUI>`_
  
+ to modify these pages:

  - git clone https://github.com/OpenPIV/WAKE-GUI.git
  - git clone https://github.com/bengida1989/WAKE-GUI.git
 
  - from Matlab shell run::

      >> WAKE 


Developer
++++++++++

Dr. Hadar Ben-Gida
