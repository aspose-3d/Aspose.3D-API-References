---
title: "Scene.FromStream"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Scene मेथड। निर्दिष्ट फ़ाइल फ़ॉर्मेट का उपयोग करके दिए गए स्ट्रीम से सीन खोलता है।"
type: docs
weight: 30
url: /hi/net/aspose.threed/scene/fromstream/
---
## FromStream(Stream, FileFormat, CancellationToken) {#fromstream}

निर्दिष्ट फ़ाइल स्वरूप का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है।

```csharp
public static Scene FromStream(Stream stream, FileFormat format, 
    CancellationToken cancellationToken = default)
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

निम्नलिखित कोड दिखाता है कि कैसे एक स्ट्रीम से सीन बनाया जाए।

```csharp
using(var stream = new FileStream("input.fbx", FileMode.Open))
{
    Scene scene = Scene.FromStream(stream);
}
```

### देखें भी

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromStream(Stream, LoadOptions, CancellationToken) {#fromstream_1}

निर्दिष्ट IO कॉन्फ़िग का उपयोग करके दिए गए स्ट्रीम से दृश्य खोलता है।

```csharp
public static Scene FromStream(Stream stream, LoadOptions options, 
    CancellationToken cancellationToken = default)
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

निम्नलिखित कोड दिखाता है कि कैसे लोड विकल्पों के साथ स्ट्रीम से सीन बनाया जाए।

```csharp
var opts = new FbxLoadOptions();
opts.LookupPaths.Add("textures");
using(var stream = new FileStream("input.fbx", FileMode.Open))
{
    Scene scene = Scene.FromStream(stream, opts);
}
```

### देखें भी

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromStream(Stream, CancellationToken) {#fromstream_2}

दिए गए स्ट्रीम से दृश्य खोलता है

```csharp
public static Scene FromStream(Stream stream, CancellationToken cancellationToken = default)
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

निम्नलिखित कोड दिखाता है कि कैसे कैंसलेशन टोकन स्रोत के साथ स्ट्रीम से सीन बनाया जाए।

```csharp
var cts = new CancellationTokenSource();
using(var stream = new FileStream("input.fbx", FileMode.Open))
{
    Scene scene = Scene.FromStream(stream, cts.Token);
}
```

### देखें भी

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


