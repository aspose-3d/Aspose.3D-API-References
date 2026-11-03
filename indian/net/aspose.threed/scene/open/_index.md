---
title: "Scene.Open"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Scene मेथड। निर्दिष्ट फ़ाइल फ़ॉर्मेट का उपयोग करके दिए गए स्ट्रीम से सीन खोलता है।"
type: docs
weight: 140
url: /hi/net/aspose.threed/scene/open/
---
## Open(Stream, FileFormat, CancellationToken) {#open_1}

निर्दिष्ट फ़ाइल स्वरूप का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है।

```csharp
public void Open(Stream stream, FileFormat format, CancellationToken cancellationToken = default)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | Stream | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए ज़िम्मेदार है। |
| फ़ॉर्मेट | FileFormat | फ़ाइल फ़ॉर्मेट। |
| cancellationToken | CancellationToken | लोड टास्क के लिए कैंसलेशन टोकन |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| IOException | इनपुट पढ़ने में विफल होने पर थ्रो किया जाता है |
| [ImportException](../../importexception/) | जब इनपुट वैध 3D फ़ॉर्मेट नहीं होता है तो थ्रो किया जाता है |

## उदाहरण

निम्नलिखित कोड दिखाता है कि स्ट्रीम से सीन कैसे खोलें

```csharp
Scene scene = new Scene();
using (var stream = new FileStream("input.fbx", FileMode.Open))
{
    scene.Open(stream, FileFormat.GLTF2);
}
```

### देखें भी

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(Stream, LoadOptions, CancellationToken) {#open_2}

निर्दिष्ट IO कॉन्फ़िग का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है।

```csharp
public void Open(Stream stream, LoadOptions options, CancellationToken cancellationToken = default)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | Stream | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए ज़िम्मेदार है। |
| options | LoadOptions | स्ट्रीम खोलने के लिए अधिक विस्तृत कॉन्फ़िगरेशन। |
| cancellationToken | CancellationToken | लोड टास्क के लिए कैंसलेशन टोकन |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| IOException | इनपुट पढ़ने में विफल होने पर थ्रो किया जाता है |
| [ImportException](../../importexception/) | जब इनपुट वैध 3D फ़ॉर्मेट नहीं होता है तो थ्रो किया जाता है |

## उदाहरण

निम्नलिखित कोड दिखाता है कि अतिरिक्त लोड विकल्पों के साथ स्ट्रीम से सीन कैसे खोलें

```csharp
Scene scene = new Scene();
using (var stream = new FileStream("input.fbx", FileMode.Open))
{
    var opt = new FbxLoadOptions();
    opt.LookupPaths.Add("textures");
    scene.Open(stream, opt);
}
```

