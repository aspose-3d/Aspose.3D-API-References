---
title: दृश्य
second_title: Aspose.3D for Java API Reference
description: 
type: docs
weight: 161
url: /hi/java/com.aspose.threed/scene/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class Scene extends SceneObject
```
## Constructors

| Constructor | विवरण |
| --- | --- |
| [Scene(Entity entity)](#Scene-com.aspose.threed.Entity-) | [Scene](../../com.aspose.threed/scene) क्लास का नया उदाहरण एक इकाई को नई नोड से संलग्न करके प्रारंभ करता है। |
| [Scene(Scene parentScene, String name)](#Scene-com.aspose.threed.Scene-java.lang.String-) | [Scene](../../com.aspose.threed/scene) क्लास का नया उदाहरण उप-दृश्य के रूप में प्रारंभ करता है। |
| [Scene()](#Scene--) | [Scene](../../com.aspose.threed/scene) क्लास का नया उदाहरण प्रारंभ करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| [VERSION](#VERSION) | वर्तमान रिलीज़ संस्करण प्राप्त करता है |
## Methods

| Method | विवरण |
| --- | --- |
| [clear()](#clear--) | दृश्य की सामग्री साफ़ करता है और डिफ़ॉल्ट सेटिंग्स पुनर्स्थापित करता है। |
| [createAnimationClip(String name)](#createAnimationClip-java.lang.String-) | एक शॉर्टहैंड फ़ंक्शन जो [AnimationClip](../../com.aspose.threed/animationclip) बनाता और पंजीकृत करता है। पहला [AnimationClip](../../com.aspose.threed/animationclip) को [getCurrentAnimationClip](../../com.aspose.threed/scene\#getCurrentAnimationClip) को सौंपा जाएगा। |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | प्रॉपर्टी को खोजता है। |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | दिए गए पथ से दृश्य खोलता है |
| [fromFile(String fileName, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.Cancellation-) | दिए गए पथ से दृश्य खोलता है |
| [fromFile(String fileName, FileFormat format)](#fromFile-java.lang.String-com.aspose.threed.FileFormat-) | निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दिए गए पथ से दृश्य खोलता है। |
| [fromFile(String fileName, FileFormat format, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दिए गए पथ से दृश्य खोलता है। |
| [fromFile(String fileName, LoadOptions options)](#fromFile-java.lang.String-com.aspose.threed.LoadOptions-) | निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दिए गए पथ से दृश्य खोलता है। |
| [fromFile(String fileName, LoadOptions options, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दिए गए पथ से दृश्य खोलता है। |
| [fromStream(Stream stream)](#fromStream-com.aspose.threed.Stream-) | दिए गए स्ट्रीम से दृश्य खोलता है |
| [fromStream(Stream stream, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.Cancellation-) | दिए गए स्ट्रीम से दृश्य खोलता है |
| [fromStream(Stream stream, FileFormat format)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है। |
| [fromStream(Stream stream, FileFormat format, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है। |
| [fromStream(Stream stream, LoadOptions options)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-) | निर्दिष्ट IO कॉन्फ़िग का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है। |
| [fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | निर्दिष्ट IO कॉन्फ़िग का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है। |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | दिए गए स्ट्रीम से दृश्य खोलता है |
| [fromStream(InputStream stream, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.Cancellation-) | दिए गए स्ट्रीम से दृश्य खोलता है |
| [fromStream(InputStream stream, FileFormat format)](#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-) | निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है। |
| [fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है। |
| [fromStream(InputStream stream, LoadOptions options)](#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-) | निर्दिष्ट IO कॉन्फ़िग का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है। |
| [fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | निर्दिष्ट IO कॉन्फ़िग का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है। |
| [getAnimationClip(String name)](#getAnimationClip-java.lang.String-) | नामित [AnimationClip](../../com.aspose.threed/animationclip) प्राप्त करता है |
| [getAnimationClips()](#getAnimationClips--) | दृश्य में परिभाषित सभी [AnimationClip](../../com.aspose.threed/animationclip) प्राप्त करता है। |
| [getAssetInfo()](#getAssetInfo--) | शीर्ष-स्तर की एसेट जानकारी प्राप्त करता है |
| [getClass()](#getClass--) |  |
| [getCurrentAnimationClip()](#getCurrentAnimationClip--) | सक्रिय [AnimationClip](../../com.aspose.threed/animationclip) प्राप्त करता है |
| [getLibrary()](#getLibrary--) | वे ऑब्जेक्ट जो दृश्य पदानुक्रम में सीधे उपयोग नहीं होते, लाइब्रेरी में परिभाषित किए जा सकते हैं। |
| [getName()](#getName--) | नाम प्राप्त करता है। |
| [getPoses()](#getPoses--) | इस दृश्य में उपयोग किए गए सभी [Pose](../../com.aspose.threed/pose) प्राप्त करता है। |
| [getProperties()](#getProperties--) | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [getProperty(String property)](#getProperty-java.lang.String-) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [getRootNode()](#getRootNode--) | दृश्य का रूट नोड प्राप्त करता है। |
| [getScene()](#getScene--) | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [getSubScenes()](#getSubScenes--) | सभी उप-दृश्य प्राप्त करता है |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [open(Stream stream)](#open-com.aspose.threed.Stream-) | दिए गए स्ट्रीम से दृश्य खोलता है |
| [open(Stream stream, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.Cancellation-) | दिए गए स्ट्रीम से दृश्य खोलता है |
| [open(Stream stream, FileFormat format)](#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है। |
| [open(Stream stream, FileFormat format, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है। |
| [open(Stream stream, LoadOptions options)](#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-) | निर्दिष्ट IO कॉन्फ़िग का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है। |
| [open(Stream stream, LoadOptions options, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | निर्दिष्ट IO कॉन्फ़िग का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है। |
| [open(InputStream stream)](#open-java.io.InputStream-) | दिए गए स्ट्रीम से दृश्य खोलता है |
| [open(InputStream stream, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.Cancellation-) | दिए गए स्ट्रीम से दृश्य खोलता है |
| [open(InputStream stream, FileFormat format)](#open-java.io.InputStream-com.aspose.threed.FileFormat-) | निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है। |
| [open(InputStream stream, FileFormat format, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है। |
| [open(InputStream stream, LoadOptions options)](#open-java.io.InputStream-com.aspose.threed.LoadOptions-) | निर्दिष्ट IO कॉन्फ़िग का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है। |
| [open(InputStream stream, LoadOptions options, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | निर्दिष्ट IO कॉन्फ़िग का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है। |
| [open(String fileName)](#open-java.lang.String-) | दिए गए पथ से दृश्य खोलता है |
| [open(String fileName, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.Cancellation-) | दिए गए पथ से दृश्य खोलता है |
| [open(String fileName, FileFormat format)](#open-java.lang.String-com.aspose.threed.FileFormat-) | निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दिए गए पथ से दृश्य खोलता है। |
| [open(String fileName, FileFormat format, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दिए गए पथ से दृश्य खोलता है। |
| [open(String fileName, LoadOptions options)](#open-java.lang.String-com.aspose.threed.LoadOptions-) | निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दिए गए पथ से दृश्य खोलता है। |
| [open(String fileName, LoadOptions options, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दिए गए पथ से दृश्य खोलता है। |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [render(Camera camera, TextureData bitmap)](#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-) | दिए गए कैमरे के दृष्टिकोण से दृश्य को बिटमैप में रेंडर करता है। |
| [render(Camera camera, TextureData bitmap, ImageRenderOptions options)](#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-com.aspose.threed.ImageRenderOptions-) | दिए गए कैमरे के दृष्टिकोण से दृश्य को बिटमैप में रेंडर करता है। |
| [render(Camera camera, String fileName)](#render-com.aspose.threed.Camera-java.lang.String-) | दिए गए कैमरे के दृष्टिकोण से दृश्य को बाहरी फ़ाइल में रेंडर करता है। |
| [render(Camera camera, String fileName, Vector2 size, String format)](#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-) | दिए गए कैमरे के दृष्टिकोण से दृश्य को बाहरी फ़ाइल में रेंडर करता है। |
| [render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options)](#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-com.aspose.threed.ImageRenderOptions-) | दिए गए कैमरे के दृष्टिकोण से दृश्य को बाहरी फ़ाइल में रेंडर करता है। |
| [save(Stream stream, FileFormat format)](#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दृश्य को स्ट्रीम में सहेजता है। |
| [save(Stream stream, FileFormat format, Cancellation cancellationToken)](#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दृश्य को स्ट्रीम में सहेजता है। |
| [save(Stream stream, SaveOptions options)](#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-) | निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दृश्य को स्ट्रीम में सहेजता है। |
| [save(Stream stream, SaveOptions options, Cancellation cancellationToken)](#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दृश्य को स्ट्रीम में सहेजता है। |
| [save(OutputStream stream, FileFormat format)](#save-java.io.OutputStream-com.aspose.threed.FileFormat-) | निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दृश्य को स्ट्रीम में सहेजता है। |
| [save(OutputStream stream, FileFormat format, Cancellation cancellationToken)](#save-java.io.OutputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दृश्य को स्ट्रीम में सहेजता है। |
| [save(OutputStream stream, SaveOptions options)](#save-java.io.OutputStream-com.aspose.threed.SaveOptions-) | निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दृश्य को स्ट्रीम में सहेजता है। |
| [save(OutputStream stream, SaveOptions options, Cancellation cancellationToken)](#save-java.io.OutputStream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दृश्य को स्ट्रीम में सहेजता है। |
| [save(String fileName)](#save-java.lang.String-) | निर्दिष्ट फ़ाइल फ़ॉर्मेट का उपयोग करके निर्दिष्ट पथ पर सीन को सहेजता है। |
| [save(String fileName, FileFormat format)](#save-java.lang.String-com.aspose.threed.FileFormat-) | निर्दिष्ट फ़ाइल फ़ॉर्मेट का उपयोग करके निर्दिष्ट पथ पर सीन को सहेजता है। |
| [save(String fileName, FileFormat format, Cancellation cancellationToken)](#save-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | निर्दिष्ट फ़ाइल फ़ॉर्मेट का उपयोग करके निर्दिष्ट पथ पर सीन को सहेजता है। |
| [save(String fileName, SaveOptions options)](#save-java.lang.String-com.aspose.threed.SaveOptions-) | निर्दिष्ट फ़ाइल फ़ॉर्मेट का उपयोग करके निर्दिष्ट पथ पर सीन को सहेजता है। |
| [save(String fileName, SaveOptions options, Cancellation cancellationToken)](#save-java.lang.String-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | निर्दिष्ट फ़ाइल फ़ॉर्मेट का उपयोग करके निर्दिष्ट पथ पर सीन को सहेजता है। |
| [setAssetInfo(AssetInfo value)](#setAssetInfo-com.aspose.threed.AssetInfo-) | शीर्ष-स्तर की एसेट जानकारी सेट करता है |
| [setCurrentAnimationClip(AnimationClip value)](#setCurrentAnimationClip-com.aspose.threed.AnimationClip-) | सक्रिय [AnimationClip](../../com.aspose.threed/animationclip) सेट करता है |
| [setName(String value)](#setName-java.lang.String-) | नाम सेट करता है। |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Scene(Entity entity) {#Scene-com.aspose.threed.Entity-}
```
public Scene(Entity entity)
```


[Scene](../../com.aspose.threed/scene) क्लास का नया उदाहरण एक इकाई को नई नोड से संलग्न करके प्रारंभ करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | entity | [Entity](../../com.aspose.threed/entity) | सीन से जुड़ी प्रारंभिक इकाई **Example:** निम्नलिखित कोड दिखाता है कि कैसे एक [getScene](../../com.aspose.threed/scene\#getScene) को सीधे एक [Entity](../../com.aspose.threed/entity) से बनाएं: |

```
var scene = new Scene(new Box());
``` |

### Scene(Scene parentScene, String name) {#Scene-com.aspose.threed.Scene-java.lang.String-}
```
public Scene(Scene parentScene, String name)
```


[Scene](../../com.aspose.threed/scene) क्लास का नया उदाहरण उप-दृश्य के रूप में प्रारंभ करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| parentScene | [Scene](../../com.aspose.threed/scene) | पैरेंट सीन। |
| name | java.lang.String | सीन का नाम। |

### Scene() {#Scene--}
```
public Scene()
```


[Scene](../../com.aspose.threed/scene) क्लास का नया उदाहरण प्रारंभ करता है।

### VERSION {#VERSION}
```
public static final String VERSION
```


वर्तमान रिलीज़ संस्करण प्राप्त करता है

### clear() {#clear--}
```
public void clear()
```


दृश्य की सामग्री साफ़ करता है और डिफ़ॉल्ट सेटिंग्स पुनर्स्थापित करता है।

### createAnimationClip(String name) {#createAnimationClip-java.lang.String-}
```
public AnimationClip createAnimationClip(String name)
```


एक शॉर्टहैंड फ़ंक्शन जो [AnimationClip](../../com.aspose.threed/animationclip) बनाता और पंजीकृत करता है। पहला [AnimationClip](../../com.aspose.threed/animationclip) को [getCurrentAnimationClip](../../com.aspose.threed/scene\#getCurrentAnimationClip) को सौंपा जाएगा।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String | एनिमेशन क्लिप का नाम |

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - A new animation clip instance with given name
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


प्रॉपर्टी को खोजता है। यह एक डायनामिक प्रॉपर्टी (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या नेटिव प्रॉपर्टी (नाम द्वारा पहचानी गई) हो सकती है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| propertyName | java.lang.String | प्रॉपर्टी नाम। |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static Scene fromFile(String fileName)
```


