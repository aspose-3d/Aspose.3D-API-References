---
title: "PolygonModifier.BuildTangentBinormal"
second_title: "Aspose.3D für .NET API-Referenz"
description: "PolygonModifier-Methode. Dies erstellt Tangenten und Binormale für alle Meshes der Szene. Normal ist erforderlich, wenn keine Normalen im Mesh vorhanden sind, wird es auch die Normaldaten aus der Position erzeugen. UV ist ebenfalls erforderlich; das Mesh wird ignoriert, wenn keine UV definiert ist."
type: docs
weight: 20
url: /de/net/aspose.threed.entities/polygonmodifier/buildtangentbinormal/
---
## BuildTangentBinormal(Scene) {#buildtangentbinormal_1}

Dies erzeugt Tangenten und Binormale für alle Meshes der Szene. Normalen sind erforderlich; wenn keine Normalen im Mesh vorhanden sind, werden die Normaldaten aus der Position erstellt. UVs sind ebenfalls erforderlich, das Mesh wird ignoriert, wenn keine UV definiert ist.

```csharp
public static void BuildTangentBinormal(Scene scene)
```

### Siehe auch

* class [Scene](../../../aspose.threed/scene/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## BuildTangentBinormal(Mesh) {#buildtangentbinormal}

Dies erzeugt Tangenten und Binormale im Mesh. Normalen sind erforderlich; wenn keine Normalen im Mesh vorhanden sind, werden die Normaldaten aus der Position erstellt. UVs sind ebenfalls erforderlich, es wird eine Ausnahme ausgelöst, wenn keine UV gefunden wird.

```csharp
public static void BuildTangentBinormal(Mesh mesh)
```

### Siehe auch

* class [Mesh](../../mesh/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


