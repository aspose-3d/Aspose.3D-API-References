---
title: "PolygonModifier.Triangulate"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος PolygonModifier. Μετατρέψτε όλα τα polygonbased meshes σε πλήρη triangle mesh"
type: docs
weight: 80
url: /el/net/aspose.threed.entities/polygonmodifier/triangulate/
---
## Triangulate(Scene) {#triangulate_5}

Μετατρέψτε όλα τα πλέγματα βασισμένα σε πολύγωνα σε πλήρη τριγωνικά πλέγματα.

```csharp
public static void Triangulate(Scene scene)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| σκηνή | Σκηνή | Η σκηνή προς επεξεργασία |

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να συγχωνεύσετε όλα τα αντικείμενα από μια σκηνή σε ένα ενιαίο mesh.

```csharp
var mesh = new Cylinder().ToMesh();

//Τριγωνοποιήστε αυτό το quadrangle-based mesh σε triangle-based 
mesh = PolygonModifier.Triangulate(mesh);

var scene = new Scene(mesh);

      scene.Save("test.obj");
```

### Δείτε επίσης

* class [Scene](../../../aspose.threed/scene/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Triangulate(Mesh) {#triangulate}

Μετατρέψτε ένα πλέγμα βασισμένο σε πολύγωνα σε πλήρες τριγωνικό πλέγμα.

```csharp
public static Mesh Triangulate(Mesh mesh)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| πλέγμα | Πλέγμα | Το αρχικό non-triangle mesh |

### Τιμή επιστροφής

Το παραγόμενο νέο triangle mesh

## Παραδείγματα

Ο παρακάτω κώδικας δείχνει πώς να συγχωνεύσετε όλα τα αντικείμενα από μια σκηνή σε ένα ενιαίο mesh.

```csharp
var mesh = new Cylinder().ToMesh();

//Τριγωνοποιήστε αυτό το quadrangle-based mesh σε triangle-based 
mesh = PolygonModifier.Triangulate(mesh);

var scene = new Scene(mesh);

      scene.Save("test.obj");
```

### Δείτε επίσης

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

### Δείτε επίσης

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

### Δείτε επίσης

* struct [Vector4](../../../aspose.threed.utilities/vector4/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;, int[]) {#triangulate_2}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints, int[] polygon)
```

### Δείτε επίσης

* struct [Vector4](../../../aspose.threed.utilities/vector4/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;) {#triangulate_1}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints)
```

### Δείτε επίσης

* struct [Vector4](../../../aspose.threed.utilities/vector4/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


