---
title: PbrMaterial
second_title: Aspose.3D for Java API 레퍼런스
description: 알베도 색상/금속성/거칠기를 기반으로 하는 물리 기반 렌더링용 재질.
type: docs
weight: 121
url: /ko/java/com.aspose.threed/pbrmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class PbrMaterial extends Material
```

알베도 색상/금속성/거칠기를 기반으로 하는 물리 기반 렌더링용 재질.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [PbrMaterial()](#PbrMaterial--) | 기본 PBR 재질 인스턴스를 생성합니다 |
| [PbrMaterial(Vector3 albedo)](#PbrMaterial-com.aspose.threed.Vector3-) | 지정된 알베도 색상 값을 사용하여 기본 PBR 재질을 생성합니다 |
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
| [fromMaterial(Material material)](#fromMaterial-com.aspose.threed.Material-) | 다른 재질을 PbrMaterial 로 변환하도록 허용합니다 **Example:** |
| [getAlbedo()](#getAlbedo--) | 재질의 기본 색상을 가져옵니다 |
| [getAlbedoTexture()](#getAlbedoTexture--) | 알베도 텍스처를 가져옵니다 |
| [getClass()](#getClass--) |  |
| [getEmissiveColor()](#getEmissiveColor--) | 에미시브 색상을 가져옵니다. |
| [getEmissiveTexture()](#getEmissiveTexture--) | 방출용 텍스처를 가져옵니다. |
| [getMetallicFactor()](#getMetallicFactor--) | 재질의 금속성을 가져옵니다, 값이 1이면 재질이 금속이고 값이 0이면 재질이 유전체임을 의미합니다. |
| [getMetallicRoughness()](#getMetallicRoughness--) | 금속성(빨간색 채널) 및 거칠기(초록색 채널) 텍스처를 가져옵니다 |
| [getName()](#getName--) | 이름을 가져옵니다. |
| [getNormalTexture()](#getNormalTexture--) | 노멀 매핑 텍스처를 가져옵니다. |
| [getOcclusionFactor()](#getOcclusionFactor--) | 앰비언트 오클루전 계수를 가져옵니다 |
| [getOcclusionTexture()](#getOcclusionTexture--) | 앰비언트 오클루전 텍스처를 가져옵니다 |
| [getProperties()](#getProperties--) | 모든 속성의 컬렉션을 가져옵니다. |
| [getProperty(String property)](#getProperty-java.lang.String-) | 지정된 속성의 값을 가져옵니다 |
| [getRoughnessFactor()](#getRoughnessFactor--) | 재질의 거칠기를 가져옵니다, 값이 1이면 재질이 완전히 거칠고 값이 0이면 재질이 완전히 매끄럽습니다 |
| [getSpecularTexture()](#getSpecularTexture--) | 스페큘러 색상 텍스처를 가져옵니다 |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | 지정된 슬롯에서 텍스처를 가져옵니다. 이는 재질의 속성 이름이거나 셰이더의 파라미터 이름일 수 있습니다. |
| [getTransparency()](#getTransparency--) | 투명도 계수를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | 내부 텍스처 슬롯을 열거하기 위한 열거자를 가져옵니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 동적 속성을 제거합니다. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 이름으로 식별되는 지정된 속성을 제거합니다. |
| [setAlbedo(Vector3 value)](#setAlbedo-com.aspose.threed.Vector3-) | 재질의 기본 색상을 설정합니다 |
| [setAlbedoTexture(TextureBase value)](#setAlbedoTexture-com.aspose.threed.TextureBase-) | 알베도 텍스처를 설정합니다 |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | 에미시브 색상을 설정합니다. |
| [setEmissiveTexture(TextureBase value)](#setEmissiveTexture-com.aspose.threed.TextureBase-) | 방출용 텍스처를 설정합니다 |
| [setMetallicFactor(double value)](#setMetallicFactor-double-) | 재질의 금속성을 설정합니다. 값이 1이면 재질이 금속이고 값이 0이면 재질이 유전체임을 의미합니다. |
| [setMetallicRoughness(TextureBase value)](#setMetallicRoughness-com.aspose.threed.TextureBase-) | 금속성(빨간색 채널) 및 거칠기(녹색 채널) 텍스처를 설정합니다 |
| [setName(String value)](#setName-java.lang.String-) | 이름을 설정합니다. |
| [setNormalTexture(TextureBase value)](#setNormalTexture-com.aspose.threed.TextureBase-) | 노멀 매핑 텍스처를 설정합니다 |
| [setOcclusionFactor(double value)](#setOcclusionFactor-double-) | 앰비언트 오클루전 계수를 설정합니다 |
| [setOcclusionTexture(TextureBase value)](#setOcclusionTexture-com.aspose.threed.TextureBase-) | 앰비언트 오클루전 텍스처를 설정합니다 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 지정된 속성의 값을 설정합니다. |
| [setRoughnessFactor(double value)](#setRoughnessFactor-double-) | 재질의 거칠기를 설정합니다. 값이 1이면 재질이 완전히 거칠고 값이 0이면 재질이 완전히 매끈함을 의미합니다. |
| [setSpecularTexture(TextureBase value)](#setSpecularTexture-com.aspose.threed.TextureBase-) | 반사광 색상 텍스처를 설정합니다 |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | 텍스처를 지정된 슬롯에 설정합니다. |
| [setTransparency(double value)](#setTransparency-double-) | 투명도 계수를 설정합니다. |
| [toString()](#toString--) | 객체를 문자열로 포맷합니다 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PbrMaterial() {#PbrMaterial--}
```
public PbrMaterial()
```


기본 PBR 재질 인스턴스를 생성합니다

### PbrMaterial(Vector3 albedo) {#PbrMaterial-com.aspose.threed.Vector3-}
```
public PbrMaterial(Vector3 albedo)
```


지정된 알베도 색상 값을 사용하여 기본 PBR 재질을 생성합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| albedo | [Vector3](../../com.aspose.threed/vector3) | 기본 알베도 색상 값 |

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
### fromMaterial(Material material) {#fromMaterial-com.aspose.threed.Material-}
```
public static PbrMaterial fromMaterial(Material material)
```


다른 재질을 PbrMaterial 로 변환하도록 허용합니다 **Example:**

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_DIFFUSE, tex);
     mat.setDiffuseColor(new Vector3(0.3, 0.9, 0.4));
     PbrMaterial pbr = PbrMaterial.fromMaterial(mat);
```

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| material | [Material](../../com.aspose.threed/material) |  |

