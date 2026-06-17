---
title: "속성"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/property/
---
## Property class

사용자 정의 속성을 보유하는 클래스.  @hideconstructor


## 메서드

### getValue{#getValue}

| 이름 | 설명 |
| --- | --- |
| getValue() | 값을 가져오거나 설정합니다. 값. |

 **Result:**



---


### setValue{#setValue}

| 이름 | 설명 |
| --- | --- |
| setValue(value) | 값을 가져오거나 설정합니다. 값. |

 **Result:**



---


### setName{#setName}

| 이름 | 설명 |
| --- | --- |
| setName(value) |  |

 **Result:**



---


### getValueType{#getValueType}

| 이름 | 설명 |
| --- | --- |
| getValueType() | 속성 값의 유형을 가져옵니다. 값의 유형. |

 **Result:**



---


### getProperties{#getProperties}

| 이름 | 설명 |
| --- | --- |
| getProperties() | 모든 속성의 컬렉션을 가져옵니다. |

 **Result:**



---


### getBindPoint{#getBindPoint}

| 이름 | 설명 |
| --- | --- |
| getBindPoint(anim, create) | 지정된 애니메이션 인스턴스에서 속성 바인드 포인트를 가져옵니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| anim | AnimationNode | 바인드 포인트를 생성할 애니메이션을 선택합니다. |
| 생성 | boolean | 속성 바인드 포인트가 없으면 생성합니다. |

 **Result:**
BindPoint


---


### getKeyframeSequence{#getKeyframeSequence}

| 이름 | 설명 |
| --- | --- |
| getKeyframeSequence(anim, create) | 지정된 애니메이션 인스턴스의 키프레임 시퀀스를 가져옵니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| anim | AnimationNode | 키프레임 시퀀스를 생성할 애니메이션을 선택합니다. |
| 생성 | boolean | 키프레임 시퀀스가 없으면 생성합니다. |

 **Result:**
KeyframeSequence


---


### toString{#toString}

| 이름 | 설명 |
| --- | --- |
| toString() | 현재 속성을 나타내는 문자열을 반환합니다. |

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



