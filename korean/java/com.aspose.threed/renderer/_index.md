---
title: Renderer
second_title: Aspose.3D for Java API 레퍼런스
description: 렌더러에 대한 컨텍스트.
type: docs
weight: 152
url: /ko/java/com.aspose.threed/renderer/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class Renderer implements Closeable
```

렌더러에 대한 컨텍스트.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [clearCache()](#clearCache--) | 캐시를 수동으로 지웁니다. |
| [close()](#close--) | [Renderer](../../com.aspose.threed/renderer)를 해제하고 모든 관련 리소스를 해제합니다. |
| [createRenderer()](#createRenderer--) | 기본 프로필로 새로운 [Renderer](../../com.aspose.threed/renderer)를 생성합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [execute(PostProcessing postProcessing, IRenderTarget result)](#execute-com.aspose.threed.PostProcessing-com.aspose.threed.IRenderTarget-) | 지정된 렌더 대상에 대해 후처리를 실행합니다. |
| [getAssetDirectories()](#getAssetDirectories--) | 외부 자산을 저장하는 디렉터리 |
| [getClass()](#getClass--) |  |
| [getEnableShadows()](#getEnableShadows--) | 그림자를 활성화할지 여부를 가져옵니다. |
| [getFallbackEntityRenderer()](#getFallbackEntityRenderer--) | 엔티티에 특수 렌더러가 정의되지 않은 경우 대체 엔티티 렌더러를 가져옵니다. |
| [getFrustum()](#getFrustum--) | 뷰 행렬을 제공하는 데 사용되는 프러스텀을 가져옵니다. |
| [getMaterial()](#getMaterial--) | 셰이더에서 사용되는 재질 정보를 제공하는 데 사용되는 재질을 가져옵니다. |
| [getNode()](#getNode--) | 월드 변환 행렬을 제공하는 데 사용되는 [getNode](../../com.aspose.threed/renderer\#getNode) 인스턴스를 가져옵니다. |
| [getPostProcessing(String name)](#getPostProcessing-java.lang.String-) | 렌더러에서 지원하는 내장 포스트 프로세서를 가져옵니다. |
| [getPostProcessings()](#getPostProcessings--) | 활성 포스트 프로세싱 체인 |
| [getPresetShaders()](#getPresetShaders--) | 프리셋 셰이더 세트를 가져옵니다 |
| [getRenderFactory()](#getRenderFactory--) | 렌더링 관련 객체를 생성하는 팩토리를 가져옵니다. |
| [getRenderStage()](#getRenderStage--) | 현재 렌더 단계를 가져옵니다. |
| [getRenderTarget()](#getRenderTarget--) | 다음 렌더 작업이 수행될 렌더 타깃을 지정합니다. |
| [getShader()](#getShader--) | 지오메트리를 렌더링하는 데 사용되는 셰이더 인스턴스를 가져옵니다. |
| [getShaderSet()](#getShaderSet--) | 씬을 렌더링하는 데 사용되는 셰이더 세트를 가져옵니다 |
| [getVariables()](#getVariables--) | 렌더링에 사용되는 내부 변수에 접근합니다 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [registerEntityRenderer(EntityRenderer renderer)](#registerEntityRenderer-com.aspose.threed.EntityRenderer-) | 지정된 엔티티에 대한 엔티티 렌더러를 등록합니다 |
| [render(IRenderTarget renderTarget)](#render-com.aspose.threed.IRenderTarget-) | 지정된 타깃을 렌더링합니다 |
| [setEnableShadows(boolean value)](#setEnableShadows-boolean-) | 그림자 사용 여부를 설정합니다. |
| [setFallbackEntityRenderer(EntityRenderer value)](#setFallbackEntityRenderer-com.aspose.threed.EntityRenderer-) | 엔티티에 특수 렌더러가 정의되지 않은 경우 대체 엔티티 렌더러를 설정합니다. |
| [setFrustum(Frustum value)](#setFrustum-com.aspose.threed.Frustum-) | 뷰 행렬을 제공하는 데 사용되는 프러스텀을 설정합니다. |
| [setMaterial(Material value)](#setMaterial-com.aspose.threed.Material-) | 셰이더에서 사용되는 재질 정보를 제공하는 데 사용되는 재질을 설정합니다. |
| [setNode(Node value)](#setNode-com.aspose.threed.Node-) | 월드 변환 행렬을 제공하는 데 사용되는 [getNode](../../com.aspose.threed/renderer\#getNode) 인스턴스를 설정합니다. |
| [setPresetShaders(PresetShaders value)](#setPresetShaders-com.aspose.threed.PresetShaders-) | 프리셋 셰이더 세트를 설정합니다 |
| [setShader(ShaderProgram value)](#setShader-com.aspose.threed.ShaderProgram-) | 지오메트리를 렌더링하는 데 사용되는 셰이더 인스턴스를 설정합니다. |
| [setShaderSet(ShaderSet value)](#setShaderSet-com.aspose.threed.ShaderSet-) | 씬을 렌더링하는 데 사용되는 셰이더 세트를 설정합니다 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### clearCache() {#clearCache--}
```
public void clearCache()
```


캐시를 수동으로 지웁니다. Aspose.3D는 재질/지오메트리와 같은 일부 객체를 렌더 파이프라인과 호환되는 내부 타입에 캐시합니다. 씬에 큰 변경이 있을 때 수동으로 호출해야 합니다.

### close() {#close--}
```
public void close()
```


[Renderer](../../com.aspose.threed/renderer)를 해제하고 모든 관련 리소스를 해제합니다.

### createRenderer() {#createRenderer--}
```
public static Renderer createRenderer()
```


기본 프로필로 새로운 [Renderer](../../com.aspose.threed/renderer)를 생성합니다.

**Returns:**
[Renderer](../../com.aspose.threed/renderer)
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
### execute(PostProcessing postProcessing, IRenderTarget result) {#execute-com.aspose.threed.PostProcessing-com.aspose.threed.IRenderTarget-}
```
public abstract void execute(PostProcessing postProcessing, IRenderTarget result)
```


지정된 렌더 대상에 대해 후처리를 실행합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| postProcessing | [PostProcessing](../../com.aspose.threed/postprocessing) |  |
| result | [IRenderTarget](../../com.aspose.threed/irendertarget) |  |

### getAssetDirectories() {#getAssetDirectories--}
```
public ArrayList<String> getAssetDirectories()
```


외부 자산을 저장하는 디렉터리

**Returns:**
java.util.ArrayList<java.lang.String> - 외부 자산을 저장하는 디렉터리
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEnableShadows() {#getEnableShadows--}
```
public boolean getEnableShadows()
```


그림자를 활성화할지 여부를 가져옵니다.

**Returns:**
boolean - 그림자를 활성화할지 여부.
### getFallbackEntityRenderer() {#getFallbackEntityRenderer--}
```
public EntityRenderer getFallbackEntityRenderer()
```


엔티티에 특수 렌더러가 정의되지 않은 경우 대체 엔티티 렌더러를 가져옵니다.

**Returns:**
[EntityRenderer](../../com.aspose.threed/entityrenderer) - the fallback entity renderer when the entity has no special renderer defined.
### getFrustum() {#getFrustum--}
```
public Frustum getFrustum()
```


뷰 행렬을 제공하는 데 사용되는 프러스텀을 가져옵니다.

**Returns:**
[Frustum](../../com.aspose.threed/frustum) - the frustum that used to provide view matrix.
### getMaterial() {#getMaterial--}
```
public Material getMaterial()
```


셰이더에서 사용되는 재질 정보를 제공하는 데 사용되는 재질을 가져옵니다.

**Returns:**
[Material](../../com.aspose.threed/material) - the material that used to provide material information used by shaders.
### getNode() {#getNode--}
```
public Node getNode()
```


월드 변환 행렬을 제공하는 데 사용되는 [getNode](../../com.aspose.threed/renderer\#getNode) 인스턴스를 가져옵니다.

**Returns:**
[Node](../../com.aspose.threed/node) - the [getNode](../../com.aspose.threed/renderer\#getNode) instance used to provide world transform matrix.
### getPostProcessing(String name) {#getPostProcessing-java.lang.String-}
```
public PostProcessing getPostProcessing(String name)
```


렌더러에서 지원하는 내장 포스트 프로세서를 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String |  |

**Returns:**
[PostProcessing](../../com.aspose.threed/postprocessing)
### getPostProcessings() {#getPostProcessings--}
```
public List<PostProcessing> getPostProcessings()
```


활성 포스트 프로세싱 체인

**Returns:**
java.util.List<com.aspose.threed.PostProcessing> - 활성화된 후처리 체인
### getPresetShaders() {#getPresetShaders--}
```
public PresetShaders getPresetShaders()
```


프리셋 셰이더 세트를 가져옵니다

**Returns:**
[PresetShaders](../../com.aspose.threed/presetshaders) - the preset shader set
### getRenderFactory() {#getRenderFactory--}
```
public abstract RenderFactory getRenderFactory()
```


렌더링 관련 객체를 생성하는 팩토리를 가져옵니다.

**Returns:**
[RenderFactory](../../com.aspose.threed/renderfactory) - the factory to build render-related objects.
### getRenderStage() {#getRenderStage--}
```
public RenderStage getRenderStage()
```


현재 렌더 단계를 가져옵니다.

**Returns:**
[RenderStage](../../com.aspose.threed/renderstage) - the current render stage.
### getRenderTarget() {#getRenderTarget--}
```
public IRenderTarget getRenderTarget()
```


다음 렌더 작업이 수행될 렌더 타깃을 지정합니다.

**Returns:**
[IRenderTarget](../../com.aspose.threed/irendertarget) - Specify the render target that the following render operations will be performed on.
### getShader() {#getShader--}
```
public ShaderProgram getShader()
```


지오메트리를 렌더링하는 데 사용되는 셰이더 인스턴스를 가져옵니다.

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader instance used for rendering the geometry.
### getShaderSet() {#getShaderSet--}
```
public ShaderSet getShaderSet()
```


씬을 렌더링하는 데 사용되는 셰이더 세트를 가져옵니다

**Returns:**
[ShaderSet](../../com.aspose.threed/shaderset) - the shader set that used to render the scene
### getVariables() {#getVariables--}
```
public RendererVariableManager getVariables()
```


렌더링에 사용되는 내부 변수에 접근합니다

**Returns:**
[RendererVariableManager](../../com.aspose.threed/renderervariablemanager) - Access to the internal variables used for rendering
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




### registerEntityRenderer(EntityRenderer renderer) {#registerEntityRenderer-com.aspose.threed.EntityRenderer-}
```
public void registerEntityRenderer(EntityRenderer renderer)
```


지정된 엔티티에 대한 엔티티 렌더러를 등록합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| renderer | [EntityRenderer](../../com.aspose.threed/entityrenderer) |  |

### render(IRenderTarget renderTarget) {#render-com.aspose.threed.IRenderTarget-}
```
public void render(IRenderTarget renderTarget)
```


지정된 타깃을 렌더링합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| renderTarget | [IRenderTarget](../../com.aspose.threed/irendertarget) |  |

### setEnableShadows(boolean value) {#setEnableShadows-boolean-}
```
public void setEnableShadows(boolean value)
```


그림자 사용 여부를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setFallbackEntityRenderer(EntityRenderer value) {#setFallbackEntityRenderer-com.aspose.threed.EntityRenderer-}
```
public void setFallbackEntityRenderer(EntityRenderer value)
```


엔티티에 특수 렌더러가 정의되지 않은 경우 대체 엔티티 렌더러를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [EntityRenderer](../../com.aspose.threed/entityrenderer) | 새 값 |

### setFrustum(Frustum value) {#setFrustum-com.aspose.threed.Frustum-}
```
public void setFrustum(Frustum value)
```


뷰 행렬을 제공하는 데 사용되는 프러스텀을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Frustum](../../com.aspose.threed/frustum) | 새 값 |

### setMaterial(Material value) {#setMaterial-com.aspose.threed.Material-}
```
public void setMaterial(Material value)
```


셰이더에서 사용되는 재질 정보를 제공하는 데 사용되는 재질을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Material](../../com.aspose.threed/material) | 새 값 |

### setNode(Node value) {#setNode-com.aspose.threed.Node-}
```
public void setNode(Node value)
```


월드 변환 행렬을 제공하는 데 사용되는 [getNode](../../com.aspose.threed/renderer\#getNode) 인스턴스를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | 새 값 |

### setPresetShaders(PresetShaders value) {#setPresetShaders-com.aspose.threed.PresetShaders-}
```
public void setPresetShaders(PresetShaders value)
```


프리셋 셰이더 세트를 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [PresetShaders](../../com.aspose.threed/presetshaders) | 새 값 |

### setShader(ShaderProgram value) {#setShader-com.aspose.threed.ShaderProgram-}
```
public void setShader(ShaderProgram value)
```


지오메트리를 렌더링하는 데 사용되는 셰이더 인스턴스를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | 새 값 |

### setShaderSet(ShaderSet value) {#setShaderSet-com.aspose.threed.ShaderSet-}
```
public void setShaderSet(ShaderSet value)
```


씬을 렌더링하는 데 사용되는 셰이더 세트를 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ShaderSet](../../com.aspose.threed/shaderset) | 새 값 |

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

