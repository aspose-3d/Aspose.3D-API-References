﻿---
title: Plane class
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 240
url: /python-net/aspose.threed.entities/plane/
is_root: false
---

## Plane class

Parameterized plane.



The Plane type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [Plane()](/3d/python-net/aspose.threed.entities/plane/__init__/#) | Initializes a new instance of the [Plane](/3d/python-net/aspose.threed.entities/plane) with default size 1x1. |
| [Plane(length, width)](/3d/python-net/aspose.threed.entities/plane/__init__/#float-float) | Initializes a new instance of the [Plane](/3d/python-net/aspose.threed.entities/plane). |
| [Plane(name, length, width, length_segments, width_segments)](/3d/python-net/aspose.threed.entities/plane/__init__/#str-float-float-int-int) | Initializes a new instance of the [Plane](/3d/python-net/aspose.threed.entities/plane). |


### Properties
| Property | Description |
| :- | :- |
| [name](/3d/python-net/aspose.threed.entities/plane/name) | Gets or sets the name. |
| [properties](/3d/python-net/aspose.threed.entities/plane/properties) | Gets the collection of all properties. |
| [scene](/3d/python-net/aspose.threed.entities/plane/scene) | Gets the scene that this object belongs to |
| [parent_nodes](/3d/python-net/aspose.threed.entities/plane/parent_nodes) | Gets all parent nodes, an entity can be attached to multiple parent nodes for geometry instancing |
| [excluded](/3d/python-net/aspose.threed.entities/plane/excluded) | Gets or sets whether to exclude this entity during exporting. |
| [parent_node](/3d/python-net/aspose.threed.entities/plane/parent_node) | Gets or sets the first parent node, if set the first parent node, this entity will be detached from other parent nodes. |
| [cast_shadows](/3d/python-net/aspose.threed.entities/plane/cast_shadows) | Gets or sets whether this geometry can cast shadow |
| [receive_shadows](/3d/python-net/aspose.threed.entities/plane/receive_shadows) | Gets or sets whether this geometry can receive shadow. |
| [up](/3d/python-net/aspose.threed.entities/plane/up) | Gets or sets the up vector of the plane, default value is (0, 1, 0), this affects the generation of the plane |
| [length](/3d/python-net/aspose.threed.entities/plane/length) | Gets or sets the length of the plane. |
| [width](/3d/python-net/aspose.threed.entities/plane/width) | Gets or sets the width of the plane. |
| [length_segments](/3d/python-net/aspose.threed.entities/plane/length_segments) | Gets or sets the length segments. |
| [width_segments](/3d/python-net/aspose.threed.entities/plane/width_segments) | Gets or sets the width segments. |


### Methods
| Method | Description |
| :- | :- |
| [remove_property(property)](/3d/python-net/aspose.threed.entities/plane/remove_property/#Property) | Removes a dynamic property. |
| [remove_property(property)](/3d/python-net/aspose.threed.entities/plane/remove_property/#str) | Remove the specified property identified by name |
| [get_property(property)](/3d/python-net/aspose.threed.entities/plane/get_property/#str) | Get the value of specified property |
| [set_property(property, value)](/3d/python-net/aspose.threed.entities/plane/set_property/#str-any) | Sets the value of specified property |
| [find_property(property_name)](/3d/python-net/aspose.threed.entities/plane/find_property/#str) | Finds the property.
| [get_bounding_box()](/3d/python-net/aspose.threed.entities/plane/get_bounding_box/#) | Gets the bounding box of current entity in its object space coordinate system. |
| [get_entity_renderer_key()](/3d/python-net/aspose.threed.entities/plane/get_entity_renderer_key/#) | Gets the key of the entity renderer registered in the renderer |
| [to_mesh()](/3d/python-net/aspose.threed.entities/plane/to_mesh/#) | Convert current object to mesh |


### See Also

* module [aspose.threed.entities](../)
* class [Primitive](/3d/python-net/aspose.threed.entities/primitive)