---
title: "Scene.FromFile"
second_title: "Aspose.3D for .NET API 参考"
description: "Scene 方法。使用指定的文件格式从给定路径打开场景"
type: docs
weight: 20
url: /zh/net/aspose.threed/scene/fromfile/
---
## FromFile(string, FileFormat, CancellationToken) {#fromfile_1}

使用指定的文件格式从给定路径打开场景。

```csharp
public static Scene FromFile(string fileName, FileFormat format, 
    CancellationToken cancellationToken = default)
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

以下代码展示了如何从文件创建场景

```csharp
var cts = new CancellationTokenSource();
Scene scene = Scene.FromFile("input.fbx", FileFormat.FBX7400ASCII, cts.Token);
```

### 另请参见

* class [FileFormat](../../fileformat/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromFile(string, LoadOptions, CancellationToken) {#fromfile_2}

使用指定的文件格式从给定路径打开场景。

```csharp
public static Scene FromFile(string fileName, LoadOptions options, 
    CancellationToken cancellationToken = default)
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

以下代码展示了如何从文件创建场景

```csharp
var cts = new CancellationTokenSource();
var opt = new FbxLoadOptions();
opt.LookupPaths.Add("textures");
Scene scene = Scene.FromFile("input.fbx", opt, cts.Token);
```

### 另请参见

* class [LoadOptions](../../../aspose.threed.formats/loadoptions/)
* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromFile(string) {#fromfile}

从给定路径打开场景

```csharp
public static Scene FromFile(string fileName)
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

以下代码展示了如何从文件创建场景

```csharp
Scene scene = Scene.FromFile("input.fbx");
```

### 另请参见

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)

---

## FromFile(string, CancellationToken) {#fromfile_3}

从给定路径打开场景

```csharp
public static Scene FromFile(string fileName, CancellationToken cancellationToken)
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

以下代码展示了如何从文件创建场景

```csharp
var cts = new CancellationTokenSource();
Scene scene = Scene.FromFile("input.fbx", cts.Token);
```

### 另请参见

* class [Scene](../)
* namespace [Aspose.ThreeD](../../scene/)
* assembly [Aspose.3D](../../../)


