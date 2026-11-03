---
title: "MathUtils.Clamp"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "MathUtils मेथड। मान को रेंज min max में क्लैंप करें।"
type: docs
weight: 20
url: /hi/net/aspose.threed.utilities/mathutils/clamp/
---
## MathUtils.Clamp method

मान को सीमा [min, max] में सीमित करें

```csharp
public static double Clamp(double val, double min, double max)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| val | डबल | क्लैंप करने के लिए मान। |
| min | डबल | न्यूनतम मान। |
| max | डबल | अधिकतम मान। |

### रिटर्न वैल्यू

मान [min, max] के बीच।

## उदाहरण

```csharp
var val = 195;
//मान को [0, 100] में क्लैंप करें।
var clampedValue = MathUtils.Clamp(val, 0, 100);
//यह 100 आउटपुट करेगा।
Console.WriteLine($"Value = {val}");
```

### देखें भी

* class [MathUtils](../)
* namespace [Aspose.ThreeD.Utilities](../../mathutils/)
* assembly [Aspose.3D](../../../)


