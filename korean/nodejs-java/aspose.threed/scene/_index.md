---
title: "Scene"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/scene/
---
## Scene class

Scene은 노드, 기하학, 재질, 텍스처, 애니메이션, 포즈, 서브 씬 등을 포함하는 최상위 객체입니다.  Scene은 서브 씬을 가질 수 있으며, collada/blender/fbx와 같은 파일에서 다중 문서 지원 역할을 합니다.  Node 계층 구조는 RootNodeLibrary를 통해 접근할 수 있으며, 직렬화 중에 연결되지 않은 객체(메타 데이터 또는 사용자 정의 객체 등)의 참조를 유지하기 위해 사용되어 라이브러리로 활용됩니다.


## 메서드

### constructor{#constructor}

| 이름 | 설명 |
| --- | --- |
| constructor() | Scene 클래스의 새 인스턴스를 초기화합니다. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 이름 | 설명 |
| --- | --- |
| constructor_overload(entity) | 새 노드에 엔터티가 연결된 상태로 Scene 클래스의 새 인스턴스를 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| entity | Entity | 씬에 연결된 초기 엔터티 |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 이름 | 설명 |
| --- | --- |
| constructor_overload2(parentScene, name) | Scene 클래스의 새 인스턴스를 서브 씬으로 초기화합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| parentScene | Scene | 부모 씬입니다. |
| name | String | 씬 이름입니다. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| 이름 | 설명 |
| --- | --- |
| constructor_overload3(fileName) | Scene 클래스의 새 인스턴스를 초기화하고 파일을 즉시 엽니다. 이 생성자는 더 이상 사용되지 않으며, #Error Cref: M:Aspose.ThreeD.Scene.FromFile(System.String,System.Threading.CancellationToken)를 사용하십시오. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| fileName | String | 열 파일의 이름입니다. |

 **Result:**



---


### getSubScenes{#getSubScenes}

| 이름 | 설명 |
| --- | --- |
| getSubScenes() | 모든 서브 씬을 가져옵니다 |

 **Result:**



---


### getLibrary{#getLibrary}

| 이름 | 설명 |
| --- | --- |
| getLibrary() | 씬 계층 구조에 직접 사용되지 않는 객체는 Library에 정의할 수 있습니다. 이는 서브 씬을 사용하고 재사용 가능한 컴포넌트를 서브 씬 아래에 배치할 때 유용합니다. |

 **Result:**



---


### getAnimationClips{#getAnimationClips}

| 이름 | 설명 |
| --- | --- |
| getAnimationClips() | 씬에 정의된 모든 AnimationClip을 가져옵니다. |

 **Result:**



---


### getCurrentAnimationClip{#getCurrentAnimationClip}

| 이름 | 설명 |
| --- | --- |
| getCurrentAnimationClip() | 활성 AnimationClip을 가져오거나 설정합니다. |

 **Result:**



---


### setCurrentAnimationClip{#setCurrentAnimationClip}

| 이름 | 설명 |
| --- | --- |
| setCurrentAnimationClip(value) | 활성 AnimationClip을 가져오거나 설정합니다. |

 **Result:**



---


### getAssetInfo{#getAssetInfo}

| 이름 | 설명 |
| --- | --- |
| getAssetInfo() | 최상위 자산 정보인 문서 정보를 가져오거나 설정합니다. |

 **Result:**



---


### setAssetInfo{#setAssetInfo}

| 이름 | 설명 |
| --- | --- |
| setAssetInfo(value) | 최상위 자산 정보인 문서 정보를 가져오거나 설정합니다. |

 **Result:**



---


### getPoses{#getPoses}

| 이름 | 설명 |
| --- | --- |
| getPoses() | 이 씬에서 사용되는 모든 Pose를 가져옵니다. Pose들. |

 **Result:**



---


### getRootNode{#getRootNode}

| 이름 | 설명 |
| --- | --- |
| getRootNode() | 씬의 루트 노드를 가져옵니다. 루트 노드. |

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


### getAnimationClip{#getAnimationClip}

| 이름 | 설명 |
| --- | --- |
| getAnimationClip(name) | 지정된 이름의 AnimationClip을 가져옵니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| name | String | 그 |

 **Result:**
AnimationClip


---


### clear{#clear}

| 이름 | 설명 |
| --- | --- |
| clear() | 씬 내용을 지우고 기본 설정을 복원합니다. |

 **Result:**
AnimationClip


---


### createAnimationClip{#createAnimationClip}

