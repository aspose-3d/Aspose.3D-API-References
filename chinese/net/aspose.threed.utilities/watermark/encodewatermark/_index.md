---
title: "Watermark.EncodeWatermark"
second_title: "Aspose.3D for .NET API 参考"
description: "Watermark 方法。将文本编码为网格盲水印"
type: docs
weight: 20
url: /zh/net/aspose.threed.utilities/watermark/encodewatermark/
---
## EncodeWatermark(Mesh, string) {#encodewatermark}

将文本编码到网格的盲水印中。

```csharp
public static Mesh EncodeWatermark(Mesh input, string text)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 输入 | 网格 | 用于编码盲水印的网格 |
| 文本 | 字符串 | 要编码到网格的文本 |

### 返回值

已编码盲水印的新网格实例

## 备注

`EncodeWatermark` 和 [`DecodeWatermark`](../decodewatermark/) 都会执行许可证检查。试用时使用将抛出异常，您可以使用 [`SuppressTrialException`](../../../aspose.threed/trialexception/suppresstrialexception/) 来抑制该异常，但这不会解除此处的限制。需要有效许可证才能在没有任何限制的情况下使用这些功能。

## 示例

以下代码演示如何将盲水印编码到网格并保存为 ply 文件

```csharp
Mesh mesh = (new Cylinder()).ToMesh();
var encodedMesh = Watermark.EncodeWatermark(mesh, "Hello");
new Scene(encodedMesh).Save("test.ply");
```

### 另请参见

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)

---

## EncodeWatermark(Mesh, string, string) {#encodewatermark_1}

将文本编码到网格的盲水印中。

```csharp
public static Mesh EncodeWatermark(Mesh input, string text, string password)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 输入 | 网格 | 用于编码盲水印的网格 |
| 文本 | 字符串 | 要编码到网格的文本 |
| 密码 | 字符串 | 用于保护水印的密码，可选 |

### 返回值

已编码盲水印的新网格实例

## 备注

`EncodeWatermark` 和 [`DecodeWatermark`](../decodewatermark/) 都会执行许可证检查。试用时使用将抛出异常，您可以使用 [`SuppressTrialException`](../../../aspose.threed/trialexception/suppresstrialexception/) 来抑制该异常，但这不会解除此处的限制。需要有效许可证才能在没有任何限制的情况下使用这些功能。

## 示例

以下代码演示如何将盲水印编码到网格并保存为 ply 文件

```csharp
Mesh mesh = (new Cylinder()).ToMesh();
var encodedMesh = Watermark.EncodeWatermark(mesh, "Hello", "password");
new Scene(encodedMesh).Save("test.ply");
```

### 另请参见

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)

---

## EncodeWatermark(Mesh, string, string, bool) {#encodewatermark_2}

将文本编码到网格的盲水印中。

```csharp
public static Mesh EncodeWatermark(Mesh input, string text, string password, bool permanent)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 输入 | 网格 | 用于编码盲水印的网格 |
| 文本 | 字符串 | 要编码到网格的文本 |
| 密码 | 字符串 | 用于保护水印的密码，可选 |
| 永久 | Boolean | 永久水印不会被覆盖或移除。 |

### 返回值

已编码盲水印的新网格实例

## 备注

`EncodeWatermark` 和 [`DecodeWatermark`](../decodewatermark/) 都会执行许可证检查。试用时使用将抛出异常，您可以使用 [`SuppressTrialException`](../../../aspose.threed/trialexception/suppresstrialexception/) 来抑制该异常，但这不会解除此处的限制。需要有效许可证才能在没有任何限制的情况下使用这些功能。

## 示例

以下代码演示如何将盲水印编码到网格并保存为 ply 文件

```csharp
Mesh mesh = (new Cylinder()).ToMesh();
var encodedMesh = Watermark.EncodeWatermark(mesh, "Hello", "password");
new Scene(encodedMesh).Save("test.ply");
```

### 另请参见

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)


