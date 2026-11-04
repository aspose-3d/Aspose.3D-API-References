---
title: "Mesh.CreatePolygon"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método Mesh. Crea un nuevo polígono con todos los vértices definidos en índices. Para crear el polígono vértice a vértice, por favor use PolygonBuilder"
type: docs
weight: 60
url: /es/net/aspose.threed.entities/mesh/createpolygon/
---
## CreatePolygon(int[], int, int) {#createpolygon_3}

Crea un nuevo polígono con todos los vértices definidos en *indices*. Para crear el polígono vértice a vértice, por favor use [`PolygonBuilder`](../../polygonbuilder/).

```csharp
public void CreatePolygon(int[] indices, int offset, int length)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| indices | Int32[] | Arreglo de los índices del polígono, cada índice apunta a un punto de control que forma el polígono. |
| offset | Int32 | El desplazamiento del primer índice del polígono |
| length | Int32 | La longitud de los índices |

## Ejemplos

El siguiente código muestra cómo crear un nuevo polígono con los índices de los puntos de control.

```csharp
var mesh = new Mesh();
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

### Ver también

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## CreatePolygon(int[]) {#createpolygon_2}

Crea un nuevo polígono con todos los vértices definidos en *indices*. Para crear el polígono vértice a vértice, por favor use [`PolygonBuilder`](../../polygonbuilder/).

```csharp
public void CreatePolygon(int[] indices)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| indices | Int32[] | Arreglo de los índices del polígono, cada índice apunta a un punto de control que forma el polígono. |

## Ejemplos

```csharp
var mesh = new Mesh();
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

### Ver también

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## CreatePolygon(int, int, int, int) {#createpolygon_1}

Crea un polígono con 4 vértices (cuadrilátero)

```csharp
public void CreatePolygon(int v1, int v2, int v3, int v4)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| v1 | Int32 | Índice del primer vértice |
| v2 | Int32 | Índice del segundo vértice |
| v3 | Int32 | Índice del tercer vértice |
| v4 | Int32 | Índice del cuarto vértice |

## Ejemplos

El siguiente código muestra cómo crear un nuevo polígono con los índices de los puntos de control.

```csharp
var mesh = new Mesh();
mesh.CreatePolygon(0, 1, 2, 3);
```

### Ver también

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## CreatePolygon(int, int, int) {#createpolygon}

Crea un polígono con 3 vértices (triángulo)

```csharp
public void CreatePolygon(int v1, int v2, int v3)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| v1 | Int32 | Índice del primer vértice |
| v2 | Int32 | Índice del segundo vértice |
| v3 | Int32 | Índice del tercer vértice |

## Ejemplos

El siguiente código muestra cómo crear un nuevo polígono con los índices de los puntos de control.

```csharp
var mesh = new Mesh();
mesh.CreatePolygon(0, 1, 2);
```

### Ver también

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


