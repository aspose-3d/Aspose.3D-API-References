---
title: 장면
second_title: Aspose.3D for Java API 레퍼런스
description: 
type: docs
weight: 161
url: /ko/java/com.aspose.threed/scene/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class Scene extends SceneObject
```
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Scene(Entity entity)](#Scene-com.aspose.threed.Entity-) | 새 노드에 엔터티가 연결된 [Scene](../../com.aspose.threed/scene) 클래스의 새 인스턴스를 초기화합니다. |
| [Scene(Scene parentScene, String name)](#Scene-com.aspose.threed.Scene-java.lang.String-) | [Scene](../../com.aspose.threed/scene) 클래스를 하위 장면으로 초기화합니다. |
| [Scene()](#Scene--) | [Scene](../../com.aspose.threed/scene) 클래스의 새 인스턴스를 초기화합니다. |
## 필드

| 필드 | 설명 |
| --- | --- |
| [VERSION](#VERSION) | 현재 릴리스 버전을 가져옵니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [clear()](#clear--) | 장면 내용을 지우고 기본 설정을 복원합니다. |
| [createAnimationClip(String name)](#createAnimationClip-java.lang.String-) | 간단한 함수로 [AnimationClip](../../com.aspose.threed/animationclip)을 생성하고 등록합니다. 첫 번째 [AnimationClip](../../com.aspose.threed/animationclip)은 [getCurrentAnimationClip](../../com.aspose.threed/scene\#getCurrentAnimationClip)에 할당됩니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 속성을 찾습니다. |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | 주어진 경로에서 장면을 엽니다. |
| [fromFile(String fileName, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.Cancellation-) | 주어진 경로에서 장면을 엽니다. |
| [fromFile(String fileName, FileFormat format)](#fromFile-java.lang.String-com.aspose.threed.FileFormat-) | 지정된 파일 형식을 사용하여 주어진 경로에서 장면을 엽니다. |
| [fromFile(String fileName, FileFormat format, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | 지정된 파일 형식을 사용하여 주어진 경로에서 장면을 엽니다. |
| [fromFile(String fileName, LoadOptions options)](#fromFile-java.lang.String-com.aspose.threed.LoadOptions-) | 지정된 파일 형식을 사용하여 주어진 경로에서 장면을 엽니다. |
| [fromFile(String fileName, LoadOptions options, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | 지정된 파일 형식을 사용하여 주어진 경로에서 장면을 엽니다. |
| [fromStream(Stream stream)](#fromStream-com.aspose.threed.Stream-) | 주어진 스트림에서 장면을 엽니다. |
| [fromStream(Stream stream, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.Cancellation-) | 주어진 스트림에서 장면을 엽니다. |
| [fromStream(Stream stream, FileFormat format)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | 지정된 파일 형식을 사용하여 주어진 스트림에서 장면을 엽니다. |
| [fromStream(Stream stream, FileFormat format, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | 지정된 파일 형식을 사용하여 주어진 스트림에서 장면을 엽니다. |
| [fromStream(Stream stream, LoadOptions options)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-) | 지정된 IO 구성을 사용하여 주어진 스트림에서 장면을 엽니다. |
| [fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | 지정된 IO 구성을 사용하여 주어진 스트림에서 장면을 엽니다. |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | 주어진 스트림에서 장면을 엽니다. |
| [fromStream(InputStream stream, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.Cancellation-) | 주어진 스트림에서 장면을 엽니다. |
| [fromStream(InputStream stream, FileFormat format)](#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-) | 지정된 파일 형식을 사용하여 주어진 스트림에서 장면을 엽니다. |
| [fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | 지정된 파일 형식을 사용하여 주어진 스트림에서 장면을 엽니다. |
| [fromStream(InputStream stream, LoadOptions options)](#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-) | 지정된 IO 구성을 사용하여 주어진 스트림에서 장면을 엽니다. |
| [fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | 지정된 IO 구성을 사용하여 주어진 스트림에서 장면을 엽니다. |
| [getAnimationClip(String name)](#getAnimationClip-java.lang.String-) | 지정된 이름의 [AnimationClip](../../com.aspose.threed/animationclip)을 가져옵니다. |
| [getAnimationClips()](#getAnimationClips--) | 장면에 정의된 모든 [AnimationClip](../../com.aspose.threed/animationclip)을 가져옵니다. |
| [getAssetInfo()](#getAssetInfo--) | 최상위 자산 정보를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getCurrentAnimationClip()](#getCurrentAnimationClip--) | 활성 [AnimationClip](../../com.aspose.threed/animationclip)을 가져옵니다. |
| [getLibrary()](#getLibrary--) | 장면 계층 구조에서 직접 사용되지 않는 객체는 라이브러리에 정의할 수 있습니다. |
| [getName()](#getName--) | 이름을 가져옵니다. |
| [getPoses()](#getPoses--) | 이 장면에서 사용된 모든 [Pose](../../com.aspose.threed/pose)를 가져옵니다. |
| [getProperties()](#getProperties--) | 모든 속성의 컬렉션을 가져옵니다. |
| [getProperty(String property)](#getProperty-java.lang.String-) | 지정된 속성의 값을 가져옵니다 |
| [getRootNode()](#getRootNode--) | 장면의 루트 노드를 가져옵니다. |
| [getScene()](#getScene--) | 이 객체가 속한 씬을 가져옵니다. |
| [getSubScenes()](#getSubScenes--) | 모든 하위 장면을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [open(Stream stream)](#open-com.aspose.threed.Stream-) | 주어진 스트림에서 장면을 엽니다. |
| [open(Stream stream, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.Cancellation-) | 주어진 스트림에서 장면을 엽니다. |
| [open(Stream stream, FileFormat format)](#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | 지정된 파일 형식을 사용하여 주어진 스트림에서 장면을 엽니다. |
| [open(Stream stream, FileFormat format, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | 지정된 파일 형식을 사용하여 주어진 스트림에서 장면을 엽니다. |
| [open(Stream stream, LoadOptions options)](#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-) | 지정된 IO 구성을 사용하여 주어진 스트림에서 장면을 엽니다. |
| [open(Stream stream, LoadOptions options, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | 지정된 IO 구성을 사용하여 주어진 스트림에서 장면을 엽니다. |
| [open(InputStream stream)](#open-java.io.InputStream-) | 주어진 스트림에서 장면을 엽니다. |
| [open(InputStream stream, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.Cancellation-) | 주어진 스트림에서 장면을 엽니다. |
| [open(InputStream stream, FileFormat format)](#open-java.io.InputStream-com.aspose.threed.FileFormat-) | 지정된 파일 형식을 사용하여 주어진 스트림에서 장면을 엽니다. |
| [open(InputStream stream, FileFormat format, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | 지정된 파일 형식을 사용하여 주어진 스트림에서 장면을 엽니다. |
| [open(InputStream stream, LoadOptions options)](#open-java.io.InputStream-com.aspose.threed.LoadOptions-) | 지정된 IO 구성을 사용하여 주어진 스트림에서 장면을 엽니다. |
| [open(InputStream stream, LoadOptions options, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | 지정된 IO 구성을 사용하여 주어진 스트림에서 장면을 엽니다. |
| [open(String fileName)](#open-java.lang.String-) | 주어진 경로에서 장면을 엽니다. |
| [open(String fileName, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.Cancellation-) | 주어진 경로에서 장면을 엽니다. |
| [open(String fileName, FileFormat format)](#open-java.lang.String-com.aspose.threed.FileFormat-) | 지정된 파일 형식을 사용하여 주어진 경로에서 장면을 엽니다. |
| [open(String fileName, FileFormat format, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | 지정된 파일 형식을 사용하여 주어진 경로에서 장면을 엽니다. |
| [open(String fileName, LoadOptions options)](#open-java.lang.String-com.aspose.threed.LoadOptions-) | 지정된 파일 형식을 사용하여 주어진 경로에서 장면을 엽니다. |
| [open(String fileName, LoadOptions options, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | 지정된 파일 형식을 사용하여 주어진 경로에서 장면을 엽니다. |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 동적 속성을 제거합니다. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 이름으로 식별되는 지정된 속성을 제거합니다. |
| [render(Camera camera, TextureData bitmap)](#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-) | 주어진 카메라 시점에서 장면을 비트맵으로 렌더링합니다. |
| [render(Camera camera, TextureData bitmap, ImageRenderOptions options)](#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-com.aspose.threed.ImageRenderOptions-) | 주어진 카메라 시점에서 장면을 비트맵으로 렌더링합니다. |
| [render(Camera camera, String fileName)](#render-com.aspose.threed.Camera-java.lang.String-) | 주어진 카메라 시점에서 장면을 외부 파일로 렌더링합니다. |
| [render(Camera camera, String fileName, Vector2 size, String format)](#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-) | 주어진 카메라 시점에서 장면을 외부 파일로 렌더링합니다. |
| [render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options)](#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-com.aspose.threed.ImageRenderOptions-) | 주어진 카메라 시점에서 장면을 외부 파일로 렌더링합니다. |
| [save(Stream stream, FileFormat format)](#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | 지정된 파일 형식을 사용하여 장면을 스트림에 저장합니다. |
| [save(Stream stream, FileFormat format, Cancellation cancellationToken)](#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | 지정된 파일 형식을 사용하여 장면을 스트림에 저장합니다. |
| [save(Stream stream, SaveOptions options)](#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-) | 지정된 파일 형식을 사용하여 장면을 스트림에 저장합니다. |
| [save(Stream stream, SaveOptions options, Cancellation cancellationToken)](#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | 지정된 파일 형식을 사용하여 장면을 스트림에 저장합니다. |
| [save(OutputStream stream, FileFormat format)](#save-java.io.OutputStream-com.aspose.threed.FileFormat-) | 지정된 파일 형식을 사용하여 장면을 스트림에 저장합니다. |
| [save(OutputStream stream, FileFormat format, Cancellation cancellationToken)](#save-java.io.OutputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | 지정된 파일 형식을 사용하여 장면을 스트림에 저장합니다. |
| [save(OutputStream stream, SaveOptions options)](#save-java.io.OutputStream-com.aspose.threed.SaveOptions-) | 지정된 파일 형식을 사용하여 장면을 스트림에 저장합니다. |
| [save(OutputStream stream, SaveOptions options, Cancellation cancellationToken)](#save-java.io.OutputStream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | 지정된 파일 형식을 사용하여 장면을 스트림에 저장합니다. |
| [save(String fileName)](#save-java.lang.String-) | 지정된 파일 형식을 사용하여 지정된 경로에 씬을 저장합니다. |
| [save(String fileName, FileFormat format)](#save-java.lang.String-com.aspose.threed.FileFormat-) | 지정된 파일 형식을 사용하여 지정된 경로에 씬을 저장합니다. |
| [save(String fileName, FileFormat format, Cancellation cancellationToken)](#save-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | 지정된 파일 형식을 사용하여 지정된 경로에 씬을 저장합니다. |
| [save(String fileName, SaveOptions options)](#save-java.lang.String-com.aspose.threed.SaveOptions-) | 지정된 파일 형식을 사용하여 지정된 경로에 씬을 저장합니다. |
| [save(String fileName, SaveOptions options, Cancellation cancellationToken)](#save-java.lang.String-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | 지정된 파일 형식을 사용하여 지정된 경로에 씬을 저장합니다. |
| [setAssetInfo(AssetInfo value)](#setAssetInfo-com.aspose.threed.AssetInfo-) | 최상위 자산 정보를 설정합니다. |
| [setCurrentAnimationClip(AnimationClip value)](#setCurrentAnimationClip-com.aspose.threed.AnimationClip-) | 활성 [AnimationClip](../../com.aspose.threed/animationclip)을 설정합니다. |
| [setName(String value)](#setName-java.lang.String-) | 이름을 설정합니다. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 지정된 속성의 값을 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Scene(Entity entity) {#Scene-com.aspose.threed.Entity-}
```
public Scene(Entity entity)
```


새 노드에 엔터티가 연결된 [Scene](../../com.aspose.threed/scene) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | entity | [Entity](../../com.aspose.threed/entity) | 씬에 연결된 초기 엔터티 **예시:** 다음 코드는 [getScene](../../com.aspose.threed/scene\#getScene) 를 [Entity](../../com.aspose.threed/entity) 로부터 직접 생성하는 방법을 보여줍니다: |

```
var scene = new Scene(new Box());
``` |

### Scene(Scene parentScene, String name) {#Scene-com.aspose.threed.Scene-java.lang.String-}
```
public Scene(Scene parentScene, String name)
```


[Scene](../../com.aspose.threed/scene) 클래스를 하위 장면으로 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| parentScene | [Scene](../../com.aspose.threed/scene) | 부모 씬입니다. |
| 이름 | java.lang.String | 씬 이름. |

### Scene() {#Scene--}
```
public Scene()
```


[Scene](../../com.aspose.threed/scene) 클래스의 새 인스턴스를 초기화합니다.

### VERSION {#VERSION}
```
public static final String VERSION
```


현재 릴리스 버전을 가져옵니다.

### clear() {#clear--}
```
public void clear()
```


장면 내용을 지우고 기본 설정을 복원합니다.

### createAnimationClip(String name) {#createAnimationClip-java.lang.String-}
```
public AnimationClip createAnimationClip(String name)
```


간단한 함수로 [AnimationClip](../../com.aspose.threed/animationclip)을 생성하고 등록합니다. 첫 번째 [AnimationClip](../../com.aspose.threed/animationclip)은 [getCurrentAnimationClip](../../com.aspose.threed/scene\#getCurrentAnimationClip)에 할당됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 애니메이션 클립 이름 |

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - A new animation clip instance with given name
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
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


속성을 찾습니다. 동적 속성 (Created by CreateDynamicProperty/SetProperty) 또는 네이티브 속성 (Identified by its name)일 수 있습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| propertyName | java.lang.String | 속성 이름. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static Scene fromFile(String fileName)
```


