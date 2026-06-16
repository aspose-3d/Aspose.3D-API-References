---
title: "PbrMaterial"
second_title: "Aspose.3D for Java API 参考"
description: "基于反照率颜色/金属度/粗糙度的物理渲染材质"
type: docs
weight: 121
url: /zh/java/com.aspose.threed/pbrmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class PbrMaterial extends Material
```

基于反照率颜色/金属度/粗糙度的物理渲染材质
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PbrMaterial()](#PbrMaterial--) | 构造默认的 PBR 材质实例 |
| [PbrMaterial(Vector3 albedo)](#PbrMaterial-com.aspose.threed.Vector3-) | 使用指定的反照率颜色值构造默认的 PBR 材质。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [MAP_AMBIENT](#MAP-AMBIENT) | 在 [setTexture](../../com.aspose.threed/material\#setTexture) 中用于分配环境纹理映射。 |
| [MAP_DIFFUSE](#MAP-DIFFUSE) | 在 [setTexture](../../com.aspose.threed/material\#setTexture) 中用于分配漫反射纹理映射。 |
| [MAP_EMISSIVE](#MAP-EMISSIVE) | 在 [setTexture](../../com.aspose.threed/material\#setTexture) 中用于分配自发光纹理映射。 |
| [MAP_NORMAL](#MAP-NORMAL) | 在 [setTexture](../../com.aspose.threed/material\#setTexture) 中用于分配法线纹理映射。 |
| [MAP_SPECULAR](#MAP-SPECULAR) | 在 [setTexture](../../com.aspose.threed/material\#setTexture) 中用于分配高光纹理映射。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 查找属性。 |
| [fromMaterial(Material material)](#fromMaterial-com.aspose.threed.Material-) | 允许将其他材质转换为 PbrMaterial **Example:** |
| [getAlbedo()](#getAlbedo--) | 获取材质的基础颜色 |
| [getAlbedoTexture()](#getAlbedoTexture--) | 获取反照率纹理 |
| [getClass()](#getClass--) |  |
| [getEmissiveColor()](#getEmissiveColor--) | 获取自发光颜色 |
| [getEmissiveTexture()](#getEmissiveTexture--) | 获取自发光纹理 |
| [getMetallicFactor()](#getMetallicFactor--) | 获取材质的金属度，值为 1 表示材质为金属，值为 0 表示材质为介电体。 |
| [getMetallicRoughness()](#getMetallicRoughness--) | 获取金属度（R 通道）和粗糙度（G 通道）的纹理 |
| [getName()](#getName--) | 获取名称。 |
| [getNormalTexture()](#getNormalTexture--) | 获取法线贴图纹理 |
| [getOcclusionFactor()](#getOcclusionFactor--) | 获取环境遮蔽因子 |
| [getOcclusionTexture()](#getOcclusionTexture--) | 获取环境遮蔽纹理 |
| [getProperties()](#getProperties--) | 获取所有属性的集合。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 获取指定属性的值 |
| [getRoughnessFactor()](#getRoughnessFactor--) | 获取材质的粗糙度，值为 1 表示材质完全粗糙，值为 0 表示材质完全光滑。 |
| [getSpecularTexture()](#getSpecularTexture--) | 获取高光颜色纹理 |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | 从指定槽获取纹理，它可以是材质的属性名称或着色器的参数名称。 |
| [getTransparency()](#getTransparency--) | 获取透明度因子。 |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | 获取枚举器以遍历内部纹理槽。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 移除动态属性。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 移除通过名称标识的指定属性 |
| [setAlbedo(Vector3 value)](#setAlbedo-com.aspose.threed.Vector3-) | 设置材质的基础颜色 |
| [setAlbedoTexture(TextureBase value)](#setAlbedoTexture-com.aspose.threed.TextureBase-) | 设置 albedo 的纹理 |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | 设置自发光颜色 |
| [setEmissiveTexture(TextureBase value)](#setEmissiveTexture-com.aspose.threed.TextureBase-) | 设置自发光的纹理 |
| [setMetallicFactor(double value)](#setMetallicFactor-double-) | 设置材质的金属度，值为 1 表示材质是金属，值为 0 表示材质是介电体。 |
| [setMetallicRoughness(TextureBase value)](#setMetallicRoughness-com.aspose.threed.TextureBase-) | 设置 metallic（R 通道）和 roughness（G 通道）的纹理 |
| [setName(String value)](#setName-java.lang.String-) | 设置名称。 |
| [setNormalTexture(TextureBase value)](#setNormalTexture-com.aspose.threed.TextureBase-) | 设置法线贴图的纹理 |
| [setOcclusionFactor(double value)](#setOcclusionFactor-double-) | 设置环境遮蔽的因子 |
| [setOcclusionTexture(TextureBase value)](#setOcclusionTexture-com.aspose.threed.TextureBase-) | 设置环境遮蔽的纹理 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 设置指定属性的值 |
| [setRoughnessFactor(double value)](#setRoughnessFactor-double-) | 设置材质的粗糙度，值为 1 表示材质完全粗糙，值为 0 表示材质完全光滑。 |
| [setSpecularTexture(TextureBase value)](#setSpecularTexture-com.aspose.threed.TextureBase-) | 设置镜面颜色的纹理 |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | 将纹理设置到指定槽 |
| [setTransparency(double value)](#setTransparency-double-) | 设置透明度因子。 |
| [toString()](#toString--) | 将对象格式化为字符串 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PbrMaterial() {#PbrMaterial--}
```
public PbrMaterial()
```


构造默认的 PBR 材质实例

### PbrMaterial(Vector3 albedo) {#PbrMaterial-com.aspose.threed.Vector3-}
```
public PbrMaterial(Vector3 albedo)
```


使用指定的反照率颜色值构造默认的 PBR 材质。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| albedo | [Vector3](../../com.aspose.threed/vector3) | 默认 albedo 颜色值 |

### MAP_AMBIENT {#MAP-AMBIENT}
```
public static final String MAP_AMBIENT
```


在 [setTexture](../../com.aspose.threed/material\#setTexture) 中用于分配环境纹理映射。

### MAP_DIFFUSE {#MAP-DIFFUSE}
```
public static final String MAP_DIFFUSE
```


在 [setTexture](../../com.aspose.threed/material\#setTexture) 中用于分配漫反射纹理映射。

### MAP_EMISSIVE {#MAP-EMISSIVE}
```
public static final String MAP_EMISSIVE
```


在 [setTexture](../../com.aspose.threed/material\#setTexture) 中用于分配自发光纹理映射。

### MAP_NORMAL {#MAP-NORMAL}
```
public static final String MAP_NORMAL
```


在 [setTexture](../../com.aspose.threed/material\#setTexture) 中用于分配法线纹理映射。

### MAP_SPECULAR {#MAP-SPECULAR}
```
public static final String MAP_SPECULAR
```


在 [setTexture](../../com.aspose.threed/material\#setTexture) 中用于分配高光纹理映射。

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
布尔
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


查找属性。它可以是动态属性（由 CreateDynamicProperty/SetProperty 创建）或本机属性（通过其名称标识）

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| propertyName | java.lang.String | 属性名称。 |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### fromMaterial(Material material) {#fromMaterial-com.aspose.threed.Material-}
```
public static PbrMaterial fromMaterial(Material material)
```


允许将其他材质转换为 PbrMaterial **Example:**

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_DIFFUSE, tex);
     mat.setDiffuseColor(new Vector3(0.3, 0.9, 0.4));
     PbrMaterial pbr = PbrMaterial.fromMaterial(mat);
```

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| material | [Material](../../com.aspose.threed/material) |  |

