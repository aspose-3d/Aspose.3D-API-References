---
title: "Scene.FromFile"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Scene मेथड। निर्दिष्ट फ़ाइल फ़ॉर्मेट का उपयोग करके दिए गए पथ से सीन खोलता है।"
type: docs
weight: 20
url: /hi/net/aspose.threed/scene/fromfile/
---
## FromFile(string, FileFormat, CancellationToken) {#fromfile_1}

निर्दिष्ट फ़ाइल स्वरूप का उपयोग करके दिए गए पथ से दृश्य खोलता है।

```csharp
public static Scene FromFile(string fileName, FileFormat format, 
    CancellationToken cancellationToken = default)
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

निम्नलिखित कोड दिखाता है कि कैसे फ़ाइल से सीन बनाया जाए।

```csharp
var cts = new CancellationTokenSource();
Scene scene = Scene.FromFile("input.fbx", FileFormat.FBX7400ASCII, cts.Token);
```

### देखें भी

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromFile(string, LoadOptions, CancellationToken) {#fromfile_2}

निर्दिष्ट फ़ाइल स्वरूप का उपयोग करके दिए गए पथ से दृश्य खोलता है।

```csharp
public static Scene FromFile(string fileName, LoadOptions options, 
    CancellationToken cancellationToken = default)
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

निम्नलिखित कोड दिखाता है कि कैसे फ़ाइल से सीन बनाया जाए।

```csharp
var cts = new CancellationTokenSource();
var opt = new FbxLoadOptions();
opt.LookupPaths.Add("textures");
Scene scene = Scene.FromFile("input.fbx", opt, cts.Token);
```

### देखें भी

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromFile(string) {#fromfile}

दिए गए पथ से दृश्य खोलता है

```csharp
public static Scene FromFile(string fileName)
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

निम्नलिखित कोड दिखाता है कि कैसे फ़ाइल से सीन बनाया जाए।

```csharp
Scene scene = Scene.FromFile("input.fbx");
```

### देखें भी

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromFile(string, CancellationToken) {#fromfile_3}

दिए गए पथ से दृश्य खोलता है

```csharp
public static Scene FromFile(string fileName, CancellationToken cancellationToken)
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

निम्नलिखित कोड दिखाता है कि कैसे फ़ाइल से सीन बनाया जाए।

```csharp
var cts = new CancellationTokenSource();
Scene scene = Scene.FromFile("input.fbx", cts.Token);
```

### देखें भी

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


