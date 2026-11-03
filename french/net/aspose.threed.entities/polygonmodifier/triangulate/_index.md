---
title: "PolygonModifier.Triangulate"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode PolygonModifier. Convertir tous les maillages basés sur des polygones en maillage complet de triangles"
type: docs
weight: 80
url: /fr/net/aspose.threed.entities/polygonmodifier/triangulate/
---
## Triangulate(Scene) {#triangulate_5}

Convertissez tous les maillages basés sur des polygones en maillage entièrement triangulaire

```csharp
public static void Triangulate(Scene scene)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| scène | Scène | La scène à traiter |

## Exemples

Le code suivant montre comment fusionner tous les objets d'une scène en un seul maillage.

```csharp
var mesh = new Cylinder().ToMesh();

//Trianguler ce maillage basé sur des quadrilatères en maillage basé sur des triangles
mesh = PolygonModifier.Triangulate(mesh);

var scene = new Scene(mesh);

      scene.Save("test.obj");
```

### Voir aussi

* class [Scene](../../../aspose.threed/scene/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Triangulate(Mesh) {#triangulate}

Convertissez un maillage basé sur des polygones en maillage entièrement triangulaire

```csharp
public static Mesh Triangulate(Mesh mesh)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| maillage | Maillage | Le maillage original non triangulaire |

### Valeur de retour

Le nouveau maillage triangulaire généré

## Exemples

Le code suivant montre comment fusionner tous les objets d'une scène en un seul maillage.

```csharp
var mesh = new Cylinder().ToMesh();

//Trianguler ce maillage basé sur des quadrilatères en maillage basé sur des triangles
mesh = PolygonModifier.Triangulate(mesh);

var scene = new Scene(mesh);

      scene.Save("test.obj");
```

### Voir aussi

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

### Voir aussi

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

### Voir aussi

* struct [Vector4](../../../aspose.threed.utilities/vector4/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;, int[]) {#triangulate_2}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints, int[] polygon)
```

### Voir aussi

* struct [Vector4](../../../aspose.threed.utilities/vector4/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;) {#triangulate_1}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints)
```

### Voir aussi

* struct [Vector4](../../../aspose.threed.utilities/vector4/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


