---
title: "Scene.FromStream"
second_title: "Aspose.3D for .NET API 参考"
description: "Scene 方法。使用指定的文件格式从给定流打开场景"
type: docs
weight: 30
url: /zh/net/aspose.threed/scene/fromstream/
---
## FromStream(Stream, FileFormat, CancellationToken) {#fromstream}

使用指定的文件格式从给定流打开场景。

```csharp
public static Scene FromStream(Stream stream, FileFormat format, 
    CancellationToken cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 输入流，用户负责关闭该流。 |
| 格式 | FileFormat | 文件格式。 |
| cancellationToken | CancellationToken | 加载任务的取消令牌 |

### 异常

| 异常 | 条件 |
| --- | --- |
| IOException | 读取输入失败时抛出 |
| [ImportException](../../importexception/) | 当输入不是有效的 3D 格式时抛出 |

## 示例

以下代码展示了如何从流创建场景

```csharp
using(var stream = new FileStream("input.fbx", FileMode.Open))
{
    Scene scene = Scene.FromStream(stream);
}
```

### 另请参见

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromStream(Stream, LoadOptions, CancellationToken) {#fromstream_1}

使用指定的 IO 配置从给定流打开场景。

```csharp
public static Scene FromStream(Stream stream, LoadOptions options, 
    CancellationToken cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 输入流，用户负责关闭该流。 |
| 选项 | LoadOptions | 更详细的打开流的配置。 |
| cancellationToken | CancellationToken | 加载任务的取消令牌 |

### 异常

| 异常 | 条件 |
| --- | --- |
| IOException | 读取输入失败时抛出 |
| [ImportException](../../importexception/) | 当输入不是有效的 3D 格式时抛出 |

## 示例

以下代码展示了如何使用加载选项从流创建场景

```csharp
var opts = new FbxLoadOptions();
opts.LookupPaths.Add("textures");
using(var stream = new FileStream("input.fbx", FileMode.Open))
{
    Scene scene = Scene.FromStream(stream, opts);
}
```

### 另请参见

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromStream(Stream, CancellationToken) {#fromstream_2}

从给定流打开场景

```csharp
public static Scene FromStream(Stream stream, CancellationToken cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 输入流，用户负责关闭该流。 |
| cancellationToken | CancellationToken | 加载任务的取消令牌 |

### 异常

| 异常 | 条件 |
| --- | --- |
| IOException | 读取输入失败时抛出 |
| [ImportException](../../importexception/) | 当输入不是有效的 3D 格式时抛出 |

## 示例

以下代码展示了如何使用取消令牌源从流创建场景

```csharp
var cts = new CancellationTokenSource();
using(var stream = new FileStream("input.fbx", FileMode.Open))
{
    Scene scene = Scene.FromStream(stream, cts.Token);
}
```

### 另请参见

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


