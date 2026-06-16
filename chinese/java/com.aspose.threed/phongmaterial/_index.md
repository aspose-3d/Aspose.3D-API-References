---
title: "PhongMaterial"
second_title: "Aspose.3D for Java API 参考"
description: "用于 Blinn-Phong 着色模型的材质。"
type: docs
weight: 126
url: /zh/java/com.aspose.threed/phongmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material), [com.aspose.threed.LambertMaterial](../../com.aspose.threed/lambertmaterial)
```
public class PhongMaterial extends LambertMaterial
```

用于 Blinn-Phong 着色模型的材质。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PhongMaterial()](#PhongMaterial--) | 初始化 [PhongMaterial](../../com.aspose.threed/phongmaterial) 类的新实例。 |
| [PhongMaterial(String name)](#PhongMaterial-java.lang.String-) | 初始化 [PhongMaterial](../../com.aspose.threed/phongmaterial) 类的新实例。 |
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
| [getAmbientColor()](#getAmbientColor--) | 获取环境颜色 |
| [getClass()](#getClass--) |  |
| [getDiffuseColor()](#getDiffuseColor--) | 获取漫反射颜色 |
| [getEmissiveColor()](#getEmissiveColor--) | 获取自发光颜色 |
| [getName()](#getName--) | 获取名称。 |
| [getProperties()](#getProperties--) | 获取所有属性的集合。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 获取指定属性的值 |
| [getReflectionColor()](#getReflectionColor--) | 获取反射颜色。 |
| [getReflectionFactor()](#getReflectionFactor--) | 获取反射颜色的衰减。 |
| [getShininess()](#getShininess--) | 获取光泽度，这决定了高光的大小。 |
| [getSpecularColor()](#getSpecularColor--) | 获取镜面反射颜色。 |
| [getSpecularFactor()](#getSpecularFactor--) | 获取镜面反射因子。 |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | 从指定槽获取纹理，它可以是材质的属性名称或着色器的参数名称。 |
| [getTransparency()](#getTransparency--) | 获取透明度因子。 |
| [getTransparentColor()](#getTransparentColor--) | 获取透明颜色。 |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | 获取枚举器以遍历内部纹理槽。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 移除动态属性。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 移除通过名称标识的指定属性 |
| [setAmbientColor(Vector3 value)](#setAmbientColor-com.aspose.threed.Vector3-) | 设置环境颜色 |
| [setDiffuseColor(Vector3 value)](#setDiffuseColor-com.aspose.threed.Vector3-) | 设置漫反射颜色 |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | 设置自发光颜色 |
| [setName(String value)](#setName-java.lang.String-) | 设置名称。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 设置指定属性的值 |
| [setReflectionColor(Vector3 value)](#setReflectionColor-com.aspose.threed.Vector3-) | 设置反射颜色。 |
| [setReflectionFactor(double value)](#setReflectionFactor-double-) | 设置反射颜色的衰减。 |
| [setShininess(double value)](#setShininess-double-) | 设置光泽度，此参数控制高光的大小。 |
| [setSpecularColor(Vector3 value)](#setSpecularColor-com.aspose.threed.Vector3-) | 设置镜面反射颜色。 |
| [setSpecularFactor(double value)](#setSpecularFactor-double-) | 设置镜面反射因子。 |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | 将纹理设置到指定槽 |
| [setTransparency(double value)](#setTransparency-double-) | 设置透明度因子。 |
| [setTransparentColor(Vector3 value)](#setTransparentColor-com.aspose.threed.Vector3-) | 设置透明颜色。 |
| [toString()](#toString--) | 将对象格式化为字符串 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PhongMaterial() {#PhongMaterial--}
```
public PhongMaterial()
```


初始化 [PhongMaterial](../../com.aspose.threed/phongmaterial) 类的新实例。

### PhongMaterial(String name) {#PhongMaterial-java.lang.String-}
```
public PhongMaterial(String name)
```


初始化 [PhongMaterial](../../com.aspose.threed/phongmaterial) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | java.lang.String | 名称 |

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
### getAmbientColor() {#getAmbientColor--}
```
public Vector3 getAmbientColor()
```


获取环境颜色

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the ambient color
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDiffuseColor() {#getDiffuseColor--}
```
public Vector3 getDiffuseColor()
```


获取漫反射颜色

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the diffuse color
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


获取自发光颜色

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color **Example:**

```
var mat = new LambertMaterial();
     mat.setEmissiveColor(new Vector3(1, 1, 1));
```
### getName() {#getName--}
```
public String getName()
```


获取名称。

**Returns:**
java.lang.String - 名称。
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
### getReflectionColor() {#getReflectionColor--}
```
public Vector3 getReflectionColor()
```


获取反射颜色。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the reflection color.
### getReflectionFactor() {#getReflectionFactor--}
```
public double getReflectionFactor()
```


获取反射颜色的衰减。

**Returns:**
double - 反射颜色的衰减。
### getShininess() {#getShininess--}
```
public double getShininess()
```


获取光泽度，此参数控制高光的大小。镜面反射公式：SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Returns:**
double - 光泽度，此参数控制高光的大小。镜面反射公式：SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess
### getSpecularColor() {#getSpecularColor--}
```
public Vector3 getSpecularColor()
```


获取镜面反射颜色。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the specular color.
### getSpecularFactor() {#getSpecularFactor--}
```
public double getSpecularFactor()
```


获取镜面反射因子。镜面反射公式：SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Returns:**
double - 镜面反射因子。镜面反射公式：SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess
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
### getTransparentColor() {#getTransparentColor--}
```
public Vector3 getTransparentColor()
```


获取透明颜色。

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the transparent color.
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
### setAmbientColor(Vector3 value) {#setAmbientColor-com.aspose.threed.Vector3-}
```
public void setAmbientColor(Vector3 value)
```


设置环境颜色

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新值 |

### setDiffuseColor(Vector3 value) {#setDiffuseColor-com.aspose.threed.Vector3-}
```
public void setDiffuseColor(Vector3 value)
```


设置漫反射颜色

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新值 |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


设置自发光颜色

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | 新值 **Example:** |

```
var mat = new LambertMaterial();
     mat.setEmissiveColor(new Vector3(1, 1, 1));
``` |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


设置名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String | 新值 |

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

### setReflectionColor(Vector3 value) {#setReflectionColor-com.aspose.threed.Vector3-}
```
public void setReflectionColor(Vector3 value)
```


设置反射颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新值 |

### setReflectionFactor(double value) {#setReflectionFactor-double-}
```
public void setReflectionFactor(double value)
```


设置反射颜色的衰减。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setShininess(double value) {#setShininess-double-}
```
public void setShininess(double value)
```


设置光泽度，此参数控制高光的大小。镜面反射公式：SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

### setSpecularColor(Vector3 value) {#setSpecularColor-com.aspose.threed.Vector3-}
```
public void setSpecularColor(Vector3 value)
```


设置镜面反射颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新值 |

### setSpecularFactor(double value) {#setSpecularFactor-double-}
```
public void setSpecularFactor(double value)
```


设置镜面反射因子。镜面反射公式：SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | double | 新值 |

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

### setTransparentColor(Vector3 value) {#setTransparentColor-com.aspose.threed.Vector3-}
```
public void setTransparentColor(Vector3 value)
```


设置透明颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 新值 |

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

