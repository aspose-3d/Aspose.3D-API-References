---
title: PhongMaterial
second_title: Aspose.3D for Java API 레퍼런스
description: Blinn-Phong 셰이딩 모델용 재질.
type: docs
weight: 126
url: /ko/java/com.aspose.threed/phongmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material), [com.aspose.threed.LambertMaterial](../../com.aspose.threed/lambertmaterial)
```
public class PhongMaterial extends LambertMaterial
```

Blinn-Phong 셰이딩 모델용 재질.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PhongMaterial()](#PhongMaterial--) | [PhongMaterial](../../com.aspose.threed/phongmaterial) 클래스의 새 인스턴스를 초기화합니다. |
| [PhongMaterial(String name)](#PhongMaterial-java.lang.String-) | [PhongMaterial](../../com.aspose.threed/phongmaterial) 클래스의 새 인스턴스를 초기화합니다. |
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
| [getAmbientColor()](#getAmbientColor--) | 앰비언트 색상을 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getDiffuseColor()](#getDiffuseColor--) | 디퓨즈 색상을 가져옵니다. |
| [getEmissiveColor()](#getEmissiveColor--) | 에미시브 색상을 가져옵니다. |
| [getName()](#getName--) | 이름을 가져옵니다. |
| [getProperties()](#getProperties--) | 모든 속성의 컬렉션을 가져옵니다. |
| [getProperty(String property)](#getProperty-java.lang.String-) | 지정된 속성의 값을 가져옵니다 |
| [getReflectionColor()](#getReflectionColor--) | 반사 색상을 가져옵니다. |
| [getReflectionFactor()](#getReflectionFactor--) | 반사 색상의 감쇠를 가져옵니다. |
| [getShininess()](#getShininess--) | 광택도를 가져옵니다. 이는 반사 하이라이트의 크기를 제어합니다. |
| [getSpecularColor()](#getSpecularColor--) | 스페큘러 색상을 가져옵니다. |
| [getSpecularFactor()](#getSpecularFactor--) | 스페큘러 계수를 가져옵니다. |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | 지정된 슬롯에서 텍스처를 가져옵니다. 이는 재질의 속성 이름이거나 셰이더의 파라미터 이름일 수 있습니다. |
| [getTransparency()](#getTransparency--) | 투명도 계수를 가져옵니다. |
| [getTransparentColor()](#getTransparentColor--) | 투명 색상을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | 내부 텍스처 슬롯을 열거하기 위한 열거자를 가져옵니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 동적 속성을 제거합니다. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 이름으로 식별되는 지정된 속성을 제거합니다. |
| [setAmbientColor(Vector3 value)](#setAmbientColor-com.aspose.threed.Vector3-) | 앰비언트 색상을 설정합니다. |
| [setDiffuseColor(Vector3 value)](#setDiffuseColor-com.aspose.threed.Vector3-) | 디퓨즈 색상을 설정합니다. |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | 에미시브 색상을 설정합니다. |
| [setName(String value)](#setName-java.lang.String-) | 이름을 설정합니다. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 지정된 속성의 값을 설정합니다. |
| [setReflectionColor(Vector3 value)](#setReflectionColor-com.aspose.threed.Vector3-) | 반사 색상을 설정합니다. |
| [setReflectionFactor(double value)](#setReflectionFactor-double-) | 반사 색상의 감쇠를 설정합니다. |
| [setShininess(double value)](#setShininess-double-) | 광택을 설정합니다. 이는 반사 하이라이트의 크기를 제어합니다. |
| [setSpecularColor(Vector3 value)](#setSpecularColor-com.aspose.threed.Vector3-) | 반사 색상을 설정합니다. |
| [setSpecularFactor(double value)](#setSpecularFactor-double-) | 반사 계수를 설정합니다. |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | 텍스처를 지정된 슬롯에 설정합니다. |
| [setTransparency(double value)](#setTransparency-double-) | 투명도 계수를 설정합니다. |
| [setTransparentColor(Vector3 value)](#setTransparentColor-com.aspose.threed.Vector3-) | 투명 색상을 설정합니다. |
| [toString()](#toString--) | 객체를 문자열로 포맷합니다 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PhongMaterial() {#PhongMaterial--}
```
public PhongMaterial()
```


[PhongMaterial](../../com.aspose.threed/phongmaterial) 클래스의 새 인스턴스를 초기화합니다.

### PhongMaterial(String name) {#PhongMaterial-java.lang.String-}
```
public PhongMaterial(String name)
```


[PhongMaterial](../../com.aspose.threed/phongmaterial) 클래스의 새 인스턴스를 초기화합니다.

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
### getAmbientColor() {#getAmbientColor--}
```
public Vector3 getAmbientColor()
```


앰비언트 색상을 가져옵니다.

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


디퓨즈 색상을 가져옵니다.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the diffuse color
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


에미시브 색상을 가져옵니다.

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
### getReflectionColor() {#getReflectionColor--}
```
public Vector3 getReflectionColor()
```


반사 색상을 가져옵니다.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the reflection color.
### getReflectionFactor() {#getReflectionFactor--}
```
public double getReflectionFactor()
```


반사 색상의 감쇠를 가져옵니다.

**Returns:**
double - 반사 색상의 감쇠.
### getShininess() {#getShininess--}
```
public double getShininess()
```


광택을 가져옵니다. 이는 반사 하이라이트의 크기를 제어합니다. 반사 공식: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Returns:**
double - 광택, 이는 반사 하이라이트의 크기를 제어합니다. 반사 공식: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess
### getSpecularColor() {#getSpecularColor--}
```
public Vector3 getSpecularColor()
```


스페큘러 색상을 가져옵니다.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the specular color.
### getSpecularFactor() {#getSpecularFactor--}
```
public double getSpecularFactor()
```


반사 계수를 가져옵니다. 반사 공식: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Returns:**
double - 반사 계수. 반사 공식: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess
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
### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


투명도 계수를 가져옵니다. 계수는 0(0%, 완전히 불투명)과 1(100%, 완전히 투명) 사이여야 합니다. 잘못된 계수 값은 클램프됩니다.

**Returns:**
double - 투명도 계수. 계수는 0(0%, 완전히 불투명)과 1(100%, 완전히 투명) 사이여야 합니다. 잘못된 계수 값은 클램프됩니다.
### getTransparentColor() {#getTransparentColor--}
```
public Vector3 getTransparentColor()
```


투명 색상을 가져옵니다.

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
### setAmbientColor(Vector3 value) {#setAmbientColor-com.aspose.threed.Vector3-}
```
public void setAmbientColor(Vector3 value)
```


앰비언트 색상을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 새 값 |

### setDiffuseColor(Vector3 value) {#setDiffuseColor-com.aspose.threed.Vector3-}
```
public void setDiffuseColor(Vector3 value)
```


디퓨즈 색상을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 새 값 |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


에미시브 색상을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | 새 값 **Example:** |

```
var mat = new LambertMaterial();
     mat.setEmissiveColor(new Vector3(1, 1, 1));
``` |

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

### setReflectionColor(Vector3 value) {#setReflectionColor-com.aspose.threed.Vector3-}
```
public void setReflectionColor(Vector3 value)
```


반사 색상을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 새 값 |

### setReflectionFactor(double value) {#setReflectionFactor-double-}
```
public void setReflectionFactor(double value)
```


반사 색상의 감쇠를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 |

### setShininess(double value) {#setShininess-double-}
```
public void setShininess(double value)
```


광택을 설정합니다. 이는 반사 하이라이트의 크기를 제어합니다. 반사 공식: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 |

### setSpecularColor(Vector3 value) {#setSpecularColor-com.aspose.threed.Vector3-}
```
public void setSpecularColor(Vector3 value)
```


반사 색상을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 새 값 |

### setSpecularFactor(double value) {#setSpecularFactor-double-}
```
public void setSpecularFactor(double value)
```


반사 계수를 설정합니다. 반사 공식: SpecularColor \* SpecularFactor \* (N dot H) ^ Shininess

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 |

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

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


투명도 계수를 설정합니다. 계수는 0(0%, 완전히 불투명)과 1(100%, 완전히 투명) 사이여야 합니다. 잘못된 계수 값은 클램프됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 |

### setTransparentColor(Vector3 value) {#setTransparentColor-com.aspose.threed.Vector3-}
```
public void setTransparentColor(Vector3 value)
```


투명 색상을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 새 값 |

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