주어진 경로에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | 파일 이름. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, Cancellation cancellationToken)
```


주어진 경로에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | 파일 이름. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 로드 작업에 대한 취소 토큰 |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, FileFormat format) {#fromFile-java.lang.String-com.aspose.threed.FileFormat-}
```
public static Scene fromFile(String fileName, FileFormat format)
```


지정된 파일 형식을 사용하여 주어진 경로에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | 파일 이름. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 파일 형식. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, FileFormat format, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, FileFormat format, Cancellation cancellationToken)
```


지정된 파일 형식을 사용하여 주어진 경로에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | 파일 이름. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 파일 형식. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 로드 작업에 대한 취소 토큰 |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, LoadOptions options) {#fromFile-java.lang.String-com.aspose.threed.LoadOptions-}
```
public static Scene fromFile(String fileName, LoadOptions options)
```


지정된 파일 형식을 사용하여 주어진 경로에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | 파일 이름. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | 스트림을 열기 위한 보다 자세한 구성. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, LoadOptions options, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, LoadOptions options, Cancellation cancellationToken)
```


지정된 파일 형식을 사용하여 주어진 경로에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | 파일 이름. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | 스트림을 열기 위한 보다 자세한 구성. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 로드 작업에 대한 취소 토큰 |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream) {#fromStream-com.aspose.threed.Stream-}
```
public static Scene fromStream(Stream stream)
```


주어진 스트림에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 입력 스트림이며, 사용자가 스트림을 닫을 책임이 있습니다. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, Cancellation cancellationToken)
```


