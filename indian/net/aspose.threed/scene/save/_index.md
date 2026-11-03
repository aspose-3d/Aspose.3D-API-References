---
title: "Scene.Save"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Scene मेथड। निर्दिष्ट फ़ाइल फ़ॉर्मेट का उपयोग करके सीन को स्ट्रीम में सहेजता है"
type: docs
weight: 160
url: /hi/net/aspose.threed/scene/save/
---
## Save(Stream, FileFormat) {#save}

निर्दिष्ट फ़ाइल स्वरूप का उपयोग करके दृश्य को स्ट्रीम में सहेजता है।

```csharp
public void Save(Stream stream, FileFormat format)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | Stream | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए ज़िम्मेदार है। |
| फ़ॉर्मेट | FileFormat | फ़ॉर्मेट। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| IOException | इनपुट पढ़ने में विफल होने पर थ्रो किया जाता है |
| [ExportException](../../exportexception/) | जब सीन को निर्दिष्ट 3D फ़ॉर्मेट में एक्सपोर्ट करने में विफलता हो तो थ्रो किया जाता है |

## उदाहरण

निम्नलिखित कोड दिखाता है कि सीन को कैसे सहेजा जाए

```csharp
Scene scene = Scene.FromFile("input.fbx");
using(var ms = new MemoryStream())
{
    scene.Save(ms, FileFormat.USDZ);
}
```

### देखें भी

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(Stream, FileFormat, CancellationToken) {#save_1}

निर्दिष्ट फ़ाइल स्वरूप का उपयोग करके दृश्य को स्ट्रीम में सहेजता है।

```csharp
public void Save(Stream stream, FileFormat format, CancellationToken cancellationToken)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | Stream | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए ज़िम्मेदार है। |
| फ़ॉर्मेट | FileFormat | फ़ॉर्मेट। |
| cancellationToken | CancellationToken | सेव टास्क के लिए कैंसलेशन टोकन |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| IOException | इनपुट पढ़ने में विफल होने पर थ्रो किया जाता है |
| [ExportException](../../exportexception/) | जब सीन को निर्दिष्ट 3D फ़ॉर्मेट में एक्सपोर्ट करने में विफलता हो तो थ्रो किया जाता है |

## उदाहरण

निम्नलिखित कोड दिखाता है कि सीन को कैसे सहेजा जाए

```csharp
Scene scene = Scene.FromFile("input.fbx");
var cts = new CancellationTokenSource();
using(var ms = new MemoryStream())
{
    scene.Save(ms, FileFormat.USDZ, cts.Token);
}
```