दिए गए पथ से दृश्य खोलता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | फ़ाइल नाम। |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, Cancellation cancellationToken)
```


दिए गए पथ से दृश्य खोलता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | फ़ाइल नाम। |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | लोड टास्क के लिए कैंसलेशन टोकन |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, FileFormat format) {#fromFile-java.lang.String-com.aspose.threed.FileFormat-}
```
public static Scene fromFile(String fileName, FileFormat format)
```


निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दिए गए पथ से दृश्य खोलता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | फ़ाइल नाम। |
| format | [FileFormat](../../com.aspose.threed/fileformat) | फ़ाइल फ़ॉर्मेट। |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, FileFormat format, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, FileFormat format, Cancellation cancellationToken)
```


निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दिए गए पथ से दृश्य खोलता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | फ़ाइल नाम। |
| format | [FileFormat](../../com.aspose.threed/fileformat) | फ़ाइल फ़ॉर्मेट। |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | लोड टास्क के लिए कैंसलेशन टोकन |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, LoadOptions options) {#fromFile-java.lang.String-com.aspose.threed.LoadOptions-}
```
public static Scene fromFile(String fileName, LoadOptions options)
```


निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दिए गए पथ से दृश्य खोलता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | फ़ाइल नाम। |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | स्ट्रीम खोलने के लिए अधिक विस्तृत कॉन्फ़िगरेशन। |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, LoadOptions options, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, LoadOptions options, Cancellation cancellationToken)
```


निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दिए गए पथ से दृश्य खोलता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | फ़ाइल नाम। |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | स्ट्रीम खोलने के लिए अधिक विस्तृत कॉन्फ़िगरेशन। |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | लोड टास्क के लिए कैंसलेशन टोकन |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream) {#fromStream-com.aspose.threed.Stream-}
```
public static Scene fromStream(Stream stream)
```


दिए गए स्ट्रीम से दृश्य खोलता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए जिम्मेदार है। |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, Cancellation cancellationToken)
```


