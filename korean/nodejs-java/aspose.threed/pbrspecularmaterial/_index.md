---
title: "PbrSpecularMaterial"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/pbrspecularmaterial/
---
## PbrSpecularMaterial class

확산 색상/스페큘러/광택을 기반으로 하는 물리 기반 렌더링용 Material


## Properties

| 이름 | 설명 |
| --- | --- |
| MAP_SPECULAR_GLOSSINESS | 반사광택을 위한 텍스처 맵 |

## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor() | PbrSpecularMaterial의 생성자 |

 **Result:**



---


### getTransparency{#getTransparency}

| 이름 | 설명 |
| --- | --- |
| getTransparency() | 투명도 계수를 가져오거나 설정합니다. 계수는 0(0%, 완전 불투명)과 1(100%, 완전 투명) 사이여야 합니다. 잘못된 계수 값은 클램프됩니다. 투명도 계수. |

 **Result:**



---


### setTransparency{#setTransparency}

| 이름 | 설명 |
| --- | --- |
| setTransparency(value) | 투명도 계수를 가져오거나 설정합니다. 계수는 0(0%, 완전 불투명)과 1(100%, 완전 투명) 사이여야 합니다. 잘못된 계수 값은 클램프됩니다. 투명도 계수. |

 **Result:**



---


### getNormalTexture{#getNormalTexture}

| 이름 | 설명 |
| --- | --- |
| getNormalTexture() | 노멀 매핑 텍스처를 가져오거나 설정합니다 |

 **Result:**



---


### setNormalTexture{#setNormalTexture}

| 이름 | 설명 |
| --- | --- |
| setNormalTexture(value) | 노멀 매핑 텍스처를 가져오거나 설정합니다 |

 **Result:**



---


### getSpecularGlossinessTexture{#getSpecularGlossinessTexture}

| 이름 | 설명 |
| --- | --- |
| getSpecularGlossinessTexture() | 반사 색상의 텍스처를 가져오거나 설정합니다. RGB 채널은 반사 색상을 저장하고 A 채널은 광택을 저장합니다. |

 **Result:**



---


### setSpecularGlossinessTexture{#setSpecularGlossinessTexture}

| 이름 | 설명 |
| --- | --- |
| setSpecularGlossinessTexture(value) | 반사 색상의 텍스처를 가져오거나 설정합니다. RGB 채널은 반사 색상을 저장하고 A 채널은 광택을 저장합니다. |

 **Result:**



---


### getGlossinessFactor{#getGlossinessFactor}

| 이름 | 설명 |
| --- | --- |
| getGlossinessFactor() | 재질의 광택(매끄러움)을 가져오거나 설정합니다. 1은 완전히 매끄럽고 0은 완전히 거친 것을 의미합니다. 기본값은 1이며 범위는 [0, 1]입니다. |

 **Result:**



---


### setGlossinessFactor{#setGlossinessFactor}

| 이름 | 설명 |
| --- | --- |
| setGlossinessFactor(value) | 재질의 광택(매끄러움)을 가져오거나 설정합니다. 1은 완전히 매끄럽고 0은 완전히 거친 것을 의미합니다. 기본값은 1이며 범위는 [0, 1]입니다. |

 **Result:**



---


### getSpecular{#getSpecular}

| 이름 | 설명 |
| --- | --- |
| getSpecular() | 재질의 반사 색상을 가져오거나 설정합니다. 기본값은 (1, 1, 1)입니다. |

 **Result:**



---


### setSpecular{#setSpecular}

| 이름 | 설명 |
| --- | --- |
| setSpecular(value) | 재질의 반사 색상을 가져오거나 설정합니다. 기본값은 (1, 1, 1)입니다. |

 **Result:**



---


### getDiffuseTexture{#getDiffuseTexture}

| 이름 | 설명 |
| --- | --- |
| getDiffuseTexture() | 디퓨즈 텍스처를 가져오거나 설정합니다 |

 **Result:**



---


### setDiffuseTexture{#setDiffuseTexture}

| 이름 | 설명 |
| --- | --- |
| setDiffuseTexture(value) | 디퓨즈 텍스처를 가져오거나 설정합니다 |

 **Result:**



---