**Returns:**
[PbrMaterial](../../com.aspose.threed/pbrmaterial)
### getAlbedo() {#getAlbedo--}
```
public Vector3 getAlbedo()
```


재질의 기본 색상을 가져옵니다

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the base color of the material
### getAlbedoTexture() {#getAlbedoTexture--}
```
public TextureBase getAlbedoTexture()
```


알베도 텍스처를 가져옵니다

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


에미시브 색상을 가져옵니다.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color
### getEmissiveTexture() {#getEmissiveTexture--}
```
public TextureBase getEmissiveTexture()
```


방출용 텍스처를 가져옵니다.

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for emissive
### getMetallicFactor() {#getMetallicFactor--}
```
public double getMetallicFactor()
```


재질의 금속성을 가져옵니다, 값이 1이면 재질이 금속이고 값이 0이면 재질이 유전체임을 의미합니다.

**Returns:**
double - 재질의 금속성, 값이 1이면 재질이 금속이고 값이 0이면 재질이 유전체임을 의미합니다.
### getMetallicRoughness() {#getMetallicRoughness--}
```
public TextureBase getMetallicRoughness()
```


금속성(빨간색 채널) 및 거칠기(초록색 채널) 텍스처를 가져옵니다

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for metallic(in R channel) and roughness(in G channel)
### getName() {#getName--}
```
public String getName()
```