दिए गए स्ट्रीम से दृश्य खोलता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए जिम्मेदार है। |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | लोड टास्क के लिए कैंसलेशन टोकन |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, FileFormat format) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public static Scene fromStream(Stream stream, FileFormat format)
```


निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए जिम्मेदार है। |
| format | [FileFormat](../../com.aspose.threed/fileformat) | फ़ाइल फ़ॉर्मेट। |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, FileFormat format, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, FileFormat format, Cancellation cancellationToken)
```


निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए जिम्मेदार है। |
| format | [FileFormat](../../com.aspose.threed/fileformat) | फ़ाइल फ़ॉर्मेट। |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | लोड टास्क के लिए कैंसलेशन टोकन |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, LoadOptions options) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-}
```
public static Scene fromStream(Stream stream, LoadOptions options)
```


निर्दिष्ट IO कॉन्फ़िग का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए जिम्मेदार है। |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | स्ट्रीम खोलने के लिए अधिक विस्तृत कॉन्फ़िगरेशन। |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken)
```


निर्दिष्ट IO कॉन्फ़िग का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए जिम्मेदार है। |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | स्ट्रीम खोलने के लिए अधिक विस्तृत कॉन्फ़िगरेशन। |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | लोड टास्क के लिए कैंसलेशन टोकन |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static Scene fromStream(InputStream stream)
```