| 이름 | 설명 |
| --- | --- |
| createAnimationClip(name) | AnimationClip을 생성하고 등록하는 간단한 함수입니다. 첫 번째 AnimationClip은 CurrentAnimationClip에 할당됩니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| name | String | Animation clip의 이름 |

 **Result:**
AnimationClip


---


### open{#open}

| 이름 | 설명 |
| --- | --- |
| open(fileName, options) | 지정된 파일 형식을 사용하여 주어진 경로에서 씬을 엽니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| fileName | String | 파일 이름. |
| 옵션 | LoadOptions | 스트림을 열기 위한 보다 자세한 구성. |

 **Result:**
AnimationClip


---


### open{#open}

| 이름 | 설명 |
| --- | --- |
| open(fileName) | 주어진 경로에서 씬을 엽니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| fileName | String | 파일 이름. |

 **Result:**
AnimationClip


---


### fromFile{#fromFile}

| 이름 | 설명 |
| --- | --- |
| fromFile(fileName) | 주어진 경로에서 씬을 엽니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| fileName | String | 파일 이름. |

 **Result:**
AnimationClip


---


### save{#save}

| 이름 | 설명 |
| --- | --- |
| save(fileName) | 지정된 파일 형식을 사용하여 지정된 경로에 씬을 저장합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| fileName | String | 파일 이름. |

 **Result:**
AnimationClip


---


### save{#save}

| 이름 | 설명 |
| --- | --- |
| save(fileName, format) | 지정된 파일 형식을 사용하여 지정된 경로에 씬을 저장합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| fileName | String | 파일 이름. |
| format | 파일 형식 | 형식. |

 **Result:**
AnimationClip


---


### save{#save}

| 이름 | 설명 |
| --- | --- |
| save(fileName, options) | 지정된 파일 형식을 사용하여 지정된 경로에 씬을 저장합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| fileName | String | 파일 이름. |
| 옵션 | SaveOptions | 스트림을 저장하기 위한 보다 자세한 구성. |

 **Result:**
AnimationClip


---


### render{#render}

| 이름 | 설명 |
| --- | --- |
| render(camera, fileName) | 주어진 카메라 시점에서 씬을 외부 파일로 렌더링합니다. 기본 출력 크기는 1024x768이며 출력 형식은 png입니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 카메라 | 카메라 | 어떤 카메라 시점에서 씬을 렌더링할지 |
| fileName | String | 출력 파일의 파일 이름 |

 **Result:**
AnimationClip


---


### render{#render}

| 이름 | 설명 |
| --- | --- |
| render(camera, fileName, size, format) | 주어진 카메라 시점에서 씬을 외부 파일로 렌더링합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 카메라 | 카메라 | 어떤 카메라 시점에서 씬을 렌더링할지 |
| fileName | String | 출력 파일의 파일 이름 |
| 크기 | Vector2 | 최종 렌더링 이미지의 크기 |
| format | String | 출력 파일의 이미지 형식 |

 **Result:**
AnimationClip


---


### render{#render}

| 이름 | 설명 |
| --- | --- |
| render(camera, fileName, size, format, options) | 주어진 카메라 시점에서 씬을 외부 파일로 렌더링합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 카메라 | 카메라 | 어떤 카메라 시점에서 씬을 렌더링할지 |
| fileName | String | 출력 파일의 파일 이름 |
| 크기 | Vector2 | 최종 렌더링 이미지의 크기 |
| format | String | 출력 파일의 이미지 형식 |
| 옵션 | ImageRenderOptions | 일부 내부 설정을 사용자 정의하는 옵션. |

 **Result:**
AnimationClip


---


### render{#render}

| 이름 | 설명 |
| --- | --- |
| render(camera, bitmap) | 주어진 카메라 시점에서 씬을 비트맵으로 렌더링합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 카메라 | 카메라 | 어떤 카메라 시점에서 씬을 렌더링할지 |
| 비트맵 | TextureData | 렌더링 결과의 대상 |

 **Result:**
AnimationClip


---


### render{#render}

| 이름 | 설명 |
| --- | --- |
| render(camera, bitmap, options) | 주어진 카메라 시점에서 씬을 비트맵으로 렌더링합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 카메라 | 카메라 | 어떤 카메라 시점에서 씬을 렌더링할지 |
| 비트맵 | TextureData | 렌더링 결과의 대상 |
| 옵션 | ImageRenderOptions | 일부 내부 설정을 사용자 정의하는 옵션. |

 **Result:**
AnimationClip


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



