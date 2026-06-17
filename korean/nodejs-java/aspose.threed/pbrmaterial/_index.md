---
title: "PbrMaterial"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/pbrmaterial/
---
## PbrMaterial class

알베도 색상/메탈릭/거칠기를 기반으로 하는 물리 기반 렌더링용 Material


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor() | 기본 PBR 재료 인스턴스를 생성합니다 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 이름 | 설명 |
| --- | --- |
| constructor_overload(albedo) | 지정된 알베도 색상 값을 사용하여 기본 PBR 재료를 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| albedo | Vector3 | 기본 알베도 색상 값 |

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


### getSpecularTexture{#getSpecularTexture}

| 이름 | 설명 |
| --- | --- |
| getSpecularTexture() | 반사 색상의 텍스처를 가져오거나 설정합니다 |

 **Result:**



---


### setSpecularTexture{#setSpecularTexture}

| 이름 | 설명 |
| --- | --- |
| setSpecularTexture(value) | 반사 색상의 텍스처를 가져오거나 설정합니다 |

 **Result:**



---


### getAlbedoTexture{#getAlbedoTexture}

| 이름 | 설명 |
| --- | --- |
| getAlbedoTexture() | 알베도 텍스처를 가져오거나 설정합니다 |

 **Result:**



---


### setAlbedoTexture{#setAlbedoTexture}

| 이름 | 설명 |
| --- | --- |
| setAlbedoTexture(value) | 알베도 텍스처를 가져오거나 설정합니다 |

 **Result:**



---


### getAlbedo{#getAlbedo}

| 이름 | 설명 |
| --- | --- |
| getAlbedo() | 재료의 기본 색상을 가져오거나 설정합니다 |

 **Result:**



---


### setAlbedo{#setAlbedo}

| 이름 | 설명 |
| --- | --- |
| setAlbedo(value) | 재료의 기본 색상을 가져오거나 설정합니다 |

 **Result:**



---


### getOcclusionTexture{#getOcclusionTexture}

| 이름 | 설명 |
| --- | --- |
| getOcclusionTexture() | 앰비언트 오클루전 텍스처를 가져오거나 설정합니다 |

 **Result:**



---


### setOcclusionTexture{#setOcclusionTexture}

| 이름 | 설명 |
| --- | --- |
| setOcclusionTexture(value) | 앰비언트 오클루전 텍스처를 가져오거나 설정합니다 |

 **Result:**



---


### getOcclusionFactor{#getOcclusionFactor}

| 이름 | 설명 |
| --- | --- |
| getOcclusionFactor() | 앰비언트 오클루전 계수를 가져오거나 설정합니다 |

 **Result:**



---


### setOcclusionFactor{#setOcclusionFactor}

| 이름 | 설명 |
| --- | --- |
| setOcclusionFactor(value) | 앰비언트 오클루전 계수를 가져오거나 설정합니다 |

 **Result:**



---


### getMetallicFactor{#getMetallicFactor}

| 이름 | 설명 |
| --- | --- |
| getMetallicFactor() | 재료의 금속성을 가져오거나 설정합니다. 값이 1이면 재료가 금속이며, 값이 0이면 재료가 유전체임을 의미합니다. |

 **Result:**



---


### setMetallicFactor{#setMetallicFactor}

| 이름 | 설명 |
| --- | --- |
| setMetallicFactor(value) | 재료의 금속성을 가져오거나 설정합니다. 값이 1이면 재료가 금속이며, 값이 0이면 재료가 유전체임을 의미합니다. |

 **Result:**



---


### getRoughnessFactor{#getRoughnessFactor}

| 이름 | 설명 |
| --- | --- |
| getRoughnessFactor() | 재료의 거칠기를 가져오거나 설정합니다. 값이 1이면 재료가 완전히 거칠고, 값이 0이면 재료가 완전히 매끄럽습니다. |

 **Result:**



---


### setRoughnessFactor{#setRoughnessFactor}

| 이름 | 설명 |
| --- | --- |
| setRoughnessFactor(value) | 재료의 거칠기를 가져오거나 설정합니다. 값이 1이면 재료가 완전히 거칠고, 값이 0이면 재료가 완전히 매끄럽습니다. |

 **Result:**



---


### getMetallicRoughness{#getMetallicRoughness}

| 이름 | 설명 |
| --- | --- |
| getMetallicRoughness() | 금속성(빨간색 채널) 및 거칠기(녹색 채널) 텍스처를 가져오거나 설정합니다 |

 **Result:**



---


### setMetallicRoughness{#setMetallicRoughness}

| 이름 | 설명 |
| --- | --- |
| setMetallicRoughness(value) | 금속성(빨간색 채널) 및 거칠기(녹색 채널) 텍스처를 가져오거나 설정합니다 |

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
| getEmissiveColor() | 방출 색상을 가져오거나 설정합니다. |

 **Result:**



---


### setEmissiveColor{#setEmissiveColor}

| 이름 | 설명 |
| --- | --- |
| setEmissiveColor(value) | 방출 색상을 가져오거나 설정합니다. |

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


### fromMaterial{#fromMaterial}

| 이름 | 설명 |
| --- | --- |
| fromMaterial(material) | 다른 재료를 PbrMaterial로 변환하도록 허용합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 재료 | 재료 | null |

 **Result:**
PbrMaterial


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