주어진 스트림에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 입력 스트림이며, 사용자가 스트림을 닫을 책임이 있습니다. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 로드 작업에 대한 취소 토큰 |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, FileFormat format) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public static Scene fromStream(Stream stream, FileFormat format)
```


지정된 파일 형식을 사용하여 주어진 스트림에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 입력 스트림이며, 사용자가 스트림을 닫을 책임이 있습니다. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 파일 형식. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, FileFormat format, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, FileFormat format, Cancellation cancellationToken)
```


지정된 파일 형식을 사용하여 주어진 스트림에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 입력 스트림이며, 사용자가 스트림을 닫을 책임이 있습니다. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 파일 형식. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 로드 작업에 대한 취소 토큰 |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, LoadOptions options) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-}
```
public static Scene fromStream(Stream stream, LoadOptions options)
```


지정된 IO 구성을 사용하여 주어진 스트림에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 입력 스트림이며, 사용자가 스트림을 닫을 책임이 있습니다. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | 스트림을 열기 위한 보다 자세한 구성. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken)
```


지정된 IO 구성을 사용하여 주어진 스트림에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 입력 스트림이며, 사용자가 스트림을 닫을 책임이 있습니다. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | 스트림을 열기 위한 보다 자세한 구성. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 로드 작업에 대한 취소 토큰 |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static Scene fromStream(InputStream stream)
```


