﻿---
title: RvmLoadOptions class
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 240
url: /python-net/aspose.threed.formats/rvmloadoptions/
is_root: false
---

## RvmLoadOptions class

Load options for AVEVA Plant Design Management System's RVM file.



The RvmLoadOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [RvmLoadOptions(content_type)](/3d/python-net/aspose.threed.formats/rvmloadoptions/__init__/#FileContentType) | Construct a [RvmLoadOptions](/3d/python-net/aspose.threed.formats/rvmloadoptions) instance |
| [RvmLoadOptions()](/3d/python-net/aspose.threed.formats/rvmloadoptions/__init__/#) | Construct a [RvmLoadOptions](/3d/python-net/aspose.threed.formats/rvmloadoptions) instance |


### Properties
| Property | Description |
| :- | :- |
| [file_format](/3d/python-net/aspose.threed.formats/rvmloadoptions/file_format) | Gets the file format that specified in current Save/Load option. |
| [encoding](/3d/python-net/aspose.threed.formats/rvmloadoptions/encoding) | Gets or sets the default encoding for text-based files.
| [file_system](/3d/python-net/aspose.threed.formats/rvmloadoptions/file_system) | Allow user to handle how to manage the external dependencies during load/save. |
| [lookup_paths](/3d/python-net/aspose.threed.formats/rvmloadoptions/lookup_paths) | Some files like OBJ depends on external file, the lookup paths will allows Aspose.3D to look for external file to load. |
| [file_name](/3d/python-net/aspose.threed.formats/rvmloadoptions/file_name) | The file name of the exporting/importing scene.
| [generate_materials](/3d/python-net/aspose.threed.formats/rvmloadoptions/generate_materials) | Generate materials with random colors for each objects in the scene if color table is not exported within the RVM file.
| [cylinder_radial_segments](/3d/python-net/aspose.threed.formats/rvmloadoptions/cylinder_radial_segments) | Gets or sets the number of cylinder's radial segments, default value is 16 |
| [dish_longitude_segments](/3d/python-net/aspose.threed.formats/rvmloadoptions/dish_longitude_segments) | Gets or sets the number of dish' longitude segments, default value is 12 |
| [dish_latitude_segments](/3d/python-net/aspose.threed.formats/rvmloadoptions/dish_latitude_segments) | Gets or sets the number of dish' latitude segments, default value is 8 |
| [torus_tubular_segments](/3d/python-net/aspose.threed.formats/rvmloadoptions/torus_tubular_segments) | Gets or sets the number of torus' tubular segments, default value is 20 |
| [rectangular_torus_segments](/3d/python-net/aspose.threed.formats/rvmloadoptions/rectangular_torus_segments) | Gets or sets the number of rectangular torus' radial segments, default value is 20 |
| [center_scene](/3d/python-net/aspose.threed.formats/rvmloadoptions/center_scene) | Center the scene after it's loaded. |
| [attribute_prefix](/3d/python-net/aspose.threed.formats/rvmloadoptions/attribute_prefix) | Gets or sets the prefix of the attributes that were defined in external attribute files,
| [lookup_attributes](/3d/python-net/aspose.threed.formats/rvmloadoptions/lookup_attributes) | Gets or sets whether to load attributes from external attribute list file(.att/.attrib/.txt), default value is true. |


### See Also

* module [aspose.threed.formats](../)
* class [LoadOptions](/3d/python-net/aspose.threed.formats/loadoptions)