# Day 1 Contents

**GETTING STARTED WITH SLICER**

* [Introduction to Slicer - Official Slicer Documentation](https://slicer.readthedocs.io/en/latest/user_guide/getting_started.html)
* [Installing SlicerMorph and other extensions](https://github.com/SlicerMorph/Spr_2021/blob/main/TechCheckin/README.md)

### Slicer Basics (UI, Input/Output and Data) from Official Slicer Documentation
Some helpful links for getting started with Slicer
* [Navigating UI](https://slicer.readthedocs.io/en/latest/user_guide/user_interface.html)
* [Extension Manager and Catalogue](https://slicer.readthedocs.io/en/latest/user_guide/getting_started.html#extensions)
* [Loading Data and Saving (Slicer's Default way)](https://slicer.readthedocs.io/en/latest/user_guide/data_loading_and_saving.html)
* [Data Module and Subject Hierarchy explained](https://slicer.readthedocs.io/en/latest/user_guide/modules/data.html)

### Fundamental Slicer Modules
A list of built-in Slicer modules, their documentation, and a brief description of their functions.
* [Welcome](https://slicer.readthedocs.io/en/latest/user_guide/modules/slicerwelcome.html): is intended as a welcome screen and basic overview of the Slicer software. Provides links to official documentation, download sample data and install extension. Also, if a new stable is released, there will be notification here. 
* [Extension Manager](https://slicer.readthedocs.io/en/latest/user_guide/extensions_manager.html): allows you to install additional extension like SlicerMorph or SlicerBiomech.
* [Python console](https://slicer.readthedocs.io/en/latest/developer_guide/python_faq.html): allows you to execute python commands, and create scripted workflow. Also, you can additionally install new packages with pip_install("package"). Some helpful and commonly used python scripts can be found in the script repository [here](https://slicer.readthedocs.io/en/latest/developer_guide/script_repository.html).
* [Sample Data](https://slicer.readthedocs.io/en/latest/user_guide/modules/sampledata.html): sample datasets that are provided by Slicer and installed extensions. 
* [Data](https://slicer.readthedocs.io/en/latest/user_guide/modules/data.html): shows all data sets loaded into the scene and allows modification of basic properties and perform common operations on all kinds of data, without switching to other modules.
* [DICOM](https://slicer.readthedocs.io/en/latest/user_guide/modules/dicom.html): allows importing and exporting and network transfer of DICOM data.  
* [Volume](https://slicer.readthedocs.io/en/latest/user_guide/modules/volumes.html): shows information about volume nodes loaded into the scene. Useful for editing the image spacing of loaded volumes.
* [Volume Rendering](https://slicer.readthedocs.io/en/latest/user_guide/modules/volumerendering.html): (also known as volume ray casting) is a visualization technique for displaying image volumes as 3D objects directly - without requiring segmentation.
* [Models](https://slicer.readthedocs.io/en/latest/user_guide/modules/models.html): is used for changing the appearance of and organizing 3d surface models.
* [Transforms](https://slicer.readthedocs.io/en/latest/user_guide/modules/transforms.html): is used for creating, editing, and visualization of spatial transformations. Transformations are stored in transform nodes and define position, orientation, and warping in the world coordinate system or relative to other nodes, such as volumes, models, markups, or other transform nodes.
* [Markups](https://slicer.readthedocs.io/en/latest/user_guide/modules/markups.html): is used to create and edit markups (point list, line, angle, curve, closed curve, plane, ROI etc.) and adjust their display properties.
* [Segment Editor](https://slicer.readthedocs.io/en/latest/user_guide/modules/segmenteditor.html): is for specifying segments (structures of interest) in 2D/3D/4D images. Some of the tools mimic a painting interface like photoshop, but work on 3D arrays of voxels rather than on 2D pixels. The module offers editing of overlapping segments, display in both 2D and 3D views, fine-grained visualization options, editing in 3D views, create segmentation by interpolating or extrapolating segmentation on a few slices, editing on slices in any orientation.
* [Segmentations](https://slicer.readthedocs.io/en/latest/user_guide/modules/segmentations.html): module manages segmentations. Each segmentation can contain multiple segments, which correspond to one structure or ROI. Each segment can contain multiple data representations for the same structure, and the module supports automatic conversion between these representations (the default ones are: planar contour, binary labelmap, closed surface model), as well as advanced display settings and import/export features.
* [SegmentStatistics](https://slicer.readthedocs.io/en/latest/user_guide/modules/segmentstatistics.html): is a module for the calculation of statistics related to the structure of segmentations, such as volume, surface area, mean intensity, and various other metrics for each segment.
* [ScreenCapture](https://slicer.readthedocs.io/en/latest/user_guide/modules/screencapture.html): is for creating videos, image sequences, or lightbox image from 3D and slice view contents
* [CropVolume](https://slicer.readthedocs.io/en/latest/user_guide/modules/cropvolume.html): is for cropping volumes using an ROI, downsampling, or reorienting oblique data

### Loading Data (the preferred way)
* [ImageStacks Tutorial](https://github.com/SlicerMorph/Tutorials/blob/main/ImageStacks/README.md): This SlicerMorph module is the most versatile for loading in non-DICOM image stacks (.png, .jpg, .tif, .bmp). It's particular strength is that it allows the user to load in a downsampled or subset of the full volume to reduce file size.
* [DICOM Tutorial](https://github.com/SlicerMorph/Spr_2021/blob/main/Day_1/DICOM/DICOM.md): To load DICOM stacks, users need to use the DICOM module.
* [MorphoSourceImport Tutorial](https://github.com/SlicerMorph/Tutorials/blob/main/MorphoSourceImport/README.md): Image stacks can be loaded directly from MorphoSource.org but requires an account and an API.
* [SkyScanReconImport Tutorial](https://github.com/SlicerMorph/Tutorials/blob/main/SkyscanReconImport/README.md): A convience module for loading in image stacks generated by Bruker Skyscan micro-CT scanner.

### Volume Rendering 
* [Volume Rendering Tutorial](https://github.com/SlicerMorph/Spr_2021/blob/main/Day_2/VolumeRendering/VolumeRendering.md)
* [Lights](https://github.com/SlicerMorph/Spr_2021/blob/main/Day_2/Lighting/Lights.md): The Lights module in the Sandbox extension provides more options for editing the lighting in the 3D view.
* [Animator Tutorial](https://github.com/SlicerMorph/Tutorials/blob/main/Animator/README.md): The Animator module in the SlicerMorph extension helps create and export simple animations that involve rotating a volume, ROI cropping, and altering rendering properties.

[Turtle Dataset](https://gwu.box.com/s/3lr8n1ceqp0c4asz88j5o98r0pesvurc)

### Segmentation 
* [Segment Editor Tutorial](https://github.com/SlicerMorph/Tutorials/tree/main/Segmentation)

### Measuring Morphology

### Learning Exercises
1. Download this non-DICOM image stack of an [arboreal salamander CT scan](), unzip it and load it into 3D Slicer using the Image Stacks extension. Note that the file size is large so you must use the ROI and downsampling features.
2. Download this DICOM data set of a [turtle skull](https://gwu.box.com/s/3lr8n1ceqp0c4asz88j5o98r0pesvurc), unzip it and load it into 3D Slicer. Generate a 3D rendering a play around with the settings to see if you can visualize both both and soft tissue.
3. With either data set, follow the Animator module tutorial and see if you can create a video with your volume rendering.
4. Work through the Segment Editor tutorial using the sample data, then see if you can use those tools to separate out the bones in the turtle data set or the salamander data set.