**Returns:**
[PbrMaterial](../../com.aspose.threed/pbrmaterial)
### getAlbedo() {#getAlbedo--}
```
public Vector3 getAlbedo()
```


获取材质的基础颜色

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the base color of the material
### getAlbedoTexture() {#getAlbedoTexture--}
```
public TextureBase getAlbedoTexture()
```


获取反照率纹理

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for albedo
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


获取自发光颜色

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color
### getEmissiveTexture() {#getEmissiveTexture--}
```
public TextureBase getEmissiveTexture()
```


获取自发光纹理

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for emissive
### getMetallicFactor() {#getMetallicFactor--}
```
public double getMetallicFactor()
```


获取材质的金属度，值为 1 表示材质为金属，值为 0 表示材质为介电体。

**Returns:**
double - 材质的金属度，值为 1 表示材质是金属，值为 0 表示材质是介电体。
### getMetallicRoughness() {#getMetallicRoughness--}
```
public TextureBase getMetallicRoughness()
```


获取金属度（R 通道）和粗糙度（G 通道）的纹理

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for metallic(in R channel) and roughness(in G channel)
### getName() {#getName--}
```
public String getName()
```


获取名称。

**Returns:**
java.lang.String - 名称。
### getNormalTexture() {#getNormalTexture--}
```
public TextureBase getNormalTexture()
```


获取法线贴图纹理

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture of normal mapping
### getOcclusionFactor() {#getOcclusionFactor--}
```
public double getOcclusionFactor()
```


获取环境遮蔽因子

**Returns:**
double - 环境遮蔽的因子
### getOcclusionTexture() {#getOcclusionTexture--}
```
public TextureBase getOcclusionTexture()
```


获取环境遮蔽纹理

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for ambient occlusion
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


获取所有属性的集合。

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


获取指定属性的值

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 属性 | java.lang.String | 属性名称 |

**Returns:**
java.lang.Object - 找到的属性的值
### getRoughnessFactor() {#getRoughnessFactor--}
```
public double getRoughnessFactor()
```


