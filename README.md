# SlicerTutorials
Compilation of 3D Slicer Tutorials


3D Slicer 2-Day Workshop 

Date & Time: TBD
Location: TBD

Learning Objectives
After this workshop you should be familiar with how to…
L1.  Import CT scans from image stacks
L2.  Segment CT scans and generate models
L3.  Analyze and measure morphology 
L4.  Visualize 3D data and generate graphics
L5.  Use SlicerMorph for 3D geometric morphometrics
L6.  Utilize resources to keep learning about 3D Slicer

Schedule (tentative)
Day 1: Intro to 3D Slicer, loading data, segmenting basics, measuring morphology (L1, L2, L3, L6)
Day 2: Advanced visualization, 3D Geometric Morphometrics, other advanced topics (L4, L5, L6) 

Introduction to 3D Slicer modules
1.	Welcome: is intended as a welcome screen and basic overview of the Slicer software. Provides links to official documentation, download sample data and install extension. Also, if a new stable is released, there will be notification here. 
2.	Extension Manager: allows you to install additional extension like SlicerMorph
3.	Python console: allows you to execute python commands, and create scripted workflow. Also, you can additionally install new packages with pip_install("package")
4.	Layout Manager: change the layout of 2D and 3D viewers in the main application window (custom layout can be created). 
5.	Sample Data: Sample Datasets that are provided by Slicer and installed extension. When you are reporting an issue on the forum, it is critical to replicate it using one of the sample datasets. 
6.	Data: shows all data sets loaded into the scene and allows modification of basic properties and perform common operations on all kinds of data, without switching to other modules.
7.	Volume Rendering: (also known as volume ray casting) is a visualization technique for displaying image volumes as 3D objects directly - without requiring segmentation.
8.	Transforms: is used for creating, editing, and visualization of spatial transformations. Transformations are stored in transform nodes and define position, orientation, and warping in the world coordinate system or relative to other nodes, such as volumes, models, markups, or other transform nodes.

L1. Importing Data
1.	DICOM: allows importing and exporting and network transfer of DICOM data.  
2.	ImageStacks: Imports non-DICOM image sequences (TIF/PNG/JPG/BMP) into 3D Slicer. ImageStacks offers additional features such as quickly previewing large datasets at very low resolution, specifying an ROI to import only a subset of the data, downsampling, skipping slice(s) along the Z plane, and reverse the stack order. Users can also specify the voxel spacing for their dataset at the import time.
3.	MorphoSourceImport (SlicerMorph Extension): This module enables to query and download data from MorphoSource website directly into the Slicer. The user has to register with the MorphoSource website and create an API key. 
4.	ImportFromURL (SlicerMorph Extension): Imports any Slicer supported dataset (3D models, volumes, markups etc) from the provided URL. It assumes the file name and extension are available as part of the URL or the correct data format is known.

L2. Segmenting CT Scans
1.	Segment Editor: is for specifying segments (structures of interest) in 2D/3D/4D images. Some of the tools mimic a painting interface like photoshop, but work on 3D arrays of voxels rather than on 2D pixels. The module offers editing of overlapping segments, display in both 2D and 3D views, fine-grained visualization options, editing in 3D views, create segmentation by interpolating or extrapolating segmentation on a few slices, editing on slices in any orientation.
2.	Segmentations: module manages segmentations. Each segmentation can contain multiple segments, which correspond to one structure or ROI. Each segment can contain multiple data representations for the same structure, and the module supports automatic conversion between these representations (the default ones are: planar contour, binary labelmap, closed surface model), as well as advanced display settings and import/export features.

L3. Analyzing and Measuring Morphology
1.	SegmentStatistics: is a module for the calculation of statistics related to the structure of segmentations, such as volume, surface area, mean intensity, and various other metrics for each segment.
2.	Markups: is used to create and edit markups (point list, line, angle, curve, closed curve, plane, ROI etc.) and adjust their display properties.

