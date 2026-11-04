---
title: "PolygonModifier.MergeMesh"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método PolygonModifier. Convertir una escena completa en una única malla transformada. Los elementos de vértice como normales/coordenadas de textura aún no son compatibles."
type: docs
weight: 50
url: /es/net/aspose.threed.entities/polygonmodifier/mergemesh/
---
## MergeMesh(Scene) {#mergemesh_1}

Convertir una escena completa en una única malla transformada. Los elementos de vértice como normales/coordenadas de textura aún no son compatibles.

```csharp
public static Mesh MergeMesh(Scene scene)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| escena | Escena | La escena a fusionar |

### Valor de retorno

La malla fusionada

## Ejemplos

El siguiente código muestra cómo combinar todos los objetos de una escena en una sola malla.

```csharp
//El archivo de entrada puede contener varios objetos
var scene = Scene.FromFile("input.fbx");
//ahora fusiona los objetos en una sola malla
Mesh merged = PolygonModifier.MergeMesh(scene);
//luego lo guardamos en un archivo con una sola malla
var newScene = new Scene(merged);
newScene.Save("test.obj");
```

### Ver también

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

### Ver también

* class [Mesh](../../mesh/)
* class [Node](../../../aspose.threed/node/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## MergeMesh(Node) {#mergemesh}

Convertir un nodo completo en una única malla transformada. Los elementos de vértice como normales/coordenadas de textura aún no son compatibles.

```csharp
public static Mesh MergeMesh(Node node)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nodo | Nodo | El nodo a fusionar |

### Valor de retorno

Malla fusionada

## Ejemplos

El siguiente código muestra cómo fusionar todos los objetos de los nodos en una sola malla.

```csharp
//El archivo de entrada puede contener varios objetos
var scene = Scene.FromFile("input.fbx");
//ahora fusiona los objetos en una sola malla
Mesh merged = PolygonModifier.MergeMesh(scene.RootNode);
//luego lo guardamos en un archivo con una sola malla
var newScene = new Scene(merged);
newScene.Save("test.obj");
```

### Ver también

* class [Mesh](../../mesh/)
* class [Node](../../../aspose.threed/node/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