주어진 스트림에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 스트림 | java.io.InputStream | 입력 스트림이며, 사용자가 스트림을 닫을 책임이 있습니다. **예시:** 다음 코드는 취소 토큰 소스를 사용하여 스트림으로부터 씬을 생성하는 방법을 보여줍니다. |

```
var cts = new Cancellation();    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, Cancellation cancellationToken) {#fromStream-java.io.InputStream-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(InputStream stream, Cancellation cancellationToken)
```


주어진 스트림에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.InputStream | 입력 스트림이며, 사용자가 스트림을 닫을 책임이 있습니다. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 로드 작업에 대한 취소 토큰 **예시:** 다음 코드는 취소 토큰 소스를 사용하여 스트림으로부터 씬을 생성하는 방법을 보여줍니다. |

```
var cts = new Cancellation();    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input, cts);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, FileFormat format) {#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-}
```
public static Scene fromStream(InputStream stream, FileFormat format)
```


지정된 파일 형식을 사용하여 주어진 스트림에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.InputStream | 입력 스트림이며, 사용자가 스트림을 닫을 책임이 있습니다. |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | 파일 형식. **예시:** 다음 코드는 스트림으로부터 씬을 생성하는 방법을 보여줍니다. |

```
try(InputStream input = new FileInputStream("input.fbx")) {    
          Scene scene = Scene.fromStream(input);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken) {#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken)
```


지정된 파일 형식을 사용하여 주어진 스트림에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.InputStream | 입력 스트림이며, 사용자가 스트림을 닫을 책임이 있습니다. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 파일 형식. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 로드 작업에 대한 취소 토큰 **예시:** 다음 코드는 스트림으로부터 씬을 생성하는 방법을 보여줍니다. |

```
try(InputStream input = new FileInputStream("input.fbx")) {    
          Scene scene = Scene.fromStream(input);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, LoadOptions options) {#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-}
```
public static Scene fromStream(InputStream stream, LoadOptions options)
```


지정된 IO 구성을 사용하여 주어진 스트림에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.InputStream | 입력 스트림이며, 사용자가 스트림을 닫을 책임이 있습니다. |
|  | options | [LoadOptions](../../com.aspose.threed/loadoptions) | 스트림을 열기 위한 보다 자세한 구성. **예시:** 다음 코드는 로드 옵션을 사용하여 스트림으로부터 씬을 생성하는 방법을 보여줍니다. |

```
var opts = new FbxLoadOptions();    
     opts.getLookupPaths().add("textures");    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input, opts);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken) {#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken)
```


지정된 IO 구성을 사용하여 주어진 스트림에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.InputStream | 입력 스트림이며, 사용자가 스트림을 닫을 책임이 있습니다. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | 스트림을 열기 위한 보다 자세한 구성. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 로드 작업에 대한 취소 토큰 **예시:** 다음 코드는 로드 옵션을 사용하여 스트림으로부터 씬을 생성하는 방법을 보여줍니다. |

```
var opts = new FbxLoadOptions();    
     opts.getLookupPaths().add("textures");    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input, opts);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### getAnimationClip(String name) {#getAnimationClip-java.lang.String-}
```
public AnimationClip getAnimationClip(String name)
```


지정된 이름의 [AnimationClip](../../com.aspose.threed/animationclip)을 가져옵니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | java.lang.String | [AnimationClip](../../com.aspose.threed/animationclip)의 조회할 이름 |

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - Returned AnimationClip
### getAnimationClips() {#getAnimationClips--}
```
public List<AnimationClip> getAnimationClips()
```


장면에 정의된 모든 [AnimationClip](../../com.aspose.threed/animationclip)을 가져옵니다.

**Returns:**
java.util.List<com.aspose.threed.AnimationClip> - 씬에 정의된 모든 [AnimationClip](../../com.aspose.threed/animationclip).
### getAssetInfo() {#getAssetInfo--}
```
public AssetInfo getAssetInfo()
```


최상위 자산 정보를 가져옵니다.

**Returns:**
[AssetInfo](../../com.aspose.threed/assetinfo) - the top-level asset information **Example:** The following code shows how to read the application information from a FBX file:

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The FBX file is created by %s %s",
         scene.getAssetInfo().getApplicationName(),
         scene.getAssetInfo().getApplicationVersion());
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCurrentAnimationClip() {#getCurrentAnimationClip--}
```
public AnimationClip getCurrentAnimationClip()
```


활성 [AnimationClip](../../com.aspose.threed/animationclip)을 가져옵니다.

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - the active [AnimationClip](../../com.aspose.threed/animationclip)
### getLibrary() {#getLibrary--}
```
public List<A3DObject> getLibrary()
```


씬 계층 구조에 직접 사용되지 않는 객체는 라이브러리에 정의할 수 있습니다. 이는 서브 씬을 사용하고 재사용 가능한 컴포넌트를 서브 씬 아래에 배치할 때 유용합니다.

**Returns:**
java.util.List<com.aspose.threed.A3DObject> - 씬 계층 구조에 직접 사용되지 않는 객체는 라이브러리에 정의할 수 있습니다. 이는 서브 씬을 사용하고 재사용 가능한 컴포넌트를 서브 씬 아래에 배치할 때 유용합니다.
### getName() {#getName--}
```
public String getName()
```


이름을 가져옵니다.

**Returns:**
java.lang.String - 이름.
### getPoses() {#getPoses--}
```
public Collection<Pose> getPoses()
```


이 장면에서 사용된 모든 [Pose](../../com.aspose.threed/pose)를 가져옵니다.

**Returns:**
java.util.Collection<com.aspose.threed.Pose> - 이 씬에서 사용된 모든 [Pose](../../com.aspose.threed/pose).
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


모든 속성의 컬렉션을 가져옵니다.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


지정된 속성의 값을 가져옵니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 속성 | java.lang.String | 속성 이름 |

**Returns:**
java.lang.Object - 찾은 속성의 값
### getRootNode() {#getRootNode--}
```
public Node getRootNode()
```


장면의 루트 노드를 가져옵니다.

**Returns:**
[Node](../../com.aspose.threed/node) - the root node of the scene. **Example:** The following code shows how to create a node with Box entity attached to the root node.

```
Scene scene = new Scene();
     scene.getRootNode().createChildNode(new Box());
     scene.save("box.stl");
```
### getScene() {#getScene--}
```
public Scene getScene()
```


이 객체가 속한 씬을 가져옵니다.

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getSubScenes() {#getSubScenes--}
```
public List<Scene> getSubScenes()
```


모든 하위 장면을 가져옵니다.

**Returns:**
java.util.List<com.aspose.threed.Scene> - 모든 서브 씬
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




### open(Stream stream) {#open-com.aspose.threed.Stream-}
```
public void open(Stream stream)
```


주어진 스트림에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 입력 스트림이며, 사용자가 스트림을 닫을 책임이 있습니다. |

### open(Stream stream, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, Cancellation cancellationToken)
```


주어진 스트림에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 입력 스트림이며, 사용자가 스트림을 닫을 책임이 있습니다. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 로드 작업에 대한 취소 토큰 |

### open(Stream stream, FileFormat format) {#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public void open(Stream stream, FileFormat format)
```


지정된 파일 형식을 사용하여 주어진 스트림에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 입력 스트림이며, 사용자가 스트림을 닫을 책임이 있습니다. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 파일 형식. |

### open(Stream stream, FileFormat format, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, FileFormat format, Cancellation cancellationToken)
```


지정된 파일 형식을 사용하여 주어진 스트림에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 입력 스트림이며, 사용자가 스트림을 닫을 책임이 있습니다. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 파일 형식. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 로드 작업에 대한 취소 토큰 |

### open(Stream stream, LoadOptions options) {#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-}
```
public void open(Stream stream, LoadOptions options)
```


지정된 IO 구성을 사용하여 주어진 스트림에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 입력 스트림이며, 사용자가 스트림을 닫을 책임이 있습니다. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | 스트림을 열기 위한 보다 자세한 구성. |

### open(Stream stream, LoadOptions options, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, LoadOptions options, Cancellation cancellationToken)
```


지정된 IO 구성을 사용하여 주어진 스트림에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 입력 스트림이며, 사용자가 스트림을 닫을 책임이 있습니다. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | 스트림을 열기 위한 보다 자세한 구성. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 로드 작업에 대한 취소 토큰 |

### open(InputStream stream) {#open-java.io.InputStream-}
```
public void open(InputStream stream)
```


주어진 스트림에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | 스트림 | java.io.InputStream | 입력 스트림이며, 사용자가 스트림을 닫을 책임이 있습니다. **예시:** 다음 코드는 스트림으로부터 씬을 여는 방법을 보여줍니다. |

```
var scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs);    
     }
