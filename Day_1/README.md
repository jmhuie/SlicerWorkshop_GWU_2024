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

### Loading Data (with SlicerMorph)
[ImageStacks](https://github.com/SlicerMorph/Spr_2021/blob/main/Day_1/ImageStacks/ImageStacks.md)
[SkyScanReconImport](https://github.com/SlicerMorph/Spr_2021/blob/main/Day_1/ImageStacks/ImageStacks.md#skyscanreconimport)
[MorphoSourceImport](https://github.com/SlicerMorph/Spr_2021/blob/main/Day_1/MorphoSourceImport/MorphoSourceImport.md)


### Volume Rendering Basics


### Segmentation Basics
* [Segment Editor Documentation](https://github.com/SlicerMorph/Tutorials/blob/main/Segmentation/README.md)
* [Segment Editor Tutorial](https://github.com/SlicerMorph/Tutorials/tree/main/Segmentation)

### Measuring Morphology Basics



### SlicerMorph Specific Functionalities for Loading Data and Saving 
* [ImageStacks](https://github.com/SlicerMorph/Spr_2021/blob/main/Day_1/ImageStacks/ImageStacks.md)
* [SkyScanReconImport](https://github.com/SlicerMorph/Spr_2021/blob/main/Day_1/ImageStacks/ImageStacks.md#skyscanreconimport)
*	~[MorphoSourceImport](https://github.com/SlicerMorph/Spr_2021/blob/main/Day_1/MorphoSourceImport/MorphoSourceImport.md)~
* [ExportAs](https://github.com/SlicerMorph/Spr_2021/blob/main/Day_1/ExportAs/ExportAs.md)

### [Working with DICOMs](https://github.com/SlicerMorph/Spr_2021/blob/main/Day_1/DICOM/DICOM.md)

### Important Slicer modules 
*	[Models](https://github.com/SlicerMorph/Spr_2021/blob/main/Day_1/Models/Models.md) 
*	[SampleData-Volumes-CropVolume](https://github.com/SlicerMorph/Spr_2021/blob/main/Day_1/CropVolume/CropVolume_and_Volumes.md)
*	[Transforms](https://github.com/SlicerMorph/Spr_2021/blob/main/Day_1/Transforms/Transforms.md)