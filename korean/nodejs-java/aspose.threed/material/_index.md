---
title: "재료"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/material/
---
## Material class

Material 은 기하학의 시각적 외관에 필요한 매개변수를 정의합니다.  Aspose.3D 는 LambertMaterial, PhongMaterial 및 ShaderMaterial 에 대한 셰이딩 모델을 제공합니다  @hideconstructor


## Properties

| 이름 | 설명 |
| --- | --- |
| MAP_SPECULAR | setTexture(java.lang.String, com.aspose.threed.TextureBase)에서 반사 텍스처 매핑을 할당하는 데 사용됩니다. |
| MAP_DIFFUSE | setTexture(java.lang.String, com.aspose.threed.TextureBase)에서 확산 텍스처 매핑을 할당하는 데 사용됩니다. |
| MAP_EMISSIVE | setTexture(java.lang.String, com.aspose.threed.TextureBase)에서 방출 텍스처 매핑을 할당하는 데 사용됩니다. |
| MAP_AMBIENT | setTexture(java.lang.String, com.aspose.threed.TextureBase)에서 주변 텍스처 매핑을 할당하는 데 사용됩니다. |
| MAP_NORMAL | setTexture(java.lang.String, com.aspose.threed.TextureBase)에서 노멀 텍스처 매핑을 할당하는 데 사용됩니다. |

## 메서드

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



