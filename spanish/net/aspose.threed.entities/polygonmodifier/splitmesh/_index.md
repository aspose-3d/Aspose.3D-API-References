---
title: "PolygonModifier.SplitMesh"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método PolygonModifier. Divide la malla en submallas por VertexElementMaterial. Cada submalla usará solo un material. Realiza la división de la malla en un nodo"
type: docs
weight: 70
url: /es/net/aspose.threed.entities/polygonmodifier/splitmesh/
---
## SplitMesh(Node, SplitMeshPolicy, bool, bool) {#splitmesh_1}

Divide la malla en sub-mallas por [`VertexElementMaterial`](../../vertexelementmaterial/). Cada sub-malla usará solo un material. Realiza la división de la malla en un nodo

```csharp
public static void SplitMesh(Node node, SplitMeshPolicy policy, bool createChildNodes = false, 
    bool removeOldMesh = true)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nodo | Nodo |  |
| política | SplitMeshPolicy |  |
| createChildNodes | Boolean | Crear nodos hijos para cada submalla. |
| removeOldMesh | Boolean | Eliminar la malla antigua después de la división; si este parámetro es falso, la malla antigua y la nueva coexistirán. |

## Ejemplos

El siguiente código muestra cómo dividir una caja en submallas usando índices de material.

```csharp
// Crea una malla de caja (Una caja está compuesta por 6 planos)
Mesh box = (new Box()).ToMesh();
// Crea un elemento de material en esta malla
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// Y especifica un índice de material diferente para cada plano
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
// Ahora divídela en 6 submallas; especificamos 6 materiales diferentes en cada plano, cada plano se convertirá en una submalla.
// Usamos la política CloneData, cada plano tendrá la misma información de puntos de control o información de elementos de vértice basada en puntos de control.
Mesh[] planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CloneData);

// Ahora divídela en 2 submallas, la primera malla contendrá los planos 0/1/2 y la segunda malla contendrá los planos 3/4/5.
mat.Indices.Clear();
mat.Indices.AddRange(new int[] { 0, 0, 0, 1, 1, 1 });
// Usamos la política CompactData, cada plano tendrá su propia información de puntos de control o información de elementos de vértice basada en puntos de control.
planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CompactData);
```

### Ver también

* class [Node](../../../aspose.threed/node/)
* enum [SplitMeshPolicy](../../splitmeshpolicy/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## SplitMesh(Scene, SplitMeshPolicy, bool) {#splitmesh_2}

Dividir la malla en submallas mediante [`VertexElementMaterial`](../../vertexelementmaterial/). Cada submalla usará solo un material. Realizar la división de la malla en todos los nodos de la escena.

```csharp
public static void SplitMesh(Scene scene, SplitMeshPolicy policy, bool removeOldMesh = true)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| escena | Escena |  |
| política | SplitMeshPolicy |  |
| removeOldMesh | Boolean |  |

## Ejemplos

El siguiente código muestra cómo dividir una caja en submallas usando índices de material.

```csharp
// Crea una malla de caja (Una caja está compuesta por 6 planos)
Mesh box = (new Box()).ToMesh();
// Crea un elemento de material en esta malla
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// Y especifica un índice de material diferente para cada plano
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
// Ahora divídela en 6 submallas; especificamos 6 materiales diferentes en cada plano, cada plano se convertirá en una submalla.
// Usamos la política CloneData, cada plano tendrá la misma información de puntos de control o información de elementos de vértice basada en puntos de control.
Mesh[] planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CloneData);

// Ahora divídela en 2 submallas, la primera malla contendrá los planos 0/1/2 y la segunda malla contendrá los planos 3/4/5.
mat.Indices.Clear();
mat.Indices.AddRange(new int[] { 0, 0, 0, 1, 1, 1 });
// Usamos la política CompactData, cada plano tendrá su propia información de puntos de control o información de elementos de vértice basada en puntos de control.
planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CompactData);
```

### Ver también

* class [Scene](../../../aspose.threed/scene/)
* enum [SplitMeshPolicy](../../splitmeshpolicy/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## SplitMesh(Mesh, SplitMeshPolicy) {#splitmesh}

Dividir la malla en submallas mediante [`VertexElementMaterial`](../../vertexelementmaterial/). Cada submalla usará solo un material. La malla original no se modificará.

```csharp
public static Mesh[] SplitMesh(Mesh mesh, SplitMeshPolicy policy)
```

### Valor de retorno

Nuevas mallas divididas

## Ejemplos

El siguiente código muestra cómo dividir una caja en submallas usando índices de material.

```csharp
// Crea una malla de caja (Una caja está compuesta por 6 planos)
Mesh box = (new Box()).ToMesh();
// Crea un elemento de material en esta malla
VertexElementMaterial mat = (VertexElementMaterial)box.CreateElement(VertexElementType.Material, MappingMode.Polygon, ReferenceMode.Index);
// Y especifica un índice de material diferente para cada plano
mat.Indices.AddRange(new int[] { 0, 1, 2, 3, 4, 5 });
// Ahora divídela en 6 submallas; especificamos 6 materiales diferentes en cada plano, cada plano se convertirá en una submalla.
// Usamos la política CloneData, cada plano tendrá la misma información de puntos de control o información de elementos de vértice basada en puntos de control.
Mesh[] planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CloneData);

// Ahora divídela en 2 submallas, la primera malla contendrá los planos 0/1/2 y la segunda malla contendrá los planos 3/4/5.
mat.Indices.Clear();
mat.Indices.AddRange(new int[] { 0, 0, 0, 1, 1, 1 });
// Usamos la política CompactData, cada plano tendrá su propia información de puntos de control o información de elementos de vértice basada en puntos de control.
planes = PolygonModifier.SplitMesh(box, SplitMeshPolicy.CompactData);
```

### Ver también

* class [Mesh](../../mesh/)
* enum [SplitMeshPolicy](../../splitmeshpolicy/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


