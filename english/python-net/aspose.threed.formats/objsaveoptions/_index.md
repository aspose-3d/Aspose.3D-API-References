﻿---
title: ObjSaveOptions class
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 190
url: /python-net/aspose.threed.formats/objsaveoptions/
is_root: false
---

## ObjSaveOptions class

Save options for wavefront obj file



**Inheritance:** [`ObjSaveOptions`](/3d/python-net/aspose.threed.formats/objsaveoptions) → 
[`SaveOptions`](/3d/python-net/aspose.threed.formats/saveoptions) → 
[`IOConfig`](/3d/python-net/aspose.threed.formats/ioconfig)



The ObjSaveOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [`__init__(self)`](/3d/python-net/aspose.threed.formats/objsaveoptions/__init__/#) | Constructor of [`ObjSaveOptions`](/3d/python-net/aspose.threed.formats/objsaveoptions) |


### Properties
| Property | Description |
| :- | :- |
| [file_format](/3d/python-net/aspose.threed.formats/objsaveoptions/file_format) | Gets the file format that specified in current Save/Load option. |
| [encoding](/3d/python-net/aspose.threed.formats/objsaveoptions/encoding) | Gets or sets the default encoding for text-based files.<br/>Default value is null which means the importer/exporter will decide which encoding to use. |
| [file_system](/3d/python-net/aspose.threed.formats/objsaveoptions/file_system) | Allow user to handle how to manage the external dependencies during load/save. |
| [lookup_paths](/3d/python-net/aspose.threed.formats/objsaveoptions/lookup_paths) | Some files like OBJ depends on external file, the lookup paths will allows Aspose.3D to look for external file to load. |
| [file_name](/3d/python-net/aspose.threed.formats/objsaveoptions/file_name) | The file name of the exporting/importing scene.<br/>This is optional, but useful when serialize external assets like OBJ's material. |
| [export_textures](/3d/python-net/aspose.threed.formats/objsaveoptions/export_textures) | Try to copy textures used in scene to output directory. |
| [apply_unit_scale](/3d/python-net/aspose.threed.formats/objsaveoptions/apply_unit_scale) | Apply [`AssetInfo.unit_scale_factor`](/3d/python-net/aspose.threed/assetinfo#unit_scale_factor) to the mesh.<br/>Default value is false. |
| [point_cloud](/3d/python-net/aspose.threed.formats/objsaveoptions/point_cloud) | Gets or sets the flag whether the exporter should export the scene as point cloud(without topological structure), default value is false |
| [verbose](/3d/python-net/aspose.threed.formats/objsaveoptions/verbose) | Gets or sets whether generate comments for each section |
| [serialize_w](/3d/python-net/aspose.threed.formats/objsaveoptions/serialize_w) | Gets or sets whether serialize W component in model's vertex position. |
| [enable_materials](/3d/python-net/aspose.threed.formats/objsaveoptions/enable_materials) | Gets or sets whether import/export materials for each object |
| [flip_coordinate_system](/3d/python-net/aspose.threed.formats/objsaveoptions/flip_coordinate_system) | Gets or sets whether flip coordinate system of control points/normal during importing/exporting. |
| [axis_system](/3d/python-net/aspose.threed.formats/objsaveoptions/axis_system) | Gets or sets the axis system in the exported file. |



### See Also
* module [`aspose.threed.formats`](..)
* class [`IOConfig`](/3d/python-net/aspose.threed.formats/ioconfig)
* class [`ObjSaveOptions`](/3d/python-net/aspose.threed.formats/objsaveoptions)
* class [`SaveOptions`](/3d/python-net/aspose.threed.formats/saveoptions)
