---
title: "Mesh.CreatePolygon"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Mesh-Methode. Erstellt ein neues Polygon mit allen in Indizes definierten Scheitelpunkten. Um das Polygon Scheitelpunkt für Scheitelpunkt zu erstellen, verwenden Sie bitte PolygonBuilder"
type: docs
weight: 60
url: /de/net/aspose.threed.entities/mesh/createpolygon/
---
## CreatePolygon(int[], int, int) {#createpolygon_3}

Erstellt ein neues Polygon mit allen in *indices* definierten Scheitelpunkten. Um das Polygon Scheitelpunkt für Scheitelpunkt zu erstellen, verwenden Sie bitte [`PolygonBuilder`](../../polygonbuilder/).

```csharp
public void CreatePolygon(int[] indices, int offset, int length)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| indices | Int32[] | Array der Polygonindizes, wobei jeder Index auf einen Kontrollpunkt zeigt, der das Polygon bildet. |
| offset | Int32 | Der Offset des ersten Polygonindex |
| length | Int32 | Die Länge der Indizes |

## Beispiele

Der folgende Code zeigt, wie man ein neues Polygon mit den Indizes der Kontrollpunkte erstellt.

```csharp
var mesh = new Mesh();
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

### Siehe auch

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## CreatePolygon(int[]) {#createpolygon_2}

Erstellt ein neues Polygon mit allen in *indices* definierten Scheitelpunkten. Um das Polygon Scheitelpunkt für Scheitelpunkt zu erstellen, verwenden Sie bitte [`PolygonBuilder`](../../polygonbuilder/).

```csharp
public void CreatePolygon(int[] indices)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| indices | Int32[] | Array der Polygonindizes, wobei jeder Index auf einen Kontrollpunkt zeigt, der das Polygon bildet. |

## Beispiele

```csharp
var mesh = new Mesh();
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

### Siehe auch

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## CreatePolygon(int, int, int, int) {#createpolygon_1}

Erstelle ein Polygon mit 4 Scheitelpunkten (Quad)

```csharp
public void CreatePolygon(int v1, int v2, int v3, int v4)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| v1 | Int32 | Index des ersten Scheitelpunkts |
| v2 | Int32 | Index des zweiten Scheitelpunkts |
| v3 | Int32 | Index des dritten Scheitelpunkts |
| v4 | Int32 | Index des vierten Scheitelpunkts |

## Beispiele

Der folgende Code zeigt, wie man ein neues Polygon mit den Indizes der Kontrollpunkte erstellt.

```csharp
var mesh = new Mesh();
mesh.CreatePolygon(0, 1, 2, 3);
```

### Siehe auch

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## CreatePolygon(int, int, int) {#createpolygon}

Erstelle ein Polygon mit 3 Scheitelpunkten (Dreieck)

```csharp
public void CreatePolygon(int v1, int v2, int v3)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| v1 | Int32 | Index des ersten Scheitelpunkts |
| v2 | Int32 | Index des zweiten Scheitelpunkts |
| v3 | Int32 | Index des dritten Scheitelpunkts |

## Beispiele

Der folgende Code zeigt, wie man ein neues Polygon mit den Indizes der Kontrollpunkte erstellt.

```csharp
var mesh = new Mesh();
mesh.CreatePolygon(0, 1, 2);
```

### Siehe auch

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


