---
title: "PolygonModifier.Triangulate"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "PolygonModifier विधि। सभी polygonbased मेष को पूर्ण त्रिभुज मेष में परिवर्तित करें"
type: docs
weight: 80
url: /hi/net/aspose.threed.entities/polygonmodifier/triangulate/
---
## Triangulate(Scene) {#triangulate_5}

सभी बहुभुज-आधारित मेषों को पूर्ण त्रिकोण मेष में परिवर्तित करें।

```csharp
public static void Triangulate(Scene scene)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| दृश्य | दृश्य | प्रसंस्करण के लिए दृश्य |

## उदाहरण

निम्नलिखित कोड दिखाता है कि कैसे एक दृश्य से सभी वस्तुओं को एकल मेष में मिलाया जाए।

```csharp
var mesh = new Cylinder().ToMesh();

//इस quadrangle-आधारित मेष को त्रिभुज-आधारित में परिवर्तित करें
mesh = PolygonModifier.Triangulate(mesh);

var scene = new Scene(mesh);

      scene.Save("test.obj");
```

### देखें भी

* class [Scene](../../../aspose.threed/scene/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Triangulate(Mesh) {#triangulate}

बहुभुज-आधारित मेष को पूर्ण त्रिकोण मेष में परिवर्तित करें।

```csharp
public static Mesh Triangulate(Mesh mesh)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| mesh | मेश | मूल गैर-त्रिभुज मेष |

### रिटर्न वैल्यू

उत्पन्न नया त्रिभुज मेष

## उदाहरण

निम्नलिखित कोड दिखाता है कि कैसे एक दृश्य से सभी वस्तुओं को एकल मेष में मिलाया जाए।

```csharp
var mesh = new Cylinder().ToMesh();

//इस quadrangle-आधारित मेष को त्रिभुज-आधारित में परिवर्तित करें
mesh = PolygonModifier.Triangulate(mesh);

var scene = new Scene(mesh);

      scene.Save("test.obj");
```

### देखें भी

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

### देखें भी

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

### देखें भी

* struct [Vector4](../../../aspose.threed.utilities/vector4/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;, int[]) {#triangulate_2}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints, int[] polygon)
```

### देखें भी

* struct [Vector4](../../../aspose.threed.utilities/vector4/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;) {#triangulate_1}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints)
```

### देखें भी

* struct [Vector4](../../../aspose.threed.utilities/vector4/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


