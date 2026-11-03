---
title: "Scene.Render"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Scene-Methode. Rendert die Szene in eine externe Datei aus der Perspektive der angegebenen Kamera. Die Standardausgabegröße ist 1024x768 und das Ausgabeformat ist png."
type: docs
weight: 150
url: /de/net/aspose.threed/scene/render/
---
## Render(Camera, string) {#render_2}

Rendert die Szene aus der Sicht der angegebenen Kamera in eine externe Datei. Die Standardausgabegröße beträgt 1024x768 und das Ausgabeformat ist png.

```csharp
public void Render(Camera camera, string fileName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Kamera | Kamera | Aus welcher Kameraperspektive die Szene gerendert werden soll |
| fileName | String | Der Dateiname der Ausgabedatei |

### Siehe auch

* class [Camera](../../../aspose.threed.entities/camera/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Render(Camera, string, Vector2, string) {#render_3}

Rendert die Szene aus der Sicht der angegebenen Kamera in eine externe Datei.

```csharp
public void Render(Camera camera, string fileName, Vector2 size, string format)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Kamera | Kamera | Aus welcher Kameraperspektive die Szene gerendert werden soll |
| fileName | String | Der Dateiname der Ausgabedatei |
| Größe | Vector2 | Die Größe des final gerenderten Bildes |
| Format | String | Das Bildformat der Ausgabedatei |

### Siehe auch

* class [Camera](../../../aspose.threed.entities/camera/)
* struct [Vector2](../../../aspose.threed.utilities/vector2/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Render(Camera, string, Vector2, string, ImageRenderOptions) {#render_4}

Rendert die Szene aus der Sicht der angegebenen Kamera in eine externe Datei.

```csharp
public void Render(Camera camera, string fileName, Vector2 size, string format, 
    ImageRenderOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Kamera | Kamera | Aus welcher Kameraperspektive die Szene gerendert werden soll |
| fileName | String | Der Dateiname der Ausgabedatei |
| Größe | Vector2 | Die Größe des final gerenderten Bildes |
| Format | String | Das Bildformat der Ausgabedatei |
| options | ImageRenderOptions | Die Option, einige interne Einstellungen anzupassen. |

### Siehe auch

* class [Camera](../../../aspose.threed.entities/camera/)
* struct [Vector2](../../../aspose.threed.utilities/vector2/)
* class [ImageRenderOptions](../../imagerenderoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Render(Camera, TextureData) {#render}

Rendert die Szene aus der Sicht der angegebenen Kamera in ein Bitmap.

```csharp
public void Render(Camera camera, TextureData bitmap)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Kamera | Kamera | Aus welcher Kameraperspektive die Szene gerendert werden soll |
| Bitmap | TextureData | Ziel des gerenderten Ergebnisses |

### Siehe auch

* class [Camera](../../../aspose.threed.entities/camera/)
* class [TextureData](../../../aspose.threed.render/texturedata/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Render(Camera, TextureData, ImageRenderOptions) {#render_1}

Rendert die Szene aus der Sicht der angegebenen Kamera in ein Bitmap.

```csharp
public void Render(Camera camera, TextureData bitmap, ImageRenderOptions options)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Kamera | Kamera | Aus welcher Kameraperspektive die Szene gerendert werden soll |
| Bitmap | TextureData | Ziel des gerenderten Ergebnisses |
| options | ImageRenderOptions | Die Option, einige interne Einstellungen anzupassen. |

### Siehe auch

* class [Camera](../../../aspose.threed.entities/camera/)
* class [TextureData](../../../aspose.threed.render/texturedata/)
* class [ImageRenderOptions](../../imagerenderoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


