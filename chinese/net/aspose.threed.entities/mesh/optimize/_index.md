---
title: Mesh.Optimize
second_title: Aspose.3D for .NET API 参考手册
description: Mesh 方法。通过消除重复的控制点来优化网格的内存使用
type: docs
weight: 100
url: /zh/net/aspose.threed.entities/mesh/optimize/
---
## Optimize(bool) {#optimize}

通过消除重复的控制点来优化网格的内存使用。

```csharp
public Mesh Optimize(bool vertexElements)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vertexElements | Boolean | 优化重复的顶点元素数据 |

### 返回值

具有紧凑内存使用的新网格实例

## 示例

以下代码展示了如何从未优化的网格中消除重复的控制点：

```csharp
//Sphere.ToMesh 生成 117 个控制点
var mesh = (new Sphere()).ToMesh();
//优化后，仅剩 86 个控制点，多边形索引也已重新映射。
var optimized = mesh.Optimize(true);
```

### 另请参见

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)

---

## Optimize(bool, float, float, float) {#optimize_1}

通过消除重复的控制点来优化网格的内存使用。

```csharp
public Mesh Optimize(bool vertexElements, float toleranceControlPoint = 1E-09, 
    float toleranceNormal = 1E-09, float toleranceUV = 1E-09)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| vertexElements | Boolean | 优化重复的顶点元素数据 |
| toleranceControlPoint | 单精度 | 控制点的容差，默认值为 1e-9 |
| toleranceNormal | 单精度 | 法线/切线/双切线的容差，默认值为 1e-9 |
| toleranceUV | 单精度 | uv 的容差，默认值为 1e-9 |

### 返回值

具有紧凑内存使用的新网格实例

### 另请参见

* class [Mesh](../)
* namespace [Aspose.ThreeD.Entities](../../mesh/)
* assembly [Aspose.3D](../../../)


