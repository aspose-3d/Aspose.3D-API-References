---
title: "RenderFactory"
second_title: "Java를 통해 Node.js용 Aspose.3D API 레퍼런스"
description: 
type: docs

url: /ko/nodejs-java/aspose.threed/renderfactory/
---
## RenderFactory class

RenderFactory는 렌더링 파이프라인에 표시되는 모든 리소스를 생성합니다.  @hideconstructor


## 메서드

### createRenderTexture{#createRenderTexture}

| 이름 | 설명 |
| --- | --- |
| createRenderTexture(parameters, targets, width, height) | 텍스처에 렌더링하는 렌더 타깃을 생성합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| parameters | RenderParameters | 렌더 텍스처를 생성하기 위한 렌더 파라미터 |
| targets | 숫자 | 색상 출력 타깃 수 |
| 너비 | 숫자 | 렌더 텍스처의 너비 |
| height | 숫자 | 렌더 텍스처의 높이 |

 **Result:**
IRenderTexture


---


### createRenderTexture{#createRenderTexture}

| 이름 | 설명 |
| --- | --- |
| createRenderTexture(parameters, width, height) | 텍스처에 렌더링하는 1개의 타깃을 포함하는 렌더 타깃을 생성합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| parameters | RenderParameters | 렌더 텍스처를 생성하기 위한 렌더 파라미터 |
| 너비 | 숫자 | 렌더 텍스처의 너비 |
| height | 숫자 | 렌더 텍스처의 높이 |

 **Result:**
IRenderTexture


---


### createDescriptorSet{#createDescriptorSet}

| 이름 | 설명 |
| --- | --- |
| createDescriptorSet(shader) | 지정된 셰이더 프로그램에 대한 디스크립터 세트를 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| shader | ShaderProgram | 셰이더 프로그램 |

 **Result:**
IDescriptorSet


---


### createCubeRenderTexture{#createCubeRenderTexture}

| 이름 | 설명 |
| --- | --- |
| createCubeRenderTexture(parameters, width, height) | 1개의 큐브 텍스처를 포함하는 렌더 타깃을 생성합니다 |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| parameters | RenderParameters | 렌더 텍스처를 생성하기 위한 렌더 파라미터 |
| 너비 | 숫자 | 렌더 텍스처의 너비 |
| height | 숫자 | 렌더 텍스처의 높이 |

 **Result:**
IRenderTexture


---


### createRenderWindow{#createRenderWindow}

| 이름 | 설명 |
| --- | --- |
| createRenderWindow(parameters, handle) | 네이티브 윈도우에 렌더링하는 렌더 타깃을 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| parameters | RenderParameters | 렌더 윈도우를 생성하기 위한 렌더 파라미터 |
| handle | WindowHandle | 렌더링할 윈도우의 핸들 |

 **Result:**
IRenderWindow


---


### createVertexBuffer{#createVertexBuffer}

| 이름 | 설명 |
| --- | --- |
| createVertexBuffer(declaration) | 다각형의 정점 정보를 저장하기 위해 com.aspose.threed.IVertexBuffer 인스턴스를 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| declaratio | VertexDeclaration | null |

 **Result:**
IVertexBuffer


---


### createIndexBuffer{#createIndexBuffer}

| 이름 | 설명 |
| --- | --- |
| createIndexBuffer() | 다각형의 면 정보를 저장하기 위해 com.aspose.threed.IIndexBuffer 인스턴스를 생성합니다. |

 **Result:**
IIndexBuffer


---


### createTextureUnit{#createTextureUnit}

| 이름 | 설명 |
| --- | --- |
| createTextureUnit(textureType) | 셰이더에서 접근할 수 있는 텍스처 유닛을 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| textureType | TextureType | TextureType |

 **Result:**
ITextureUnit


---


### createTextureUnit{#createTextureUnit}

| 이름 | 설명 |
| --- | --- |
| createTextureUnit() | 셰이더에서 접근할 수 있는 2D 텍스처 유닛을 생성합니다. |

 **Result:**
ITextureUnit


---


### createShaderProgram{#createShaderProgram}

| 이름 | 설명 |
| --- | --- |
| createShaderProgram(shaderSource) | ShaderProgram 객체를 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| shaderSource | ShaderSource | 셰이더의 소스 코드 |

 **Result:**
ShaderProgram


---


### createPipeline{#createPipeline}

| 이름 | 설명 |
| --- | --- |
| createPipeline(shader, renderState, vertexDeclaration, drawOperation) | 사전 구성된 셰이더/렌더 상태/버텍스 선언 및 그리기 작업이 포함된 그래픽 파이프라인을 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| shader | ShaderProgram | 렌더링에 사용되는 셰이더 |
| renderState | RenderState | 렌더링에 사용되는 렌더 상태 |
| vertexDeclaration | VertexDeclaration | 입력 정점 데이터의 버텍스 선언 |
| drawOperation | DrawOperation | DrawOperation |

 **Result:**
IPipeline


---


### createUniformBuffer{#createUniformBuffer}

| 이름 | 설명 |
| --- | --- |
| createUniformBuffer(size) | GPU 측에서 사전 할당된 크기로 새로운 유니폼 버퍼를 생성합니다. |

 **Parameters:**

| 이름 | 유형 | 설명 |
| --- | --- | --- |
| 크기 | 숫자 | 유니폼 버퍼의 크기 |

 **Result:**
IBuffer


---