दिए गए स्ट्रीम से दृश्य खोलता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | स्ट्रीम | java.io.InputStream | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए जिम्मेदार है। **Example:** निम्नलिखित कोड दिखाता है कि कैसे एक कैंसलेशन टोकन स्रोत के साथ स्ट्रीम से सीन बनाया जाए |

```
var cts = new Cancellation();    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, Cancellation cancellationToken) {#fromStream-java.io.InputStream-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(InputStream stream, Cancellation cancellationToken)
```


दिए गए स्ट्रीम से दृश्य खोलता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.InputStream | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए जिम्मेदार है। |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | लोड टास्क के लिए कैंसलेशन टोकन **Example:** निम्नलिखित कोड दिखाता है कि कैसे एक कैंसलेशन टोकन स्रोत के साथ स्ट्रीम से सीन बनाया जाए |

```
var cts = new Cancellation();    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input, cts);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, FileFormat format) {#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-}
```
public static Scene fromStream(InputStream stream, FileFormat format)
```


निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.InputStream | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए जिम्मेदार है। |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | फ़ाइल फ़ॉर्मेट। **Example:** निम्नलिखित कोड दिखाता है कि कैसे स्ट्रीम से सीन बनाया जाए |

```
try(InputStream input = new FileInputStream("input.fbx")) {    
          Scene scene = Scene.fromStream(input);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken) {#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken)
```


निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.InputStream | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए जिम्मेदार है। |
| format | [FileFormat](../../com.aspose.threed/fileformat) | फ़ाइल फ़ॉर्मेट। |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | लोड टास्क के लिए कैंसलेशन टोकन **Example:** निम्नलिखित कोड दिखाता है कि कैसे स्ट्रीम से सीन बनाया जाए |

```
try(InputStream input = new FileInputStream("input.fbx")) {    
          Scene scene = Scene.fromStream(input);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, LoadOptions options) {#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-}
```
public static Scene fromStream(InputStream stream, LoadOptions options)
```


निर्दिष्ट IO कॉन्फ़िग का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.InputStream | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए जिम्मेदार है। |
|  | options | [LoadOptions](../../com.aspose.threed/loadoptions) | स्ट्रीम खोलने के लिए अधिक विस्तृत कॉन्फ़िगरेशन। **Example:** निम्नलिखित कोड दिखाता है कि कैसे लोड विकल्पों के साथ स्ट्रीम से सीन बनाया जाए |

```
var opts = new FbxLoadOptions();    
     opts.getLookupPaths().add("textures");    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input, opts);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken) {#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken)
```


निर्दिष्ट IO कॉन्फ़िग का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.InputStream | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए जिम्मेदार है। |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | स्ट्रीम खोलने के लिए अधिक विस्तृत कॉन्फ़िगरेशन। |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | लोड टास्क के लिए कैंसलेशन टोकन **Example:** निम्नलिखित कोड दिखाता है कि कैसे लोड विकल्पों के साथ स्ट्रीम से सीन बनाया जाए |

```
var opts = new FbxLoadOptions();    
     opts.getLookupPaths().add("textures");    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input, opts);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### getAnimationClip(String name) {#getAnimationClip-java.lang.String-}
```
public AnimationClip getAnimationClip(String name)
```


नामित [AnimationClip](../../com.aspose.threed/animationclip) प्राप्त करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String | देखने के लिए [AnimationClip](../../com.aspose.threed/animationclip) का नाम |

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - Returned AnimationClip
### getAnimationClips() {#getAnimationClips--}
```
public List<AnimationClip> getAnimationClips()
```


दृश्य में परिभाषित सभी [AnimationClip](../../com.aspose.threed/animationclip) प्राप्त करता है।

**Returns:**
java.util.List<com.aspose.threed.AnimationClip> - सीन में परिभाषित सभी [AnimationClip](../../com.aspose.threed/animationclip)।
### getAssetInfo() {#getAssetInfo--}
```
public AssetInfo getAssetInfo()
```


शीर्ष-स्तर की एसेट जानकारी प्राप्त करता है

**Returns:**
[AssetInfo](../../com.aspose.threed/assetinfo) - the top-level asset information **Example:** The following code shows how to read the application information from a FBX file:

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The FBX file is created by %s %s",
         scene.getAssetInfo().getApplicationName(),
         scene.getAssetInfo().getApplicationVersion());
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCurrentAnimationClip() {#getCurrentAnimationClip--}
```
public AnimationClip getCurrentAnimationClip()
```


सक्रिय [AnimationClip](../../com.aspose.threed/animationclip) प्राप्त करता है

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - the active [AnimationClip](../../com.aspose.threed/animationclip)
### getLibrary() {#getLibrary--}
```
public List<A3DObject> getLibrary()
```


सीन पदानुक्रम में सीधे उपयोग नहीं किए गए ऑब्जेक्ट्स को लाइब्रेरी में परिभाषित किया जा सकता है। यह तब उपयोगी होता है जब आप सब-सीन्स का उपयोग कर रहे हों और पुन: उपयोग योग्य घटकों को सब-सीन्स के तहत रखें।

**Returns:**
java.util.List<com.aspose.threed.A3DObject> - सीन पदानुक्रम में सीधे उपयोग नहीं किए गए ऑब्जेक्ट्स को लाइब्रेरी में परिभाषित किया जा सकता है। यह तब उपयोगी होता है जब आप सब-सीन्स का उपयोग कर रहे हों और पुन: उपयोग योग्य घटकों को सब-सीन्स के तहत रखें।
### getName() {#getName--}
```
public String getName()
```


नाम प्राप्त करता है।

**Returns:**
java.lang.String - नाम।
### getPoses() {#getPoses--}
```
public Collection<Pose> getPoses()
```


इस दृश्य में उपयोग किए गए सभी [Pose](../../com.aspose.threed/pose) प्राप्त करता है।

**Returns:**
java.util.Collection<com.aspose.threed.Pose> - इस सीन में उपयोग किए गए सभी [Pose](../../com.aspose.threed/pose)।
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है।

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | प्रॉपर्टी नाम |

**Returns:**
java.lang.Object - मिली हुई प्रॉपर्टी का मान
### getRootNode() {#getRootNode--}
```
public Node getRootNode()
```


दृश्य का रूट नोड प्राप्त करता है।

**Returns:**
[Node](../../com.aspose.threed/node) - the root node of the scene. **Example:** The following code shows how to create a node with Box entity attached to the root node.

```
Scene scene = new Scene();
     scene.getRootNode().createChildNode(new Box());
     scene.save("box.stl");
```
### getScene() {#getScene--}
```
public Scene getScene()
```


उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getSubScenes() {#getSubScenes--}
```
public List<Scene> getSubScenes()
```


सभी उप-दृश्य प्राप्त करता है

**Returns:**
java.util.List<com.aspose.threed.Scene> - सभी सब-सीन्स
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### open(Stream stream) {#open-com.aspose.threed.Stream-}
```
public void open(Stream stream)
```


दिए गए स्ट्रीम से दृश्य खोलता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए जिम्मेदार है। |

### open(Stream stream, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, Cancellation cancellationToken)
```


दिए गए स्ट्रीम से दृश्य खोलता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए जिम्मेदार है। |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | लोड टास्क के लिए कैंसलेशन टोकन |

### open(Stream stream, FileFormat format) {#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public void open(Stream stream, FileFormat format)
```


निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए जिम्मेदार है। |
| format | [FileFormat](../../com.aspose.threed/fileformat) | फ़ाइल फ़ॉर्मेट। |

### open(Stream stream, FileFormat format, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, FileFormat format, Cancellation cancellationToken)
```


निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए जिम्मेदार है। |
| format | [FileFormat](../../com.aspose.threed/fileformat) | फ़ाइल फ़ॉर्मेट। |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | लोड टास्क के लिए कैंसलेशन टोकन |

### open(Stream stream, LoadOptions options) {#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-}
```
public void open(Stream stream, LoadOptions options)
```


निर्दिष्ट IO कॉन्फ़िग का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए जिम्मेदार है। |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | स्ट्रीम खोलने के लिए अधिक विस्तृत कॉन्फ़िगरेशन। |

### open(Stream stream, LoadOptions options, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, LoadOptions options, Cancellation cancellationToken)
```


निर्दिष्ट IO कॉन्फ़िग का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए जिम्मेदार है। |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | स्ट्रीम खोलने के लिए अधिक विस्तृत कॉन्फ़िगरेशन। |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | लोड टास्क के लिए कैंसलेशन टोकन |

### open(InputStream stream) {#open-java.io.InputStream-}
```
public void open(InputStream stream)
```


दिए गए स्ट्रीम से दृश्य खोलता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | स्ट्रीम | java.io.InputStream | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए जिम्मेदार है। **Example:** निम्नलिखित कोड दिखाता है कि कैसे स्ट्रीम से सीन खोला जाए |

```
var scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs);    
     }
