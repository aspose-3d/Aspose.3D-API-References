---
title: "Clase VertexElementUV"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Entities.VertexElementUV. Define las coordenadas UV para los componentes especificados. Una geometría puede tener múltiples elementos VertexElementUV y cada uno tiene diferentes TextureMappings."
type: docs
weight: 960
url: /es/net/aspose.threed.entities/vertexelementuv/
---
## VertexElementUV class

Define las coordenadas UV para los componentes especificados. Una geometría puede tener múltiples elementos `VertexElementUV`, y cada uno tiene diferentes [`TextureMapping`](../texturemapping/)s.

```csharp
public class VertexElementUV : VertexElementVector4
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [VertexElementUV](vertexelementuv/#constructor)() | Inicializa una nueva instancia de la clase `VertexElementUV`. El tipo de mapeo de textura predeterminado es Diffuse |
| [VertexElementUV](vertexelementuv/#constructor_1)(TextureMapping) | Inicializa una nueva instancia de la clase `VertexElementUV`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Data](../../aspose.threed.entities/vertexelementvector4/data/) { get; } | Obtiene los datos del vértice |
| [Indices](../../aspose.threed.entities/vertexelement/indices/) { get; } | Obtiene los datos de los índices |
| [MappingMode](../../aspose.threed.entities/vertexelement/mappingmode/) { get; set; } | Obtiene o establece cómo se asigna el elemento. |
| [Name](../../aspose.threed.entities/vertexelement/name/) { get; set; } | Obtiene o establece el nombre. |
| [ReferenceMode](../../aspose.threed.entities/vertexelement/referencemode/) { get; set; } | Obtiene o establece cómo se referencia el elemento. |
| [VertexElementType](../../aspose.threed.entities/vertexelement/vertexelementtype/) { get; } | Obtiene el tipo del [`VertexElement`](../vertexelement/) |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddData](../../aspose.threed.entities/vertexelementuv/adddata/#adddata)(IEnumerable&lt;Vector2&gt;) |  |
| [AddData](../../aspose.threed.entities/vertexelementuv/adddata/#adddata_1)(IEnumerable&lt;Vector3&gt;) |  |
| override [Clear](../../aspose.threed.entities/vertexelementvector4/clear/)() | Elimina todos los elementos de los arreglos directos y de índices. |
| [CopyTo](../../aspose.threed.entities/vertexelementvector4/copyto/)(VertexElementVector4) | Copia datos al elemento especificado |
| [SetData](../../aspose.threed.entities/vertexelementvector4/setdata/)(Vector4[]) | Cargar datos |
| [SetIndices](../../aspose.threed.entities/vertexelement/setindices/)(int[]) | Cargar índices |
| override [ToString](../../aspose.threed.entities/vertexelement/tostring/)() | Representación en cadena del elemento de vértice. |

### Ver también

* class [VertexElementVector4](../vertexelementvector4/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


