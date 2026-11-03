---
title: "Entity.GetBoundingBox"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Entity मेथड। वर्तमान एंटिटी का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कोऑर्डिनेट सिस्टम में प्राप्त करता है"
type: docs
weight: 50
url: /hi/net/aspose.threed/entity/getboundingbox/
---
## Entity.GetBoundingBox method

वर्तमान एंटिटी का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कोऑर्डिनेट सिस्टम में प्राप्त करता है।

```csharp
public BoundingBox GetBoundingBox()
```

### रिटर्न वैल्यू

वर्तमान एंटिटी का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कोऑर्डिनेट सिस्टम में।

## उदाहरण

निम्नलिखित कोड दिखाता है कि कैसे किसी आकार का बाउंडिंग बॉक्स गणना किया जाए

```csharp
Entity entity = new Sphere() { Radius = 10 };
var bbox = entity.GetBoundingBox();
Console.WriteLine($"The bounding box of the entity is {bbox.Minimum} ~ {bbox.Maximum}");
```

### देखें भी

* struct [BoundingBox](../../../aspose.threed.utilities/boundingbox/)
* class [Entity](../)
* namespace [Aspose.ThreeD](../../entity/)
* assembly [Aspose.3D](../../../)