``` |

### open(InputStream stream, Cancellation cancellationToken) {#open-java.io.InputStream-com.aspose.threed.Cancellation-}
```
public void open(InputStream stream, Cancellation cancellationToken)
```


दिए गए स्ट्रीम से दृश्य खोलता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.InputStream | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए जिम्मेदार है। |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | लोड कार्य के लिए कैंसलेशन टोकन **Example:** निम्न कोड दिखाता है कि कैसे स्ट्रीम से एक सीन को कैंसलेशन टोकन के साथ खोलें |

```
var scene = new Scene();    
     Cancellation cts = new Cancellation();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs, cts);    
     }
``` |

### open(InputStream stream, FileFormat format) {#open-java.io.InputStream-com.aspose.threed.FileFormat-}
```
public void open(InputStream stream, FileFormat format)
```


निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.InputStream | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए जिम्मेदार है। |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | फ़ाइल फ़ॉर्मेट। **Example:** निम्न कोड दिखाता है कि कैसे स्ट्रीम से एक सीन खोलें |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs, FileFormat.GLTF2);    
     }
``` |

### open(InputStream stream, FileFormat format, Cancellation cancellationToken) {#open-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(InputStream stream, FileFormat format, Cancellation cancellationToken)
```


निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.InputStream | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए जिम्मेदार है। |
| format | [FileFormat](../../com.aspose.threed/fileformat) | फ़ाइल फ़ॉर्मेट। |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | लोड कार्य के लिए कैंसलेशन टोकन **Example:** निम्न कोड दिखाता है कि कैसे स्ट्रीम से एक सीन खोलें |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs, FileFormat.GLTF2);    
     }
``` |

