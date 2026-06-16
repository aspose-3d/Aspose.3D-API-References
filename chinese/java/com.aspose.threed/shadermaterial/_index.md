---
title: "ShaderMaterial"
second_title: "Aspose.3D for Java API 参考"
description: "着色器材质允许通过外部渲染引擎或着色器语言来描述材质。"
type: docs
weight: 164
url: /zh/java/com.aspose.threed/shadermaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class ShaderMaterial extends Material
```

着色器材质允许通过外部渲染引擎或着色器语言来描述材质。[ShaderMaterial](../../com.aspose.threed/shadermaterial) 使用 [ShaderTechnique](../../com.aspose.threed/shadertechnique) 来描述具体的渲染细节，并且会根据最终渲染平台选择最合适的技术。例如，您的 [ShaderMaterial](../../com.aspose.threed/shadermaterial) 实例可以拥有两种技术，一种由 HLSL 定义，另一种由 GLSL 定义。在非 Windows 平台上应使用 GLSL 而不是 HLSL
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ShaderMaterial()](#ShaderMaterial--) | 初始化 [ShaderMaterial](../../com.aspose.threed/shadermaterial) 类的新实例。 |
| [ShaderMaterial(String name)](#ShaderMaterial-java.lang.String-) | 初始化 [ShaderMaterial](../../com.aspose.threed/shadermaterial) 类的新实例。 |
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
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | 获取名称。 |
| [getProperties()](#getProperties--) | 获取所有属性的集合。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 获取指定属性的值 |
| [getTechniques()](#getTechniques--) | 获取此材质中定义的所有可用技术。 |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | 从指定槽获取纹理，它可以是材质的属性名称或着色器的参数名称。 |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | 获取枚举器以遍历内部纹理槽。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 移除动态属性。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 移除通过名称标识的指定属性 |
| [setName(String value)](#setName-java.lang.String-) | 设置名称。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 设置指定属性的值 |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | 将纹理设置到指定槽 |
| [toString()](#toString--) | 将对象格式化为字符串 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ShaderMaterial() {#ShaderMaterial--}
```
public ShaderMaterial()
```


初始化 [ShaderMaterial](../../com.aspose.threed/shadermaterial) 类的新实例。

### ShaderMaterial(String name) {#ShaderMaterial-java.lang.String-}
```
public ShaderMaterial(String name)
```


初始化 [ShaderMaterial](../../com.aspose.threed/shadermaterial) 类的新实例。

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getTechniques() {#getTechniques--}
```
public List<ShaderTechnique> getTechniques()
```


获取此材质中定义的所有可用技术。

**Returns:**
java.util.List<com.aspose.threed.ShaderTechnique> - 此材质中定义的所有可用技术。
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

