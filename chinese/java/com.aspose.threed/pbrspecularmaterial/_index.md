---
title: "PbrSpecularMaterial"
second_title: "Aspose.3D for Java API 参考"
description: "基于漫反射颜色/高光/光泽度的物理渲染材质"
type: docs
weight: 122
url: /zh/java/com.aspose.threed/pbrspecularmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class PbrSpecularMaterial extends Material
```

基于漫反射颜色/高光/光泽度的物理渲染材质
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PbrSpecularMaterial()](#PbrSpecularMaterial--) | [PbrSpecularMaterial](../../com.aspose.threed/pbrspecularmaterial) 的构造函数 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [MAP_AMBIENT](#MAP-AMBIENT) | 在 [setTexture](../../com.aspose.threed/material\#setTexture) 中用于分配环境纹理映射。 |
| [MAP_DIFFUSE](#MAP-DIFFUSE) | 在 [setTexture](../../com.aspose.threed/material\#setTexture) 中用于分配漫反射纹理映射。 |
| [MAP_EMISSIVE](#MAP-EMISSIVE) | 在 [setTexture](../../com.aspose.threed/material\#setTexture) 中用于分配自发光纹理映射。 |
| [MAP_NORMAL](#MAP-NORMAL) | 在 [setTexture](../../com.aspose.threed/material\#setTexture) 中用于分配法线纹理映射。 |
| [MAP_SPECULAR](#MAP-SPECULAR) | 在 [setTexture](../../com.aspose.threed/material\#setTexture) 中用于分配高光纹理映射。 |
| [MAP_SPECULAR_GLOSSINESS](#MAP-SPECULAR-GLOSSINESS) | 用于高光光泽的纹理贴图 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 查找属性。 |
| [getClass()](#getClass--) |  |
| [getDiffuse()](#getDiffuse--) | 获取材质的漫反射颜色，默认值为 (1, 1, 1) |
| [getDiffuseTexture()](#getDiffuseTexture--) | 获取漫反射纹理 |
| [getEmissiveColor()](#getEmissiveColor--) | 获取自发光颜色，默认值为 (0, 0, 0) |
| [getEmissiveTexture()](#getEmissiveTexture--) | 获取自发光纹理 |
| [getGlossinessFactor()](#getGlossinessFactor--) | 获取材质的光泽度（光滑度），1 表示完全光滑，0 表示完全粗糙，默认值为 1，范围为 [0, 1] |
| [getName()](#getName--) | 获取名称。 |
| [getNormalTexture()](#getNormalTexture--) | 获取法线贴图纹理 |
| [getProperties()](#getProperties--) | 获取所有属性的集合。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 获取指定属性的值 |
| [getSpecular()](#getSpecular--) | 获取材质的高光颜色，默认值为 (1, 1, 1)。 |
| [getSpecularGlossinessTexture()](#getSpecularGlossinessTexture--) | 获取高光颜色纹理，RGB 通道存储高光颜色，A 通道存储光泽度。 |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | 从指定槽获取纹理，它可以是材质的属性名称或着色器的参数名称。 |
| [getTransparency()](#getTransparency--) | 获取透明度因子。 |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | 获取枚举器以遍历内部纹理槽。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 移除动态属性。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 移除通过名称标识的指定属性 |
| [setDiffuse(Vector3 value)](#setDiffuse-com.aspose.threed.Vector3-) | 设置材质的漫反射颜色，默认值为 (1, 1, 1) |
| [setDiffuseTexture(TextureBase value)](#setDiffuseTexture-com.aspose.threed.TextureBase-) | 设置漫反射纹理 |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | 设置自发光颜色，默认值为 (0, 0, 0) |
| [setEmissiveTexture(TextureBase value)](#setEmissiveTexture-com.aspose.threed.TextureBase-) | 设置自发光的纹理 |
| [setGlossinessFactor(double value)](#setGlossinessFactor-double-) | 设置材质的光泽度（光滑度），1 表示完全光滑，0 表示完全粗糙，默认值为 1，范围为 [0, 1] |
| [setName(String value)](#setName-java.lang.String-) | 设置名称。 |
| [setNormalTexture(TextureBase value)](#setNormalTexture-com.aspose.threed.TextureBase-) | 设置法线贴图的纹理 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 设置指定属性的值 |
| [setSpecular(Vector3 value)](#setSpecular-com.aspose.threed.Vector3-) | 设置材质的高光颜色，默认值为 (1, 1, 1)。 |
| [setSpecularGlossinessTexture(TextureBase value)](#setSpecularGlossinessTexture-com.aspose.threed.TextureBase-) | 设置高光颜色的纹理，RGB 通道存储高光颜色，A 通道存储光泽度。 |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | 将纹理设置到指定槽 |
| [setTransparency(double value)](#setTransparency-double-) | 设置透明度因子。 |
| [toString()](#toString--) | 将对象格式化为字符串 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PbrSpecularMaterial() {#PbrSpecularMaterial--}
```
public PbrSpecularMaterial()
```


[PbrSpecularMaterial](../../com.aspose.threed/pbrspecularmaterial) 的构造函数

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

### MAP_SPECULAR_GLOSSINESS {#MAP-SPECULAR-GLOSSINESS}
```
public static final String MAP_SPECULAR_GLOSSINESS
```


用于高光光泽的纹理贴图

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDiffuse() {#getDiffuse--}
```
public Vector3 getDiffuse()
```


获取材质的漫反射颜色，默认值为 (1, 1, 1)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the diffuse color of the material, default value is (1, 1, 1)
### getDiffuseTexture() {#getDiffuseTexture--}
```
public TextureBase getDiffuseTexture()
```


获取漫反射纹理

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for diffuse
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


获取自发光颜色，默认值为 (0, 0, 0)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color, default value is (0, 0, 0)
### getEmissiveTexture() {#getEmissiveTexture--}
```
public TextureBase getEmissiveTexture()
```


获取自发光纹理

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for emissive
### getGlossinessFactor() {#getGlossinessFactor--}
```
public double getGlossinessFactor()
```


获取材质的光泽度（光滑度），1 表示完全光滑，0 表示完全粗糙，默认值为 1，范围为 [0, 1]

**Returns:**
double - 材质的光泽度（光滑度），1 表示完全光滑，0 表示完全粗糙，默认值为 1，范围为 [0, 1]
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
### getSpecular() {#getSpecular--}
```
public Vector3 getSpecular()
```


获取材质的高光颜色，默认值为 (1, 1, 1)。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the specular color of the material, default value is (1, 1, 1).
### getSpecularGlossinessTexture() {#getSpecularGlossinessTexture--}
```
public TextureBase getSpecularGlossinessTexture()
```


获取高光颜色纹理，RGB 通道存储高光颜色，A 通道存储光泽度。

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for specular color, channel RGB stores the specular color and channel A stores the glossiness.
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
### setDiffuse(Vector3 value) {#setDiffuse-com.aspose.threed.Vector3-}
```
public void setDiffuse(Vector3 value)
```


设置材质的漫反射颜色，默认值为 (1, 1, 1)

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新值 |

### setDiffuseTexture(TextureBase value) {#setDiffuseTexture-com.aspose.threed.TextureBase-}
```
public void setDiffuseTexture(TextureBase value)
```


设置漫反射纹理

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | 新值 |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


设置自发光颜色，默认值为 (0, 0, 0)

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

### setGlossinessFactor(double value) {#setGlossinessFactor-double-}
```
public void setGlossinessFactor(double value)
```


设置材质的光泽度（光滑度），1 表示完全光滑，0 表示完全粗糙，默认值为 1，范围为 [0, 1]

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

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

### setSpecular(Vector3 value) {#setSpecular-com.aspose.threed.Vector3-}
```
public void setSpecular(Vector3 value)
```


设置材质的高光颜色，默认值为 (1, 1, 1)。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新值 |

### setSpecularGlossinessTexture(TextureBase value) {#setSpecularGlossinessTexture-com.aspose.threed.TextureBase-}
```
public void setSpecularGlossinessTexture(TextureBase value)
```


设置高光颜色的纹理，RGB 通道存储高光颜色，A 通道存储光泽度。

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

