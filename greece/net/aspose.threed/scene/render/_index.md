---
title: "Scene.Render"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Μέθοδος Scene. Αποδίδει τη σκηνή σε εξωτερικό αρχείο από την προοπτική της δοσμένης κάμερας. Το προεπιλεγμένο μέγεθος εξόδου είναι 1024x768 και η μορφή εξόδου είναι png"
type: docs
weight: 150
url: /el/net/aspose.threed/scene/render/
---
## Render(Camera, string) {#render_2}

Αποδίδει τη σκηνή σε εξωτερικό αρχείο από την προοπτική της δοσμένης κάμερας. Το προεπιλεγμένο μέγεθος εξόδου είναι 1024x768 και η μορφή εξόδου είναι png

```csharp
public void Render(Camera camera, string fileName)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κάμερα | Κάμερα | Από την προοπτική ποιας κάμερας θα αποδοθεί η σκηνή |
| fileName | String | Το όνομα αρχείου του αρχείου εξόδου |

### Δείτε επίσης

* class [Camera](../../../aspose.threed.entities/camera/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Render(Camera, string, Vector2, string) {#render_3}

Αποδίδει τη σκηνή σε εξωτερικό αρχείο από την προοπτική της δοσμένης κάμερας.

```csharp
public void Render(Camera camera, string fileName, Vector2 size, string format)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κάμερα | Κάμερα | Από την προοπτική ποιας κάμερας θα αποδοθεί η σκηνή |
| fileName | String | Το όνομα αρχείου του αρχείου εξόδου |
| μέγεθος | Vector2 | Το μέγεθος της τελικής αποδιδόμενης εικόνας |
| μορφή | String | Η μορφή εικόνας του αρχείου εξόδου |

### Δείτε επίσης

* class [Camera](../../../aspose.threed.entities/camera/)
* struct [Vector2](../../../aspose.threed.utilities/vector2/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Render(Camera, string, Vector2, string, ImageRenderOptions) {#render_4}

Αποδίδει τη σκηνή σε εξωτερικό αρχείο από την προοπτική της δοσμένης κάμερας.

```csharp
public void Render(Camera camera, string fileName, Vector2 size, string format, 
    ImageRenderOptions options)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κάμερα | Κάμερα | Από την προοπτική ποιας κάμερας θα αποδοθεί η σκηνή |
| fileName | String | Το όνομα αρχείου του αρχείου εξόδου |
| μέγεθος | Vector2 | Το μέγεθος της τελικής αποδιδόμενης εικόνας |
| μορφή | String | Η μορφή εικόνας του αρχείου εξόδου |
| επιλογές | ImageRenderOptions | Η επιλογή για προσαρμογή ορισμένων εσωτερικών ρυθμίσεων. |

### Δείτε επίσης

* class [Camera](../../../aspose.threed.entities/camera/)
* struct [Vector2](../../../aspose.threed.utilities/vector2/)
* class [ImageRenderOptions](../../imagerenderoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Render(Camera, TextureData) {#render}

Αποδίδει τη σκηνή σε bitmap από την προοπτική της δοσμένης κάμερας.

```csharp
public void Render(Camera camera, TextureData bitmap)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κάμερα | Κάμερα | Από την προοπτική ποιας κάμερας θα αποδοθεί η σκηνή |
| bitmap | TextureData | Στόχος του αποδιδόμενου αποτελέσματος |

### Δείτε επίσης

* class [Camera](../../../aspose.threed.entities/camera/)
* class [TextureData](../../../aspose.threed.render/texturedata/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Render(Camera, TextureData, ImageRenderOptions) {#render_1}

Αποδίδει τη σκηνή σε bitmap από την προοπτική της δοσμένης κάμερας.

```csharp
public void Render(Camera camera, TextureData bitmap, ImageRenderOptions options)
```

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κάμερα | Κάμερα | Από την προοπτική ποιας κάμερας θα αποδοθεί η σκηνή |
| bitmap | TextureData | Στόχος του αποδιδόμενου αποτελέσματος |
| επιλογές | ImageRenderOptions | Η επιλογή για προσαρμογή ορισμένων εσωτερικών ρυθμίσεων. |

### Δείτε επίσης

* class [Camera](../../../aspose.threed.entities/camera/)
* class [TextureData](../../../aspose.threed.render/texturedata/)
* class [ImageRenderOptions](../../imagerenderoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


