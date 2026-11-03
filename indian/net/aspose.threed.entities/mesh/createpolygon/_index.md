---
title: "Mesh.CreatePolygon"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Mesh मेथड। सभी वर्टिसेज़ को इंडेक्स में परिभाषित करके एक नया पॉलीगॉन बनाता है। पॉलीगॉन को वर्टेक्स दर वर्टेक्स बनाने के लिए कृपया PolygonBuilder का उपयोग करें।"
type: docs
weight: 60
url: /hi/net/aspose.threed.entities/mesh/createpolygon/
---
## CreatePolygon(int[], int, int) {#createpolygon_3}

सभी शीर्ष बिंदु *indices* में परिभाषित एक नया बहुभुज बनाता है। बहुभुज को बिंदु दर बिंदु बनाने के लिए, कृपया [`PolygonBuilder`](../../polygonbuilder/) का उपयोग करें।

```csharp
public void CreatePolygon(int[] indices, int offset, int length)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| सूचकांक | Int32[] | बहुभुज के सूचकांकों की सरणी, प्रत्येक सूचकांक एक नियंत्रण बिंदु की ओर संकेत करता है जो बहुभुज बनाता है। |
| ऑफ़सेट | Int32 | पहले बहुभुज सूचकांक का ऑफ़सेट |
| लंबाई | Int32 | सूचकांकों की लंबाई |

## उदाहरण

निम्नलिखित कोड दर्शाता है कि नियंत्रण बिंदुओं के सूचकांकों के साथ नया बहुभुज कैसे बनाया जाए।

```csharp
var mesh = new Mesh();
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

### देखें भी

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## CreatePolygon(int[]) {#createpolygon_2}

सभी शीर्ष बिंदु *indices* में परिभाषित एक नया बहुभुज बनाता है। बहुभुज को बिंदु दर बिंदु बनाने के लिए, कृपया [`PolygonBuilder`](../../polygonbuilder/) का उपयोग करें।

```csharp
public void CreatePolygon(int[] indices)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| सूचकांक | Int32[] | बहुभुज के सूचकांकों की सरणी, प्रत्येक सूचकांक एक नियंत्रण बिंदु की ओर संकेत करता है जो बहुभुज बनाता है। |

## उदाहरण

```csharp
var mesh = new Mesh();
int[] indices = new int[] {0, 1, 2};
mesh.CreatePolygon(indices);
```

### देखें भी

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## CreatePolygon(int, int, int, int) {#createpolygon_1}

4 वर्टेक्स (चतुर्भुज) के साथ एक बहुभुज बनाएं

```csharp
public void CreatePolygon(int v1, int v2, int v3, int v4)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| v1 | Int32 | पहले शीर्ष बिंदु का सूचकांक |
| v2 | Int32 | दूसरे शीर्ष बिंदु का सूचकांक |
| v3 | Int32 | तीसरे शीर्ष बिंदु का सूचकांक |
| v4 | Int32 | चौथे शीर्ष बिंदु का सूचकांक |

## उदाहरण

निम्नलिखित कोड दर्शाता है कि नियंत्रण बिंदुओं के सूचकांकों के साथ नया बहुभुज कैसे बनाया जाए।

```csharp
var mesh = new Mesh();
mesh.CreatePolygon(0, 1, 2, 3);
```

### देखें भी

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## CreatePolygon(int, int, int) {#createpolygon}

3 वर्टेक्स (त्रिभुज) के साथ एक बहुभुज बनाएं

```csharp
public void CreatePolygon(int v1, int v2, int v3)
```

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| v1 | Int32 | पहले शीर्ष बिंदु का सूचकांक |
| v2 | Int32 | दूसरे शीर्ष बिंदु का सूचकांक |
| v3 | Int32 | तीसरे शीर्ष बिंदु का सूचकांक |

## उदाहरण

निम्नलिखित कोड दर्शाता है कि नियंत्रण बिंदुओं के सूचकांकों के साथ नया बहुभुज कैसे बनाया जाए।

```csharp
var mesh = new Mesh();
mesh.CreatePolygon(0, 1, 2);
```

### देखें भी

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


