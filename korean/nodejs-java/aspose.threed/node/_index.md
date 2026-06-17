---
title: "Node"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/node/
---
## Node class

씬 그래프의 요소를 나타냅니다. 씬 그래프는 Node 객체들의 트리 구조입니다. 트리 관리 서비스는 이 클래스에 자체적으로 포함되어 있습니다. Aspose.3D SDK 가 구성된 씬 그래프의 유효성을 검사하지 않음을 유의하십시오. 호출자는 노드 계층 구조에서 순환 그래프가 생성되지 않도록 책임을 져야 합니다. 트리 관리 외에도, 이 클래스는 씬 내 객체의 위치를 설명하는 데 필요한 모든 속성을 정의합니다. 이 정보에는 기본적인 Translation, Rotation, Scaling 속성뿐만 아니라 피벗, 제한, IK 조인트 속성(예: 강성 및 감쇠)과 같은 고급 옵션이 포함됩니다. 처음 생성될 때 Node 객체는 \"empty\"(즉, 그래픽 표현이 없고 위치 정보만 포함하는 객체) 상태입니다. 이 상태에서는 노드 트리 구조에서 부모를 나타내는 데 사용할 수 있지만 그 이상은 사용할 수 없습니다. 이러한 유형의 객체의 일반적인 사용 방법은 노드를 특화시킬 엔티티를 추가하는 것입니다(예: \"Entity\" 참조). 엔티티 자체가 객체이며 Node와 연결됩니다. 이는 동일한 엔티티를 여러 노드가 공유할 수 있음을 의미합니다. Camera, Light, Mesh 등은 모두 엔티티이며 모두 기본 클래스 Entity에서 파생됩니다.


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor() | Node 클래스의 새 인스턴스를 초기화합니다. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 이름 | 설명 |
| --- | --- |
| constructor_overload(name, entity) | Node 클래스의 새 인스턴스를 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| name | String | 이름. |
| entity | Entity | 기본 엔터티. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 이름 | 설명 |
| --- | --- |
| constructor_overload2(name) | Node 클래스의 새 인스턴스를 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| name | String | 이름. |

 **Result:**



---


### getAssetInfo{#getAssetInfo}

| 이름 | 설명 |
| --- | --- |
| getAssetInfo() | 노드당 자산 정보 |

 **Result:**



---


### setAssetInfo{#setAssetInfo}

| 이름 | 설명 |
| --- | --- |
| setAssetInfo(value) | 노드당 자산 정보 |

 **Result:**



---


### getVisible{#getVisible}

| 이름 | 설명 |
| --- | --- |
| getVisible() | 노드를 표시하도록 가져오거나 설정합니다 |

 **Result:**



---


### setVisible{#setVisible}

| 이름 | 설명 |
| --- | --- |
| setVisible(value) | 노드를 표시하도록 가져오거나 설정합니다 |

 **Result:**



---


### getChildNodes{#getChildNodes}

| 이름 | 설명 |
| --- | --- |
| getChildNodes() | 자식 노드를 가져옵니다. 노드들. |

 **Result:**



---


### getEntity{#getEntity}

| 이름 | 설명 |
| --- | --- |
| getEntity() | 이 노드에 연결된 첫 번째 엔터티를 가져오거나 설정합니다. 설정할 경우 다른 엔터티가 모두 삭제됩니다. 노드 엔터티. |

 **Result:**



---


### setEntity{#setEntity}

| 이름 | 설명 |
| --- | --- |
| setEntity(value) | 이 노드에 연결된 첫 번째 엔터티를 가져오거나 설정합니다. 설정할 경우 다른 엔터티가 모두 삭제됩니다. 노드 엔터티. |

 **Result:**



---


### getExcluded{#getExcluded}

| 이름 | 설명 |
| --- | --- |
| getExcluded() | 내보내기 중에 이 노드와 모든 자식 노드/엔터티를 제외할지 여부를 가져오거나 설정합니다. |

 **Result:**



---


### setExcluded{#setExcluded}

| 이름 | 설명 |
| --- | --- |
| setExcluded(value) | 내보내기 중에 이 노드와 모든 자식 노드/엔터티를 제외할지 여부를 가져오거나 설정합니다. |

 **Result:**



---


### getEntities{#getEntities}

| 이름 | 설명 |
| --- | --- |
| getEntities() | 모든 노드 엔터티를 가져옵니다. 노드 엔터티들. |

 **Result:**



---


### getMetaDatas{#getMetaDatas}

| 이름 | 설명 |
| --- | --- |
| getMetaDatas() | 이 노드에 정의된 메타 데이터를 가져옵니다. 메타 데이터들. |

 **Result:**



---


### getMaterials{#getMaterials}

| 이름 | 설명 |
| --- | --- |
| getMaterials() | 이 노드와 연결된 재료를 가져옵니다. 재료들. |

 **Result:**



---


### getMaterial{#getMaterial}

| 이름 | 설명 |
| --- | --- |
| getMaterial() | 이 노드와 연결된 첫 번째 재료를 가져오거나 설정합니다. 설정할 경우 다른 재료가 모두 삭제됩니다. 재료. |

 **Result:**



---


### setMaterial{#setMaterial}

| 이름 | 설명 |
| --- | --- |
| setMaterial(value) | 이 노드와 연결된 첫 번째 재료를 가져오거나 설정합니다. 설정할 경우 다른 재료가 모두 삭제됩니다. 재료. |

 **Result:**



---


### getParentNode{#getParentNode}

