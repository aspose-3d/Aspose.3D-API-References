---
title: "ShaderMaterial"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/shadermaterial/
---
## ShaderMaterial class

셰이더 머티리얼은 외부 렌더링 엔진이나 셰이더 언어를 사용하여 머티리얼을 설명할 수 있게 합니다.  ShaderMaterial은 구체적인 렌더링 세부 사항을 설명하기 위해 ShaderTechnique을 사용하며, 최종 렌더링 플랫폼에 따라 가장 적합한 것이 사용됩니다.  예를 들어, ShaderMaterial 인스턴스는 두 개의 technique을 가질 수 있는데, 하나는 HLSL로 정의되고 다른 하나는 GLSL로 정의됩니다.  비윈도우 플랫폼에서는 HLSL 대신 GLSL을 사용해야 합니다.


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor() | ShaderMaterial 클래스의 새 인스턴스를 초기화합니다. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 이름 | 설명 |
| --- | --- |
| constructor_overload(name) | ShaderMaterial 클래스의 새 인스턴스를 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| name | String | 이름 |

 **Result:**



---


### getTechniques{#getTechniques}

| 이름 | 설명 |
| --- | --- |
| getTechniques() | 이 자료에 정의된 모든 사용 가능한 기술을 가져옵니다. |

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