获取材质的粗糙度，值为 1 表示材质完全粗糙，值为 0 表示材质完全光滑。

**Returns:**
double - 材质的粗糙度，值为 1 表示材质完全粗糙，值为 0 表示材质完全光滑。
### getSpecularTexture() {#getSpecularTexture--}
```
public TextureBase getSpecularTexture()
```


获取高光颜色纹理

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for specular color
### getTexture(String slotName) {#getTexture-java.lang.String-}
```
public TextureBase getTexture(String slotName)
```


从指定槽获取纹理，它可以是材质的属性名称或着色器的参数名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| slotName | java.lang.String | 槽名称。 |

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - The texture. **Example:**

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_DIFFUSE, tex);
     tex = (Texture)mat.getTexture(Material.MAP_DIFFUSE);
```
### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


获取透明度因子。该因子的取值范围应在 0（0%，完全不透明）到 1（100%，完全透明）之间。任何无效的因子值都会被限制在范围内。

**Returns:**
double - 透明度因子。该因子的取值范围应在 0（0%，完全不透明）到 1（100%，完全透明）之间。任何无效的因子值都会被限制在范围内。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### iterator() {#iterator--}
```
public Iterator<TextureSlot> iterator()
```


获取枚举器以遍历内部纹理槽。

**Returns:**
java.util.Iterator<com.aspose.threed.TextureSlot>
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


移除动态属性。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | 要删除哪个属性 |

**Returns:**
boolean - 如果属性成功删除则为 true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


移除通过名称标识的指定属性

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 属性 | java.lang.String | 要删除哪个属性 |

**Returns:**
boolean - 如果属性成功删除则为 true
### setAlbedo(Vector3 value) {#setAlbedo-com.aspose.threed.Vector3-}
```
public void setAlbedo(Vector3 value)
```


设置材质的基础颜色

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新值 |

### setAlbedoTexture(TextureBase value) {#setAlbedoTexture-com.aspose.threed.TextureBase-}
```
public void setAlbedoTexture(TextureBase value)
```


设置 albedo 的纹理

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | 新值 |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


设置自发光颜色

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新值 |

### setEmissiveTexture(TextureBase value) {#setEmissiveTexture-com.aspose.threed.TextureBase-}
```
public void setEmissiveTexture(TextureBase value)
```


设置自发光的纹理

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | 新值 |

### setMetallicFactor(double value) {#setMetallicFactor-double-}
```
public void setMetallicFactor(double value)
```


设置材质的金属度，值为 1 表示材质是金属，值为 0 表示材质是介电体。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setMetallicRoughness(TextureBase value) {#setMetallicRoughness-com.aspose.threed.TextureBase-}
```
public void setMetallicRoughness(TextureBase value)
```


设置 metallic（R 通道）和 roughness（G 通道）的纹理

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | 新值 |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


设置名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

### setNormalTexture(TextureBase value) {#setNormalTexture-com.aspose.threed.TextureBase-}
```
public void setNormalTexture(TextureBase value)
```


设置法线贴图的纹理

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | 新值 |

### setOcclusionFactor(double value) {#setOcclusionFactor-double-}
```
public void setOcclusionFactor(double value)
```


设置环境遮蔽的因子

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setOcclusionTexture(TextureBase value) {#setOcclusionTexture-com.aspose.threed.TextureBase-}
```
public void setOcclusionTexture(TextureBase value)
```


设置环境遮蔽的纹理

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | 新值 |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


设置指定属性的值

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 属性 | java.lang.String | 属性名称 |
| 值 | java.lang.Object | 属性的值 |

### setRoughnessFactor(double value) {#setRoughnessFactor-double-}
```
public void setRoughnessFactor(double value)
```


设置材质的粗糙度，值为 1 表示材质完全粗糙，值为 0 表示材质完全光滑。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setSpecularTexture(TextureBase value) {#setSpecularTexture-com.aspose.threed.TextureBase-}
```
public void setSpecularTexture(TextureBase value)
```


设置镜面颜色的纹理

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | 新值 |

### setTexture(String slotName, TextureBase texture) {#setTexture-java.lang.String-com.aspose.threed.TextureBase-}
```
public void setTexture(String slotName, TextureBase texture)
```


将纹理设置到指定槽

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| slotName | java.lang.String | 槽名称。 |
|  | texture | [TextureBase](../../com.aspose.threed/texturebase) | 纹理。 **Example:** |

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_NORMAL, tex);
``` |

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


设置透明度因子。该因子的取值范围应在 0（0%，完全不透明）到 1（100%，完全透明）之间。任何无效的因子值都会被限制在范围内。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### toString() {#toString--}
```
public String toString()
```


将对象格式化为字符串

**Returns:**
java.lang.String - 对象字符串
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

