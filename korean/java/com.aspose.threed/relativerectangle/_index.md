---
title: RelativeRectangle
second_title: Aspose.3D for Java API 레퍼런스
description: Relative rectangle  상대 구성 요소와 절대 값 사이의 공식은  Scale  Reference Width  offset  입니다. 절대 값을 나타내려면 모든 scale 필드를 0으로 두고 offset 필드를 대신 사용하십시오.
type: docs
weight: 147
url: /ko/java/com.aspose.threed/relativerectangle/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class RelativeRectangle implements Struct<RelativeRectangle>, Serializable
```

상대 사각형 상대 구성 요소와 절대 값 사이의 공식은 다음과 같습니다: Scale \* (Reference Width) + offset 따라서 절대 값을 나타내려면 모든 스케일 필드를 0으로 두고 대신 오프셋 필드를 사용하십시오.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [RelativeRectangle(int left, int top, int width, int height)](#RelativeRectangle-int-int-int-int-) | 생성합니다 [RelativeRectangle](../../com.aspose.threed/relativerectangle) |
| [RelativeRectangle()](#RelativeRectangle--) |  |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(RelativeRectangle src)](#copyFrom-com.aspose.threed.RelativeRectangle-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight)](#fromScale-float-float-float-float-) | 모든 offset 필드를 0으로 하고 주어진 매개변수에서 scale 필드를 사용하여 [RelativeRectangle](../../com.aspose.threed/relativerectangle)를 생성합니다. |
| [getClass()](#getClass--) |  |
| [getOffsetHeight()](#getOffsetHeight--) | 높이에 대한 offset을 가져옵니다 |
| [getOffsetWidth()](#getOffsetWidth--) | 너비에 대한 offset을 가져옵니다 |
| [getOffsetX()](#getOffsetX--) | 좌표 X에 대한 offset을 가져옵니다 |
| [getOffsetY()](#getOffsetY--) | 좌표 Y에 대한 offset을 가져옵니다 |
| [getScaleHeight()](#getScaleHeight--) | 상대 높이 |
| [getScaleWidth()](#getScaleWidth--) | 상대 너비 |
| [getScaleX()](#getScaleX--) | 상대 좌표 X |
| [getScaleY()](#getScaleY--) | 상대 좌표 Y |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOffsetHeight(int value)](#setOffsetHeight-int-) | 높이에 대한 offset을 설정합니다 |
| [setOffsetWidth(int value)](#setOffsetWidth-int-) | 너비에 대한 offset을 설정합니다 |
| [setOffsetX(int value)](#setOffsetX-int-) | 좌표 X에 대한 offset을 설정합니다 |
| [setOffsetY(int value)](#setOffsetY-int-) | 좌표 Y에 대한 offset을 설정합니다 |
| [setScaleHeight(float value)](#setScaleHeight-float-) | 상대 높이 |
| [setScaleWidth(float value)](#setScaleWidth-float-) | 상대 너비 |
| [setScaleX(float value)](#setScaleX-float-) | 상대 좌표 X |
| [setScaleY(float value)](#setScaleY-float-) | 상대 좌표 Y |
| [toAbsolute(int left, int top, int width, int height)](#toAbsolute-int-int-int-int-) | 상대 사각형을 절대 사각형으로 변환합니다 |
| [toString()](#toString--) | 이 인스턴스의 값을 java.lang.String으로 변환합니다. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RelativeRectangle(int left, int top, int width, int height) {#RelativeRectangle-int-int-int-int-}
```
public RelativeRectangle(int left, int top, int width, int height)
```


생성합니다 [RelativeRectangle](../../com.aspose.threed/relativerectangle)

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 왼쪽 | int |  |
| 위쪽 | int |  |
| 너비 | int |  |
| 높이 | int |  |

### RelativeRectangle() {#RelativeRectangle--}
```
public RelativeRectangle()
```


### clone() {#clone--}
```
public RelativeRectangle clone()
```


현재 인스턴스를 복제합니다

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle)
### copyFrom(RelativeRectangle src) {#copyFrom-com.aspose.threed.RelativeRectangle-}
```
public void copyFrom(RelativeRectangle src)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| src | [RelativeRectangle](../../com.aspose.threed/relativerectangle) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight) {#fromScale-float-float-float-float-}
```
public static RelativeRectangle fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight)
```


모든 offset 필드를 0으로 하고 주어진 매개변수에서 scale 필드를 사용하여 [RelativeRectangle](../../com.aspose.threed/relativerectangle)를 생성합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| scaleX | float |  |
| scaleY | float |  |
| scaleWidth | float |  |
| scaleHeight | float |  |

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getOffsetHeight() {#getOffsetHeight--}
```
public int getOffsetHeight()
```


높이에 대한 offset을 가져옵니다

**Returns:**
int - 높이에 대한 오프셋
### getOffsetWidth() {#getOffsetWidth--}
```
public int getOffsetWidth()
```


너비에 대한 offset을 가져옵니다

**Returns:**
int - 너비에 대한 오프셋
### getOffsetX() {#getOffsetX--}
```
public int getOffsetX()
```


좌표 X에 대한 offset을 가져옵니다

**Returns:**
int - X 좌표에 대한 오프셋
### getOffsetY() {#getOffsetY--}
```
public int getOffsetY()
```


좌표 Y에 대한 offset을 가져옵니다

**Returns:**
int - Y 좌표에 대한 오프셋
### getScaleHeight() {#getScaleHeight--}
```
public float getScaleHeight()
```


상대 높이

**Returns:**
float - 상대 높이
### getScaleWidth() {#getScaleWidth--}
```
public float getScaleWidth()
```


상대 너비

**Returns:**
float - 상대 너비
### getScaleX() {#getScaleX--}
```
public float getScaleX()
```


상대 좌표 X

**Returns:**
float - 상대 X 좌표
### getScaleY() {#getScaleY--}
```
public float getScaleY()
```


상대 좌표 Y

**Returns:**
float - 상대 Y 좌표
### hashCode() {#hashCode--}
```
public int hashCode()
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




### setOffsetHeight(int value) {#setOffsetHeight-int-}
```
public void setOffsetHeight(int value)
```


높이에 대한 offset을 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 새 값 |

### setOffsetWidth(int value) {#setOffsetWidth-int-}
```
public void setOffsetWidth(int value)
```


너비에 대한 offset을 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 새 값 |

### setOffsetX(int value) {#setOffsetX-int-}
```
public void setOffsetX(int value)
```


좌표 X에 대한 offset을 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 새 값 |

### setOffsetY(int value) {#setOffsetY-int-}
```
public void setOffsetY(int value)
```


좌표 Y에 대한 offset을 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | int | 새 값 |

### setScaleHeight(float value) {#setScaleHeight-float-}
```
public void setScaleHeight(float value)
```


상대 높이

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float | 새 값 |

### setScaleWidth(float value) {#setScaleWidth-float-}
```
public void setScaleWidth(float value)
```


상대 너비

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float | 새 값 |

### setScaleX(float value) {#setScaleX-float-}
```
public void setScaleX(float value)
```


상대 좌표 X

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float | 새 값 |

### setScaleY(float value) {#setScaleY-float-}
```
public void setScaleY(float value)
```


상대 좌표 Y

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | float | 새 값 |

### toAbsolute(int left, int top, int width, int height) {#toAbsolute-int-int-int-int-}
```
public Rect toAbsolute(int left, int top, int width, int height)
```


상대 사각형을 절대 사각형으로 변환합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 왼쪽 | int | 사각형의 왼쪽 |
| 위쪽 | int | 사각형의 위쪽 |
| 너비 | int | 사각형의 너비 |
| 높이 | int | 사각형의 높이 |

**Returns:**
[Rect](../../com.aspose.threed/rect)
### toString() {#toString--}
```
public String toString()
```


이 인스턴스의 값을 java.lang.String으로 변환합니다.

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