### देखें भी

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(Stream, SaveOptions) {#save_2}

निर्दिष्ट फ़ाइल स्वरूप का उपयोग करके दृश्य को स्ट्रीम में सहेजता है।

```csharp
public void Save(Stream stream, SaveOptions options)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | Stream | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए ज़िम्मेदार है। |
| options | SaveOptions | स्ट्रीम को सहेजने के लिए अधिक विस्तृत कॉन्फ़िगरेशन। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| IOException | इनपुट पढ़ने में विफल होने पर थ्रो किया जाता है |
| [ExportException](../../exportexception/) | जब सीन को निर्दिष्ट 3D फ़ॉर्मेट में एक्सपोर्ट करने में विफलता हो तो थ्रो किया जाता है |

## उदाहरण

निम्नलिखित कोड दिखाता है कि सीन को कैसे सहेजा जाए

```csharp
Scene scene = Scene.FromFile("input.fbx");
var opt = new UsdSaveOptions();
opt.PrimitiveToMesh = true;
using(var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
```

### देखें भी

* class [SaveOptions](../../../aspose.threed.formats/saveoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(Stream, SaveOptions, CancellationToken) {#save_3}

निर्दिष्ट फ़ाइल स्वरूप का उपयोग करके दृश्य को स्ट्रीम में सहेजता है।

```csharp
public void Save(Stream stream, SaveOptions options, CancellationToken cancellationToken)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| stream | Stream | इनपुट स्ट्रीम, उपयोगकर्ता स्ट्रीम को बंद करने के लिए ज़िम्मेदार है। |
| options | SaveOptions | स्ट्रीम को सहेजने के लिए अधिक विस्तृत कॉन्फ़िगरेशन। |
| cancellationToken | CancellationToken | सेव टास्क के लिए कैंसलेशन टोकन |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| IOException | इनपुट पढ़ने में विफल होने पर थ्रो किया जाता है |
| [ExportException](../../exportexception/) | जब सीन को निर्दिष्ट 3D फ़ॉर्मेट में एक्सपोर्ट करने में विफलता हो तो थ्रो किया जाता है |

## उदाहरण

निम्नलिखित कोड दिखाता है कि सीन को कैसे सहेजा जाए

```csharp
Scene scene = Scene.FromFile("input.fbx");
var cts = new CancellationTokenSource();
var opt = new UsdSaveOptions();
opt.PrimitiveToMesh = true;
using(var ms = new MemoryStream())
{
    scene.Save(ms, opt, cts.Token);
}
```

### देखें भी

* class [SaveOptions](../../../aspose.threed.formats/saveoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string) {#save_4}

निर्दिष्ट फ़ाइल स्वरूप का उपयोग करके दृश्य को निर्दिष्ट पथ पर सहेजता है।

```csharp
public void Save(string fileName)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fileName | String | फ़ाइल नाम। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| IOException | इनपुट पढ़ने में विफल होने पर थ्रो किया जाता है |
| [ExportException](../../exportexception/) | जब सीन को निर्दिष्ट 3D फ़ॉर्मेट में एक्सपोर्ट करने में विफलता हो तो थ्रो किया जाता है |

## उदाहरण

निम्नलिखित कोड दिखाता है कि सीन को कैसे सहेजा जाए

```csharp
Scene scene = Scene.FromFile("input.fbx");
scene.Save("output.usdz");
```

### देखें भी

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string, FileFormat) {#save_5}

निर्दिष्ट फ़ाइल स्वरूप का उपयोग करके दृश्य को निर्दिष्ट पथ पर सहेजता है।

```csharp
public void Save(string fileName, FileFormat format)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fileName | String | फ़ाइल नाम। |
| फ़ॉर्मेट | FileFormat | फ़ॉर्मेट। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| IOException | इनपुट पढ़ने में विफल होने पर थ्रो किया जाता है |
| [ExportException](../../exportexception/) | जब सीन को निर्दिष्ट 3D फ़ॉर्मेट में एक्सपोर्ट करने में विफलता हो तो थ्रो किया जाता है |

## उदाहरण

निम्नलिखित कोड दिखाता है कि सीन को कैसे सहेजा जाए

```csharp
Scene scene = Scene.FromFile("input.fbx");
scene.Save("output.usdz", FileFormat.USDZ);
```

### देखें भी

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string, FileFormat, CancellationToken) {#save_6}

निर्दिष्ट फ़ाइल स्वरूप का उपयोग करके दृश्य को निर्दिष्ट पथ पर सहेजता है।

```csharp
public void Save(string fileName, FileFormat format, CancellationToken cancellationToken)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fileName | String | फ़ाइल नाम। |
| फ़ॉर्मेट | FileFormat | फ़ॉर्मेट। |
| cancellationToken | CancellationToken | सेव टास्क के लिए कैंसलेशन टोकन |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| IOException | इनपुट पढ़ने में विफल होने पर थ्रो किया जाता है |
| [ExportException](../../exportexception/) | जब सीन को निर्दिष्ट 3D फ़ॉर्मेट में एक्सपोर्ट करने में विफलता हो तो थ्रो किया जाता है |

## उदाहरण

निम्नलिखित कोड दिखाता है कि सीन को कैसे सहेजा जाए

```csharp
var cts = new CancellationTokenSource();
Scene scene = Scene.FromFile("input.fbx");
scene.Save("output.usdz", FileFormat.USDZ, cts.Token);
```

### देखें भी

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string, SaveOptions) {#save_7}

निर्दिष्ट फ़ाइल स्वरूप का उपयोग करके दृश्य को निर्दिष्ट पथ पर सहेजता है।

```csharp
public void Save(string fileName, SaveOptions options)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fileName | String | फ़ाइल नाम। |
| options | SaveOptions | स्ट्रीम को सहेजने के लिए अधिक विस्तृत कॉन्फ़िगरेशन। |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| IOException | इनपुट पढ़ने में विफल होने पर थ्रो किया जाता है |
| [ExportException](../../exportexception/) | जब सीन को निर्दिष्ट 3D फ़ॉर्मेट में एक्सपोर्ट करने में विफलता हो तो थ्रो किया जाता है |

## उदाहरण

निम्नलिखित कोड दिखाता है कि सीन को कैसे सहेजा जाए

```csharp
var scene = Scene.FromFile("input.fbx");
var opts = new UsdSaveOptions();
opts.PrimitiveToMesh = true;
scene.Save("output.usdz", opts);
```

### देखें भी

* class [SaveOptions](../../../aspose.threed.formats/saveoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string, SaveOptions, CancellationToken) {#save_8}

निर्दिष्ट फ़ाइल स्वरूप का उपयोग करके दृश्य को निर्दिष्ट पथ पर सहेजता है।

```csharp
public void Save(string fileName, SaveOptions options, CancellationToken cancellationToken)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| fileName | String | फ़ाइल नाम। |
| options | SaveOptions | स्ट्रीम को सहेजने के लिए अधिक विस्तृत कॉन्फ़िगरेशन। |
| cancellationToken | CancellationToken | सेव टास्क के लिए कैंसलेशन टोकन |

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| IOException | इनपुट पढ़ने में विफल होने पर थ्रो किया जाता है |
| [ExportException](../../exportexception/) | जब सीन को निर्दिष्ट 3D फ़ॉर्मेट में एक्सपोर्ट करने में विफलता हो तो थ्रो किया जाता है |

## उदाहरण

निम्नलिखित कोड दिखाता है कि सीन को कैसे सहेजा जाए

```csharp
var cts = new CancellationTokenSource();
var scene = Scene.FromFile("input.fbx");
var opts = new UsdSaveOptions();
opts.PrimitiveToMesh = true;
scene.Save("output.usdz", opts, cts.Token);
```

### देखें भी

* class [SaveOptions](../../../aspose.threed.formats/saveoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


