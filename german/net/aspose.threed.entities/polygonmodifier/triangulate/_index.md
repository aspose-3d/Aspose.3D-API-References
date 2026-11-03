---
title: "PolygonModifier.Triangulate"
second_title: "Aspose.3D für .NET API-Referenz"
description: "PolygonModifier-Methode. Konvertiert alle polygonbasierten Meshes in ein vollständiges Dreiecks-Mesh"
type: docs
weight: 80
url: /de/net/aspose.threed.entities/polygonmodifier/triangulate/
---
## Triangulate(Scene) {#triangulate_5}

Alle polygonbasierten Meshes in ein vollständiges Dreiecks-Mesh konvertieren

```csharp
public static void Triangulate(Scene scene)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scene | Scene | Die zu verarbeitende Szene |

## Beispiele

Der folgende Code zeigt, wie alle Objekte einer Szene zu einem einzigen Mesh zusammengeführt werden.

```csharp
var mesh = new Cylinder().ToMesh();

//Trianguliere dieses vierecksbasiertes Mesh zu einem dreiecksbasierten 
mesh = PolygonModifier.Triangulate(mesh);

var scene = new Scene(mesh);

      scene.Save("test.obj");
```

### Siehe auch

* class [Scene](../../../aspose.threed/scene/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Triangulate(Mesh) {#triangulate}

Ein polygonbasiertes Mesh in ein vollständiges Dreiecks-Mesh konvertieren

```csharp
public static Mesh Triangulate(Mesh mesh)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Mesh | Mesh | Das ursprüngliche nicht-dreieckige Mesh |

### Rückgabewert

Das erzeugte neue Dreiecks-Mesh

## Beispiele

Der folgende Code zeigt, wie alle Objekte einer Szene zu einem einzigen Mesh zusammengeführt werden.

```csharp
var mesh = new Cylinder().ToMesh();

//Trianguliere dieses vierecksbasiertes Mesh zu einem dreiecksbasierten 
mesh = PolygonModifier.Triangulate(mesh);

var scene = new Scene(mesh);

      scene.Save("test.obj");
```

### Siehe auch

* class [Mesh](../../mesh/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;, IList&lt;int[]&gt;, bool, out Vector3[]) {#triangulate_4}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints, IList<int[]> polygons, 
    bool generateNormals, out Vector3[] nor_out)
```

### Siehe auch

* struct [Vector4](../../../aspose.threed.utilities/vector4/)
* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;, IList&lt;int[]&gt;) {#triangulate_3}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints, IList<int[]> polygons)
```

### Siehe auch

* struct [Vector4](../../../aspose.threed.utilities/vector4/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;, int[]) {#triangulate_2}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints, int[] polygon)
```

### Siehe auch

* struct [Vector4](../../../aspose.threed.utilities/vector4/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;) {#triangulate_1}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints)
```

### Siehe auch

* struct [Vector4](../../../aspose.threed.utilities/vector4/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


