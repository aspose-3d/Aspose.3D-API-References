---
title: "IRenderTarget"
second_title: "Référence d'API Aspose.3D pour Java"
description: "L'interface de base de la cible de rendu"
type: docs
weight: 249
url: /fr/java/com.aspose.threed/irendertarget/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface IRenderTarget extends Closeable
```

L'interface de base de la cible de rendu
## Méthodes

| Méthode | Description |
| --- | --- |
| [createViewport(Camera camera)](#createViewport-com.aspose.threed.Camera-) | Créer une fenêtre d'affichage dans la perspective de la caméra spécifiée. |
| [createViewport(Camera camera, RelativeRectangle rect)](#createViewport-com.aspose.threed.Camera-com.aspose.threed.RelativeRectangle-) | Créer une fenêtre d'affichage avec position/taille dans la perspective de la caméra spécifiée. |
| [createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect)](#createViewport-com.aspose.threed.Camera-com.aspose.threed.Vector3-com.aspose.threed.RelativeRectangle-) | Créer une fenêtre d'affichage avec la couleur d'arrière-plan spécifiée et la position/taille dans la perspective de la caméra spécifiée. |
| [getSize()](#getSize--) | Obtient la taille de la cible de rendu. |
| [getViewports()](#getViewports--) | Obtient toutes les fenêtres d'affichage associées à cette cible de rendu. |
| [setSize(Vector2 value)](#setSize-com.aspose.threed.Vector2-) | Définit la taille de la cible de rendu. |
### createViewport(Camera camera) {#createViewport-com.aspose.threed.Camera-}
```
public abstract Viewport createViewport(Camera camera)
```


Créer une fenêtre d'affichage dans la perspective de la caméra spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | La caméra |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### createViewport(Camera camera, RelativeRectangle rect) {#createViewport-com.aspose.threed.Camera-com.aspose.threed.RelativeRectangle-}
```
public abstract Viewport createViewport(Camera camera, RelativeRectangle rect)
```


Créer une fenêtre d'affichage avec position/taille dans la perspective de la caméra spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | La caméra |
| rect | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | Position et taille de la fenêtre d'affichage |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect) {#createViewport-com.aspose.threed.Camera-com.aspose.threed.Vector3-com.aspose.threed.RelativeRectangle-}
```
public abstract Viewport createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect)
```


Créer une fenêtre d'affichage avec la couleur d'arrière-plan spécifiée et la position/taille dans la perspective de la caméra spécifiée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | La caméra |
| backgroundColor | [Vector3](../../com.aspose.threed/vector3) | L'arrière-plan de la fenêtre d'affichage |
| rect | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | Position et taille de la fenêtre d'affichage |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### getSize() {#getSize--}
```
public abstract Vector2 getSize()
```


Obtient la taille de la cible de rendu.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the size of the render target.
### getViewports() {#getViewports--}
```
public abstract List<Viewport> getViewports()
```


Obtient toutes les fenêtres d'affichage associées à cette cible de rendu.

**Returns:**
java.util.List<com.aspose.threed.Viewport> - toutes les fenêtres d'affichage associées à cette cible de rendu.
### setSize(Vector2 value) {#setSize-com.aspose.threed.Vector2-}
```
public abstract void setSize(Vector2 value)
```


Définit la taille de la cible de rendu.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nouvelle valeur |

