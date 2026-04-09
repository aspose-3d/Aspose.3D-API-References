---
title: RenderFactory
second_title: Aspose.3D for Java API 레퍼런스
description: RenderFactory는 렌더링 파이프라인에 표시되는 모든 리소스를 생성합니다.
type: docs
weight: 148
url: /ko/java/com.aspose.threed/renderfactory/
---

**Inheritance:**
java.lang.Object
```
public abstract class RenderFactory
```

RenderFactory는 렌더링 파이프라인에 표시되는 모든 리소스를 생성합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [RenderFactory()](#RenderFactory--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [createCubeRenderTexture(RenderParameters parameters, int width, int height)](#createCubeRenderTexture-com.aspose.threed.RenderParameters-int-int-) | 1개의 큐브 텍스처를 포함하는 렌더 타깃을 생성합니다. |
| [createDescriptorSet(ShaderProgram shader)](#createDescriptorSet-com.aspose.threed.ShaderProgram-) | 지정된 셰이더 프로그램에 대한 디스크립터 세트를 생성합니다. |
| [createIndexBuffer()](#createIndexBuffer--) | 폴리곤의 면 정보를 저장하기 위해 [IIndexBuffer](../../com.aspose.threed/iindexbuffer) 인스턴스를 생성합니다. |
| [createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation)](#createPipeline-com.aspose.threed.ShaderProgram-com.aspose.threed.RenderState-com.aspose.threed.VertexDeclaration-com.aspose.threed.DrawOperation-) | 사전 구성된 셰이더/렌더 상태/버텍스 선언 및 드로우 연산을 포함하는 사전 구성된 그래픽 파이프라인을 생성합니다. |
| [createRenderTexture(RenderParameters parameters, int width, int height)](#createRenderTexture-com.aspose.threed.RenderParameters-int-int-) | 텍스처에 렌더링하는 1개의 타깃을 포함하는 렌더 타깃을 생성합니다. |
| [createRenderTexture(RenderParameters parameters, int targets, int width, int height)](#createRenderTexture-com.aspose.threed.RenderParameters-int-int-int-) | 텍스처에 렌더링하는 렌더 타깃을 생성합니다. |
| [createRenderWindow(RenderParameters parameters, WindowHandle handle)](#createRenderWindow-com.aspose.threed.RenderParameters-com.aspose.threed.WindowHandle-) | 네이티브 윈도우에 렌더링하는 렌더 타깃을 생성합니다. |
| [createShaderProgram(ShaderSource shaderSource)](#createShaderProgram-com.aspose.threed.ShaderSource-) | [ShaderProgram](../../com.aspose.threed/shaderprogram) 객체를 생성합니다. |
| [createTextureUnit()](#createTextureUnit--) | 셰이더에서 접근할 수 있는 2D 텍스처 유닛을 생성합니다. |
| [createTextureUnit(TextureType textureType)](#createTextureUnit-com.aspose.threed.TextureType-) | 셰이더에서 접근할 수 있는 텍스처 유닛을 생성합니다. |
| [createUniformBuffer(int size)](#createUniformBuffer-int-) | 미리 할당된 크기로 GPU 측에 새로운 유니폼 버퍼를 생성합니다. |
| [createVertexBuffer(VertexDeclaration declaration)](#createVertexBuffer-com.aspose.threed.VertexDeclaration-) | 폴리곤의 버텍스 정보를 저장하기 위해 [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) 인스턴스를 생성합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RenderFactory() {#RenderFactory--}
```
public RenderFactory()
```


### createCubeRenderTexture(RenderParameters parameters, int width, int height) {#createCubeRenderTexture-com.aspose.threed.RenderParameters-int-int-}
```
public abstract IRenderTexture createCubeRenderTexture(RenderParameters parameters, int width, int height)
```


1개의 큐브 텍스처를 포함하는 렌더 타깃을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | 렌더 텍스처를 생성하기 위한 렌더 파라미터 |
| 너비 | int | 렌더 텍스처의 너비 |
| 높이 | int | 렌더 텍스처의 높이 |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createDescriptorSet(ShaderProgram shader) {#createDescriptorSet-com.aspose.threed.ShaderProgram-}
```
public abstract IDescriptorSet createDescriptorSet(ShaderProgram shader)
```


지정된 셰이더 프로그램에 대한 디스크립터 세트를 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shader | [ShaderProgram](../../com.aspose.threed/shaderprogram) | 셰이더 프로그램 |

**Returns:**
[IDescriptorSet](../../com.aspose.threed/idescriptorset) - A new descriptor set instance
### createIndexBuffer() {#createIndexBuffer--}
```
public abstract IIndexBuffer createIndexBuffer()
```


폴리곤의 면 정보를 저장하기 위해 [IIndexBuffer](../../com.aspose.threed/iindexbuffer) 인스턴스를 생성합니다.

**Returns:**
[IIndexBuffer](../../com.aspose.threed/iindexbuffer)
### createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation) {#createPipeline-com.aspose.threed.ShaderProgram-com.aspose.threed.RenderState-com.aspose.threed.VertexDeclaration-com.aspose.threed.DrawOperation-}
```
public abstract IPipeline createPipeline(ShaderProgram shader, RenderState renderState, VertexDeclaration vertexDeclaration, DrawOperation drawOperation)
```


사전 구성된 셰이더/렌더 상태/버텍스 선언 및 드로우 연산을 포함하는 사전 구성된 그래픽 파이프라인을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shader | [ShaderProgram](../../com.aspose.threed/shaderprogram) | 렌더링에 사용되는 셰이더 |
| renderState | [RenderState](../../com.aspose.threed/renderstate) | 렌더링에 사용되는 렌더 상태 |
| vertexDeclaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | 입력 버텍스 데이터의 버텍스 선언 |
| drawOperation | [DrawOperation](../../com.aspose.threed/drawoperation) | Draw operation |

**Returns:**
[IPipeline](../../com.aspose.threed/ipipeline) - A new pipeline instance
### createRenderTexture(RenderParameters parameters, int width, int height) {#createRenderTexture-com.aspose.threed.RenderParameters-int-int-}
```
public abstract IRenderTexture createRenderTexture(RenderParameters parameters, int width, int height)
```


텍스처에 렌더링하는 1개의 타깃을 포함하는 렌더 타깃을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | 렌더 텍스처를 생성하기 위한 렌더 파라미터 |
| 너비 | int | 렌더 텍스처의 너비 |
| 높이 | int | 렌더 텍스처의 높이 |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createRenderTexture(RenderParameters parameters, int targets, int width, int height) {#createRenderTexture-com.aspose.threed.RenderParameters-int-int-int-}
```
public abstract IRenderTexture createRenderTexture(RenderParameters parameters, int targets, int width, int height)
```


텍스처에 렌더링하는 렌더 타깃을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | 렌더 텍스처를 생성하기 위한 렌더 파라미터 |
| targets | int | How many color output targets |
| 너비 | int | 렌더 텍스처의 너비 |
| 높이 | int | 렌더 텍스처의 높이 |

**Returns:**
[IRenderTexture](../../com.aspose.threed/irendertexture)
### createRenderWindow(RenderParameters parameters, WindowHandle handle) {#createRenderWindow-com.aspose.threed.RenderParameters-com.aspose.threed.WindowHandle-}
```
public abstract IRenderWindow createRenderWindow(RenderParameters parameters, WindowHandle handle)
```


네이티브 윈도우에 렌더링하는 렌더 타깃을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| parameters | [RenderParameters](../../com.aspose.threed/renderparameters) | Render parameters to create the render window |
| handle | [WindowHandle](../../com.aspose.threed/windowhandle) | The handle of the window to render |

**Returns:**
[IRenderWindow](../../com.aspose.threed/irenderwindow)
### createShaderProgram(ShaderSource shaderSource) {#createShaderProgram-com.aspose.threed.ShaderSource-}
```
public abstract ShaderProgram createShaderProgram(ShaderSource shaderSource)
```


[ShaderProgram](../../com.aspose.threed/shaderprogram) 객체를 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shaderSource | [ShaderSource](../../com.aspose.threed/shadersource) | The source code of the shader |

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram)
### createTextureUnit() {#createTextureUnit--}
```
public ITextureUnit createTextureUnit()
```


셰이더에서 접근할 수 있는 2D 텍스처 유닛을 생성합니다.

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit)
### createTextureUnit(TextureType textureType) {#createTextureUnit-com.aspose.threed.TextureType-}
```
public abstract ITextureUnit createTextureUnit(TextureType textureType)
```


셰이더에서 접근할 수 있는 텍스처 유닛을 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| textureType | [TextureType](../../com.aspose.threed/texturetype) | Type of the texture |

**Returns:**
[ITextureUnit](../../com.aspose.threed/itextureunit)
### createUniformBuffer(int size) {#createUniformBuffer-int-}
```
public abstract IBuffer createUniformBuffer(int size)
```


미리 할당된 크기로 GPU 측에 새로운 유니폼 버퍼를 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 크기 | int | The size of the uniform buffer |

**Returns:**
[IBuffer](../../com.aspose.threed/ibuffer) - The uniform buffer instance
### createVertexBuffer(VertexDeclaration declaration) {#createVertexBuffer-com.aspose.threed.VertexDeclaration-}
```
public abstract IVertexBuffer createVertexBuffer(VertexDeclaration declaration)
```


폴리곤의 버텍스 정보를 저장하기 위해 [IVertexBuffer](../../com.aspose.threed/ivertexbuffer) 인스턴스를 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| declaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) |  |

**Returns:**
[IVertexBuffer](../../com.aspose.threed/ivertexbuffer)
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

