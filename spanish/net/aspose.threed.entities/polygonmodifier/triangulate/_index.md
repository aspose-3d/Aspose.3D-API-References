---
title: "PolygonModifier.Triangulate"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método PolygonModifier. Convierte todas las mallas basadas en polígonos en una malla completa de triángulos"
type: docs
weight: 80
url: /es/net/aspose.threed.entities/polygonmodifier/triangulate/
---
## Triangulate(Scene) {#triangulate_5}

Convierta todas las mallas basadas en polígonos en una malla completa de triángulos.

```csharp
public static void Triangulate(Scene scene)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| escena | Escena | La escena a procesar |

## Ejemplos

El siguiente código muestra cómo combinar todos los objetos de una escena en una sola malla.

```csharp
var mesh = new Cylinder().ToMesh();

//Triangulariza esta malla basada en cuadriláteros a una basada en triángulos 
mesh = PolygonModifier.Triangulate(mesh);

var scene = new Scene(mesh);

      scene.Save("test.obj");
```

### Ver también

* class [Scene](../../../aspose.threed/scene/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Triangulate(Mesh) {#triangulate}

Convierta una malla basada en polígonos en una malla completa de triángulos.

```csharp
public static Mesh Triangulate(Mesh mesh)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| malla | Malla | La malla original que no es de triángulos |

### Valor de retorno

La nueva malla de triángulos generada

## Ejemplos

El siguiente código muestra cómo combinar todos los objetos de una escena en una sola malla.

```csharp
var mesh = new Cylinder().ToMesh();

//Triangulariza esta malla basada en cuadriláteros a una basada en triángulos 
mesh = PolygonModifier.Triangulate(mesh);

var scene = new Scene(mesh);

      scene.Save("test.obj");
```

### Ver también

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

### Ver también

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

### Ver también

* struct [Vector4](../../../aspose.threed.utilities/vector4/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;, int[]) {#triangulate_2}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints, int[] polygon)
```

### Ver también

* struct [Vector4](../../../aspose.threed.utilities/vector4/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Triangulate(IList&lt;Vector4&gt;) {#triangulate_1}

```csharp
public static int[][] Triangulate(IList<Vector4> controlPoints)
```

### Ver también

* struct [Vector4](../../../aspose.threed.utilities/vector4/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