### open(InputStream stream, LoadOptions options) {#open-java.io.InputStream-com.aspose.threed.LoadOptions-}
```
public void open(InputStream stream, LoadOptions options)
```


निर्दिष्ट IO कॉन्फ़िग का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.InputStream | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए जिम्मेदार है। |
|  | options | [LoadOptions](../../com.aspose.threed/loadoptions) | स्ट्रीम खोलने के लिए अधिक विस्तृत कॉन्फ़िगरेशन। **Example:** निम्न कोड दिखाता है कि कैसे अतिरिक्त लोड विकल्पों के साथ स्ट्रीम से एक सीन खोलें |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         var opt = new FbxLoadOptions();    
         opt.getLookupPaths().add("textures");    
         scene.open(fs, opt);    
     }
``` |

### open(InputStream stream, LoadOptions options, Cancellation cancellationToken) {#open-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(InputStream stream, LoadOptions options, Cancellation cancellationToken)
```


निर्दिष्ट IO कॉन्फ़िग का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.InputStream | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए जिम्मेदार है। |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | स्ट्रीम खोलने के लिए अधिक विस्तृत कॉन्फ़िगरेशन। |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | लोड कार्य के लिए कैंसलेशन टोकन **Example:** निम्न कोड दिखाता है कि कैसे अतिरिक्त लोड विकल्पों के साथ स्ट्रीम से एक सीन खोलें |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         var opt = new FbxLoadOptions();    
         opt.getLookupPaths().add("textures");    
         scene.open(fs, opt);    
     }
``` |

### open(String fileName) {#open-java.lang.String-}
```
public void open(String fileName)
```


दिए गए पथ से दृश्य खोलता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | फ़ाइल नाम। |

### open(String fileName, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.Cancellation-}
```
public void open(String fileName, Cancellation cancellationToken)
```


दिए गए पथ से दृश्य खोलता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | फ़ाइल नाम। |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | लोड टास्क के लिए कैंसलेशन टोकन |

### open(String fileName, FileFormat format) {#open-java.lang.String-com.aspose.threed.FileFormat-}
```
public void open(String fileName, FileFormat format)
```


निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दिए गए पथ से दृश्य खोलता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | फ़ाइल नाम। |
| format | [FileFormat](../../com.aspose.threed/fileformat) | फ़ाइल फ़ॉर्मेट। |

### open(String fileName, FileFormat format, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(String fileName, FileFormat format, Cancellation cancellationToken)
```


निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दिए गए पथ से दृश्य खोलता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | फ़ाइल नाम। |
| format | [FileFormat](../../com.aspose.threed/fileformat) | फ़ाइल फ़ॉर्मेट। |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | लोड टास्क के लिए कैंसलेशन टोकन |

### open(String fileName, LoadOptions options) {#open-java.lang.String-com.aspose.threed.LoadOptions-}
```
public void open(String fileName, LoadOptions options)
```


निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दिए गए पथ से दृश्य खोलता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | फ़ाइल नाम। |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | स्ट्रीम खोलने के लिए अधिक विस्तृत कॉन्फ़िगरेशन। |

