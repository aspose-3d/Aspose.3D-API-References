---
title: "BindPoint"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/bindpoint/
---
## BindPoint class

BindPoint는 일반적으로 객체의 속성에 생성되며, 일부 속성 유형은 여러 구성 요소 필드(예: Vector3 필드)를 포함합니다. BindPoint는 각 구성 요소 필드에 대해 채널을 생성하고, 해당 필드를 하나 이상의 키프레임 시퀀스 인스턴스와 채널을 통해 연결합니다.


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor(scene, prop) | BindPoint 클래스의 새 인스턴스를 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| scene | Scene | 애니메이션을 포함하는 씬입니다. |
| prop | 속성 | 속성. |

 **Result:**



---


### getProperty{#getProperty}

| 이름 | 설명 |
| --- | --- |
| getProperty() | CurveMapping과 연결된 속성을 가져옵니다 |

 **Result:**



---


### setProperty{#setProperty}

| 이름 | 설명 |
| --- | --- |
| setProperty(value) | CurveMapping과 연결된 속성을 가져옵니다 |

 **Result:**



---


### getChannelsCount{#getChannelsCount}

| 이름 | 설명 |
| --- | --- |
| getChannelsCount() | 이 애니메이션 커브 매핑에 정의된 속성 채널의 총 개수를 가져옵니다. |

 **Result:**
숫자


---


### getName{#getName}

| 이름 | 설명 |
| --- | --- |
| getName() | 이름을 가져오거나 설정합니다. 이름. |

 **Result:**
숫자


---


### setName{#setName}

| 이름 | 설명 |
| --- | --- |
| setName(value) | 이름을 가져오거나 설정합니다. 이름. |

 **Result:**
숫자


---


### getProperties{#getProperties}

| 이름 | 설명 |
| --- | --- |
| getProperties() | 모든 속성의 컬렉션을 가져옵니다. |

 **Result:**
숫자


---


### get{#get}

| 이름 | 설명 |
| --- | --- |
| get(channelName) |  |

 **Result:**
숫자


---


### getKeyframeSequence{#getKeyframeSequence}

| 이름 | 설명 |
| --- | --- |
| getKeyframeSequence(channelName) | 지정된 채널에서 첫 번째 키프레임 시퀀스를 가져옵니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| channelName | String | 찾을 채널 이름 |

 **Result:**
KeyframeSequence


---


### getKeyframeSequences{#getKeyframeSequences}

| 이름 | 설명 |
| --- | --- |
| getKeyframeSequences(channelName) | 지정된 채널의 모든 키프레임 시퀀스를 가져옵니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| channelName | String | 찾을 채널 이름 |

 **Result:**
0, Culture=neutral, PublicKeyToken=f071c641d0b4582b]]


---


### createKeyframeSequence{#createKeyframeSequence}

| 이름 | 설명 |
| --- | --- |
| createKeyframeSequence(name) | 새 곡선을 생성하고 곡선 매핑의 첫 번째 채널에 연결합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| name | String | 새 시퀀스의 이름입니다. |

 **Result:**
KeyframeSequence


---


### bindKeyframeSequence{#bindKeyframeSequence}

| 이름 | 설명 |
| --- | --- |
| bindKeyframeSequence(channelName, sequence) | 키프레임 시퀀스를 지정된 채널에 바인드합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| channelName | String | 키프레임 시퀀스가 바인드될 채널 |
| sequence | KeyframeSequence | 바인드할 키프레임 시퀀스 |

 **Result:**
KeyframeSequence


---


### getChannel{#getChannel}

| 이름 | 설명 |
| --- | --- |
| getChannel(channelName) | 주어진 이름으로 채널을 가져옵니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| channelName | String | 찾을 채널 이름 |

 **Result:**
AnimationChannel


---


### addChannel{#addChannel}

| 이름 | 설명 |
| --- | --- |
| addChannel(name, value) | 지정된 채널 속성을 추가합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| name | String | 이름. |
| value | Object | 값. |

 **Result:**
boolean


---


### addChannel{#addChannel}

| 이름 | 설명 |
| --- | --- |
| addChannel(name, type, value) | 지정된 채널 속성을 추가합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| name | String | 이름. |
| type | 클래스 | 유형. |
| value | Object | 값. |

 **Result:**
boolean


---


### resetChannels{#resetChannels}

| 이름 | 설명 |
| --- | --- |
| resetChannels() | 이 애니메이션 곡선 매핑의 속성 채널을 비웁니다. |

 **Result:**
boolean


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



