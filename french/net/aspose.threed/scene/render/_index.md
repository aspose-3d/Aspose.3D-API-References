---
title: "Scene.Render"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode Scene. Rend la scène dans un fichier externe depuis la perspective de la caméra donnée. La taille de sortie par défaut est 1024x768 et le format de sortie est png"
type: docs
weight: 150
url: /fr/net/aspose.threed/scene/render/
---
## Render(Camera, string) {#render_2}

Rendu de la scène dans un fichier externe depuis la perspective de la caméra donnée. La taille de sortie par défaut est 1024x768 et le format de sortie est png.

```csharp
public void Render(Camera camera, string fileName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| caméra | Caméra | Depuis quelle perspective de caméra rendre la scène |
| fileName | String | Le nom du fichier de sortie |

### Voir aussi

* class [Camera](../../../aspose.threed.entities/camera/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Render(Camera, string, Vector2, string) {#render_3}

Rendu de la scène dans un fichier externe depuis la perspective de la caméra donnée.

```csharp
public void Render(Camera camera, string fileName, Vector2 size, string format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| caméra | Caméra | Depuis quelle perspective de caméra rendre la scène |
| fileName | String | Le nom du fichier de sortie |
| taille | Vector2 | La taille de l'image rendue finale |
| format | String | Le format d'image du fichier de sortie |

### Voir aussi

* class [Camera](../../../aspose.threed.entities/camera/)
* struct [Vector2](../../../aspose.threed.utilities/vector2/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Render(Camera, string, Vector2, string, ImageRenderOptions) {#render_4}

Rendu de la scène dans un fichier externe depuis la perspective de la caméra donnée.

```csharp
public void Render(Camera camera, string fileName, Vector2 size, string format, 
    ImageRenderOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| caméra | Caméra | Depuis quelle perspective de caméra rendre la scène |
| fileName | String | Le nom du fichier de sortie |
| taille | Vector2 | La taille de l'image rendue finale |
| format | String | Le format d'image du fichier de sortie |
| options | ImageRenderOptions | L'option de personnaliser certains paramètres internes. |

### Voir aussi

* class [Camera](../../../aspose.threed.entities/camera/)
* struct [Vector2](../../../aspose.threed.utilities/vector2/)
* class [ImageRenderOptions](../../imagerenderoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Render(Camera, TextureData) {#render}

Rendu de la scène en bitmap depuis la perspective de la caméra donnée.

```csharp
public void Render(Camera camera, TextureData bitmap)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| caméra | Caméra | Depuis quelle perspective de caméra rendre la scène |
| bitmap | TextureData | Cible du résultat rendu |

### Voir aussi

* class [Camera](../../../aspose.threed.entities/camera/)
* class [TextureData](../../../aspose.threed.render/texturedata/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Render(Camera, TextureData, ImageRenderOptions) {#render_1}

Rendu de la scène en bitmap depuis la perspective de la caméra donnée.

```csharp
public void Render(Camera camera, TextureData bitmap, ImageRenderOptions options)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| caméra | Caméra | Depuis quelle perspective de caméra rendre la scène |
| bitmap | TextureData | Cible du résultat rendu |
| options | ImageRenderOptions | L'option de personnaliser certains paramètres internes. |

### Voir aussi

* class [Camera](../../../aspose.threed.entities/camera/)
* class [TextureData](../../../aspose.threed.render/texturedata/)
* class [ImageRenderOptions](../../imagerenderoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