### open(String fileName, LoadOptions options, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(String fileName, LoadOptions options, Cancellation cancellationToken)
```


निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दिए गए पथ से दृश्य खोलता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | फ़ाइल नाम। |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | स्ट्रीम खोलने के लिए अधिक विस्तृत कॉन्फ़िगरेशन। |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | लोड टास्क के लिए कैंसलेशन टोकन |

### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


डायनामिक प्रॉपर्टी को हटाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | कौन सी प्रॉपर्टी हटानी है |

**Returns:**
boolean - यदि प्रॉपर्टी सफलतापूर्वक हटाई गई हो तो true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | कौन सी प्रॉपर्टी हटानी है |

**Returns:**
boolean - यदि प्रॉपर्टी सफलतापूर्वक हटाई गई हो तो true
### render(Camera camera, TextureData bitmap) {#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-}
```
public void render(Camera camera, TextureData bitmap)
```


दिए गए कैमरे के दृष्टिकोण से दृश्य को बिटमैप में रेंडर करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | किस कैमरे के दृष्टिकोण से सीन को रेंडर किया जाए |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | रेंडर किए गए परिणाम का लक्ष्य |

### render(Camera camera, TextureData bitmap, ImageRenderOptions options) {#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-com.aspose.threed.ImageRenderOptions-}
```
public void render(Camera camera, TextureData bitmap, ImageRenderOptions options)
```


दिए गए कैमरे के दृष्टिकोण से दृश्य को बिटमैप में रेंडर करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | किस कैमरे के दृष्टिकोण से सीन को रेंडर किया जाए |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | रेंडर किए गए परिणाम का लक्ष्य |
| options | [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions) | कुछ आंतरिक सेटिंग्स को अनुकूलित करने का विकल्प। |

### render(Camera camera, String fileName) {#render-com.aspose.threed.Camera-java.lang.String-}
```
public void render(Camera camera, String fileName)
```


दिए गए कैमरे के दृष्टिकोण से सीन को बाहरी फ़ाइल में रेंडर करें। डिफ़ॉल्ट आउटपुट आकार 1024x768 है और आउटपुट फ़ॉर्मेट png है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | किस कैमरे के दृष्टिकोण से सीन को रेंडर किया जाए |
| fileName | java.lang.String | आउटपुट फ़ाइल का फ़ाइल नाम |

### render(Camera camera, String fileName, Vector2 size, String format) {#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-}
```
public void render(Camera camera, String fileName, Vector2 size, String format)
```


दिए गए कैमरे के दृष्टिकोण से दृश्य को बाहरी फ़ाइल में रेंडर करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | किस कैमरे के दृष्टिकोण से सीन को रेंडर किया जाए |
| fileName | java.lang.String | आउटपुट फ़ाइल का फ़ाइल नाम |
| size | [Vector2](../../com.aspose.threed/vector2) | अंतिम रेंडर की गई छवि का आकार |
| format | java.lang.String | आउटपुट फ़ाइल का इमेज फ़ॉर्मेट |

### render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options) {#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-com.aspose.threed.ImageRenderOptions-}
```
public void render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options)
```


दिए गए कैमरे के दृष्टिकोण से दृश्य को बाहरी फ़ाइल में रेंडर करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | किस कैमरे के दृष्टिकोण से सीन को रेंडर किया जाए |
| fileName | java.lang.String | आउटपुट फ़ाइल का फ़ाइल नाम |
| size | [Vector2](../../com.aspose.threed/vector2) | अंतिम रेंडर की गई छवि का आकार |
| format | java.lang.String | आउटपुट फ़ाइल का इमेज फ़ॉर्मेट |
| options | [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions) | कुछ आंतरिक सेटिंग्स को अनुकूलित करने का विकल्प। |

### save(Stream stream, FileFormat format) {#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public void save(Stream stream, FileFormat format)
```


निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दृश्य को स्ट्रीम में सहेजता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए जिम्मेदार है। |
| format | [FileFormat](../../com.aspose.threed/fileformat) | फ़ॉर्मेट। |

### save(Stream stream, FileFormat format, Cancellation cancellationToken) {#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(Stream stream, FileFormat format, Cancellation cancellationToken)
```


निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दृश्य को स्ट्रीम में सहेजता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए जिम्मेदार है। |
| format | [FileFormat](../../com.aspose.threed/fileformat) | फ़ॉर्मेट। |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | सेव कार्य के लिए कैंसलेशन टोकन |

### save(Stream stream, SaveOptions options) {#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-}
```
public void save(Stream stream, SaveOptions options)
```


निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दृश्य को स्ट्रीम में सहेजता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए जिम्मेदार है। |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | स्ट्रीम को सेव करने के लिए अधिक विस्तृत कॉन्फ़िगरेशन। |

### save(Stream stream, SaveOptions options, Cancellation cancellationToken) {#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(Stream stream, SaveOptions options, Cancellation cancellationToken)
```


निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दृश्य को स्ट्रीम में सहेजता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए जिम्मेदार है। |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | स्ट्रीम को सेव करने के लिए अधिक विस्तृत कॉन्फ़िगरेशन। |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | सेव कार्य के लिए कैंसलेशन टोकन |

### save(OutputStream stream, FileFormat format) {#save-java.io.OutputStream-com.aspose.threed.FileFormat-}
```
public void save(OutputStream stream, FileFormat format)
```


निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दृश्य को स्ट्रीम में सहेजता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.OutputStream | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए जिम्मेदार है। |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | फ़ॉर्मेट। **Example:** निम्न कोड दिखाता है कि कैसे सीन को सेव करें |

```
Scene scene = Scene.fromFile("input.fbx");    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, FileFormat.USDZ);    
     }
``` |

### save(OutputStream stream, FileFormat format, Cancellation cancellationToken) {#save-java.io.OutputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(OutputStream stream, FileFormat format, Cancellation cancellationToken)
```


निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दृश्य को स्ट्रीम में सहेजता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.OutputStream | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए जिम्मेदार है। |
| format | [FileFormat](../../com.aspose.threed/fileformat) | फ़ॉर्मेट। |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | सेव कार्य के लिए कैंसलेशन टोकन **Example:** निम्न कोड दिखाता है कि कैसे सीन को सेव करें |

```
Scene scene = Scene.fromFile("input.fbx");    
     var cts = new Cancellation();    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, FileFormat.USDZ, cts);    
     }
