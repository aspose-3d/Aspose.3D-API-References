---
title: BuildTangentBinormal
second_title: Aspose.3D for .NET API Reference
description: 
type: docs
weight: 10
url: /net/aspose.threed.entities/polygonmodifier/buildtangentbinormal/
---
## PolygonModifier.BuildTangentBinormal method (1 of 2)

This will create tangent and binormal on all meshes of the scene Normal is required, if normal is not existing on the mesh, it will also create the normal data from position. UV is also required, the mesh will be ignored if no UV is defined.

```csharp
public static void BuildTangentBinormal(Scene scene)
```

### See Also

* class [Scene](../../../aspose.threed/scene)
* class [PolygonModifier](../../polygonmodifier)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier)
* assembly [Aspose.3D](../../../)

---

## PolygonModifier.BuildTangentBinormal method (2 of 2)

This will create tangent and binormal on the mesh Normal is required, if normal is not existing on the mesh, it will also create the normal data from position. UV is also required, an exception will be raised if no UV found.

```csharp
public static void BuildTangentBinormal(Mesh mesh)
```

### See Also

* class [Mesh](../../mesh)
* class [PolygonModifier](../../polygonmodifier)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier)
* assembly [Aspose.3D](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
