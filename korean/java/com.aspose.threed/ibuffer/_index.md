---
title: IBuffer
second_title: Aspose.3D for Java API 레퍼런스
description: 렌더링에 사용되는 모든 관리 버퍼의 기본 인터페이스
type: docs
weight: 239
url: /ko/java/com.aspose.threed/ibuffer/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface IBuffer extends Closeable
```

렌더링에 사용되는 모든 관리 버퍼의 기본 인터페이스
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getSize()](#getSize--) | 이 버퍼의 크기(바이트 단위). |
| [loadData(byte[] data)](#loadData-byte---) | 데이터를 현재 버퍼에 로드합니다. |
### getSize() {#getSize--}
```
public abstract int getSize()
```


이 버퍼의 크기(바이트 단위).

**Returns:**
int - 이 버퍼의 크기(바이트 단위)
### loadData(byte[] data) {#loadData-byte---}
```
public abstract void loadData(byte[] data)
```


데이터를 현재 버퍼에 로드합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 데이터 | byte[] |  |

