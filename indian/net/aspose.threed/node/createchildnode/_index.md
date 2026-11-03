---
title: "Node.CreateChildNode"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Node method. एक चाइल्ड नोड बनाता है।"
type: docs
weight: 170
url: /hi/net/aspose.threed/node/createchildnode/
---
## CreateChildNode() {#createchildnode}

एक चाइल्ड नोड बनाता है

```csharp
public Node CreateChildNode()
```

### रिटर्न वैल्यू

नया चाइल्ड नोड।

## उदाहरण

निम्नलिखित कोड दिखाता है कि रूट नोड के तहत नया चाइल्ड नोड कैसे बनाया जाए।

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode();
node.Entity = new Box();
scene.Save("output.fbx");
```

### देखें भी

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## CreateChildNode(string) {#createchildnode_2}

दिए गए नोड नाम के साथ एक नया चाइल्ड नोड बनाएं

```csharp
public Node CreateChildNode(string nodeName)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| nodeName | String | नए चाइल्ड नोड का नाम |

### रिटर्न वैल्यू

नया चाइल्ड नोड।

## उदाहरण

निम्नलिखित कोड दिखाता है कि रूट नोड के तहत नया चाइल्ड नोड कैसे बनाया जाए।

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode("new node");
node.Entity = new Box();
scene.Save("output.fbx");
```

### देखें भी

* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## CreateChildNode(Entity) {#createchildnode_1}

दिए गए एंटिटी संलग्न के साथ एक नया चाइल्ड नोड बनाएं

```csharp
public Node CreateChildNode(Entity entity)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| एंटिटी | एंटिटी | नोड से जुड़ी डिफ़ॉल्ट एंटिटी |

### रिटर्न वैल्यू

नया चाइल्ड नोड।

## उदाहरण

निम्नलिखित कोड दिखाता है कि रूट नोड के तहत नया चाइल्ड नोड कैसे बनाया जाए।

```csharp
Scene scene = new Scene();
Node node = scene.RootNode.CreateChildNode(new Box());
scene.Save("output.fbx");
```

### देखें भी

* class [Entity](../../entity/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## CreateChildNode(string, Entity) {#createchildnode_3}

दिए गए नोड नाम के साथ एक नया चाइल्ड नोड बनाएं

```csharp
public Node CreateChildNode(string nodeName, Entity entity)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| nodeName | String | नए चाइल्ड नोड का नाम |
| एंटिटी | एंटिटी | नोड से जुड़ी डिफ़ॉल्ट एंटिटी |

### रिटर्न वैल्यू

नया चाइल्ड नोड।

### देखें भी

* class [Entity](../../entity/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)

---

## CreateChildNode(string, Entity, Material) {#createchildnode_4}

दिए गए नोड नाम के साथ एक नया चाइल्ड नोड बनाएं, और निर्दिष्ट एंटिटी तथा एक सामग्री संलग्न करें

```csharp
public Node CreateChildNode(string nodeName, Entity entity, Material material)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| nodeName | String | नए चाइल्ड नोड का नाम |
| एंटिटी | एंटिटी | नोड से जुड़ी डिफ़ॉल्ट एंटिटी |
| material | मैटेरियल | नोड से जुड़ा सामग्री |

### रिटर्न वैल्यू

नया चाइल्ड नोड।

### देखें भी

* class [Entity](../../entity/)
* class [Material](../../../aspose.threed.shading/material/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


