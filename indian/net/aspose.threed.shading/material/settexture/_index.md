---
title: "Material.SetTexture"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Material method. निर्दिष्ट स्लॉट में texture सेट करता है"
type: docs
weight: 30
url: /hi/net/aspose.threed.shading/material/settexture/
---
## Material.SetTexture method

टेक्सचर को निर्दिष्ट स्लॉट में सेट करता है

```csharp
public void SetTexture(string slotName, TextureBase texture)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| slotName | String | स्लॉट नाम। |
| texture | TextureBase | Texture. |

## उदाहरण

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapNormal, tex);
```

### देखें भी

* class [TextureBase](../../texturebase/)
* class [Material](../)
* namespace [Aspose.ThreeD.Shading](../../material/)
* assembly [Aspose.3D](../../../)


