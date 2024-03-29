---
title: PolygonModifier
second_title: Aspose.3D voor .NET API-referentie
description: Hulpprogrammas om polygonen te wijzigen
type: docs
weight: 560
url: /nl/net/aspose.threed.entities/polygonmodifier/
---
## PolygonModifier class

Hulpprogramma's om polygonen te wijzigen

```csharp
public class PolygonModifier
```

## methoden

| Naam | Beschrijving |
| --- | --- |
| static [BuildTangentBinormal](../../aspose.threed.entities/polygonmodifier/buildtangentbinormal/#buildtangentbinormal)(Mesh) | Dit zal tangens en binormaal op de mesh creëren Normaal is vereist, als normaal niet aanwezig is op de mesh, zal het ook de normale gegevens van positie creëren. UV is ook vereist, er zal een uitzondering worden gemaakt als er geen UV gevonden wordt. |
| static [BuildTangentBinormal](../../aspose.threed.entities/polygonmodifier/buildtangentbinormal/#buildtangentbinormal_1)(Scene) | Dit creëert tangens en binormaal op alle mazen van de scène. Normaal is vereist, als normaal niet aanwezig is op het net, worden ook de normale gegevens van positie gemaakt. UV is ook vereist, het net wordt genegeerd als er geen UV is is gedefinieerd. |
| static [GenerateNormal](../../aspose.threed.entities/polygonmodifier/generatenormal/)(Mesh) | Genereer normale gegevens uit mesh-definitie |
| static [GenerateUV](../../aspose.threed.entities/polygonmodifier/generateuv/#generateuv)(Mesh) | Genereer UV-gegevens uit de gegeven invoer mesh |
| static [GenerateUV](../../aspose.threed.entities/polygonmodifier/generateuv/#generateuv_1)(Mesh, VertexElementNormal) | Genereer UV-gegevens uit het gegeven invoernet en gespecificeerde normale gegevens. |
| static [MergeMesh](../../aspose.threed.entities/polygonmodifier/mergemesh/#mergemesh_2)(IList&lt;Node&gt;) |  |
| static [MergeMesh](../../aspose.threed.entities/polygonmodifier/mergemesh/#mergemesh)(Node) | Converteer een heel knooppunt naar een enkele getransformeerde mesh Vertex-elementen zoals normale/textuurcoördinaten worden nog niet ondersteund |
| static [MergeMesh](../../aspose.threed.entities/polygonmodifier/mergemesh/#mergemesh_1)(Scene) | Converteer een hele scène naar een enkele getransformeerde mesh Vertex-elementen zoals normale/textuurcoördinaten worden nog niet ondersteund |
| static [Scale](../../aspose.threed.entities/polygonmodifier/scale/#scale_1)(Node, Vector3) | Schaal alle geometrieën (schaal de controlepunten niet de transformatiematrix) in dit knooppunt |
| static [Scale](../../aspose.threed.entities/polygonmodifier/scale/#scale)(Scene, Vector3) | Schaal alle geometrieën (schaal de controlepunten niet de transformatiematrix) in deze scène |
| static [SplitMesh](../../aspose.threed.entities/polygonmodifier/splitmesh/#splitmesh)(Mesh, SplitMeshPolicy) | Split mesh in sub-meshes door[`VertexElementMaterial`](../vertexelementmaterial/) . Elke sub-mesh gebruikt slechts één materiaal. De originele mesh wordt niet gewijzigd. |
| static [SplitMesh](../../aspose.threed.entities/polygonmodifier/splitmesh/#splitmesh_2)(Scene, SplitMeshPolicy, bool) | Split mesh in sub-meshes door[`VertexElementMaterial`](../vertexelementmaterial/) . Elke sub-mesh gebruikt slechts één materiaal. Voer mesh-splitsing uit op alle knooppunten van de scène. |
| static [SplitMesh](../../aspose.threed.entities/polygonmodifier/splitmesh/#splitmesh_1)(Node, SplitMeshPolicy, bool, bool) | Split mesh in sub-meshes door[`VertexElementMaterial`](../vertexelementmaterial/) . Elke sub-mesh gebruikt slechts één materiaal. Voer mesh-splitsing uit op een knooppunt |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_1)(IList&lt;Vector4&gt;) |  |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate)(Mesh) | Converteer een op polygoon gebaseerde mesh naar mesh met volledige driehoek |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_5)(Scene) | Zet alle op veelhoeken gebaseerde meshes om in volledige driehoek mesh |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_3)(IList&lt;Vector4&gt;, IList&lt;int[]&gt;) |  |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_2)(IList&lt;Vector4&gt;, int[]) |  |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_4)(IList&lt;Vector4&gt;, IList&lt;int[]&gt;, bool, out Vector3[]) |  |

### Zie ook

* naamruimte [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* montage [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