L4. Generating Graphics
1.	Lights (Sandbox Extension): customize lighting in 3D views.
2.	Colorize Volume (Sandbox Extension): Create a colored (RGB) intensity image from a segmentation of a scalar volume. Allows you manipulate the opacity, threshold and other visualization settings: 
3.	ScreenCapture: is for creating videos, image sequences, or lightbox image from 3D and slice view contents
4.	Animator (SlicerMorph Extension): This module enables simple keyframe-based animation of 3D volumes. It supports interpolation of ROI, rotations, and transfer functions for volume rendering. Individual time-tracks can be set to each of these actions.

L5. 3D Geometric Morphometrics
1.	Markups: is used to create and edit markups (point list, line, angle, curve, closed curve, plane, ROI etc.) and adjust their display properties.
2.	PseudoLMGenerator (SlicerMorph Extension): uses a 3D model’s geometry, or its geometric approximation, to create a dense template of pseudo-landmarks. The landmark placement is constrained to the external surface of the mesh
3.	ALPACA (also FastModelAlign) (SlicerMorph Extension): provides fast landmark transfer from a 3D model and its associated landmark set to target 3D model(s) through point cloud alignment and deformable mesh registration. FastModelAlign is built-on ALPACA, and can be used to scale and register (affine) 3D models.
4.	GPA (SlicerMorph Extension): This module performs Generalized Procrustes Analysis (GPA) with or without scaling shape configurations to unit size, conducts principal component analysis (PCA) of GPA aligned shape coordinates, provides graphical output of GPA results and real-time 3D visualization of PC warps either using the landmarks of mean shape, or using a reference model that is transformed into the mean shape.

L6. Additional Resources
•	Slicer User Documentation
https://slicer.readthedocs.io
•	SlicerMorph Tutorials:	
https://github.com/SlicerMorph/Tutorials
•	TBD


Citing 3D Slicer
To cite 3D Slicer as a general-purpose biomedical visualization platform, please use: 

Kikinis, R., Pieper, S. D., & Vosburgh, K. G. (2014). 3D Slicer: A Platform for Subject-Specific Image Analysis, Visualization, and Clinical Support. In Intraoperative Imaging and Image-Guided Therapy (pp. 277–289). Springer, New York, NY. https://doi.org/10.1007/978-1-4614-7657-3_19

If you use SlicerMorph in your research, please cite one or more of these publications as appropriate.
•	SlicerMorph as a general platform for digital morphology: Rolfe S, Pieper S, Porto A, Diamond K, Winchester J, Shan S, Kirveslahti H, Boyer D, Summers A, Maga AM (2021) SlicerMorph: An open and extensible platform to retrieve, visualize and analyse 3D morphology. Methods in Ecology and Evolution, 12(10):1816–1825. https://doi.org/10.1111/2041-210X.13669 (Open access)
•	For CreateSemiLMPatches, ProjectSemiLMs, PseudoLMGenerator: Rolfe, S., Davis, C., & Maga, A. M. (2021). Comparing semi-landmarking approaches for analyzing three-dimensional cranial morphology. American Journal of Physical Anthropology. 175(1):227-237. https://doi.org/10.1002/ajpa.24214
•	For ALPACA: Porto, A., Rolfe, S. M., & Maga, A. M. (2021). ALPACA: A fast and accurate approach for automated landmarking of three-dimensional biological structures. Methods in Ecology and Evolution. 12:2129–2144. http://doi.org/10.1111/2041-210X.13689 (Open access).
•	For MALPACA (Multi-Template ALPACA): Zhang, C., Porto, A., Rolfe, S., Kocatulum, A., & Maga, A. M. (2022). Automated landmarking via multiple templates. PLOS ONE. 17(12). e0278035. https://doi.org/10.1371/journal.pone.0278035 (Open access).
•	For MEMOS: Rolfe SM, Whikehart SM, Maga AM (2023) Deep learning enabled multi-organ segmentation of mouse embryos. Biology Open, 12(2):bio059698. https://doi.org/10.1242/bio.059698 (open-access)



![image](https://github.com/jmhuie/SlicerTutorials/assets/52302862/a9e0c825-6050-4d7b-a794-9110acea0cc4)
