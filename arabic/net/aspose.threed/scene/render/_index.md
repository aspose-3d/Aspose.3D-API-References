---
title: "Scene.Render"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة Scene. تصيير المشهد إلى ملف خارجي من منظور الكاميرا المحددة. حجم الإخراج الافتراضي هو 1024x768 وتنسيق الإخراج هو png"
type: docs
weight: 150
url: /ar/net/aspose.threed/scene/render/
---
## Render(Camera, string) {#render_2}

يُصوّر المشهد إلى ملف خارجي من منظور الكاميرا المحددة. حجم الإخراج الافتراضي هو 1024x768 وتنسيق الإخراج هو png

```csharp
public void Render(Camera camera, string fileName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| كاميرا | كاميرا | من أي منظور للكاميرا يتم تصيير المشهد |
| fileName | سلسلة | اسم ملف الإخراج |

### انظر أيضًا

* class [Camera](../../../aspose.threed.entities/camera/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Render(Camera, string, Vector2, string) {#render_3}

يُصوّر المشهد إلى ملف خارجي من منظور الكاميرا المحددة.

```csharp
public void Render(Camera camera, string fileName, Vector2 size, string format)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| كاميرا | كاميرا | من أي منظور للكاميرا يتم تصيير المشهد |
| fileName | سلسلة | اسم ملف الإخراج |
| الحجم | Vector2 | حجم الصورة المصورة النهائية |
| تنسيق | سلسلة | تنسيق الصورة لملف الإخراج |

### انظر أيضًا

* class [Camera](../../../aspose.threed.entities/camera/)
* struct [Vector2](../../../aspose.threed.utilities/vector2/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Render(Camera, string, Vector2, string, ImageRenderOptions) {#render_4}

يُصوّر المشهد إلى ملف خارجي من منظور الكاميرا المحددة.

```csharp
public void Render(Camera camera, string fileName, Vector2 size, string format, 
    ImageRenderOptions options)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| كاميرا | كاميرا | من أي منظور للكاميرا يتم تصيير المشهد |
| fileName | سلسلة | اسم ملف الإخراج |
| الحجم | Vector2 | حجم الصورة المصورة النهائية |
| تنسيق | سلسلة | تنسيق الصورة لملف الإخراج |
| خيارات | ImageRenderOptions | الخيار لتخصيص بعض الإعدادات الداخلية. |

### انظر أيضًا

* class [Camera](../../../aspose.threed.entities/camera/)
* struct [Vector2](../../../aspose.threed.utilities/vector2/)
* class [ImageRenderOptions](../../imagerenderoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Render(Camera, TextureData) {#render}

يُصوّر المشهد إلى صورة نقطية من منظور الكاميرا المحددة.

```csharp
public void Render(Camera camera, TextureData bitmap)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| كاميرا | كاميرا | من أي منظور للكاميرا يتم تصيير المشهد |
| صورة نقطية | TextureData | هدف النتيجة المصورة |

### انظر أيضًا

* class [Camera](../../../aspose.threed.entities/camera/)
* class [TextureData](../../../aspose.threed.render/texturedata/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Render(Camera, TextureData, ImageRenderOptions) {#render_1}

يُصوّر المشهد إلى صورة نقطية من منظور الكاميرا المحددة.

```csharp
public void Render(Camera camera, TextureData bitmap, ImageRenderOptions options)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| كاميرا | كاميرا | من أي منظور للكاميرا يتم تصيير المشهد |
| صورة نقطية | TextureData | هدف النتيجة المصورة |
| خيارات | ImageRenderOptions | الخيار لتخصيص بعض الإعدادات الداخلية. |

### انظر أيضًا

* class [Camera](../../../aspose.threed.entities/camera/)
* class [TextureData](../../../aspose.threed.render/texturedata/)
* class [ImageRenderOptions](../../imagerenderoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


