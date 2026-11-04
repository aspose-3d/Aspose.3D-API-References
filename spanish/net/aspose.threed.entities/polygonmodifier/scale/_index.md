---
title: "PolygonModifier.Scale"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método PolygonModifier. Escalar todas las geometrías. Escalar los puntos de control, no la matriz de transformación en esta escena."
type: docs
weight: 60
url: /es/net/aspose.threed.entities/polygonmodifier/scale/
---
## Scale(Scene, Vector3) {#scale}

Escalar todas las geometrías (escalar los puntos de control, no la matriz de transformación) en esta escena

```csharp
public static Scene Scale(Scene scene, Vector3 scale)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| escena | Escena | La escena a escalar |
| escala | Vector3 | El factor de escala |

## Ejemplos

El siguiente código muestra cómo escalar todas las geometrías en la escena por 10 veces.

```csharp
//Cargar un archivo de prueba para escalar
var scene = Scene.FromFile("input.fbx");
//escalar todas las geometrías 10 veces.
PolygonModifier.Scale(scene, new Vector3(10, 10, 10));
scene.Save("test.obj");
```

### Ver también

* class [Scene](../../../aspose.threed/scene/)
* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)

---

## Scale(Node, Vector3) {#scale_1}

Escalar todas las geometrías (escalar los puntos de control, no la matriz de transformación) en este nodo

```csharp
public static void Scale(Node node, Vector3 scale)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nodo | Nodo | El nodo a escalar |
| escala | Vector3 | El factor de escala |

## Ejemplos

El siguiente código muestra cómo escalar todas las geometrías en la escena por 10 veces.

```csharp
//Cargar un archivo de prueba para escalar
var scene = Scene.FromFile("input.fbx");
//escalar todas las geometrías 10 veces.
PolygonModifier.Scale(scene.RootNode, new Vector3(10, 10, 10));
scene.Save("test.obj");
```

### Ver también

* class [Node](../../../aspose.threed/node/)
* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [PolygonModifier](../)
* namespace [Aspose.ThreeD.Entities](../../polygonmodifier/)
* assembly [Aspose.3D](../../../)