``` |

### open(InputStream stream, Cancellation cancellationToken) {#open-java.io.InputStream-com.aspose.threed.Cancellation-}
```
public void open(InputStream stream, Cancellation cancellationToken)
```


주어진 스트림에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.InputStream | 입력 스트림이며, 사용자가 스트림을 닫을 책임이 있습니다. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 로드 작업에 대한 취소 토큰 **예시:** 다음 코드는 스트림에서 씬을 열 때 취소 토큰을 사용하는 방법을 보여줍니다. |

```
var scene = new Scene();    
     Cancellation cts = new Cancellation();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs, cts);    
     }
``` |

### open(InputStream stream, FileFormat format) {#open-java.io.InputStream-com.aspose.threed.FileFormat-}
```
public void open(InputStream stream, FileFormat format)
```


지정된 파일 형식을 사용하여 주어진 스트림에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.InputStream | 입력 스트림이며, 사용자가 스트림을 닫을 책임이 있습니다. |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | 파일 형식. **예시:** 다음 코드는 스트림에서 씬을 여는 방법을 보여줍니다. |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs, FileFormat.GLTF2);    
     }
``` |

### open(InputStream stream, FileFormat format, Cancellation cancellationToken) {#open-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(InputStream stream, FileFormat format, Cancellation cancellationToken)
```


지정된 파일 형식을 사용하여 주어진 스트림에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.InputStream | 입력 스트림이며, 사용자가 스트림을 닫을 책임이 있습니다. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 파일 형식. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 로드 작업에 대한 취소 토큰 **예시:** 다음 코드는 스트림에서 씬을 여는 방법을 보여줍니다. |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs, FileFormat.GLTF2);    
     }
``` |

