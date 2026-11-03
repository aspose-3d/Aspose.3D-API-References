---
title: "Scene.Scene"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Scene कंस्ट्रक्टर। Scene क्लास का नया इंस्टेंस इनिशियलाइज़ करता है"
type: docs
weight: 10
url: /hi/net/aspose.threed/scene/scene/
---
## Scene() {#constructor}

[`Scene`](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है।

```csharp
public Scene()
```

### देखें भी

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Scene(Entity) {#constructor_1}

[`Scene`](../) क्लास का नया इंस्टेंस इनिशियलाइज़ करता है जिसमें एक एंटिटी नई नोड से जुड़ी होती है।

```csharp
public Scene(Entity entity)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| एंटिटी | एंटिटी | सीन से जुड़ी प्रारंभिक एंटिटी |

## उदाहरण

निम्नलिखित कोड दिखाता है कि कैसे एक [`Scene`](../) को सीधे एक [`Entity`](../../entity/) से बनाया जाए:

```csharp
var scene = new Scene(new Box());
```

### देखें भी

* class [Entity](../../entity/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Scene(Scene, string) {#constructor_2}

[`Scene`](../) क्लास का नया इंस्टेंस एक सब-सीन के रूप में इनिशियलाइज़ करता है।

```csharp
public Scene(Scene parentScene, string name)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| parentScene | दृश्य | पैरेंट सीन। |
| नाम | String | सीन का नाम। |

### देखें भी

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


