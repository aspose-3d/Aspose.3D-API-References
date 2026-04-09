---
title: Watermark
second_title: Aspose.3D for Java API 레퍼런스
description: 메시에서 블라인드 워터마크를 인코딩/디코딩하기 위한 유틸리티.
type: docs
weight: 230
url: /ko/java/com.aspose.threed/watermark/
---

**Inheritance:**
java.lang.Object
```
public class Watermark
```

메시에서 블라인드 워터마크를 인코딩/디코딩하기 위한 유틸리티. **비고:** 두 [Watermark](../../com.aspose.threed/watermark) 및 [Watermark](../../com.aspose.threed/watermark)은 라이선스 검사를 수행합니다. 체험판 사용 시 예외가 발생하며, [TrialException.getSuppressTrialException](../../com.aspose.threed/trialexception\#getSuppressTrialException)를 사용하여 예외를 억제할 수 있지만 여기서는 제한이 해제되지 않습니다. 제한 없이 이 기능을 사용하려면 유효한 라이선스가 필요합니다. **예시:** 다음 코드는 블라인드 워터마크를 메시에 인코딩하고 디코딩하는 방법을 보여줍니다.

```
Mesh mesh = (new Cylinder()).toMesh();
     Mesh encodedMesh = Watermark.encodeWatermark(mesh, "Hello", null);
     String watermark = Watermark.decodeWatermark(encodedMesh, null);
```
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [decodeWatermark(Mesh input)](#decodeWatermark-com.aspose.threed.Mesh-) | 메시에서 워터마크를 디코딩합니다. |
| [decodeWatermark(Mesh input, String password)](#decodeWatermark-com.aspose.threed.Mesh-java.lang.String-) | 메시에서 워터마크를 디코딩합니다. |
| [encodeWatermark(Mesh input, String text)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-) | 텍스트를 메시의 블라인드 워터마크에 인코딩합니다. |
| [encodeWatermark(Mesh input, String text, String password)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-) | 텍스트를 메시의 블라인드 워터마크에 인코딩합니다. |
| [encodeWatermark(Mesh input, String text, String password, boolean permanent)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-boolean-) | 텍스트를 메시의 블라인드 워터마크에 인코딩합니다. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### decodeWatermark(Mesh input) {#decodeWatermark-com.aspose.threed.Mesh-}
```
public static String decodeWatermark(Mesh input)
```


메시에서 워터마크를 디코딩합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | 워터마크를 추출할 메시. |

**Returns:**
java.lang.String - 워터마크가 디코딩되지 않은 경우 블라인드 워터마크 또는 null.
### decodeWatermark(Mesh input, String password) {#decodeWatermark-com.aspose.threed.Mesh-java.lang.String-}
```
public static String decodeWatermark(Mesh input, String password)
```


메시에서 워터마크를 디코딩합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | 워터마크를 추출할 메시. |
| 비밀번호 | java.lang.String | 워터마크를 복호화하기 위한 비밀번호. |

**Returns:**
java.lang.String - 워터마크가 디코딩되지 않은 경우 블라인드 워터마크 또는 null.
### encodeWatermark(Mesh input, String text) {#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-}
```
public static Mesh encodeWatermark(Mesh input, String text)
```


텍스트를 메시의 블라인드 워터마크에 인코딩합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | 블라인드 워터마크를 인코딩할 메시. |
| 텍스트 | java.lang.String | 메시로 인코딩할 텍스트. |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - A new mesh instance with blind watermark encoded **Remarks:** Both [Watermark](../../com.aspose.threed/watermark) and [Watermark](../../com.aspose.threed/watermark) will perform license check Trial usage will throw exception, you can use [TrialException.getSuppressTrialException](../../com.aspose.threed/trialexception\#getSuppressTrialException) to suppress the exception, but it will not lift the restriction here. A valid license is required to use these features without any restrictions. **Example:** The following code shows how to encode a blind watermark into a mesh and save to ply file

```
Mesh mesh = (new Cylinder()).toMesh();
     Mesh encodedMesh = Watermark.encodeWatermark(mesh, "Hello");
     new Scene(encodedMesh).save("test.ply");
```
### encodeWatermark(Mesh input, String text, String password) {#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-}
```
public static Mesh encodeWatermark(Mesh input, String text, String password)
```


텍스트를 메시의 블라인드 워터마크에 인코딩합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | 블라인드 워터마크를 인코딩할 메시. |
| 텍스트 | java.lang.String | 메시로 인코딩할 텍스트. |
| 비밀번호 | java.lang.String | 워터마크를 보호하기 위한 비밀번호(선택 사항). |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - A new mesh instance with blind watermark encoded **Remarks:** Both [Watermark](../../com.aspose.threed/watermark) and [Watermark](../../com.aspose.threed/watermark) will perform license check Trial usage will throw exception, you can use [TrialException.getSuppressTrialException](../../com.aspose.threed/trialexception\#getSuppressTrialException) to suppress the exception, but it will not lift the restriction here. A valid license is required to use these features without any restrictions. **Example:** The following code shows how to encode a blind watermark into a mesh and save to ply file

```
Mesh mesh = (new Cylinder()).toMesh();
     var encodedMesh = Watermark.encodeWatermark(mesh, "Hello", "password");
     new Scene(encodedMesh).save("test.ply");
```
### encodeWatermark(Mesh input, String text, String password, boolean permanent) {#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-boolean-}
```
public static Mesh encodeWatermark(Mesh input, String text, String password, boolean permanent)
```


텍스트를 메시의 블라인드 워터마크에 인코딩합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | 블라인드 워터마크를 인코딩할 메시. |
| 텍스트 | java.lang.String | 메시로 인코딩할 텍스트. |
| 비밀번호 | java.lang.String | 워터마크를 보호하기 위한 비밀번호(선택 사항). |
| 영구적인 | boolean | 영구적인 워터마크는 덮어쓰거나 제거되지 않습니다. |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - A new mesh instance with blind watermark encoded **Remarks:** Both [Watermark](../../com.aspose.threed/watermark) and [Watermark](../../com.aspose.threed/watermark) will perform license check Trial usage will throw exception, you can use [TrialException.getSuppressTrialException](../../com.aspose.threed/trialexception\#getSuppressTrialException) to suppress the exception, but it will not lift the restriction here. A valid license is required to use these features without any restrictions. **Example:** The following code shows how to encode a blind watermark into a mesh and save to ply file

```
Mesh mesh = (new Cylinder()).toMesh();
     var encodedMesh = Watermark.encodeWatermark(mesh, "Hello", "password");
     new Scene(encodedMesh).save("test.ply");
```
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

