---
title: 구조체
second_title: Aspose.3D for Java API 레퍼런스
description: 2017년 11월 13일에 lexchou가 만들었습니다.
type: docs
weight: 262
url: /ko/java/com.aspose.threed/struct/
---

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public interface Struct<T> extends Cloneable, Serializable
```

2017년 11월 13일에 lexchou가 만들었습니다.
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [<T>byVal(T value)](#-T-byVal-T-) | 입력 값이 구조체이면 복사해 보세요 |
| [clone()](#clone--) | 현재 인스턴스를 복제합니다 |
| [copyFrom(T t)](#copyFrom-T-) | 인수 t에서 내부 상태를 복사합니다 |
### <T>byVal(T value) {#-T-byVal-T-}
```
public static T <T>byVal(T value)
```


입력 값이 구조체이면 복사해 보세요

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | T | 복제할 입력 값 |

**Returns:**
T - 입력이 null이거나 복제된 인스턴스인 경우 null
### clone() {#clone--}
```
public abstract T clone()
```


현재 인스턴스를 복제합니다

**Returns:**
T - 복제된 인스턴스
### copyFrom(T t) {#copyFrom-T-}
```
public abstract void copyFrom(T t)
```


인수 t에서 내부 상태를 복사합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| t | T | 복사할 소스 인스턴스 |

