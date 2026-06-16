---
title: "Mesh.Mesh"
second_title: "Aspose.3D for .NET API 参考"
description: "Mesh 构造函数。初始化 Mesh 类的新实例"
type: docs
weight: 10
url: /zh/net/aspose.threed.entities/mesh/mesh/
---
## Mesh() {#constructor}

初始化 [`Mesh`](../) 类的新实例。

```csharp
public Mesh()
```

### 另请参见

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## Mesh(TextureData) {#constructor_1}

使用指定的高度图构建网格，如果高度图的像素格式包含多个分量，则使用第一个（通常是红色）分量作为高度值 (z)。控制点的 x 和 y 分量为归一化像素坐标。

```csharp
public Mesh(TextureData heightMap)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| heightMap | TextureData | 输入高度图 |

### 另请参见

* class [TextureData](../../../aspose.threed.render/texturedata/)
* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## Mesh(TextureData, Matrix4) {#constructor_2}

使用指定的高度图构建网格，如果高度图的像素格式包含多个分量，则使用第一个（通常是红色）分量作为高度值 (z)。控制点的 x 和 y 分量为归一化像素坐标。

```csharp
public Mesh(TextureData heightMap, Matrix4 transform)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| heightMap | TextureData | 输入高度图 |
| transform | Matrix4 | 该 transform 应用于控制点 |

### 另请参见

* class [TextureData](../../../aspose.threed.render/texturedata/)
* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## Mesh(TextureData, bool, Matrix4) {#constructor_3}

使用指定的高度图构建网格，如果高度图的像素格式包含多个分量，则使用第一个（通常是红色）分量作为高度值 (z)。控制点的 x 和 y 分量为归一化像素坐标。

```csharp
public Mesh(TextureData heightMap, bool triMesh, Matrix4 transform)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| heightMap | TextureData | 输入高度图 |
| triMesh | Boolean |  |
| transform | Matrix4 | 该 transform 应用于控制点 |

### 另请参见

* class [TextureData](../../../aspose.threed.render/texturedata/)
* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## Mesh(string) {#constructor_4}

初始化 [`Mesh`](../) 类的新实例。

```csharp
public Mesh(string name)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | 字符串 | 名称。 |

### 另请参见

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


