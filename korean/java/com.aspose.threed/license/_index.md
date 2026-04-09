---
title: 라이선스
second_title: Aspose.3D for Java API 레퍼런스
description: 구성 요소를 라이선스하는 메서드를 제공합니다.
type: docs
weight: 93
url: /ko/java/com.aspose.threed/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

구성 요소를 라이선스하는 메서드를 제공합니다.

자세히 알아보려면 **Licensing and Subscription** 문서 기사를 방문하십시오.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [License()](#License--) | 이 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | 구성 요소에 라이선스를 적용합니다. |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | 구성 요소에 라이선스를 적용합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### License() {#License--}
```
public License()
```


이 클래스의 새 인스턴스를 초기화합니다.

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




### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public void setLicense(InputStream stream)
```


구성 요소에 라이선스를 적용합니다.

이 메서드를 사용하여 스트림에서 라이선스를 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 스트림 | java.io.InputStream | 라이선스를 포함하는 스트림입니다. |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public void setLicense(String licenseName)
```


구성 요소에 라이선스를 적용합니다.

다음 위치에서 라이선스를 찾으려고 시도합니다:

1. 명시적 경로.

2. Aspose 구성 요소 JAR 파일이 들어 있는 폴더.

3. 클라이언트가 호출하는 JAR 파일이 들어 있는 폴더.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| licenseName | java.lang.String | 전체 파일 이름이거나 짧은 파일 이름일 수 있습니다. 빈 문자열을 사용하면 평가 모드로 전환됩니다. |

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

