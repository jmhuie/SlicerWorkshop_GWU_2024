# Day 2 Contents

### Learning Objectives
1. Visualize 3D data and generate graphics 
2. Analyze and measure morphology 
3. Use SlicerMorph for 3D geometric morphometrics 
4. Utilize resources to keep learning about 3D Slicer

### More Advanced Rendering Tools
* [Lights](https://github.com/SlicerMorph/Spr_2021/blob/main/Day_2/Lighting/Lights.md): The Lights module in the Sandbox extension provides more options for editing the lighting in the 3D view.
* [Colorize Volume](https://github.com/SlicerMorph/Tutorials/tree/main/ColorizeVolume): The Colorize Volume modules allows for the volume rendering of multiple segmented structures based on segment colors.
* [Animator Tutorial](https://github.com/SlicerMorph/Tutorials/blob/main/Animator/README.md): The Animator module in the SlicerMorph extension helps create and export simple animations that involve rotating a volume, ROI cropping, and altering rendering properties.

### Python Scripting
* [Script Repository](https://slicer.readthedocs.io/en/latest/developer_guide/script_repository.html): This is a repository of python scripts that are useful for a variety of functions. A good resources for learning how to code in python for 3D Slicer.

### Advanced Markups
* [Intro to Markups](https://github.com/SlicerMorph/Tutorials/blob/main/Markups_1/README.md)
* [Resampling a Curve](https://github.com/SlicerMorph/Tutorials/blob/main/Markups_2/README.md)
* [Creating a template](https://github.com/SlicerMorph/Tutorials/blob/main/Markups_3/README.md)

### SlicerMorph Landmarking Tools 
* [Patch Semilandmarks Tutorial](https://github.com/SlicerMorph/Tutorials/tree/main/CreateSemiLMPatches/README.md): The CreateSemiLMPatches module can be used to create patches of semilandmarks based on fixed landmarks. 
* [Pseudolandmarks Tutorial](https://github.com/SlicerMorph/Tutorials/tree/main/PseudoLMGenerator): The PseudoLMGenerator module can be used to create semilandmarks when no fixed landmarks exist. 
* [Selecting and editing markups](https://github.com/SlicerMorph/Tutorials/tree/main/MarkupsEditor): This tutorial demonstrates how select whole regions of landmarks using a curve.
* [Merge Landmarks](https://github.com/SlicerMorph/Tutorials/blob/main/MergeMarkups/README.md): The MergeMarkups module can be used to combine separate curves, as well as fixed and semi landmarks into a single file.
* [Transferring Patch Landmarks](https://github.com/SlicerMorph/SlicerMorph/blob/23d21fd9f8d09c3e0a4402ea58fba9f0352217c8/Docs/ProjectSemiLM/README.md): ProjectSemiLM module can be used to transfer patch landmarks but requires fixed references for every specimen.
* [Transferring Landmarks with ALPACA](https://github.com/SlicerMorph/Tutorials/blob/main/ALPACA/README.md): The ALPACA module can be used to transfer the landmarks from one model to another without any fixed references.
* [Transferring Landmarks with MALPACA](https://github.com/SlicerMorph/Tutorials/tree/main/MALPACA/README.md): MALPACA expands the utility of ALPACA by taking advantage of more reference models


### Generalized Procrustes Analysis
* [GPA Tutorial 1](https://github.com/SlicerMorph/Tutorials/tree/main/GPA_1/README.md): This tutorial demonstrates how to use the GPA module to conduct the analysis
* [GPA Tutorial 2](https://github.com/SlicerMorph/Tutorials/blob/main/GPA_2/README.md): This tutorial demonstrates how to visualize variation in morphospace.
* [SlicerMorph to R](https://github.com/SlicerMorph/Tutorials/blob/main/GPA_3/README.md): This tutorial demonstrates how to import SlicerMorph GPA results in R
* [Geomorph to SlicerMorph](https://github.com/SlicerMorph/SlicerMorphR?tab=readme-ov-file#how-to-run-a-geomorph-analysis-with-slicermorph-data-and-get-the-results-back-into-slicermorph-for-visualization): How to export geomorph R results to visualize in SlicerMorph


### Learning Exercises
1. Pick a data set, follow the Animator module tutorial and see if you can create a video with your volume rendering.
2. Use a sample data model and play around with the different landmarking tools
3. Link to the Mouse Models and LMS for the ALPACA tutorial: https://github.com/SlicerMorph/mouse_models

