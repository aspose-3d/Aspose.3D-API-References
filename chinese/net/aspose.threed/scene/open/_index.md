---
title: "Scene.Open"
second_title: "Aspose.3D for .NET API 参考"
description: "Scene 方法。使用指定的文件格式从给定流打开场景"
type: docs
weight: 140
url: /zh/net/aspose.threed/scene/open/
---
## Open(Stream, FileFormat, CancellationToken) {#open_1}

使用指定的文件格式从给定流打开场景。

```csharp
public void Open(Stream stream, FileFormat format, CancellationToken cancellationToken = default)
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

以下代码演示如何从流中打开场景

```csharp
Scene scene = new Scene();
using (var stream = new FileStream("input.fbx", FileMode.Open))
{
    scene.Open(stream, FileFormat.GLTF2);
}
```

### 另请参见

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(Stream, LoadOptions, CancellationToken) {#open_2}

使用指定的 IO 配置从给定流打开场景。

```csharp
public void Open(Stream stream, LoadOptions options, CancellationToken cancellationToken = default)
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

以下代码演示如何使用额外的加载选项从流中打开场景

```csharp
Scene scene = new Scene();
using (var stream = new FileStream("input.fbx", FileMode.Open))
{
    var opt = new FbxLoadOptions();
    opt.LookupPaths.Add("textures");
    scene.Open(stream, opt);
}
```

### 另请参见

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(Stream) {#open}

从给定流打开场景

```csharp
public void Open(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 输入流，用户负责关闭该流。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| IOException | 读取输入失败时抛出 |
| [ImportException](../../importexception/) | 当输入不是有效的 3D 格式时抛出 |

## 示例

以下代码演示如何从流中打开场景

```csharp
Scene scene = new Scene();
using (var stream = new FileStream("input.fbx", FileMode.Open))
{
    scene.Open(stream);
}
```

### 另请参见

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(Stream, CancellationToken) {#open_3}

从给定流打开场景

```csharp
public void Open(Stream stream, CancellationToken cancellationToken)
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

以下代码演示如何使用取消令牌从流中打开场景

```csharp
Scene scene = new Scene();
CancellationTokenSource cts = new CancellationTokenSource();
using (var stream = new FileStream("input.fbx", FileMode.Open))
{
    scene.Open(stream, cts.Token);
}
```

### 另请参见

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string, FileFormat, CancellationToken) {#open_5}

使用指定的文件格式从给定路径打开场景。

```csharp
public void Open(string fileName, FileFormat format, CancellationToken cancellationToken = default)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | 字符串 | 文件名。 |
| 格式 | FileFormat | 文件格式。 |
| cancellationToken | CancellationToken | 加载任务的取消令牌 |

### 异常

| 异常 | 条件 |
| --- | --- |
| IOException | 读取输入失败时抛出 |
| [ImportException](../../importexception/) | 当输入不是有效的 3D 格式时抛出 |

## 示例

以下代码展示了如何使用取消令牌从文件名打开场景

```csharp
Scene scene = new Scene();
CancellationTokenSource cts = new CancellationTokenSource();
scene.Open("input.fbx", FileFormat.FBX7400ASCII, cts.Token);

```

### 另请参见

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string, LoadOptions) {#open_6}

使用指定的文件格式从给定路径打开场景。

```csharp
public void Open(string fileName, LoadOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | 字符串 | 文件名。 |
| 选项 | LoadOptions | 更详细的打开流的配置。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| IOException | 读取输入失败时抛出 |
| [ImportException](../../importexception/) | 当输入不是有效的 3D 格式时抛出 |

## 示例

以下代码展示了如何使用额外加载选项从文件名打开场景

```csharp
Scene scene = new Scene();
var opts = new FbxLoadOptions();
opts.LookupPaths.Add("textures");
scene.Open("input.fbx", opts);
```

### 另请参见

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string, LoadOptions, CancellationToken) {#open_7}

使用指定的文件格式从给定路径打开场景。

```csharp
public void Open(string fileName, LoadOptions options, CancellationToken cancellationToken)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | 字符串 | 文件名。 |
| 选项 | LoadOptions | 更详细的打开流的配置。 |
| cancellationToken | CancellationToken | 加载任务的取消令牌 |

### 异常

| 异常 | 条件 |
| --- | --- |
| IOException | 读取输入失败时抛出 |
| [ImportException](../../importexception/) | 当输入不是有效的 3D 格式时抛出 |

## 示例

以下代码展示了如何使用额外加载选项和取消令牌从文件名打开场景

```csharp
var cts = new CancellationTokenSource();
Scene scene = new Scene();
var opts = new FbxLoadOptions();
opts.LookupPaths.Add("textures");
scene.Open("input.fbx", opts, cts.Token);
```

### 另请参见

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string) {#open_4}

从给定路径打开场景

```csharp
public void Open(string fileName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | 字符串 | 文件名。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| IOException | 读取输入失败时抛出 |
| [ImportException](../../importexception/) | 当输入不是有效的 3D 格式时抛出 |

## 示例

以下代码展示了如何从文件名打开场景

```csharp
Scene scene = new Scene();
scene.Open("input.fbx");
```

### 另请参见

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Open(string, CancellationToken) {#open_8}

从给定路径打开场景

```csharp
public void Open(string fileName, CancellationToken cancellationToken)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | 字符串 | 文件名。 |
| cancellationToken | CancellationToken | 加载任务的取消令牌 |

### 异常

| 异常 | 条件 |
| --- | --- |
| IOException | 读取输入失败时抛出 |
| [ImportException](../../importexception/) | 当输入不是有效的 3D 格式时抛出 |

## 示例

以下代码展示了如何从文件名打开场景以及取消令牌源

```csharp
var cts = new CancellationTokenSource();
Scene scene = new Scene();
scene.Open("input.fbx", cts.Token);
```

### 另请参见

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


