---
title: GLSLSource
second_title: Aspose.3D for Java API 레퍼런스
description: GLSL에서 쉐이더의 소스 코드
type: docs
weight: 70
url: /ko/java/com.aspose.threed/glslsource/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.ShaderSource](../../com.aspose.threed/shadersource)
```
public final class GLSLSource extends ShaderSource
```

GLSL에서 쉐이더의 소스 코드
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [GLSLSource()](#GLSLSource--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [defineInclude(String fileName, String content)](#defineInclude-java.lang.String-java.lang.String-) | GLSL 소스 코드에서 \#include를 위한 가상 파일을 정의합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getComputeShader()](#getComputeShader--) | 컴퓨트 셰이더의 소스 코드를 가져옵니다. |
| [getFragmentShader()](#getFragmentShader--) | 프래그먼트 셰이더의 소스 코드를 가져옵니다. |
| [getGeometryShader()](#getGeometryShader--) | 지오메트리 셰이더의 소스 코드를 가져옵니다. |
| [getVertexShader()](#getVertexShader--) | 버텍스 셰이더의 소스 코드를 가져옵니다 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setComputeShader(String value)](#setComputeShader-java.lang.String-) | 컴퓨트 셰이더의 소스 코드를 설정합니다. |
| [setFragmentShader(String value)](#setFragmentShader-java.lang.String-) | 프래그먼트 셰이더의 소스 코드를 설정합니다. |
| [setGeometryShader(String value)](#setGeometryShader-java.lang.String-) | 지오메트리 셰이더의 소스 코드를 설정합니다. |
| [setVertexShader(String value)](#setVertexShader-java.lang.String-) | 버텍스 셰이더의 소스 코드를 설정합니다 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GLSLSource() {#GLSLSource--}
```
public GLSLSource()
```


### defineInclude(String fileName, String content) {#defineInclude-java.lang.String-java.lang.String-}
```
public void defineInclude(String fileName, String content)
```


GLSL 소스 코드에서 \#include를 위한 가상 파일을 정의합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| fileName | java.lang.String | 가상 파일의 파일 이름 |
| 내용 | java.lang.String |  |

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
### getComputeShader() {#getComputeShader--}
```
public String getComputeShader()
```


컴퓨트 셰이더의 소스 코드를 가져옵니다.

**Returns:**
java.lang.String - 컴퓨트 셰이더의 소스 코드.
### getFragmentShader() {#getFragmentShader--}
```
public String getFragmentShader()
```


프래그먼트 셰이더의 소스 코드를 가져옵니다.

**Returns:**
java.lang.String - 프래그먼트 셰이더의 소스 코드.
### getGeometryShader() {#getGeometryShader--}
```
public String getGeometryShader()
```


지오메트리 셰이더의 소스 코드를 가져옵니다.

**Returns:**
java.lang.String - 지오메트리 셰이더의 소스 코드.
### getVertexShader() {#getVertexShader--}
```
public String getVertexShader()
```


버텍스 셰이더의 소스 코드를 가져옵니다

**Returns:**
java.lang.String - 버텍스 셰이더의 소스 코드
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




### setComputeShader(String value) {#setComputeShader-java.lang.String-}
```
public void setComputeShader(String value)
```


컴퓨트 셰이더의 소스 코드를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setFragmentShader(String value) {#setFragmentShader-java.lang.String-}
```
public void setFragmentShader(String value)
```


프래그먼트 셰이더의 소스 코드를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setGeometryShader(String value) {#setGeometryShader-java.lang.String-}
```
public void setGeometryShader(String value)
```


지오메트리 셰이더의 소스 코드를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setVertexShader(String value) {#setVertexShader-java.lang.String-}
```
public void setVertexShader(String value)
```


버텍스 셰이더의 소스 코드를 설정합니다

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

