﻿---
title: Shape class
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 320
url: /aspose.threed.entities/shape/
is_root: false
---

## Shape class

The shape describes the deformation on a set of control points, which is similar to the cluster deformer in Maya.
For example, we can add a shape to a created geometry. 
And the shape and the geometry have the same topological information but different position of the control points. 
With varying amounts of influence, the geometry performs a deformation effect.



**Inheritance:** [`Shape`](/3d/python-net/aspose.threed.entities/shape) → 
[`Geometry`](/3d/python-net/aspose.threed.entities/geometry) → 
[`Entity`](/3d/python-net/aspose.threed/entity) → 
[`SceneObject`](/3d/python-net/aspose.threed/sceneobject) → 
[`A3DObject`](/3d/python-net/aspose.threed/a3dobject)



The Shape type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [__init__](/3d/python-net/aspose.threed.entities/shape/__init__/#) | Initializes a new instance of the [`Shape`](/3d/python-net/aspose.threed.entities/shape) class. |
| [__init__](/3d/python-net/aspose.threed.entities/shape/__init__/#str) | Initializes a new instance of the [`Shape`](/3d/python-net/aspose.threed.entities/shape) class. |


### Properties
| Property | Description |
| :- | :- |
| [name](/3d/python-net/aspose.threed.entities/shape/name) | Gets or sets the name. |
| [properties](/3d/python-net/aspose.threed.entities/shape/properties) | Gets the collection of all properties. |
| [scene](/3d/python-net/aspose.threed.entities/shape/scene) | Gets the scene that this object belongs to |
| [parent_nodes](/3d/python-net/aspose.threed.entities/shape/parent_nodes) | Gets all parent nodes, an entity can be attached to multiple parent nodes for geometry instancing |
| [excluded](/3d/python-net/aspose.threed.entities/shape/excluded) | Gets or sets whether to exclude this entity during exporting. |
| [parent_node](/3d/python-net/aspose.threed.entities/shape/parent_node) | Gets or sets the first parent node, if set the first parent node, this entity will be detached from other parent nodes. |
| [visible](/3d/python-net/aspose.threed.entities/shape/visible) | Gets or sets if the geometry is visible |
| [deformers](/3d/python-net/aspose.threed.entities/shape/deformers) | Gets all deformers associated with this geometry. |
| [cast_shadows](/3d/python-net/aspose.threed.entities/shape/cast_shadows) | Gets or sets whether this geometry can cast shadow |
| [receive_shadows](/3d/python-net/aspose.threed.entities/shape/receive_shadows) | Gets or sets whether this geometry can receive shadow. |
| [vertex_elements](/3d/python-net/aspose.threed.entities/shape/vertex_elements) | Gets all vertex elements |
| [indices](/3d/python-net/aspose.threed.entities/shape/indices) | Gets the indices. |


### Methods
| Method | Description |
| :- | :- |
| [remove_property](/3d/python-net/aspose.threed.entities/shape/remove_property/#aspose.threed.Property) | Removes a dynamic property. |
| [remove_property](/3d/python-net/aspose.threed.entities/shape/remove_property/#str) | Remove the specified property identified by name |
| [create_element](/3d/python-net/aspose.threed.entities/shape/create_element/#aspose.threed.entities.VertexElementType) | Creates a vertex element with specified type and add it to the geometry. |
| [create_element](/3d/python-net/aspose.threed.entities/shape/create_element/#aspose.threed.entities.VertexElementType-aspose.threed.entities.MappingMode-aspose.threed.entities.ReferenceMode) | Creates a vertex element with specified type and add it to the geometry. |
| [create_element_uv](/3d/python-net/aspose.threed.entities/shape/create_element_uv/#aspose.threed.entities.TextureMapping) | Creates a [`VertexElementUV`](/3d/python-net/aspose.threed.entities/vertexelementuv) with given texture mapping type. |
| [create_element_uv](/3d/python-net/aspose.threed.entities/shape/create_element_uv/#aspose.threed.entities.TextureMapping-aspose.threed.entities.MappingMode-aspose.threed.entities.ReferenceMode) | Creates a [`VertexElementUV`](/3d/python-net/aspose.threed.entities/vertexelementuv) with given texture mapping type. |
| [get_property](/3d/python-net/aspose.threed.entities/shape/get_property/#str) | Get the value of specified property |
| [set_property](/3d/python-net/aspose.threed.entities/shape/set_property/#str-any) | Sets the value of specified property |
| [find_property](/3d/python-net/aspose.threed.entities/shape/find_property/#str) | Finds the property.<br/>It can be a dynamic property (Created by CreateDynamicProperty/SetProperty) <br/>or native property(Identified by its name) |
| [get_bounding_box](/3d/python-net/aspose.threed.entities/shape/get_bounding_box/#) | Gets the bounding box of current entity in its object space coordinate system. |
| [get_entity_renderer_key](/3d/python-net/aspose.threed.entities/shape/get_entity_renderer_key/#) | Gets the key of the entity renderer registered in the renderer |
| [get_element](/3d/python-net/aspose.threed.entities/shape/get_element/#aspose.threed.entities.VertexElementType) | Gets a vertex element with specified type |
| [get_vertex_element_of_uv](/3d/python-net/aspose.threed.entities/shape/get_vertex_element_of_uv/#aspose.threed.entities.TextureMapping) | Gets a [`VertexElementUV`](/3d/python-net/aspose.threed.entities/vertexelementuv) instance with given texture mapping type |
| [add_element](/3d/python-net/aspose.threed.entities/shape/add_element/#aspose.threed.entities.VertexElement) | Adds an existing vertex element to current geometry |
| [from_control_points](/3d/python-net/aspose.threed.entities/shape/from_control_points/#list) | Create a shape with specified control points with a default indices. |



### See Also
* module [`aspose.threed.entities`](..)
* class [`A3DObject`](/3d/python-net/aspose.threed/a3dobject)
* class [`Entity`](/3d/python-net/aspose.threed/entity)
* class [`Geometry`](/3d/python-net/aspose.threed.entities/geometry)
* class [`SceneObject`](/3d/python-net/aspose.threed/sceneobject)
* class [`Shape`](/3d/python-net/aspose.threed.entities/shape)
* class [`VertexElementUV`](/3d/python-net/aspose.threed.entities/vertexelementuv)
