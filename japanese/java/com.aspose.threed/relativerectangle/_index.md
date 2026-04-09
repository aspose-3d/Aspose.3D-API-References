---
title: RelativeRectangle
second_title: Aspose.3D for Java API リファレンス
description: 相対矩形  相対コンポーネントと絶対値の間の式は  Scale  Reference Width  offset  です。したがって、絶対値を表す場合は、すべてのスケールフィールドをゼロにし、代わりにオフセットフィールドを使用します。
type: docs
weight: 147
url: /ja/java/com.aspose.threed/relativerectangle/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class RelativeRectangle implements Struct<RelativeRectangle>, Serializable
```

相対矩形 相対コンポーネントと絶対値の間の式は: Scale \* (Reference Width) + offset です。したがって、絶対値を表したい場合は、すべてのスケールフィールドを0にし、代わりにオフセットフィールドを使用してください。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [RelativeRectangle(int left, int top, int width, int height)](#RelativeRectangle-int-int-int-int-) | [RelativeRectangle](../../com.aspose.threed/relativerectangle) を構築する |
| [RelativeRectangle()](#RelativeRectangle--) |  |
## Methods

| Method | 説明 |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(RelativeRectangle src)](#copyFrom-com.aspose.threed.RelativeRectangle-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight)](#fromScale-float-float-float-float-) | [RelativeRectangle](../../com.aspose.threed/relativerectangle) を、すべてのオフセットフィールドをゼロにし、スケールフィールドを指定されたパラメータから設定して構築する。 |
| [getClass()](#getClass--) |  |
| [getOffsetHeight()](#getOffsetHeight--) | 高さのオフセットを取得する |
| [getOffsetWidth()](#getOffsetWidth--) | 幅のオフセットを取得する |
| [getOffsetX()](#getOffsetX--) | 座標 X のオフセットを取得する |
| [getOffsetY()](#getOffsetY--) | 座標 Y のオフセットを取得する |
| [getScaleHeight()](#getScaleHeight--) | 相対高さ |
| [getScaleWidth()](#getScaleWidth--) | 相対幅 |
| [getScaleX()](#getScaleX--) | 相対座標 X |
| [getScaleY()](#getScaleY--) | 相対座標 Y |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOffsetHeight(int value)](#setOffsetHeight-int-) | 高さのオフセットを設定する |
| [setOffsetWidth(int value)](#setOffsetWidth-int-) | 幅のオフセットを設定する |
| [setOffsetX(int value)](#setOffsetX-int-) | 座標 X のオフセットを設定する |
| [setOffsetY(int value)](#setOffsetY-int-) | 座標 Y のオフセットを設定する |
| [setScaleHeight(float value)](#setScaleHeight-float-) | 相対高さ |
| [setScaleWidth(float value)](#setScaleWidth-float-) | 相対幅 |
| [setScaleX(float value)](#setScaleX-float-) | 相対座標 X |
| [setScaleY(float value)](#setScaleY-float-) | 相対座標 Y |
| [toAbsolute(int left, int top, int width, int height)](#toAbsolute-int-int-int-int-) | 相対矩形を絶対矩形に変換する |
| [toString()](#toString--) | このインスタンスの値を java.lang.String に変換する。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RelativeRectangle(int left, int top, int width, int height) {#RelativeRectangle-int-int-int-int-}
```
public RelativeRectangle(int left, int top, int width, int height)
```


[RelativeRectangle](../../com.aspose.threed/relativerectangle) を構築する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 左 | int |  |
| 上 | int |  |
| 幅 | int |  |
| 高さ | int |  |

### RelativeRectangle() {#RelativeRectangle--}
```
public RelativeRectangle()
```


### clone() {#clone--}
```
public RelativeRectangle clone()
```


現在のインスタンスをクローンする

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle)
### copyFrom(RelativeRectangle src) {#copyFrom-com.aspose.threed.RelativeRectangle-}
```
public void copyFrom(RelativeRectangle src)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| src | [RelativeRectangle](../../com.aspose.threed/relativerectangle) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight) {#fromScale-float-float-float-float-}
```
public static RelativeRectangle fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight)
```


[RelativeRectangle](../../com.aspose.threed/relativerectangle) を、すべてのオフセットフィールドをゼロにし、スケールフィールドを指定されたパラメータから設定して構築する。

**Parameters:**
| Parameter | Type | 説明 |
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


高さのオフセットを取得する

**Returns:**
int - 高さのオフセット
### getOffsetWidth() {#getOffsetWidth--}
```
public int getOffsetWidth()
```


幅のオフセットを取得する

**Returns:**
int - 幅のオフセット
### getOffsetX() {#getOffsetX--}
```
public int getOffsetX()
```


座標 X のオフセットを取得する

**Returns:**
int - X座標のオフセット
### getOffsetY() {#getOffsetY--}
```
public int getOffsetY()
```


座標 Y のオフセットを取得する

**Returns:**
int - Y座標のオフセット
### getScaleHeight() {#getScaleHeight--}
```
public float getScaleHeight()
```


相対高さ

**Returns:**
float - 相対高さ
### getScaleWidth() {#getScaleWidth--}
```
public float getScaleWidth()
```


相対幅

**Returns:**
float - 相対幅
### getScaleX() {#getScaleX--}
```
public float getScaleX()
```


相対座標 X

**Returns:**
float - X座標の相対値
### getScaleY() {#getScaleY--}
```
public float getScaleY()
```


相対座標 Y

**Returns:**
float - Y座標の相対値
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


高さのオフセットを設定する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

### setOffsetWidth(int value) {#setOffsetWidth-int-}
```
public void setOffsetWidth(int value)
```


幅のオフセットを設定する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

### setOffsetX(int value) {#setOffsetX-int-}
```
public void setOffsetX(int value)
```


座標 X のオフセットを設定する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

### setOffsetY(int value) {#setOffsetY-int-}
```
public void setOffsetY(int value)
```


座標 Y のオフセットを設定する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | int | 新しい値 |

### setScaleHeight(float value) {#setScaleHeight-float-}
```
public void setScaleHeight(float value)
```


相対高さ

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | float | 新しい値 |

### setScaleWidth(float value) {#setScaleWidth-float-}
```
public void setScaleWidth(float value)
```


相対幅

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | float | 新しい値 |

### setScaleX(float value) {#setScaleX-float-}
```
public void setScaleX(float value)
```


相対座標 X

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | float | 新しい値 |

### setScaleY(float value) {#setScaleY-float-}
```
public void setScaleY(float value)
```


相対座標 Y

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | float | 新しい値 |

### toAbsolute(int left, int top, int width, int height) {#toAbsolute-int-int-int-int-}
```
public Rect toAbsolute(int left, int top, int width, int height)
```


相対矩形を絶対矩形に変換する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 左 | int | 矩形の左側 |
| 上 | int | 矩形の上側 |
| 幅 | int | 矩形の幅 |
| 高さ | int | 矩形の高さ |

**Returns:**
[Rect](../../com.aspose.threed/rect)
### toString() {#toString--}
```
public String toString()
```


このインスタンスの値を java.lang.String に変換する。

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
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