``` |

### save(OutputStream stream, SaveOptions options) {#save-java.io.OutputStream-com.aspose.threed.SaveOptions-}
```
public void save(OutputStream stream, SaveOptions options)
```


निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दृश्य को स्ट्रीम में सहेजता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.OutputStream | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए जिम्मेदार है। |
|  | options | [SaveOptions](../../com.aspose.threed/saveoptions) | स्ट्रीम को सेव करने के लिए अधिक विस्तृत कॉन्फ़िगरेशन। **Example:** निम्न कोड दिखाता है कि कैसे सीन को सेव करें |

```
Scene scene = Scene.fromFile("input.fbx");    
     var opt = new UsdSaveOptions();    
     opt.setPrimitiveToMesh(true);    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, opt);    
     }
``` |

### save(OutputStream stream, SaveOptions options, Cancellation cancellationToken) {#save-java.io.OutputStream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(OutputStream stream, SaveOptions options, Cancellation cancellationToken)
```


निर्दिष्ट फ़ाइल प्रारूप का उपयोग करके दृश्य को स्ट्रीम में सहेजता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| स्ट्रीम | java.io.OutputStream | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए जिम्मेदार है। |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | स्ट्रीम को सेव करने के लिए अधिक विस्तृत कॉन्फ़िगरेशन। |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | सेव कार्य के लिए कैंसलेशन टोकन **Example:** निम्न कोड दिखाता है कि कैसे सीन को सेव करें |

```
Scene scene = Scene.fromFile("input.fbx");    
     var cts = new Cancellation();    
     var opt = new UsdSaveOptions();    
     opt.setPrimitiveToMesh(true);    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, opt, cts);    
     }
``` |

### save(String fileName) {#save-java.lang.String-}
```
public void save(String fileName)
```


निर्दिष्ट फ़ाइल फ़ॉर्मेट का उपयोग करके निर्दिष्ट पथ पर सीन को सहेजता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | फ़ाइल नाम। |

### save(String fileName, FileFormat format) {#save-java.lang.String-com.aspose.threed.FileFormat-}
```
public void save(String fileName, FileFormat format)
```


निर्दिष्ट फ़ाइल फ़ॉर्मेट का उपयोग करके निर्दिष्ट पथ पर सीन को सहेजता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | फ़ाइल नाम। |
| format | [FileFormat](../../com.aspose.threed/fileformat) | फ़ॉर्मेट। |

### save(String fileName, FileFormat format, Cancellation cancellationToken) {#save-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(String fileName, FileFormat format, Cancellation cancellationToken)
```


निर्दिष्ट फ़ाइल फ़ॉर्मेट का उपयोग करके निर्दिष्ट पथ पर सीन को सहेजता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | फ़ाइल नाम। |
| format | [FileFormat](../../com.aspose.threed/fileformat) | फ़ॉर्मेट। |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | सेव कार्य के लिए कैंसलेशन टोकन |

### save(String fileName, SaveOptions options) {#save-java.lang.String-com.aspose.threed.SaveOptions-}
```
public void save(String fileName, SaveOptions options)
```


निर्दिष्ट फ़ाइल फ़ॉर्मेट का उपयोग करके निर्दिष्ट पथ पर सीन को सहेजता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | फ़ाइल नाम। |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | स्ट्रीम को सेव करने के लिए अधिक विस्तृत कॉन्फ़िगरेशन। |

### save(String fileName, SaveOptions options, Cancellation cancellationToken) {#save-java.lang.String-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(String fileName, SaveOptions options, Cancellation cancellationToken)
```


निर्दिष्ट फ़ाइल फ़ॉर्मेट का उपयोग करके निर्दिष्ट पथ पर सीन को सहेजता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| fileName | java.lang.String | फ़ाइल नाम। |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | स्ट्रीम को सेव करने के लिए अधिक विस्तृत कॉन्फ़िगरेशन। |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | सेव कार्य के लिए कैंसलेशन टोकन |

### setAssetInfo(AssetInfo value) {#setAssetInfo-com.aspose.threed.AssetInfo-}
```
public void setAssetInfo(AssetInfo value)
```


शीर्ष-स्तर की एसेट जानकारी सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
|  | value | [AssetInfo](../../com.aspose.threed/assetinfo) | नया मान **Example:** निम्न कोड दिखाता है कि कैसे FBX फ़ाइल से एप्लिकेशन जानकारी पढ़ें: |

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The FBX file is created by %s %s",
         scene.getAssetInfo().getApplicationName(),
         scene.getAssetInfo().getApplicationVersion());
``` |

### setCurrentAnimationClip(AnimationClip value) {#setCurrentAnimationClip-com.aspose.threed.AnimationClip-}
```
public void setCurrentAnimationClip(AnimationClip value)
```


सक्रिय [AnimationClip](../../com.aspose.threed/animationclip) सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [AnimationClip](../../com.aspose.threed/animationclip) | नया मान |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


नाम सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


निर्दिष्ट प्रॉपर्टी का मान सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | प्रॉपर्टी नाम |
| मान | java.lang.Object | प्रॉपर्टी का मान |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

