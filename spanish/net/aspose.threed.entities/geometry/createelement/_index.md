---
title: "Geometry.CreateElement"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método Geometry. Crea un elemento de vértice con el tipo especificado y lo agrega a la geometría"
type: docs
weight: 90
url: /es/net/aspose.threed.entities/geometry/createelement/
---
## CreateElement(VertexElementType) {#createelement}

Crea un elemento de vértice con el tipo especificado y lo agrega a la geometría.

```csharp
public VertexElement CreateElement(VertexElementType type)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tipo | VertexElementType | Tipo de elemento de vértice |

### Valor de retorno

Elemento creado.

## Observaciones

Si el tipo es UV, se creará un [`VertexElementUV`](../../vertexelementuv/) con tipo de mapeo de textura a Difuso.

### Ver también

* class [VertexElement](../../vertexelement/)
* enum [VertexElementType](../../vertexelementtype/)
* class [Geometry](../)
* namespace [Aspose.ThreeD.Entities](../../geometry/)
* assembly [Aspose.3D](../../../)

---

## CreateElement(VertexElementType, MappingMode, ReferenceMode) {#createelement_1}

Crea un elemento de vértice con el tipo especificado y lo agrega a la geometría.

```csharp
public VertexElement CreateElement(VertexElementType type, MappingMode mappingMode, 
    ReferenceMode referenceMode)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| tipo | VertexElementType | Tipo de elemento de vértice |
| mappingMode | MappingMode | Modo de mapeo predeterminado |
| referenceMode | ReferenceMode | Modo de referencia predeterminado |

### Valor de retorno

Elemento creado.

## Observaciones

Si el tipo es UV, se creará un [`VertexElementUV`](../../vertexelementuv/) con tipo de mapeo de textura a Difuso.

### Ver también

* class [VertexElement](../../vertexelement/)
* enum [VertexElementType](../../vertexelementtype/)
* enum [MappingMode](../../mappingmode/)
* enum [ReferenceMode](../../referencemode/)
* class [Geometry](../)
* namespace [Aspose.ThreeD.Entities](../../geometry/)
* assembly [Aspose.3D](../../../)