### open(InputStream stream, LoadOptions options) {#open-java.io.InputStream-com.aspose.threed.LoadOptions-}
```
public void open(InputStream stream, LoadOptions options)
```


지정된 IO 구성을 사용하여 주어진 스트림에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.InputStream | 입력 스트림이며, 사용자가 스트림을 닫을 책임이 있습니다. |
|  | options | [LoadOptions](../../com.aspose.threed/loadoptions) | 스트림을 열기 위한 보다 자세한 구성. **예시:** 다음 코드는 추가 로드 옵션을 사용하여 스트림에서 씬을 여는 방법을 보여줍니다. |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         var opt = new FbxLoadOptions();    
         opt.getLookupPaths().add("textures");    
         scene.open(fs, opt);    
     }
``` |

### open(InputStream stream, LoadOptions options, Cancellation cancellationToken) {#open-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(InputStream stream, LoadOptions options, Cancellation cancellationToken)
```


지정된 IO 구성을 사용하여 주어진 스트림에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.InputStream | 입력 스트림이며, 사용자가 스트림을 닫을 책임이 있습니다. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | 스트림을 열기 위한 보다 자세한 구성. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 로드 작업에 대한 취소 토큰 **예시:** 다음 코드는 추가 로드 옵션을 사용하여 스트림에서 씬을 여는 방법을 보여줍니다. |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         var opt = new FbxLoadOptions();    
         opt.getLookupPaths().add("textures");    
         scene.open(fs, opt);    
     }
``` |

### open(String fileName) {#open-java.lang.String-}
```
public void open(String fileName)
```


주어진 경로에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | 파일 이름. |

### open(String fileName, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.Cancellation-}
```
public void open(String fileName, Cancellation cancellationToken)
```


주어진 경로에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | 파일 이름. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 로드 작업에 대한 취소 토큰 |

### open(String fileName, FileFormat format) {#open-java.lang.String-com.aspose.threed.FileFormat-}
```
public void open(String fileName, FileFormat format)
```


지정된 파일 형식을 사용하여 주어진 경로에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | 파일 이름. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 파일 형식. |

### open(String fileName, FileFormat format, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(String fileName, FileFormat format, Cancellation cancellationToken)
```


지정된 파일 형식을 사용하여 주어진 경로에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | 파일 이름. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 파일 형식. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 로드 작업에 대한 취소 토큰 |

### open(String fileName, LoadOptions options) {#open-java.lang.String-com.aspose.threed.LoadOptions-}
```
public void open(String fileName, LoadOptions options)
```


