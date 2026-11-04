---
title: "Scene.Render"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método Scene. Renderiza la escena a un archivo externo desde la perspectiva de la cámara dada. El tamaño de salida predeterminado es 1024x768 y el formato de salida es png"
type: docs
weight: 150
url: /es/net/aspose.threed/scene/render/
---
## Render(Camera, string) {#render_2}

Renderiza la escena a un archivo externo desde la perspectiva de la cámara especificada. El tamaño de salida predeterminado es 1024x768 y el formato de salida es png

```csharp
public void Render(Camera camera, string fileName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cámara | Cámara | Desde la perspectiva de qué cámara renderizar la escena |
| fileName | String | El nombre de archivo del archivo de salida |

### Ver también

* class [Camera](../../../aspose.threed.entities/camera/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Render(Camera, string, Vector2, string) {#render_3}

Renderiza la escena a un archivo externo desde la perspectiva de la cámara especificada.

```csharp
public void Render(Camera camera, string fileName, Vector2 size, string format)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cámara | Cámara | Desde la perspectiva de qué cámara renderizar la escena |
| fileName | String | El nombre de archivo del archivo de salida |
| tamaño | Vector2 | El tamaño de la imagen renderizada final |
| formato | String | El formato de imagen del archivo de salida |

### Ver también

* class [Camera](../../../aspose.threed.entities/camera/)
* struct [Vector2](../../../aspose.threed.utilities/vector2/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Render(Camera, string, Vector2, string, ImageRenderOptions) {#render_4}

Renderiza la escena a un archivo externo desde la perspectiva de la cámara especificada.

```csharp
public void Render(Camera camera, string fileName, Vector2 size, string format, 
    ImageRenderOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cámara | Cámara | Desde la perspectiva de qué cámara renderizar la escena |
| fileName | String | El nombre de archivo del archivo de salida |
| tamaño | Vector2 | El tamaño de la imagen renderizada final |
| formato | String | El formato de imagen del archivo de salida |
| opciones | ImageRenderOptions | La opción para personalizar algunos ajustes internos. |

### Ver también

* class [Camera](../../../aspose.threed.entities/camera/)
* struct [Vector2](../../../aspose.threed.utilities/vector2/)
* class [ImageRenderOptions](../../imagerenderoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Render(Camera, TextureData) {#render}

Renderiza la escena a un bitmap desde la perspectiva de la cámara especificada.

```csharp
public void Render(Camera camera, TextureData bitmap)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cámara | Cámara | Desde la perspectiva de qué cámara renderizar la escena |
| bitmap | TextureData | Objetivo del resultado renderizado |

### Ver también

* class [Camera](../../../aspose.threed.entities/camera/)
* class [TextureData](../../../aspose.threed.render/texturedata/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Render(Camera, TextureData, ImageRenderOptions) {#render_1}

Renderiza la escena a un bitmap desde la perspectiva de la cámara especificada.

```csharp
public void Render(Camera camera, TextureData bitmap, ImageRenderOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cámara | Cámara | Desde la perspectiva de qué cámara renderizar la escena |
| bitmap | TextureData | Objetivo del resultado renderizado |
| opciones | ImageRenderOptions | La opción para personalizar algunos ajustes internos. |

### Ver también

* class [Camera](../../../aspose.threed.entities/camera/)
* class [TextureData](../../../aspose.threed.render/texturedata/)
* class [ImageRenderOptions](../../imagerenderoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


