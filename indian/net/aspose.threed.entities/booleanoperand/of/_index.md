---
title: "BooleanOperand.Of"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "BooleanOperand मेथड। एक नोड से BooleanOperand का उदाहरण बनाएं, एक वैध इकाई जो IMeshConvertible लागू करती है, आवश्यक है।"
type: docs
weight: 10
url: /hi/net/aspose.threed.entities/booleanoperand/of/
---
## Of(Node) {#of_2}

`[`BooleanOperand`](../)` का उदाहरण एक नोड से बनाएं, एक वैध इकाई जो [`IMeshConvertible`](../../imeshconvertible/) लागू करती है, आवश्यक है।

```csharp
public static BooleanOperand Of(Node node)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| node | Node | `[`Node`](../../../aspose.threed/node/)` का एक उदाहरण, जिसमें एक वैध इकाई है जो [`IMeshConvertible`](../../imeshconvertible/) लागू करती है। |

### रिटर्न वैल्यू

`[`BooleanOperand`](../)` का एक उदाहरण।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *node* शून्य होने पर उठाया जाता है। |
| InvalidOperationException | इस नोड के तहत कोई इकाई जो [`IMeshConvertible`](../../imeshconvertible/) लागू करती है, न मिलने पर उठाया जाता है। |

### देखें भी

* class [Node](../../../aspose.threed/node/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)

---

## Of(Entity) {#of}

`[`BooleanOperand`](../)` का उदाहरण एक खाली [`IMeshConvertible`](../../imeshconvertible/) उदाहरण से बनाएं।

```csharp
public static BooleanOperand Of(Entity mesh)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| mesh | Entity | Boolean ऑपरेशन के ऑपरेण्ड के रूप में उपयोग किया गया मेष, यह [`IMeshConvertible`](../../imeshconvertible/) या [`HalfSpace`](../../halfspace/) का उदाहरण हो सकता है। |

### रिटर्न वैल्यू

`[`BooleanOperand`](../)` का एक उदाहरण।

### अपवाद

| अपवाद | शर्त |
| --- | --- |
| ArgumentNullException | *mesh* शून्य होने पर उठाया जाता है। |

### देखें भी

* class [Entity](../../../aspose.threed/entity/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)

---

## Of(Entity, Matrix4?) {#of_1}

```csharp
public static BooleanOperand Of(Entity mesh, Matrix4? transform)
```

### देखें भी

* class [Entity](../../../aspose.threed/entity/)
* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [BooleanOperand](../)
* namespace [Aspose.ThreeD.Entities](../../booleanoperand/)
* assembly [Aspose.3D](../../../)


