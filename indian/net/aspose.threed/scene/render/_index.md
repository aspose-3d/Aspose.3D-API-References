---
title: "Scene.Render"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Scene मेथड। दिए गए कैमरों के दृष्टिकोण से सीन को बाहरी फ़ाइल में रेंडर करता है। डिफ़ॉल्ट आउटपुट आकार 1024x768 है और आउटपुट फ़ॉर्मेट png है।"
type: docs
weight: 150
url: /hi/net/aspose.threed/scene/render/
---
## Render(Camera, string) {#render_2}

दिए गए कैमरे के दृष्टिकोण से दृश्य को बाहरी फ़ाइल में रेंडर करता है। डिफ़ॉल्ट आउटपुट आकार 1024x768 है और आउटपुट स्वरूप png है।

```csharp
public void Render(Camera camera, string fileName)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| कैमरा | कैमरा | किस कैमरे के दृष्टिकोण से सीन को रेंडर किया जाए |
| fileName | String | आउटपुट फ़ाइल का नाम |

### देखें भी

* class [Camera](../../../aspose.threed.entities/camera/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Render(Camera, string, Vector2, string) {#render_3}

दिए गए कैमरे के दृष्टिकोण से दृश्य को बाहरी फ़ाइल में रेंडर करता है।

```csharp
public void Render(Camera camera, string fileName, Vector2 size, string format)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| कैमरा | कैमरा | किस कैमरे के दृष्टिकोण से सीन को रेंडर किया जाए |
| fileName | String | आउटपुट फ़ाइल का नाम |
| आकार | Vector2 | अंतिम रेंडर की गई छवि का आकार |
| फ़ॉर्मेट | String | आउटपुट फ़ाइल का छवि फ़ॉर्मेट |

### देखें भी

* class [Camera](../../../aspose.threed.entities/camera/)
* struct [Vector2](../../../aspose.threed.utilities/vector2/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Render(Camera, string, Vector2, string, ImageRenderOptions) {#render_4}

दिए गए कैमरे के दृष्टिकोण से दृश्य को बाहरी फ़ाइल में रेंडर करता है।

```csharp
public void Render(Camera camera, string fileName, Vector2 size, string format, 
    ImageRenderOptions options)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| कैमरा | कैमरा | किस कैमरे के दृष्टिकोण से सीन को रेंडर किया जाए |
| fileName | String | आउटपुट फ़ाइल का नाम |
| आकार | Vector2 | अंतिम रेंडर की गई छवि का आकार |
| फ़ॉर्मेट | String | आउटपुट फ़ाइल का छवि फ़ॉर्मेट |
| options | ImageRenderOptions | कुछ आंतरिक सेटिंग्स को अनुकूलित करने का विकल्प। |

### देखें भी

* class [Camera](../../../aspose.threed.entities/camera/)
* struct [Vector2](../../../aspose.threed.utilities/vector2/)
* class [ImageRenderOptions](../../imagerenderoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Render(Camera, TextureData) {#render}

दिए गए कैमरे के दृष्टिकोण से दृश्य को बिटमैप में रेंडर करता है।

```csharp
public void Render(Camera camera, TextureData bitmap)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| कैमरा | कैमरा | किस कैमरे के दृष्टिकोण से सीन को रेंडर किया जाए |
| bitmap | TextureData | रेंडर किए गए परिणाम का लक्ष्य |

### देखें भी

* class [Camera](../../../aspose.threed.entities/camera/)
* class [TextureData](../../../aspose.threed.render/texturedata/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Render(Camera, TextureData, ImageRenderOptions) {#render_1}

दिए गए कैमरे के दृष्टिकोण से दृश्य को बिटमैप में रेंडर करता है।

```csharp
public void Render(Camera camera, TextureData bitmap, ImageRenderOptions options)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| कैमरा | कैमरा | किस कैमरे के दृष्टिकोण से सीन को रेंडर किया जाए |
| bitmap | TextureData | रेंडर किए गए परिणाम का लक्ष्य |
| options | ImageRenderOptions | कुछ आंतरिक सेटिंग्स को अनुकूलित करने का विकल्प। |

### देखें भी

* class [Camera](../../../aspose.threed.entities/camera/)
* class [TextureData](../../../aspose.threed.render/texturedata/)
* class [ImageRenderOptions](../../imagerenderoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