이름을 가져옵니다.

**Returns:**
java.lang.String - 이름.
### getNormalTexture() {#getNormalTexture--}
```
public TextureBase getNormalTexture()
```


노멀 매핑 텍스처를 가져옵니다.

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture of normal mapping
### getOcclusionFactor() {#getOcclusionFactor--}
```
public double getOcclusionFactor()
```


앰비언트 오클루전 계수를 가져옵니다

**Returns:**
double - 앰비언트 오클루전 계수
### getOcclusionTexture() {#getOcclusionTexture--}
```
public TextureBase getOcclusionTexture()
```


앰비언트 오클루전 텍스처를 가져옵니다

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for ambient occlusion
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
### getRoughnessFactor() {#getRoughnessFactor--}
```
public double getRoughnessFactor()
```


재질의 거칠기를 가져옵니다, 값이 1이면 재질이 완전히 거칠고 값이 0이면 재질이 완전히 매끄럽습니다

**Returns:**
double - 재질의 거칠기, 값이 1이면 재질이 완전히 거칠고 값이 0이면 재질이 완전히 매끈함을 의미합니다.
### getSpecularTexture() {#getSpecularTexture--}
```
public TextureBase getSpecularTexture()
```


스페큘러 색상 텍스처를 가져옵니다

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for specular color
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
### setAlbedo(Vector3 value) {#setAlbedo-com.aspose.threed.Vector3-}
```
public void setAlbedo(Vector3 value)
```


재질의 기본 색상을 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 새 값 |

### setAlbedoTexture(TextureBase value) {#setAlbedoTexture-com.aspose.threed.TextureBase-}
```
public void setAlbedoTexture(TextureBase value)
```


알베도 텍스처를 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | 새 값 |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


에미시브 색상을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 새 값 |

### setEmissiveTexture(TextureBase value) {#setEmissiveTexture-com.aspose.threed.TextureBase-}
```
public void setEmissiveTexture(TextureBase value)
```


방출용 텍스처를 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | 새 값 |

### setMetallicFactor(double value) {#setMetallicFactor-double-}
```
public void setMetallicFactor(double value)
```


재질의 금속성을 설정합니다. 값이 1이면 재질이 금속이고 값이 0이면 재질이 유전체임을 의미합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 |

### setMetallicRoughness(TextureBase value) {#setMetallicRoughness-com.aspose.threed.TextureBase-}
```
public void setMetallicRoughness(TextureBase value)
```


금속성(빨간색 채널) 및 거칠기(녹색 채널) 텍스처를 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | 새 값 |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


이름을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setNormalTexture(TextureBase value) {#setNormalTexture-com.aspose.threed.TextureBase-}
```
public void setNormalTexture(TextureBase value)
```


노멀 매핑 텍스처를 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | 새 값 |

### setOcclusionFactor(double value) {#setOcclusionFactor-double-}
```
public void setOcclusionFactor(double value)
```


앰비언트 오클루전 계수를 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 |

### setOcclusionTexture(TextureBase value) {#setOcclusionTexture-com.aspose.threed.TextureBase-}
```
public void setOcclusionTexture(TextureBase value)
```


앰비언트 오클루전 텍스처를 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | 새 값 |

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

### setRoughnessFactor(double value) {#setRoughnessFactor-double-}
```
public void setRoughnessFactor(double value)
```


재질의 거칠기를 설정합니다. 값이 1이면 재질이 완전히 거칠고 값이 0이면 재질이 완전히 매끈함을 의미합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 |

### setSpecularTexture(TextureBase value) {#setSpecularTexture-com.aspose.threed.TextureBase-}
```
public void setSpecularTexture(TextureBase value)
```


반사광 색상 텍스처를 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | 새 값 |

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

