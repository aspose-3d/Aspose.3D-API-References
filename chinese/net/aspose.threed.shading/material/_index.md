---
title: "类 Material"
second_title: "Aspose.3D for .NET API 参考"
description: "Aspose.ThreeD.Shading.Material 类。Material 定义了几何体外观所需的参数。Aspose.3D 提供了 LambertMaterial、PhongMaterial 和 ShaderMaterial 的着色模型。"
type: docs
weight: 2540
url: /zh/net/aspose.threed.shading/material/
---
## Material class

Material 定义了几何体外观所需的参数。Aspose.3D 提供了针对 [`LambertMaterial`](../lambertmaterial/)、[`PhongMaterial`](../phongmaterial/) 和 [`ShaderMaterial`](../shadermaterial/) 的着色模型。

```csharp
public abstract class Material : A3DObject, IEnumerable<TextureSlot>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 获取或设置名称。 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | 获取所有属性的集合。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | 查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本地属性（通过其名称识别） |
| [GetEnumerator](../../aspose.threed.shading/material/getenumerator/)() | 获取枚举器以枚举内部纹理槽。 |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 获取指定属性的值 |
| [GetTexture](../../aspose.threed.shading/material/gettexture/)(string) | 从指定槽获取纹理，它可以是材质的属性名称或着色器的参数名称。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 移除动态属性。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 移除通过名称识别的指定属性 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 设置指定属性的值 |
| [SetTexture](../../aspose.threed.shading/material/settexture/)(string, TextureBase) | 将纹理设置到指定槽。 |
| override [ToString](../../aspose.threed.shading/material/tostring/)() | 将对象格式化为字符串。 |

## 字段

| 名称 | 描述 |
| --- | --- |
| const [MapAmbient](../../aspose.threed.shading/material/mapambient/) | 在 [`SetTexture`](./settexture/) 中用于分配环境纹理映射。 |
| const [MapDiffuse](../../aspose.threed.shading/material/mapdiffuse/) | 在[`SetTexture`](./settexture/)中用于分配漫反射纹理映射。 |
| const [MapEmissive](../../aspose.threed.shading/material/mapemissive/) | 在[`SetTexture`](./settexture/)中用于分配自发光纹理映射。 |
| const [MapNormal](../../aspose.threed.shading/material/mapnormal/) | 在[`SetTexture`](./settexture/)中用于分配法线纹理映射。 |
| const [MapSpecular](../../aspose.threed.shading/material/mapspecular/) | 在[`SetTexture`](./settexture/)中用于分配高光纹理映射。 |

## 示例

```csharp
var mat = new LambertMaterial();
var tex = new Texture();
tex.FileName = "diffuse.png";
mat.SetTexture(Material.MapDiffuse, tex);
foreach(var slot in mat)
{
    Console.WriteLine($"Texture slot {slot.SlotName} = {slot.Texture}");
}
```

### 另请参见

* class [A3DObject](../../aspose.threed/a3dobject/)
* class [TextureSlot](../textureslot/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


