﻿---
title: GltfSaveOptions class
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 110
url: /python-net/aspose.threed.formats/gltfsaveoptions/
is_root: false
---

## GltfSaveOptions class

Save options for glTF format.



The GltfSaveOptions type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [GltfSaveOptions(content_type)](/3d/python-net/aspose.threed.formats/gltfsaveoptions/__init__/#FileContentType) | Constructor of [GltfSaveOptions](/3d/python-net/aspose.threed.formats/gltfsaveoptions) |
| [GltfSaveOptions(format)](/3d/python-net/aspose.threed.formats/gltfsaveoptions/__init__/#FileFormat) | Constructor of [GltfSaveOptions](/3d/python-net/aspose.threed.formats/gltfsaveoptions) |


### Properties
| Property | Description |
| :- | :- |
| [file_format](/3d/python-net/aspose.threed.formats/gltfsaveoptions/file_format) | Gets the file format that specified in current Save/Load option. |
| [encoding](/3d/python-net/aspose.threed.formats/gltfsaveoptions/encoding) | Gets or sets the default encoding for text-based files.
| [file_system](/3d/python-net/aspose.threed.formats/gltfsaveoptions/file_system) | Allow user to handle how to manage the external dependencies during load/save. |
| [lookup_paths](/3d/python-net/aspose.threed.formats/gltfsaveoptions/lookup_paths) | Some files like OBJ depends on external file, the lookup paths will allows Aspose.3D to look for external file to load. |
| [file_name](/3d/python-net/aspose.threed.formats/gltfsaveoptions/file_name) | The file name of the exporting/importing scene.
| [pretty_print](/3d/python-net/aspose.threed.formats/gltfsaveoptions/pretty_print) | The JSON content of GLTF file is indented for human reading, default value is false |
| [fallback_normal](/3d/python-net/aspose.threed.formats/gltfsaveoptions/fallback_normal) | When GLTF2 exporter detected an invalid normal, this will be used instead of its original value to bypass the validation.
| [embed_assets](/3d/python-net/aspose.threed.formats/gltfsaveoptions/embed_assets) | Embed all external assets as base64 into single file in ASCII mode, default value is false. |
| [image_format](/3d/python-net/aspose.threed.formats/gltfsaveoptions/image_format) | Standard glTF only supports PNG/JPG as its texture format, this option will guide how Aspose.3D
| [use_common_materials](/3d/python-net/aspose.threed.formats/gltfsaveoptions/use_common_materials) | Serialize materials using KHR common material extensions, default value is false.
| [external_draco_encoder](/3d/python-net/aspose.threed.formats/gltfsaveoptions/external_draco_encoder) | Use external draco encoder to accelerate the draco compression speed. |
| [flip_tex_coord_v](/3d/python-net/aspose.threed.formats/gltfsaveoptions/flip_tex_coord_v) | Flip texture coordinate  v(t) component, default value is true. |
| [buffer_file](/3d/python-net/aspose.threed.formats/gltfsaveoptions/buffer_file) | The file name of the external buffer file used to store binary data.
| [save_extras](/3d/python-net/aspose.threed.formats/gltfsaveoptions/save_extras) | Save scene object's dynamic properties into 'extra' fields in the generated glTF file.
| [draco_compression](/3d/python-net/aspose.threed.formats/gltfsaveoptions/draco_compression) | Gets or sets whether to enable draco compression |


### See Also

* module [aspose.threed.formats](../)
* class [SaveOptions](/3d/python-net/aspose.threed.formats/saveoptions)