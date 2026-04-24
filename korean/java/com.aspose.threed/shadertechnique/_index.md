---
title: ShaderTechnique
second_title: Aspose.3D for Java API 레퍼런스
description: 셰이더 기술은 구체적인 렌더링 구현을 나타냅니다.
type: docs
weight: 169
url: /ko/java/com.aspose.threed/shadertechnique/
---

**Inheritance:**
java.lang.Object
```
public class ShaderTechnique
```

셰이더 기술은 구체적인 렌더링 구현을 나타냅니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ShaderTechnique()](#ShaderTechnique--) | 새로운 [ShaderTechnique](../../com.aspose.threed/shadertechnique) 클래스 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [addBinding(String property, String shaderParameter)](#addBinding-java.lang.String-java.lang.String-) | 동적 속성을 셰이더 파라미터에 바인딩합니다 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | 이 기술의 설명을 가져옵니다 |
| [getRenderAPI()](#getRenderAPI--) | 이 기술에서 사용되는 렌더링 API를 가져옵니다 |
| [getRenderAPIVersion()](#getRenderAPIVersion--) | 렌더링 API의 버전을 가져옵니다. |
| [getShaderContent()](#getShaderContent--) | 임베디드 셰이더 스크립트의 내용을 가져옵니다. |
| [getShaderEntry()](#getShaderEntry--) | 셰이더의 진입점을 가져옵니다. HLSL과 같은 일부 셰이더는 사용자 정의 진입점을 가질 수 있습니다. |
| [getShaderFile()](#getShaderFile--) | 외부 셰이더 파일의 파일 이름을 가져옵니다. |
| [getShaderLanguage()](#getShaderLanguage--) | 이 기술에서 사용되는 셰이더 언어를 가져옵니다. |
| [getShaderParameters()](#getShaderParameters--) | 셰이더 파라미터 정의를 가져옵니다. |
| [getShaderVersion()](#getShaderVersion--) | 이 기술에서 사용되는 셰이더 버전을 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDescription(String value)](#setDescription-java.lang.String-) | 이 기술의 설명을 설정합니다. |
| [setRenderAPI(String value)](#setRenderAPI-java.lang.String-) | 이 기술에서 사용되는 렌더링 API를 설정합니다. |
| [setRenderAPIVersion(String value)](#setRenderAPIVersion-java.lang.String-) | 렌더링 API의 버전을 설정합니다. |
| [setShaderContent(byte[] value)](#setShaderContent-byte---) | 내장 셰이더 스크립트의 내용을 설정합니다. |
| [setShaderEntry(String value)](#setShaderEntry-java.lang.String-) | 셰이더의 진입점을 설정합니다. HLSL과 같은 일부 셰이더는 사용자 정의 진입점을 가질 수 있습니다. |
| [setShaderFile(String value)](#setShaderFile-java.lang.String-) | 외부 셰이더 파일의 파일 이름을 설정합니다. |
| [setShaderLanguage(String value)](#setShaderLanguage-java.lang.String-) | 이 기술에서 사용되는 셰이더 언어를 설정합니다. |
| [setShaderVersion(String value)](#setShaderVersion-java.lang.String-) | 이 기술에서 사용되는 셰이더 버전을 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ShaderTechnique() {#ShaderTechnique--}
```
public ShaderTechnique()
```


새로운 [ShaderTechnique](../../com.aspose.threed/shadertechnique) 클래스 인스턴스를 초기화합니다.

### addBinding(String property, String shaderParameter) {#addBinding-java.lang.String-java.lang.String-}
```
public void addBinding(String property, String shaderParameter)
```


동적 속성을 셰이더 파라미터에 바인딩합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 속성 | java.lang.String | 동적 속성의 이름입니다. |
| shaderParameter | java.lang.String | 셰이더 매개변수의 이름입니다. |

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
### getDescription() {#getDescription--}
```
public String getDescription()
```


이 기술의 설명을 가져옵니다

**Returns:**
java.lang.String - 이 기술의 설명
### getRenderAPI() {#getRenderAPI--}
```
public String getRenderAPI()
```


이 기술에서 사용되는 렌더링 API를 가져옵니다

**Returns:**
java.lang.String - 이 기술에서 사용되는 렌더링 API
### getRenderAPIVersion() {#getRenderAPIVersion--}
```
public String getRenderAPIVersion()
```


렌더링 API의 버전을 가져옵니다.

**Returns:**
java.lang.String - 렌더링 API의 버전
### getShaderContent() {#getShaderContent--}
```
public byte[] getShaderContent()
```


내장 셰이더 스크립트의 내용을 가져옵니다. HLSL/GLSL 셰이더 소스 파일일 수 있습니다.

**Returns:**
byte[] - 내장 셰이더 스크립트의 내용. HLSL/GLSL 셰이더 소스 파일일 수 있습니다.
### getShaderEntry() {#getShaderEntry--}
```
public String getShaderEntry()
```


셰이더의 진입점을 가져옵니다. HLSL과 같은 일부 셰이더는 사용자 정의 진입점을 가질 수 있습니다.

**Returns:**
java.lang.String - 셰이더의 진입점, HLSL과 같은 일부 셰이더는 사용자 정의 진입점을 가질 수 있습니다.
### getShaderFile() {#getShaderFile--}
```
public String getShaderFile()
```


외부 셰이더 파일의 파일 이름을 가져옵니다.

**Returns:**
java.lang.String - 외부 셰이더 파일의 파일 이름.
### getShaderLanguage() {#getShaderLanguage--}
```
public String getShaderLanguage()
```


이 기술에서 사용되는 셰이더 언어를 가져옵니다.

**Returns:**
java.lang.String - 이 기술에서 사용되는 셰이더 언어.
### getShaderParameters() {#getShaderParameters--}
```
public Map<String,String> getShaderParameters()
```


셰이더 매개변수 정의를 가져옵니다. 키는 동적 속성의 이름이며, 값은 해당 속성이 연결된 셰이더 매개변수 이름입니다.

**Returns:**
java.util.Map<java.lang.String,java.lang.String> - 셰이더 매개변수 정의. 키는 동적 속성의 이름이며, 값은 해당 속성이 연결된 셰이더 매개변수 이름입니다.
### getShaderVersion() {#getShaderVersion--}
```
public String getShaderVersion()
```


이 기술에서 사용되는 셰이더 버전을 가져옵니다.

**Returns:**
java.lang.String - 이 기술에서 사용되는 셰이더 버전.
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




### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


이 기술의 설명을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setRenderAPI(String value) {#setRenderAPI-java.lang.String-}
```
public void setRenderAPI(String value)
```


이 기술에서 사용되는 렌더링 API를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setRenderAPIVersion(String value) {#setRenderAPIVersion-java.lang.String-}
```
public void setRenderAPIVersion(String value)
```


렌더링 API의 버전을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setShaderContent(byte[] value) {#setShaderContent-byte---}
```
public void setShaderContent(byte[] value)
```


내장 셰이더 스크립트의 내용을 설정합니다. HLSL/GLSL 셰이더 소스 파일일 수 있습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | byte[] | 새 값 |

### setShaderEntry(String value) {#setShaderEntry-java.lang.String-}
```
public void setShaderEntry(String value)
```


셰이더의 진입점을 설정합니다. HLSL과 같은 일부 셰이더는 사용자 정의 진입점을 가질 수 있습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setShaderFile(String value) {#setShaderFile-java.lang.String-}
```
public void setShaderFile(String value)
```


외부 셰이더 파일의 파일 이름을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setShaderLanguage(String value) {#setShaderLanguage-java.lang.String-}
```
public void setShaderLanguage(String value)
```


이 기술에서 사용되는 셰이더 언어를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setShaderVersion(String value) {#setShaderVersion-java.lang.String-}
```
public void setShaderVersion(String value)
```


이 기술에서 사용되는 셰이더 버전을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

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