지정된 파일 형식을 사용하여 주어진 경로에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | 파일 이름. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | 스트림을 열기 위한 보다 자세한 구성. |

### open(String fileName, LoadOptions options, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(String fileName, LoadOptions options, Cancellation cancellationToken)
```


지정된 파일 형식을 사용하여 주어진 경로에서 장면을 엽니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | 파일 이름. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | 스트림을 열기 위한 보다 자세한 구성. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 로드 작업에 대한 취소 토큰 |

### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


동적 속성을 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | 제거할 속성 |

**Returns:**
boolean - 속성이 성공적으로 제거되면 true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


이름으로 식별되는 지정된 속성을 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 속성 | java.lang.String | 제거할 속성 |

**Returns:**
boolean - 속성이 성공적으로 제거되면 true
### render(Camera camera, TextureData bitmap) {#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-}
```
public void render(Camera camera, TextureData bitmap)
```


주어진 카메라 시점에서 장면을 비트맵으로 렌더링합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | 어떤 카메라의 시점에서 씬을 렌더링할지 |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | 렌더링 결과의 대상 |

### render(Camera camera, TextureData bitmap, ImageRenderOptions options) {#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-com.aspose.threed.ImageRenderOptions-}
```
public void render(Camera camera, TextureData bitmap, ImageRenderOptions options)
```


주어진 카메라 시점에서 장면을 비트맵으로 렌더링합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | 어떤 카메라의 시점에서 씬을 렌더링할지 |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | 렌더링 결과의 대상 |
| options | [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions) | 일부 내부 설정을 사용자 지정하는 옵션. |

### render(Camera camera, String fileName) {#render-com.aspose.threed.Camera-java.lang.String-}
```
public void render(Camera camera, String fileName)
```


주어진 카메라 시점에서 씬을 외부 파일로 렌더링합니다. 기본 출력 크기는 1024x768이며 출력 형식은 png입니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | 어떤 카메라의 시점에서 씬을 렌더링할지 |
| fileName | java.lang.String | 출력 파일의 파일 이름 |

### render(Camera camera, String fileName, Vector2 size, String format) {#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-}
```
public void render(Camera camera, String fileName, Vector2 size, String format)
```


주어진 카메라 시점에서 장면을 외부 파일로 렌더링합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | 어떤 카메라의 시점에서 씬을 렌더링할지 |
| fileName | java.lang.String | 출력 파일의 파일 이름 |
| size | [Vector2](../../com.aspose.threed/vector2) | 최종 렌더링 이미지의 크기 |
| 형식 | java.lang.String | 출력 파일의 이미지 형식 |

### render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options) {#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-com.aspose.threed.ImageRenderOptions-}
```
public void render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options)
```


주어진 카메라 시점에서 장면을 외부 파일로 렌더링합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | 어떤 카메라의 시점에서 씬을 렌더링할지 |
| fileName | java.lang.String | 출력 파일의 파일 이름 |
| size | [Vector2](../../com.aspose.threed/vector2) | 최종 렌더링 이미지의 크기 |
| 형식 | java.lang.String | 출력 파일의 이미지 형식 |
| options | [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions) | 일부 내부 설정을 사용자 지정하는 옵션. |

### save(Stream stream, FileFormat format) {#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public void save(Stream stream, FileFormat format)
```


지정된 파일 형식을 사용하여 장면을 스트림에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 입력 스트림이며, 사용자가 스트림을 닫을 책임이 있습니다. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 형식. |

### save(Stream stream, FileFormat format, Cancellation cancellationToken) {#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(Stream stream, FileFormat format, Cancellation cancellationToken)
```


지정된 파일 형식을 사용하여 장면을 스트림에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 입력 스트림이며, 사용자가 스트림을 닫을 책임이 있습니다. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 형식. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 저장 작업에 대한 취소 토큰 |

### save(Stream stream, SaveOptions options) {#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-}
```
public void save(Stream stream, SaveOptions options)
```


지정된 파일 형식을 사용하여 장면을 스트림에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 입력 스트림이며, 사용자가 스트림을 닫을 책임이 있습니다. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | 스트림을 저장하기 위한 보다 자세한 구성. |

### save(Stream stream, SaveOptions options, Cancellation cancellationToken) {#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(Stream stream, SaveOptions options, Cancellation cancellationToken)
```


지정된 파일 형식을 사용하여 장면을 스트림에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 입력 스트림이며, 사용자가 스트림을 닫을 책임이 있습니다. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | 스트림을 저장하기 위한 보다 자세한 구성. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 저장 작업에 대한 취소 토큰 |

### save(OutputStream stream, FileFormat format) {#save-java.io.OutputStream-com.aspose.threed.FileFormat-}
```
public void save(OutputStream stream, FileFormat format)
```


지정된 파일 형식을 사용하여 장면을 스트림에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.OutputStream | 입력 스트림이며, 사용자가 스트림을 닫을 책임이 있습니다. |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | 형식. **예시:** 다음 코드는 씬을 저장하는 방법을 보여줍니다. |

