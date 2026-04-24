---
title: PdfRenderMode
second_title: Aspose.3D for Java API リファレンス
description: レンダーモードは 3D アートワークがレンダリングされるスタイルを指定します。
type: docs
weight: 289
url: /ja/java/com.aspose.threed/pdfrendermode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum PdfRenderMode extends Enum<PdfRenderMode>
```

レンダーモードは 3D アートワークがレンダリングされるスタイルを指定します。
## フィールド

| フィールド | 説明 |
| --- | --- |
| [BOUNDING_BOX](#BOUNDING-BOX) | 各ノードのバウンディングボックスのエッジを表示し、そのノードのローカル座標空間の軸に合わせます。 |
| [HIDDEN_WIREFRAME](#HIDDEN-WIREFRAME) | エッジを単一の色で表示しますが、背面向きや隠れたエッジは除去します。 |
| [ILLUSTRATION](#ILLUSTRATION) | シルエットエッジを表面と共に表示し、隠れた線を除去します。 |
| [SHADED_ILLUSTRATION](#SHADED-ILLUSTRATION) | シルエットエッジを照明されたテクスチャ表面と共に表示し、作品の光が不足した領域を除去する追加の放射項を適用します。 |
| [SHADED_VERTICES](#SHADED-VERTICES) | 頂点のみを表示しますが、頂点カラーを使用し、ライティングを適用します。 |
| [SHADED_WIREFRAME](#SHADED-WIREFRAME) | エッジのみを表示しますが、2つの頂点間で色を補間し、ライティングを適用します。 |
| [SOLID](#SOLID) | テクスチャと照明が適用された幾何学的形状を表示します。 |
| [SOLID_OUTLINE](#SOLID-OUTLINE) | シルエットエッジを照明されたテクスチャ表面と共に表示し、隠れた線を除去します。 |
| [SOLID_WIREFRAME](#SOLID-WIREFRAME) | テクスチャと照明が適用された幾何学的形状（三角形）を表示し、その上に単一色のエッジを重ねます。 |
| [TRANSPARENT](#TRANSPARENT) | テクスチャと照明が適用された幾何学的形状（三角形）を表示し、透明度を追加します。 |
| [TRANSPARENT_BOUNDING_BOX](#TRANSPARENT-BOUNDING-BOX) | 各ノードのバウンディングボックスの面を表示し、ローカル座標空間の軸に合わせ、透明度を追加します。 |
| [TRANSPARENT_BOUNDING_BOX_OUTLINE](#TRANSPARENT-BOUNDING-BOX-OUTLINE) | 各ノードのバウンディングボックスのエッジと面を表示し、ローカル座標空間の軸に合わせ、透明度を追加します。 |
| [TRANSPARENT_WIREFRAME](#TRANSPARENT-WIREFRAME) | テクスチャと照明が適用された幾何学的形状（三角形）を透明度を追加して表示し、その上に単一色の不透明エッジを重ねます。 |
| [VERTICES](#VERTICES) | 単一色で頂点のみを表示します。 |
| [WIREFRAME](#WIREFRAME) | 単一色でエッジのみを表示します。 |
## Methods

| Method | 説明 |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BOUNDING_BOX {#BOUNDING-BOX}
```
public static final PdfRenderMode BOUNDING_BOX
```


各ノードのバウンディングボックスのエッジを表示し、そのノードのローカル座標空間の軸に合わせます。

### HIDDEN_WIREFRAME {#HIDDEN-WIREFRAME}
```
public static final PdfRenderMode HIDDEN_WIREFRAME
```


エッジを単一の色で表示しますが、背面向きや隠れたエッジは除去します。

### ILLUSTRATION {#ILLUSTRATION}
```
public static final PdfRenderMode ILLUSTRATION
```


シルエットエッジを表面と共に表示し、隠れた線を除去します。

### SHADED_ILLUSTRATION {#SHADED-ILLUSTRATION}
```
public static final PdfRenderMode SHADED_ILLUSTRATION
```


シルエットエッジを照明されたテクスチャ表面と共に表示し、作品の光が不足した領域を除去する追加の放射項を適用します。

### SHADED_VERTICES {#SHADED-VERTICES}
```
public static final PdfRenderMode SHADED_VERTICES
```


頂点のみを表示しますが、頂点カラーを使用し、ライティングを適用します。

### SHADED_WIREFRAME {#SHADED-WIREFRAME}
```
public static final PdfRenderMode SHADED_WIREFRAME
```


エッジのみを表示しますが、2つの頂点間で色を補間し、ライティングを適用します。

### SOLID {#SOLID}
```
public static final PdfRenderMode SOLID
```


テクスチャと照明が適用された幾何学的形状を表示します。

### SOLID_OUTLINE {#SOLID-OUTLINE}
```
public static final PdfRenderMode SOLID_OUTLINE
```


シルエットエッジを照明されたテクスチャ表面と共に表示し、隠れた線を除去します。

### SOLID_WIREFRAME {#SOLID-WIREFRAME}
```
public static final PdfRenderMode SOLID_WIREFRAME
```


テクスチャと照明が適用された幾何学的形状（三角形）を表示し、その上に単一色のエッジを重ねます。

### TRANSPARENT {#TRANSPARENT}
```
public static final PdfRenderMode TRANSPARENT
```


テクスチャと照明が適用された幾何学的形状（三角形）を表示し、透明度を追加します。

### TRANSPARENT_BOUNDING_BOX {#TRANSPARENT-BOUNDING-BOX}
```
public static final PdfRenderMode TRANSPARENT_BOUNDING_BOX
```


各ノードのバウンディングボックスの面を表示し、ローカル座標空間の軸に合わせ、透明度を追加します。

### TRANSPARENT_BOUNDING_BOX_OUTLINE {#TRANSPARENT-BOUNDING-BOX-OUTLINE}
```
public static final PdfRenderMode TRANSPARENT_BOUNDING_BOX_OUTLINE
```


各ノードのバウンディングボックスのエッジと面を表示し、ローカル座標空間の軸に合わせ、透明度を追加します。

### TRANSPARENT_WIREFRAME {#TRANSPARENT-WIREFRAME}
```
public static final PdfRenderMode TRANSPARENT_WIREFRAME
```


テクスチャと照明が適用された幾何学的形状（三角形）を透明度を追加して表示し、その上に単一色の不透明エッジを重ねます。

### VERTICES {#VERTICES}
```
public static final PdfRenderMode VERTICES
```


単一色で頂点のみを表示します。

### WIREFRAME {#WIREFRAME}
```
public static final PdfRenderMode WIREFRAME
```


単一色でエッジのみを表示します。

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 説明 |
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
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static PdfRenderMode valueOf(String name)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[PdfRenderMode](../../com.aspose.threed/pdfrendermode)
### values() {#values--}
```
public static PdfRenderMode[] values()
```




**Returns:**
com.aspose.threed.PdfRenderMode[]
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

