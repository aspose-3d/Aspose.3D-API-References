---
title: "Clase PolygonModifier"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Entities.PolygonModifier. Utilidades para modificar polígonos"
type: docs
weight: 620
url: /es/net/aspose.threed.entities/polygonmodifier/
---
## PolygonModifier class

Utilidades para modificar polígonos.

```csharp
public class PolygonModifier
```

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [ApplyTransform](../../aspose.threed.entities/polygonmodifier/applytransform/)(Node, Matrix4) | Aplicar la matriz de transformación a los puntos de control de todas las geometrías |
| static [BuildTangentBinormal](../../aspose.threed.entities/polygonmodifier/buildtangentbinormal/#buildtangentbinormal)(Mesh) | Esto creará tangentes y binormales en la malla. Se requiere la normal; si la normal no existe en la malla, también se creará la información de la normal a partir de la posición. También se requiere UV; se lanzará una excepción si no se encuentra UV. |
| static [BuildTangentBinormal](../../aspose.threed.entities/polygonmodifier/buildtangentbinormal/#buildtangentbinormal_1)(Scene) | Esto creará tangentes y binormales en todas las mallas de la escena. Se requiere la normal; si la normal no existe en la malla, también se creará la información de la normal a partir de la posición. También se requiere UV; la malla será ignorada si no se define UV. |
| static [GenerateNormal](../../aspose.threed.entities/polygonmodifier/generatenormal/)(Mesh) | Generar datos de normales a partir de la definición de la malla |
| static [GenerateUV](../../aspose.threed.entities/polygonmodifier/generateuv/#generateuv)(Mesh) | Generar datos UV a partir de la malla de entrada proporcionada |
| static [GenerateUV](../../aspose.threed.entities/polygonmodifier/generateuv/#generateuv_1)(Mesh, VertexElementNormal) | Generar datos UV a partir de la malla de entrada proporcionada y los datos de normales especificados. |
| static [MergeMesh](../../aspose.threed.entities/polygonmodifier/mergemesh/#mergemesh_2)(IList&lt;Node&gt;) |  |
| static [MergeMesh](../../aspose.threed.entities/polygonmodifier/mergemesh/#mergemesh)(Node) | Convertir un nodo completo en una única malla transformada. Los elementos de vértice como normales/coordenadas de textura aún no son compatibles. |
| static [MergeMesh](../../aspose.threed.entities/polygonmodifier/mergemesh/#mergemesh_1)(Scene) | Convertir una escena completa en una única malla transformada. Los elementos de vértice como normales/coordenadas de textura aún no son compatibles. |
| static [Scale](../../aspose.threed.entities/polygonmodifier/scale/#scale_1)(Node, Vector3) | Escalar todas las geometrías (escalar los puntos de control, no la matriz de transformación) en este nodo |
| static [Scale](../../aspose.threed.entities/polygonmodifier/scale/#scale)(Scene, Vector3) | Escalar todas las geometrías (escalar los puntos de control, no la matriz de transformación) en esta escena |
| static [SplitMesh](../../aspose.threed.entities/polygonmodifier/splitmesh/#splitmesh)(Mesh, SplitMeshPolicy) | Divida la malla en submallas por [`VertexElementMaterial`](../vertexelementmaterial/). Cada submalla usará solo un material. La malla original no se modificará. |
| static [SplitMesh](../../aspose.threed.entities/polygonmodifier/splitmesh/#splitmesh_2)(Scene, SplitMeshPolicy, bool) | Divida la malla en submallas por [`VertexElementMaterial`](../vertexelementmaterial/). Cada submalla usará solo un material. Realice la división de la malla en todos los nodos de la escena. |
| static [SplitMesh](../../aspose.threed.entities/polygonmodifier/splitmesh/#splitmesh_1)(Node, SplitMeshPolicy, bool, bool) | Divida la malla en submallas por [`VertexElementMaterial`](../vertexelementmaterial/). Cada submalla usará solo un material. Realice la división de la malla en un nodo. |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_1)(IList&lt;Vector4&gt;) |  |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate)(Mesh) | Convierta una malla basada en polígonos en una malla completa de triángulos. |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_5)(Scene) | Convierta todas las mallas basadas en polígonos en una malla completa de triángulos. |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_3)(IList&lt;Vector4&gt;, IList&lt;int[]&gt;) |  |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_2)(IList&lt;Vector4&gt;, int[]) |  |
| static [Triangulate](../../aspose.threed.entities/polygonmodifier/triangulate/#triangulate_4)(IList&lt;Vector4&gt;, IList&lt;int[]&gt;, bool, out Vector3[]) |  |

### Ver también

* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


