---
title: "Material.GetTexture"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Material मेथड। निर्दिष्ट स्लॉट से टेक्सचर प्राप्त करता है; यह सामग्री की प्रॉपर्टी नाम या शेडर पैरामीटर नाम हो सकता है"
type: docs
weight: 20
url: /hi/net/aspose.threed.shading/material/gettexture/
---
## Material.GetTexture method

निर्दिष्ट स्लॉट से टेक्सचर प्राप्त करता है, यह मैटेरियल की प्रॉपर्टी नाम या शेडर के पैरामीटर नाम हो सकता है

```csharp
public TextureBase GetTexture(string slotName)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| slotName | String | स्लॉट नाम। |

### रिटर्न वैल्यू

टेक्सचर।

## उदाहरण

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapDiffuse, tex);
tex = (Texture)mat.GetTexture(Material.MapDiffuse);
```

### देखें भी

* class [TextureBase](../../texturebase/)
* class [Material](../)
* namespace [Aspose.ThreeD.Shading](../../material/)
* assembly [Aspose.3D](../../../)


