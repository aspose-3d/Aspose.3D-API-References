---
title: "Clase VertexElementMaterial"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Entities.VertexElementMaterial. Define el índice de material para los componentes especificados. Un nodo puede tener múltiples materiales; el VertexElementMaterial se usa para renderizar diferentes partes de la geometría con diferentes materiales"
type: docs
weight: 880
url: /es/net/aspose.threed.entities/vertexelementmaterial/
---
## VertexElementMaterial class

Define el índice de material para los componentes especificados. Un nodo puede tener múltiples materiales, el `VertexElementMaterial` se usa para renderizar diferentes partes de la geometría con diferentes materiales.

```csharp
public class VertexElementMaterial : VertexElement
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [VertexElementMaterial](vertexelementmaterial/)() | Inicializa una nueva instancia de la clase `VertexElementMaterial`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Indices](../../aspose.threed.entities/vertexelement/indices/) { get; } | Obtiene los datos de los índices |
| [MappingMode](../../aspose.threed.entities/vertexelement/mappingmode/) { get; set; } | Obtiene o establece cómo se asigna el elemento. |
| [Name](../../aspose.threed.entities/vertexelement/name/) { get; set; } | Obtiene o establece el nombre. |
| [ReferenceMode](../../aspose.threed.entities/vertexelement/referencemode/) { get; set; } | Obtiene o establece cómo se referencia el elemento. |
| [VertexElementType](../../aspose.threed.entities/vertexelement/vertexelementtype/) { get; } | Obtiene el tipo del [`VertexElement`](../vertexelement/) |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Clear](../../aspose.threed.entities/vertexelementmaterial/clear/)() | Elimina todos los elementos de los arreglos directos y de índices. |
| [SetIndices](../../aspose.threed.entities/vertexelement/setindices/)(int[]) | Cargar índices |
| override [ToString](../../aspose.threed.entities/vertexelement/tostring/)() | Representación en cadena del elemento de vértice. |

## Ejemplos

El siguiente código muestra cómo asignar diferentes materiales a diferentes caras de una caja.

```csharp
// Crea una malla de caja (Una caja está compuesta por 6 planos)
Mesh box = (new Box()).ToMesh();
// Crea un elemento de material en esta malla
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// Y especifica un índice de material diferente para cada plano
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
```

### Ver también

* class [VertexElement](../vertexelement/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


