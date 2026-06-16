---
title: "Scene.Save"
second_title: "Aspose.3D for .NET API 参考"
description: "Scene 方法。保存场景到流，使用指定的文件格式"
type: docs
weight: 160
url: /zh/net/aspose.threed/scene/save/
---
## Save(Stream, FileFormat) {#save}

使用指定的文件格式将场景保存到流。

```csharp
public void Save(Stream stream, FileFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 输入流，用户负责关闭该流。 |
| 格式 | FileFormat | 格式。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| IOException | 读取输入失败时抛出 |
| [ExportException](../../exportexception/) | 当导出场景到指定的 3D 格式失败时抛出 |

## 示例

以下代码展示了如何保存场景

```csharp
Scene scene = Scene.FromFile("input.fbx");
using(var ms = new MemoryStream())
{
    scene.Save(ms, FileFormat.USDZ);
}
```

### 另请参见

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(Stream, FileFormat, CancellationToken) {#save_1}

使用指定的文件格式将场景保存到流。

```csharp
public void Save(Stream stream, FileFormat format, CancellationToken cancellationToken)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 输入流，用户负责关闭该流。 |
| 格式 | FileFormat | 格式。 |
| cancellationToken | CancellationToken | 保存任务的取消令牌 |

### 异常

| 异常 | 条件 |
| --- | --- |
| IOException | 读取输入失败时抛出 |
| [ExportException](../../exportexception/) | 当导出场景到指定的 3D 格式失败时抛出 |

## 示例

以下代码展示了如何保存场景

```csharp
Scene scene = Scene.FromFile("input.fbx");
var cts = new CancellationTokenSource();
using(var ms = new MemoryStream())
{
    scene.Save(ms, FileFormat.USDZ, cts.Token);
}
```

### 另请参见

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(Stream, SaveOptions) {#save_2}

使用指定的文件格式将场景保存到流。

```csharp
public void Save(Stream stream, SaveOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 输入流，用户负责关闭该流。 |
| 选项 | SaveOptions | 更详细的保存流配置。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| IOException | 读取输入失败时抛出 |
| [ExportException](../../exportexception/) | 当导出场景到指定的 3D 格式失败时抛出 |

## 示例

以下代码展示了如何保存场景

```csharp
Scene scene = Scene.FromFile("input.fbx");
var opt = new UsdSaveOptions();
opt.PrimitiveToMesh = true;
using(var ms = new MemoryStream())
{
    scene.Save(ms, opt);
}
```

### 另请参见

* class [SaveOptions](../../../aspose.threed.formats/saveoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(Stream, SaveOptions, CancellationToken) {#save_3}

使用指定的文件格式将场景保存到流。

```csharp
public void Save(Stream stream, SaveOptions options, CancellationToken cancellationToken)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 输入流，用户负责关闭该流。 |
| 选项 | SaveOptions | 更详细的保存流配置。 |
| cancellationToken | CancellationToken | 保存任务的取消令牌 |

### 异常

| 异常 | 条件 |
| --- | --- |
| IOException | 读取输入失败时抛出 |
| [ExportException](../../exportexception/) | 当导出场景到指定的 3D 格式失败时抛出 |

## 示例

以下代码展示了如何保存场景

```csharp
Scene scene = Scene.FromFile("input.fbx");
var cts = new CancellationTokenSource();
var opt = new UsdSaveOptions();
opt.PrimitiveToMesh = true;
using(var ms = new MemoryStream())
{
    scene.Save(ms, opt, cts.Token);
}
```

### 另请参见

* class [SaveOptions](../../../aspose.threed.formats/saveoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string) {#save_4}

使用指定的文件格式将场景保存到指定路径。

```csharp
public void Save(string fileName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | 字符串 | 文件名。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| IOException | 读取输入失败时抛出 |
| [ExportException](../../exportexception/) | 当导出场景到指定的 3D 格式失败时抛出 |

## 示例

以下代码展示了如何保存场景

```csharp
Scene scene = Scene.FromFile("input.fbx");
scene.Save("output.usdz");
```

### 另请参见

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string, FileFormat) {#save_5}

使用指定的文件格式将场景保存到指定路径。

```csharp
public void Save(string fileName, FileFormat format)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | 字符串 | 文件名。 |
| 格式 | FileFormat | 格式。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| IOException | 读取输入失败时抛出 |
| [ExportException](../../exportexception/) | 当导出场景到指定的 3D 格式失败时抛出 |

## 示例

以下代码展示了如何保存场景

```csharp
Scene scene = Scene.FromFile("input.fbx");
scene.Save("output.usdz", FileFormat.USDZ);
```

### 另请参见

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string, FileFormat, CancellationToken) {#save_6}

使用指定的文件格式将场景保存到指定路径。

```csharp
public void Save(string fileName, FileFormat format, CancellationToken cancellationToken)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | 字符串 | 文件名。 |
| 格式 | FileFormat | 格式。 |
| cancellationToken | CancellationToken | 保存任务的取消令牌 |

### 异常

| 异常 | 条件 |
| --- | --- |
| IOException | 读取输入失败时抛出 |
| [ExportException](../../exportexception/) | 当导出场景到指定的 3D 格式失败时抛出 |

## 示例

以下代码展示了如何保存场景

```csharp
var cts = new CancellationTokenSource();
Scene scene = Scene.FromFile("input.fbx");
scene.Save("output.usdz", FileFormat.USDZ, cts.Token);
```

### 另请参见

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string, SaveOptions) {#save_7}

使用指定的文件格式将场景保存到指定路径。

```csharp
public void Save(string fileName, SaveOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | 字符串 | 文件名。 |
| 选项 | SaveOptions | 更详细的保存流配置。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| IOException | 读取输入失败时抛出 |
| [ExportException](../../exportexception/) | 当导出场景到指定的 3D 格式失败时抛出 |

## 示例

以下代码展示了如何保存场景

```csharp
var scene = Scene.FromFile("input.fbx");
var opts = new UsdSaveOptions();
opts.PrimitiveToMesh = true;
scene.Save("output.usdz", opts);
```

### 另请参见

* class [SaveOptions](../../../aspose.threed.formats/saveoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## Save(string, SaveOptions, CancellationToken) {#save_8}

使用指定的文件格式将场景保存到指定路径。

```csharp
public void Save(string fileName, SaveOptions options, CancellationToken cancellationToken)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | 字符串 | 文件名。 |
| 选项 | SaveOptions | 更详细的保存流配置。 |
| cancellationToken | CancellationToken | 保存任务的取消令牌 |

### 异常

| 异常 | 条件 |
| --- | --- |
| IOException | 读取输入失败时抛出 |
| [ExportException](../../exportexception/) | 当导出场景到指定的 3D 格式失败时抛出 |

## 示例

以下代码展示了如何保存场景

```csharp
var cts = new CancellationTokenSource();
var scene = Scene.FromFile("input.fbx");
var opts = new UsdSaveOptions();
opts.PrimitiveToMesh = true;
scene.Save("output.usdz", opts, cts.Token);
```

### 另请参见

* class [SaveOptions](../../../aspose.threed.formats/saveoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


