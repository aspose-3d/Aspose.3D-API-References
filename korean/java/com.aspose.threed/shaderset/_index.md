---
title: ShaderSet
second_title: Aspose.3D for Java API 레퍼런스
description: 각 종류의 머티리얼에 대한 셰이더 프로그램
type: docs
weight: 166
url: /ko/java/com.aspose.threed/shaderset/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class ShaderSet implements Closeable
```

각 종류의 머티리얼에 대한 셰이더 프로그램
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [ShaderSet()](#ShaderSet--) | [ShaderSet](../../com.aspose.threed/shaderset) 인스턴스를 생성합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [close()](#close--) | 이 인스턴스를 해제하고 모든 셰이더 프로그램을 해제합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFallback()](#getFallback--) | 필요한 셰이더를 사용할 수 없을 때 대체 셰이더를 가져옵니다. |
| [getLambert()](#getLambert--) | 람버트 재질을 렌더링하는 데 사용되는 셰이더를 가져옵니다. |
| [getPbr()](#getPbr--) | PBR 재질을 렌더링하는 데 사용되는 셰이더를 가져옵니다. |
| [getPhong()](#getPhong--) | 퐁 재질을 렌더링하는 데 사용되는 셰이더를 가져옵니다. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFallback(ShaderProgram value)](#setFallback-com.aspose.threed.ShaderProgram-) | 필요한 셰이더를 사용할 수 없을 때 대체 셰이더를 설정합니다. |
| [setLambert(ShaderProgram value)](#setLambert-com.aspose.threed.ShaderProgram-) | 람버트 재질을 렌더링하는 데 사용되는 셰이더를 설정합니다. |
| [setPbr(ShaderProgram value)](#setPbr-com.aspose.threed.ShaderProgram-) | PBR 재질을 렌더링하는 데 사용되는 셰이더를 설정합니다. |
| [setPhong(ShaderProgram value)](#setPhong-com.aspose.threed.ShaderProgram-) | 퐁 재질을 렌더링하는 데 사용되는 셰이더를 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ShaderSet() {#ShaderSet--}
```
public ShaderSet()
```


[ShaderSet](../../com.aspose.threed/shaderset) 인스턴스를 생성합니다.

### close() {#close--}
```
public void close()
```


이 인스턴스를 해제하고 모든 셰이더 프로그램을 해제합니다.

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
### getFallback() {#getFallback--}
```
public ShaderProgram getFallback()
```


필요한 셰이더를 사용할 수 없을 때 대체 셰이더를 가져옵니다.

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the fallback shader when required shader is unavailable
### getLambert() {#getLambert--}
```
public ShaderProgram getLambert()
```


람버트 재질을 렌더링하는 데 사용되는 셰이더를 가져옵니다.

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the lambert material
### getPbr() {#getPbr--}
```
public ShaderProgram getPbr()
```


PBR 재질을 렌더링하는 데 사용되는 셰이더를 가져옵니다.

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the PBR material
### getPhong() {#getPhong--}
```
public ShaderProgram getPhong()
```


퐁 재질을 렌더링하는 데 사용되는 셰이더를 가져옵니다.

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the phong material
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




### setFallback(ShaderProgram value) {#setFallback-com.aspose.threed.ShaderProgram-}
```
public void setFallback(ShaderProgram value)
```


필요한 셰이더를 사용할 수 없을 때 대체 셰이더를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | 새 값 |

### setLambert(ShaderProgram value) {#setLambert-com.aspose.threed.ShaderProgram-}
```
public void setLambert(ShaderProgram value)
```


람버트 재질을 렌더링하는 데 사용되는 셰이더를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | 새 값 |

### setPbr(ShaderProgram value) {#setPbr-com.aspose.threed.ShaderProgram-}
```
public void setPbr(ShaderProgram value)
```


PBR 재질을 렌더링하는 데 사용되는 셰이더를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | 새 값 |

### setPhong(ShaderProgram value) {#setPhong-com.aspose.threed.ShaderProgram-}
```
public void setPhong(ShaderProgram value)
```


퐁 재질을 렌더링하는 데 사용되는 셰이더를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | 새 값 |

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