### देखें भी

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(Stream) {#open}

दिए गए स्ट्रीम से दृश्य खोलता है

```csharp
public void Open(Stream stream)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | Stream | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए ज़िम्मेदार है। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| IOException | इनपुट पढ़ने में विफल होने पर थ्रो किया जाता है |
| [ImportException](../../importexception/) | जब इनपुट वैध 3D फ़ॉर्मेट नहीं होता है तो थ्रो किया जाता है |

## उदाहरण

निम्नलिखित कोड दिखाता है कि स्ट्रीम से सीन कैसे खोलें

```csharp
Scene scene = new Scene();
using (var stream = new FileStream("input.fbx", FileMode.Open))
{
    scene.Open(stream);
}
```

### देखें भी

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(Stream, CancellationToken) {#open_3}

दिए गए स्ट्रीम से दृश्य खोलता है

```csharp
public void Open(Stream stream, CancellationToken cancellationToken)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | Stream | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए ज़िम्मेदार है। |
| cancellationToken | CancellationToken | लोड टास्क के लिए कैंसलेशन टोकन |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| IOException | इनपुट पढ़ने में विफल होने पर थ्रो किया जाता है |
| [ImportException](../../importexception/) | जब इनपुट वैध 3D फ़ॉर्मेट नहीं होता है तो थ्रो किया जाता है |

## उदाहरण

निम्नलिखित कोड दिखाता है कि कैंसलेशन टोकन के साथ स्ट्रीम से सीन कैसे खोलें

```csharp
Scene scene = new Scene();
CancellationTokenSource cts = new CancellationTokenSource();
using (var stream = new FileStream("input.fbx", FileMode.Open))
{
    scene.Open(stream, cts.Token);
}
```

### देखें भी

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string, FileFormat, CancellationToken) {#open_5}

निर्दिष्ट फ़ाइल स्वरूप का उपयोग करके दिए गए पथ से दृश्य खोलता है।

```csharp
public void Open(string fileName, FileFormat format, CancellationToken cancellationToken = default)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fileName | String | फ़ाइल नाम। |
| फ़ॉर्मेट | FileFormat | फ़ाइल फ़ॉर्मेट। |
| cancellationToken | CancellationToken | लोड टास्क के लिए कैंसलेशन टोकन |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| IOException | इनपुट पढ़ने में विफल होने पर थ्रो किया जाता है |
| [ImportException](../../importexception/) | जब इनपुट वैध 3D फ़ॉर्मेट नहीं होता है तो थ्रो किया जाता है |

## उदाहरण

निम्नलिखित कोड दिखाता है कि कैंसलेशन टोकन के साथ फ़ाइल नाम से सीन कैसे खोलें

```csharp
Scene scene = new Scene();
CancellationTokenSource cts = new CancellationTokenSource();
scene.Open("input.fbx", FileFormat.FBX7400ASCII, cts.Token);

```

### देखें भी

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string, LoadOptions) {#open_6}

निर्दिष्ट फ़ाइल स्वरूप का उपयोग करके दिए गए पथ से दृश्य खोलता है।

```csharp
public void Open(string fileName, LoadOptions options)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fileName | String | फ़ाइल नाम। |
| options | LoadOptions | स्ट्रीम खोलने के लिए अधिक विस्तृत कॉन्फ़िगरेशन। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| IOException | इनपुट पढ़ने में विफल होने पर थ्रो किया जाता है |
| [ImportException](../../importexception/) | जब इनपुट वैध 3D फ़ॉर्मेट नहीं होता है तो थ्रो किया जाता है |

## उदाहरण

निम्नलिखित कोड दिखाता है कि अतिरिक्त लोड विकल्पों के साथ फ़ाइल नाम से सीन कैसे खोलें

```csharp
Scene scene = new Scene();
var opts = new FbxLoadOptions();
opts.LookupPaths.Add("textures");
scene.Open("input.fbx", opts);
```

### देखें भी

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string, LoadOptions, CancellationToken) {#open_7}

निर्दिष्ट फ़ाइल स्वरूप का उपयोग करके दिए गए पथ से दृश्य खोलता है।

```csharp
public void Open(string fileName, LoadOptions options, CancellationToken cancellationToken)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fileName | String | फ़ाइल नाम। |
| options | LoadOptions | स्ट्रीम खोलने के लिए अधिक विस्तृत कॉन्फ़िगरेशन। |
| cancellationToken | CancellationToken | लोड टास्क के लिए कैंसलेशन टोकन |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| IOException | इनपुट पढ़ने में विफल होने पर थ्रो किया जाता है |
| [ImportException](../../importexception/) | जब इनपुट वैध 3D फ़ॉर्मेट नहीं होता है तो थ्रो किया जाता है |

## उदाहरण

निम्नलिखित कोड दिखाता है कि अतिरिक्त लोड विकल्पों और कैंसलेशन टोकन के साथ फ़ाइल नाम से सीन कैसे खोलें

```csharp
var cts = new CancellationTokenSource();
Scene scene = new Scene();
var opts = new FbxLoadOptions();
opts.LookupPaths.Add("textures");
scene.Open("input.fbx", opts, cts.Token);
```

### देखें भी

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string) {#open_4}

दिए गए पथ से दृश्य खोलता है

```csharp
public void Open(string fileName)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fileName | String | फ़ाइल नाम। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| IOException | इनपुट पढ़ने में विफल होने पर थ्रो किया जाता है |
| [ImportException](../../importexception/) | जब इनपुट वैध 3D फ़ॉर्मेट नहीं होता है तो थ्रो किया जाता है |

## उदाहरण

निम्नलिखित कोड दिखाता है कि फ़ाइल नाम से सीन कैसे खोलें

```csharp
Scene scene = new Scene();
scene.Open("input.fbx");
```

### देखें भी

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string, CancellationToken) {#open_8}

दिए गए पथ से दृश्य खोलता है

```csharp
public void Open(string fileName, CancellationToken cancellationToken)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fileName | String | फ़ाइल नाम। |
| cancellationToken | CancellationToken | लोड टास्क के लिए कैंसलेशन टोकन |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| IOException | इनपुट पढ़ने में विफल होने पर थ्रो किया जाता है |
| [ImportException](../../importexception/) | जब इनपुट वैध 3D फ़ॉर्मेट नहीं होता है तो थ्रो किया जाता है |

## उदाहरण

निम्नलिखित कोड दिखाता है कि फ़ाइल नाम और कैंसलेशन टोकन स्रोत के साथ सीन कैसे खोलें

```csharp
var cts = new CancellationTokenSource();
Scene scene = new Scene();
scene.Open("input.fbx", cts.Token);
```

### देखें भी

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


