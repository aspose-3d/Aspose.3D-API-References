---
title: "PolygonModifier.BuildTangentBinormal"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método PolygonModifier. Esto creará tangente y binormal en todas las mallas de la escena. Se requiere la normal; si la normal no existe en la malla, también se crearán los datos normales a partir de la posición. También se requiere UV; la malla será ignorada si no se define UV."
type: docs
weight: 20
url: /es/net/aspose.threed.entities/polygonmodifier/buildtangentbinormal/
---
## BuildTangentBinormal(Scene) {#buildtangentbinormal_1}

Esto creará tangentes y binormales en todas las mallas de la escena. Se requiere la normal; si la normal no existe en la malla, también se creará la información de la normal a partir de la posición. También se requiere UV; la malla será ignorada si no se define UV.

```csharp
public static void BuildTangentBinormal(Scene scene)
```

### Ver también

* class [Scene](../../../aspose.threed/scene/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## BuildTangentBinormal(Mesh) {#buildtangentbinormal}

Esto creará tangentes y binormales en la malla. Se requiere la normal; si la normal no existe en la malla, también se creará la información de la normal a partir de la posición. También se requiere UV; se lanzará una excepción si no se encuentra UV.

```csharp
public static void BuildTangentBinormal(Mesh mesh)
```

### Ver también

* class [Mesh](../../mesh/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


