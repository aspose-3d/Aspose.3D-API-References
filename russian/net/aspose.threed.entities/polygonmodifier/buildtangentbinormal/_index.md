---
title: "PolygonModifier.BuildTangentBinormal"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод PolygonModifier. Это создаст tangent и binormal на всех мешах сцены. Normal требуется; если normal отсутствует в меше, он также будет создан из позиции. UV также требуется; меш будет игнорироваться, если UV не определён."
type: docs
weight: 20
url: /ru/net/aspose.threed.entities/polygonmodifier/buildtangentbinormal/
---
## BuildTangentBinormal(Scene) {#buildtangentbinormal_1}

Это создаст касательные и бинормали на всех сетках сцены. Нормаль требуется; если нормаль отсутствует на сетке, она также будет создана из позиции. UV также требуется, сетка будет игнорироваться, если UV не определён.

```csharp
public static void BuildTangentBinormal(Scene scene)
```

### См. также

* class [Scene](../../../aspose.threed/scene/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## BuildTangentBinormal(Mesh) {#buildtangentbinormal}

Это создаст касательные и бинормали на сетке. Нормаль требуется; если нормаль отсутствует на сетке, она также будет создана из позиции. UV также требуется, будет выброшено исключение, если UV не найдено.

```csharp
public static void BuildTangentBinormal(Mesh mesh)
```

### См. также

* class [Mesh](../../mesh/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