```
Scene scene = Scene.fromFile("input.fbx");    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, FileFormat.USDZ);    
     }
``` |

### save(OutputStream stream, FileFormat format, Cancellation cancellationToken) {#save-java.io.OutputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(OutputStream stream, FileFormat format, Cancellation cancellationToken)
```


지정된 파일 형식을 사용하여 장면을 스트림에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.OutputStream | 입력 스트림이며, 사용자가 스트림을 닫을 책임이 있습니다. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 형식. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 저장 작업에 대한 취소 토큰 **예시:** 다음 코드는 씬을 저장하는 방법을 보여줍니다. |

```
Scene scene = Scene.fromFile("input.fbx");    
     var cts = new Cancellation();    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, FileFormat.USDZ, cts);    
     }
``` |

### save(OutputStream stream, SaveOptions options) {#save-java.io.OutputStream-com.aspose.threed.SaveOptions-}
```
public void save(OutputStream stream, SaveOptions options)
```


지정된 파일 형식을 사용하여 장면을 스트림에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.OutputStream | 입력 스트림이며, 사용자가 스트림을 닫을 책임이 있습니다. |
|  | options | [SaveOptions](../../com.aspose.threed/saveoptions) | 스트림을 저장하기 위한 보다 자세한 구성. **예시:** 다음 코드는 씬을 저장하는 방법을 보여줍니다. |

```
Scene scene = Scene.fromFile("input.fbx");    
     var opt = new UsdSaveOptions();    
     opt.setPrimitiveToMesh(true);    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, opt);    
     }
``` |

### save(OutputStream stream, SaveOptions options, Cancellation cancellationToken) {#save-java.io.OutputStream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(OutputStream stream, SaveOptions options, Cancellation cancellationToken)
```


지정된 파일 형식을 사용하여 장면을 스트림에 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.OutputStream | 입력 스트림이며, 사용자가 스트림을 닫을 책임이 있습니다. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | 스트림을 저장하기 위한 보다 자세한 구성. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 저장 작업에 대한 취소 토큰 **예시:** 다음 코드는 씬을 저장하는 방법을 보여줍니다. |

```
Scene scene = Scene.fromFile("input.fbx");    
     var cts = new Cancellation();    
     var opt = new UsdSaveOptions();    
     opt.setPrimitiveToMesh(true);    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, opt, cts);    
     }
``` |

### save(String fileName) {#save-java.lang.String-}
```
public void save(String fileName)
```


지정된 파일 형식을 사용하여 지정된 경로에 씬을 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | 파일 이름. |

### save(String fileName, FileFormat format) {#save-java.lang.String-com.aspose.threed.FileFormat-}
```
public void save(String fileName, FileFormat format)
```


지정된 파일 형식을 사용하여 지정된 경로에 씬을 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | 파일 이름. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 형식. |

### save(String fileName, FileFormat format, Cancellation cancellationToken) {#save-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(String fileName, FileFormat format, Cancellation cancellationToken)
```


지정된 파일 형식을 사용하여 지정된 경로에 씬을 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | 파일 이름. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 형식. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 저장 작업에 대한 취소 토큰 |

### save(String fileName, SaveOptions options) {#save-java.lang.String-com.aspose.threed.SaveOptions-}
```
public void save(String fileName, SaveOptions options)
```


지정된 파일 형식을 사용하여 지정된 경로에 씬을 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | 파일 이름. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | 스트림을 저장하기 위한 보다 자세한 구성. |

### save(String fileName, SaveOptions options, Cancellation cancellationToken) {#save-java.lang.String-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(String fileName, SaveOptions options, Cancellation cancellationToken)
```


지정된 파일 형식을 사용하여 지정된 경로에 씬을 저장합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | 파일 이름. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | 스트림을 저장하기 위한 보다 자세한 구성. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 저장 작업에 대한 취소 토큰 |

### setAssetInfo(AssetInfo value) {#setAssetInfo-com.aspose.threed.AssetInfo-}
```
public void setAssetInfo(AssetInfo value)
```


최상위 자산 정보를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
|  | value | [AssetInfo](../../com.aspose.threed/assetinfo) | 새 값 **예시:** 다음 코드는 FBX 파일에서 애플리케이션 정보를 읽는 방법을 보여줍니다: |

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The FBX file is created by %s %s",
         scene.getAssetInfo().getApplicationName(),
         scene.getAssetInfo().getApplicationVersion());
``` |

### setCurrentAnimationClip(AnimationClip value) {#setCurrentAnimationClip-com.aspose.threed.AnimationClip-}
```
public void setCurrentAnimationClip(AnimationClip value)
```


활성 [AnimationClip](../../com.aspose.threed/animationclip)을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [AnimationClip](../../com.aspose.threed/animationclip) | 새 값 |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


이름을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


지정된 속성의 값을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 속성 | java.lang.String | 속성 이름 |
| 값 | java.lang.Object | 속성의 값 |

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

