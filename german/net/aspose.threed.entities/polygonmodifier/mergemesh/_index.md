---
title: "PolygonModifier.MergeMesh"
second_title: "Aspose.3D für .NET API-Referenz"
description: "PolygonModifier-Methode. Konvertieren Sie eine ganze Szene in ein einzelnes transformiertes Mesh. Vertex-Elemente wie Normalen-/Texturkoordinaten werden noch nicht unterstützt."
type: docs
weight: 50
url: /de/net/aspose.threed.entities/polygonmodifier/mergemesh/
---
## MergeMesh(Scene) {#mergemesh_1}

Eine gesamte Szene in ein einzelnes transformiertes Mesh konvertieren. Vertex-Elemente wie Normalen-/Texturkoordinaten werden noch nicht unterstützt.

```csharp
public static Mesh MergeMesh(Scene scene)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| scene | Scene | Die Szene zum Zusammenführen |

### Rückgabewert

Das zusammengeführte Mesh

## Beispiele

Der folgende Code zeigt, wie alle Objekte einer Szene zu einem einzigen Mesh zusammengeführt werden.

```csharp
//Eingabedatei kann mehrere Objekte enthalten
var scene = Scene.FromFile("input.fbx");
//Jetzt werden sie zu einem einzigen Mesh zusammengeführt
Mesh merged = PolygonModifier.MergeMesh(scene);
//Dann speichern wir es in einer Datei mit nur einem Mesh
var newScene = new Scene(merged);
newScene.Save("test.obj");
```

### Siehe auch

* class [Mesh](../../mesh/)
* class [Scene](../../../aspose.threed/scene/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## MergeMesh(IList&lt;Node&gt;) {#mergemesh_2}

```csharp
public static Mesh MergeMesh(IList<Node> nodes)
```

### Siehe auch

* class [Mesh](../../mesh/)
* class [Node](../../../aspose.threed/node/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## MergeMesh(Node) {#mergemesh}

Einen gesamten Knoten in ein einzelnes transformiertes Mesh konvertieren. Vertex-Elemente wie Normalen-/Texturkoordinaten werden noch nicht unterstützt.

```csharp
public static Mesh MergeMesh(Node node)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Knoten | Knoten | Der Knoten zum Zusammenführen |

### Rückgabewert

Zusammengeführtes Mesh

## Beispiele

Der folgende Code zeigt, wie man alle Objekte von Knoten zu einem einzigen Mesh zusammenführt.

```csharp
//Eingabedatei kann mehrere Objekte enthalten
var scene = Scene.FromFile("input.fbx");
//Jetzt werden sie zu einem einzigen Mesh zusammengeführt
Mesh merged = PolygonModifier.MergeMesh(scene.RootNode);
//Dann speichern wir es in einer Datei mit nur einem Mesh
var newScene = new Scene(merged);
newScene.Save("test.obj");
```

### Siehe auch

* class [Mesh](../../mesh/)
* class [Node](../../../aspose.threed/node/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


