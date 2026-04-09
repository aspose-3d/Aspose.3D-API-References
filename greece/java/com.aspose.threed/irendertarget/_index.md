---
title: IRenderTarget
second_title: Aspose.3D for Java API Reference
description: Η βασική διεπαφή του στόχου απόδοσης
type: docs
weight: 249
url: /el/java/com.aspose.threed/irendertarget/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface IRenderTarget extends Closeable
```

Η βασική διεπαφή του στόχου απόδοσης
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [createViewport(Camera camera)](#createViewport-com.aspose.threed.Camera-) | Δημιουργήστε ένα παράθυρο προβολής στην καθορισμένη προοπτική της κάμερας. |
| [createViewport(Camera camera, RelativeRectangle rect)](#createViewport-com.aspose.threed.Camera-com.aspose.threed.RelativeRectangle-) | Δημιουργήστε ένα παράθυρο προβολής με θέση/μέγεθος στην καθορισμένη προοπτική της κάμερας. |
| [createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect)](#createViewport-com.aspose.threed.Camera-com.aspose.threed.Vector3-com.aspose.threed.RelativeRectangle-) | Δημιουργήστε ένα παράθυρο προβολής με καθορισμένο χρώμα φόντου και θέση/μέγεθος στην καθορισμένη προοπτική της κάμερας. |
| [getSize()](#getSize--) | Λαμβάνει το μέγεθος του στόχου απόδοσης. |
| [getViewports()](#getViewports--) | Λαμβάνει όλα τα παράθυρα προβολής που σχετίζονται με αυτόν τον στόχο απόδοσης. |
| [setSize(Vector2 value)](#setSize-com.aspose.threed.Vector2-) | Ορίζει το μέγεθος του στόχου απόδοσης. |
### createViewport(Camera camera) {#createViewport-com.aspose.threed.Camera-}
```
public abstract Viewport createViewport(Camera camera)
```


Δημιουργήστε ένα παράθυρο προβολής στην καθορισμένη προοπτική της κάμερας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Η κάμερα |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### createViewport(Camera camera, RelativeRectangle rect) {#createViewport-com.aspose.threed.Camera-com.aspose.threed.RelativeRectangle-}
```
public abstract Viewport createViewport(Camera camera, RelativeRectangle rect)
```


Δημιουργήστε ένα παράθυρο προβολής με θέση/μέγεθος στην καθορισμένη προοπτική της κάμερας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Η κάμερα |
| rect | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | Θέση και μέγεθος του παραθύρου προβολής |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect) {#createViewport-com.aspose.threed.Camera-com.aspose.threed.Vector3-com.aspose.threed.RelativeRectangle-}
```
public abstract Viewport createViewport(Camera camera, Vector3 backgroundColor, RelativeRectangle rect)
```


Δημιουργήστε ένα παράθυρο προβολής με καθορισμένο χρώμα φόντου και θέση/μέγεθος στην καθορισμένη προοπτική της κάμερας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Η κάμερα |
| backgroundColor | [Vector3](../../com.aspose.threed/vector3) | Το φόντο του παραθύρου προβολής |
| rect | [RelativeRectangle](../../com.aspose.threed/relativerectangle) | Θέση και μέγεθος του παραθύρου προβολής |

**Returns:**
[Viewport](../../com.aspose.threed/viewport)
### getSize() {#getSize--}
```
public abstract Vector2 getSize()
```


Λαμβάνει το μέγεθος του στόχου απόδοσης.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the size of the render target.
### getViewports() {#getViewports--}
```
public abstract List<Viewport> getViewports()
```


Λαμβάνει όλα τα παράθυρα προβολής που σχετίζονται με αυτόν τον στόχο απόδοσης.

**Returns:**
java.util.List<com.aspose.threed.Viewport> - όλα τα παράθυρα προβολής που σχετίζονται με αυτόν τον στόχο απόδοσης.
### setSize(Vector2 value) {#setSize-com.aspose.threed.Vector2-}
```
public abstract void setSize(Vector2 value)
```


Ορίζει το μέγεθος του στόχου απόδοσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Νέα τιμή |

