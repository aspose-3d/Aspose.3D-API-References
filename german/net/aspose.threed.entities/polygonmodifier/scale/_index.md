---
title: "PolygonModifier.Scale"
second_title: "Aspose.3D für .NET API-Referenz"
description: "PolygonModifier-Methode. Skalieren Sie alle Geometrien. Skalieren Sie die Kontrollpunkte, nicht die Transformationsmatrix in dieser Szene"
type: docs
weight: 60
url: /de/net/aspose.threed.entities/polygonmodifier/scale/
---
## Scale(Scene, Vector3) {#scale}

Alle Geometrien in dieser Szene skalieren (die Kontrollpunkte skalieren, nicht die Transformationsmatrix).

```csharp
public static Scene Scale(Scene scene, Vector3 scale)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scene | Scene | Die Szene zum Skalieren |
| Skalierung | Vector3 | Der Skalierungsfaktor |

## Beispiele

Der folgende Code zeigt, wie man alle Geometrien in der Szene um das 10-fache skaliert.

```csharp
//Laden Sie eine Testdatei zum Skalieren
var scene = Scene.FromFile("input.fbx");
//Skalieren Sie alle Geometrien um das 10-fache.
PolygonModifier.Scale(scene, new Vector3(10, 10, 10));
scene.Save("test.obj");
```

### Siehe auch

* class [Scene](../../../aspose.threed/scene/)
* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Scale(Node, Vector3) {#scale_1}

Alle Geometrien in diesem Knoten skalieren (die Kontrollpunkte skalieren, nicht die Transformationsmatrix).

```csharp
public static void Scale(Node node, Vector3 scale)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Knoten | Knoten | Der Knoten zum Skalieren |
| Skalierung | Vector3 | Der Skalierungsfaktor |

## Beispiele

Der folgende Code zeigt, wie man alle Geometrien in der Szene um das 10-fache skaliert.

```csharp
//Laden Sie eine Testdatei zum Skalieren
var scene = Scene.FromFile("input.fbx");
//Skalieren Sie alle Geometrien um das 10-fache.
PolygonModifier.Scale(scene.RootNode, new Vector3(10, 10, 10));
scene.Save("test.obj");
```

### Siehe auch

* class [Node](../../../aspose.threed/node/)
* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