| 이름 | 설명 |
| --- | --- |
| getParentNode() | 부모 노드를 가져오거나 설정합니다. 부모 노드. |

 **Result:**



---


### setParentNode{#setParentNode}

| 이름 | 설명 |
| --- | --- |
| setParentNode(value) | 부모 노드를 가져오거나 설정합니다. 부모 노드. |

 **Result:**



---


### getTransform{#getTransform}

| 이름 | 설명 |
| --- | --- |
| getTransform() | 로컬 변환을 가져옵니다. 변환. |

 **Result:**



---


### getGlobalTransform{#getGlobalTransform}

| 이름 | 설명 |
| --- | --- |
| getGlobalTransform() | 글로벌 변환을 가져옵니다. 글로벌 변환. |

 **Result:**



---


### getScene{#getScene}

| 이름 | 설명 |
| --- | --- |
| getScene() | 이 객체가 속한 씬을 가져옵니다. |

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


### createChildNode{#createChildNode}

| 이름 | 설명 |
| --- | --- |
| createChildNode() | 자식 노드를 생성합니다 |

 **Result:**
Node


---


### merge{#merge}

| 이름 | 설명 |
| --- | --- |
| merge(node) | 노드 아래의 모든 것을 분리하고 현재 노드에 연결합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| nod | Node | null |

 **Result:**
Node


---


### createChildNode{#createChildNode}

| 이름 | 설명 |
| --- | --- |
| createChildNode(nodeName) | 지정된 노드 이름으로 새 자식 노드를 생성합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| nodeName | String | 새 자식 노드의 이름 |

 **Result:**
Node


---


### createChildNode{#createChildNode}

| 이름 | 설명 |
| --- | --- |
| createChildNode(entity) | 지정된 엔터티가 연결된 새 자식 노드를 생성합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| entity | Entity | 노드에 연결된 기본 엔터티 |

 **Result:**
Node


---


### createChildNode{#createChildNode}

| 이름 | 설명 |
| --- | --- |
| createChildNode(nodeName, entity) | 지정된 노드 이름으로 새 자식 노드를 생성합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| nodeName | String | 새 자식 노드의 이름 |
| entity | Entity | 노드에 연결된 기본 엔터티 |

 **Result:**
Node


---


### createChildNode{#createChildNode}

| 이름 | 설명 |
| --- | --- |
| createChildNode(nodeName, entity, material) | 지정된 노드 이름으로 새 자식 노드를 생성하고, 지정된 엔터티와 재료를 연결합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| nodeName | String | 새 자식 노드의 이름 |
| entity | Entity | 노드에 연결된 기본 엔터티 |
| material | 재료 | 노드에 연결된 재료 |

 **Result:**
Node


---


### evaluateGlobalTransform{#evaluateGlobalTransform}

| 이름 | 설명 |
| --- | --- |
| evaluateGlobalTransform(withGeometricTransform) | 글로벌 변환을 평가합니다. 기하학적 변환을 포함할지 여부. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| withGeometricTransform | boolean | 기하학적 변환이 필요한지 여부. |

 **Result:**
Matrix4


---


### getChild{#getChild}

| 이름 | 설명 |
| --- | --- |
| getChild(index) | 지정된 인덱스에 있는 자식 노드를 가져옵니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 인덱스 | 숫자 | 인덱스. |

 **Result:**
Node


---


### getChild{#getChild}

| 이름 | 설명 |
| --- | --- |
| getChild(nodeName) | 지정된 이름을 가진 자식 노드를 가져옵니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| nodeName | String | 찾을 자식 이름입니다. |

 **Result:**
Node


---


### accept{#accept}

| 이름 | 설명 |
| --- | --- |
| accept(visitor) | 모든 하위 노드(현재 노드 포함)를 순회하며 노드와 함께 방문자를 호출합니다. 방문자는 false를 반환하여 순회를 중단할 수 있습니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| visitor | NodeVisitor | 노드를 방문하기 위한 Visitor 콜백 |

 **Result:**
boolean


---


### toString{#toString}

| 이름 | 설명 |
| --- | --- |
| toString() | 이 노드의 문자열 표현을 가져옵니다. |

 **Result:**
String


---


### getBoundingBox{#getBoundingBox}

| 이름 | 설명 |
| --- | --- |
| getBoundingBox() | 노드의 경계 상자를 계산합니다. |

 **Result:**
BoundingBox


---


### addEntity{#addEntity}

| 이름 | 설명 |
| --- | --- |
| addEntity(entity) | 노드에 엔터티를 추가합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| entity | Entity | 노드에 첨부될 엔터티입니다. |

 **Result:**
BoundingBox


---


### addChildNode{#addChildNode}

| 이름 | 설명 |
| --- | --- |
| addChildNode(node) | 이 노드에 자식 노드를 추가합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| node | Node | 첨부될 자식 노드입니다. |

 **Result:**
BoundingBox


---


### selectSingleObject{#selectSingleObject}

| 이름 | 설명 |
| --- | --- |
| selectSingleObject(path) | XPath와 유사한 쿼리 구문을 사용하여 현재 노드 아래의 단일 객체를 선택합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| pat | String | null |

 **Result:**
Object


---


### selectObjects{#selectObjects}

| 이름 | 설명 |
| --- | --- |
| selectObjects(path) | XPath와 유사한 쿼리 구문을 사용하여 현재 노드 아래의 여러 객체를 선택합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| pat | String | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=b77a5c561934e089]]


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



