---
title: 계량식
second_title: Aspose.3D for Java API 레퍼런스
description: 계량된 키를 설정하는 메서드를 제공합니다.
type: docs
weight: 103
url: /ko/java/com.aspose.threed/metered/
---

**Inheritance:**
java.lang.Object
```
public class Metered
```

계량된 키를 설정하는 메서드를 제공합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Metered()](#Metered--) | 이 클래스의 새 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getConsumptionCredit()](#getConsumptionCredit--) | 소비 크레딧을 가져옵니다 |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | 소비 파일 크기를 가져옵니다 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | 계량식 공개 및 개인 키를 설정합니다. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Metered() {#Metered--}
```
public Metered()
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
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


소비 크레딧을 가져옵니다

**Returns:**
double - 소비 양
### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


소비 파일 크기를 가져옵니다

**Returns:**
double - 소비 양
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




### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


계량식 공개 및 개인 키를 설정합니다. 계량식 라이선스를 구매한 경우, 애플리케이션을 시작할 때 이 API를 호출해야 하며, 일반적으로 이것만으로 충분합니다. 그러나 소비 데이터 업로드에 지속적으로 실패하고 24시간을 초과하면 라이선스가 평가 상태로 전환됩니다. 이러한 상황을 방지하려면 라이선스 상태를 정기적으로 확인하고, 평가 상태인 경우 이 API를 다시 호출해야 합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| publicKey | java.lang.String | 공개 키 |
| privateKey | java.lang.String | 개인 키 |

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

