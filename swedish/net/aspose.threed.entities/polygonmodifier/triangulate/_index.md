---
title: Triangulate
second_title: Aspose.3D för .NET API-referens
description: Konvertera alla polygonbaserade maskor till full triangel mesh
type: docs
weight: 70
url: /sv/net/aspose.threed.entities/polygonmodifier/triangulate/
---
## Triangulate(Scene) {#triangulate_5}

Konvertera alla polygonbaserade maskor till full triangel mesh

```csharp
public static void Triangulate(Scene scene)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| scene | Scene | Scenen att bearbeta |

### Se även

* class [Scene](../../../aspose.threed/scene)
* class [PolygonModifier](../../polygonmodifier)
* namnutrymme [Aspose.ThreeD.Entities](../../polygonmodifier)
* hopsättning [Aspose.3D](../../../)

---

## Triangulate(Mesh) {#triangulate}

Konvertera ett polygonbaserat nät till hel triangelnät

```csharp
public static Mesh Triangulate(Mesh mesh)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mesh | Mesh | Det ursprungliga icke-triangelnätet |

### Returvärde

Det genererade nya triangelnätet

### Se även

* class [Mesh](../../mesh)
* class [PolygonModifier](../../polygonmodifier)
* namnutrymme [Aspose.ThreeD.Entities](../../polygonmodifier)
* hopsättning [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;, IList&lt;int[]&gt;, bool, out Vector3[]) {#triangulate_4}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints, IList<int[]> polygons, 
    bool generateNormals, out Vector3[] nor_out)
```

### Se även

* struct [Vector4](../../../aspose.threed.utilities/vector4)
* struct [Vector3](../../../aspose.threed.utilities/vector3)
* class [PolygonModifier](../../polygonmodifier)
* namnutrymme [Aspose.ThreeD.Entities](../../polygonmodifier)
* hopsättning [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;, IList&lt;int[]&gt;) {#triangulate_3}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints, IList<int[]> polygons)
```

### Se även

* struct [Vector4](../../../aspose.threed.utilities/vector4)
* class [PolygonModifier](../../polygonmodifier)
* namnutrymme [Aspose.ThreeD.Entities](../../polygonmodifier)
* hopsättning [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;, int[]) {#triangulate_2}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints, int[] polygon)
```

### Se även

* struct [Vector4](../../../aspose.threed.utilities/vector4)
* class [PolygonModifier](../../polygonmodifier)
* namnutrymme [Aspose.ThreeD.Entities](../../polygonmodifier)
* hopsättning [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;) {#triangulate_1}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints)
```

### Se även

* struct [Vector4](../../../aspose.threed.utilities/vector4)
* class [PolygonModifier](../../polygonmodifier)
* namnutrymme [Aspose.ThreeD.Entities](../../polygonmodifier)
* hopsättning [Aspose.3D](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->