### getDiffuse{#getDiffuse}

| 이름 | 설명 |
| --- | --- |
| getDiffuse() | 재질의 디퓨즈 색상을 가져오거나 설정합니다. 기본값은 (1, 1, 1)입니다 |

 **Result:**



---


### setDiffuse{#setDiffuse}

| 이름 | 설명 |
| --- | --- |
| setDiffuse(value) | 재질의 디퓨즈 색상을 가져오거나 설정합니다. 기본값은 (1, 1, 1)입니다 |

 **Result:**



---


### getEmissiveTexture{#getEmissiveTexture}

| 이름 | 설명 |
| --- | --- |
| getEmissiveTexture() | 에미시브 텍스처를 가져오거나 설정합니다 |

 **Result:**



---


### setEmissiveTexture{#setEmissiveTexture}

| 이름 | 설명 |
| --- | --- |
| setEmissiveTexture(value) | 에미시브 텍스처를 가져오거나 설정합니다 |

 **Result:**



---


### getEmissiveColor{#getEmissiveColor}

| 이름 | 설명 |
| --- | --- |
| getEmissiveColor() | 에미시브 색상을 가져오거나 설정합니다. 기본값은 (0, 0, 0)입니다 |

 **Result:**



---


### setEmissiveColor{#setEmissiveColor}

| 이름 | 설명 |
| --- | --- |
| setEmissiveColor(value) | 에미시브 색상을 가져오거나 설정합니다. 기본값은 (0, 0, 0)입니다 |

 **Result:**



---


### getName{#getName}

| 이름 | 설명 |
| --- | --- |
| getName() | 이름을 가져오거나 설정합니다. 이름. |

 **Result:**



---


### setName{#setName}

| 이름 | 설명 |
| --- | --- |
| setName(value) | 이름을 가져오거나 설정합니다. 이름. |

 **Result:**



---


### getProperties{#getProperties}

| 이름 | 설명 |
| --- | --- |
| getProperties() | 모든 속성의 컬렉션을 가져옵니다. |

 **Result:**



---


### getTexture{#getTexture}

| 이름 | 설명 |
| --- | --- |
| getTexture(slotName) | 지정된 슬롯에서 텍스처를 가져옵니다. 이는 재질의 속성 이름이거나 셰이더의 매개변수 이름일 수 있습니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| slotName | String | 슬롯 이름. |

 **Result:**
TextureBase


---


### setTexture{#setTexture}

| 이름 | 설명 |
| --- | --- |
| setTexture(slotName, texture) | 지정된 슬롯에 텍스처를 설정합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| slotName | String | 슬롯 이름. |
| texture | TextureBase | 텍스처. |

 **Result:**
TextureBase


---


### toString{#toString}

| 이름 | 설명 |
| --- | --- |
| toString() | 객체를 문자열로 포맷합니다. |

 **Result:**
String


---


### removeProperty{#removeProperty}

| 이름 | 설명 |
| --- | --- |
| removeProperty(property) | 동적 속성을 제거합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 속성 | 속성 | 제거할 속성은 무엇입니까 |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| 이름 | 설명 |
| --- | --- |
| removeProperty(property) | 이름으로 식별된 지정된 속성을 제거합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| propert | String | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| 이름 | 설명 |
| --- | --- |
| getProperty(property) | 지정된 속성의 값을 가져옵니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 속성 | String | 속성 이름 |

 **Result:**
Object


---


### setProperty{#setProperty}

| 이름 | 설명 |
| --- | --- |
| setProperty(property, value) | 지정된 속성의 값을 설정합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 속성 | String | 속성 이름 |
| value | Object | 속성의 값 |

 **Result:**
Object


---


### findProperty{#findProperty}

| 이름 | 설명 |
| --- | --- |
| findProperty(propertyName) | 속성을 찾습니다. 동적 속성 (Created by CreateDynamicProperty/SetProperty) 또는 네이티브 속성(Identified by its name) 일 수 있습니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| propertyName | String | 속성 이름. |

 **Result:**
속성


---


### iterator{#iterator}

| 이름 | 설명 |
| --- | --- |
| iterator() | 내부 사용을 위해 예약되었습니다. |

 **Result:**
속성


---



