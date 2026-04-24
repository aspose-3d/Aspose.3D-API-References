---
title: ShaderMaterial
second_title: Aspose.3D for Java API 레퍼런스
description: 셰이더 머티리얼은 외부 렌더링 엔진이나 셰이더 언어를 사용하여 머티리얼을 설명할 수 있게 합니다.
type: docs
weight: 164
url: /ko/java/com.aspose.threed/shadermaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class ShaderMaterial extends Material
```

셰이더 재질은 외부 렌더링 엔진이나 셰이더 언어를 사용하여 재질을 설명할 수 있게 합니다. [ShaderMaterial](../../com.aspose.threed/shadermaterial)은 구체적인 렌더링 세부 정보를 설명하기 위해 [ShaderTechnique](../../com.aspose.threed/shadertechnique)을 사용하며, 최종 렌더링 플랫폼에 따라 가장 적합한 것이 사용됩니다. 예를 들어, 사용자의 [ShaderMaterial](../../com.aspose.threed/shadermaterial) 인스턴스는 두 가지 기술을 가질 수 있는데, 하나는 HLSL로 정의되고 다른 하나는 GLSL로 정의됩니다. 비윈도우 플랫폼에서는 HLSL 대신 GLSL을 사용해야 합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ShaderMaterial()](#ShaderMaterial--) | [ShaderMaterial](../../com.aspose.threed/shadermaterial) 클래스의 새 인스턴스를 초기화합니다. |
| [ShaderMaterial(String name)](#ShaderMaterial-java.lang.String-) | [ShaderMaterial](../../com.aspose.threed/shadermaterial) 클래스의 새 인스턴스를 초기화합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [MAP_AMBIENT](#MAP-AMBIENT) | [setTexture](../../com.aspose.threed/material\#setTexture)에서 앰비언트 텍스처 매핑을 할당하는 데 사용됩니다. |
| [MAP_DIFFUSE](#MAP-DIFFUSE) | [setTexture](../../com.aspose.threed/material\#setTexture)에서 디퓨즈 텍스처 매핑을 할당하는 데 사용됩니다. |
| [MAP_EMISSIVE](#MAP-EMISSIVE) | [setTexture](../../com.aspose.threed/material\#setTexture)에서 에미시브 텍스처 매핑을 할당하는 데 사용됩니다. |
| [MAP_NORMAL](#MAP-NORMAL) | [setTexture](../../com.aspose.threed/material\#setTexture)에서 노멀 텍스처 매핑을 할당하는 데 사용됩니다. |
| [MAP_SPECULAR](#MAP-SPECULAR) | [setTexture](../../com.aspose.threed/material\#setTexture)에서 스페큘러 텍스처 매핑을 할당하는 데 사용됩니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 속성을 찾습니다. |
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | 이름을 가져옵니다. |
| [getProperties()](#getProperties--) | 모든 속성의 컬렉션을 가져옵니다. |
| [getProperty(String property)](#getProperty-java.lang.String-) | 지정된 속성의 값을 가져옵니다 |
| [getTechniques()](#getTechniques--) | 이 재질에 정의된 모든 사용 가능한 기술을 가져옵니다. |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | 지정된 슬롯에서 텍스처를 가져옵니다. 이는 재질의 속성 이름이거나 셰이더의 파라미터 이름일 수 있습니다. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | 내부 텍스처 슬롯을 열거하기 위한 열거자를 가져옵니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 동적 속성을 제거합니다. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 이름으로 식별되는 지정된 속성을 제거합니다. |
| [setName(String value)](#setName-java.lang.String-) | 이름을 설정합니다. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 지정된 속성의 값을 설정합니다. |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | 텍스처를 지정된 슬롯에 설정합니다. |
| [toString()](#toString--) | 객체를 문자열로 포맷합니다 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ShaderMaterial() {#ShaderMaterial--}
```
public ShaderMaterial()
```


[ShaderMaterial](../../com.aspose.threed/shadermaterial) 클래스의 새 인스턴스를 초기화합니다.

### ShaderMaterial(String name) {#ShaderMaterial-java.lang.String-}
```
public ShaderMaterial(String name)
```


[ShaderMaterial](../../com.aspose.threed/shadermaterial) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 이름 |

### MAP_AMBIENT {#MAP-AMBIENT}
```
public static final String MAP_AMBIENT
```


[setTexture](../../com.aspose.threed/material\#setTexture)에서 앰비언트 텍스처 매핑을 할당하는 데 사용됩니다.

### MAP_DIFFUSE {#MAP-DIFFUSE}
```
public static final String MAP_DIFFUSE
```


[setTexture](../../com.aspose.threed/material\#setTexture)에서 디퓨즈 텍스처 매핑을 할당하는 데 사용됩니다.

### MAP_EMISSIVE {#MAP-EMISSIVE}
```
public static final String MAP_EMISSIVE
```


[setTexture](../../com.aspose.threed/material\#setTexture)에서 에미시브 텍스처 매핑을 할당하는 데 사용됩니다.

### MAP_NORMAL {#MAP-NORMAL}
```
public static final String MAP_NORMAL
```


[setTexture](../../com.aspose.threed/material\#setTexture)에서 노멀 텍스처 매핑을 할당하는 데 사용됩니다.

### MAP_SPECULAR {#MAP-SPECULAR}
```
public static final String MAP_SPECULAR
```


[setTexture](../../com.aspose.threed/material\#setTexture)에서 스페큘러 텍스처 매핑을 할당하는 데 사용됩니다.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


속성을 찾습니다. 동적 속성 (Created by CreateDynamicProperty/SetProperty) 또는 네이티브 속성 (Identified by its name)일 수 있습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| propertyName | java.lang.String | 속성 이름. |

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


이름을 가져옵니다.

**Returns:**
java.lang.String - 이름.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


모든 속성의 컬렉션을 가져옵니다.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


지정된 속성의 값을 가져옵니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 속성 | java.lang.String | 속성 이름 |

**Returns:**
java.lang.Object - 찾은 속성의 값
### getTechniques() {#getTechniques--}
```
public List<ShaderTechnique> getTechniques()
```


이 재질에 정의된 모든 사용 가능한 기술을 가져옵니다.

**Returns:**
java.util.List<com.aspose.threed.ShaderTechnique> - 이 재질에 정의된 모든 사용 가능한 기술.
### getTexture(String slotName) {#getTexture-java.lang.String-}
```
public TextureBase getTexture(String slotName)
```


지정된 슬롯에서 텍스처를 가져옵니다. 이는 재질의 속성 이름이거나 셰이더의 파라미터 이름일 수 있습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| slotName | java.lang.String | 슬롯 이름. |

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


내부 텍스처 슬롯을 열거하기 위한 열거자를 가져옵니다.

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


동적 속성을 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | 제거할 속성 |

**Returns:**
boolean - 속성이 성공적으로 제거되면 true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


이름으로 식별되는 지정된 속성을 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 속성 | java.lang.String | 제거할 속성 |

**Returns:**
boolean - 속성이 성공적으로 제거되면 true
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


이름을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


지정된 속성의 값을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 속성 | java.lang.String | 속성 이름 |
| 값 | java.lang.Object | 속성의 값 |

### setTexture(String slotName, TextureBase texture) {#setTexture-java.lang.String-com.aspose.threed.TextureBase-}
```
public void setTexture(String slotName, TextureBase texture)
```


텍스처를 지정된 슬롯에 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| slotName | java.lang.String | 슬롯 이름. |
|  | texture | [TextureBase](../../com.aspose.threed/texturebase) | 텍스처. **Example:** |

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


객체를 문자열로 포맷합니다

**Returns:**
java.lang.String - 객체 문자열
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

