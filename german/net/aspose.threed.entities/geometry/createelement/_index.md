---
title: "Geometry.CreateElement"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Geometry-Methode. Erstellt ein Vertex-Element mit angegebenem Typ und fügt es zur Geometrie hinzu"
type: docs
weight: 90
url: /de/net/aspose.threed.entities/geometry/createelement/
---
## CreateElement(VertexElementType) {#createelement}

Erstellt ein Vertex-Element mit dem angegebenen Typ und fügt es der Geometrie hinzu.

```csharp
public VertexElement CreateElement(VertexElementType type)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | VertexElementType | Vertex-Elementtyp |

### Rückgabewert

Element erstellt.

## Hinweise

Wenn der Typ UV ist, wird ein [`VertexElementUV`](../../vertexelementuv/) mit Texturzuordnungs‑Typ zu Diffuse erstellt.

### Siehe auch

* class [VertexElement](../../vertexelement/)
* enum [VertexElementType](../../vertexelementtype/)
* class [Geometry](../)
* namespace [Aspose.ThreeD.Entities](../../geometry/)
* assembly [Aspose.3D](../../../)

---

## CreateElement(VertexElementType, MappingMode, ReferenceMode) {#createelement_1}

Erstellt ein Vertex-Element mit dem angegebenen Typ und fügt es der Geometrie hinzu.

```csharp
public VertexElement CreateElement(VertexElementType type, MappingMode mappingMode, 
    ReferenceMode referenceMode)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Typ | VertexElementType | Vertex-Elementtyp |
| mappingMode | MappingMode | Standard-Mappingmodus |
| referenceMode | ReferenceMode | Standard-Referenzmodus |

### Rückgabewert

Element erstellt.

## Hinweise

Wenn der Typ UV ist, wird ein [`VertexElementUV`](../../vertexelementuv/) mit Texturzuordnungs‑Typ zu Diffuse erstellt.

### Siehe auch

* class [VertexElement](../../vertexelement/)
* enum [VertexElementType](../../vertexelementtype/)
* enum [MappingMode](../../mappingmode/)
* enum [ReferenceMode](../../referencemode/)
* class [Geometry](../)
* namespace [Aspose.ThreeD.Entities](../../geometry/)
* assembly [Aspose.3D](../../../)


