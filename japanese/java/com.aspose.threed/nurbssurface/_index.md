---
title: NurbsSurface
second_title: Aspose.3D for Java API リファレンス
description: NURBS（非一様有理基底スプライン）で表現されるサーフェスです。Aは2つの と で定義されます。
type: docs
weight: 114
url: /ja/java/com.aspose.threed/nurbssurface/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Geometry](../../com.aspose.threed/geometry)

**All Implemented Interfaces:**
[com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class NurbsSurface extends Geometry implements IMeshConvertible
```

[NurbsSurface](../../com.aspose.threed/nurbssurface) is a surface represented by [NURBS(Non-uniform rational basis spline)][NURBS_Non-uniform rational basis spline], A [NurbsSurface](../../com.aspose.threed/nurbssurface) is defined by two [NurbsDirection](../../com.aspose.threed/nurbsdirection)[getU](../../com.aspose.threed/nurbssurface\#getU) and [getV](../../com.aspose.threed/nurbssurface\#getV). The w component in control point is used as control point's weight whatever the direction's type is a [CurveDimension.TWO\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#TWO-DIMENSIONAL) or [CurveDimension.THREE\_DIMENSIONAL](../../com.aspose.threed/curvedimension\#THREE-DIMENSIONAL)


[NURBS_Non-uniform rational basis spline]: https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline
## Constructors

| Constructor | 説明 |
| --- | --- |
| [NurbsSurface()](#NurbsSurface--) | [NurbsSurface](../../com.aspose.threed/nurbssurface) クラスの新しいインスタンスを初期化します。 |
| [NurbsSurface(String name)](#NurbsSurface-java.lang.String-) | [NurbsSurface](../../com.aspose.threed/nurbssurface) クラスの新しいインスタンスを初期化します。 |
## Methods

| Method | 説明 |
| --- | --- |
| [<T>getDeformers2()](#-T-getDeformers2--) | Gets all deformers with specified deformer types |
| [addElement(VertexElement element)](#addElement-com.aspose.threed.VertexElement-) | Adds an existing vertex element to current geometry |
| [createElement(VertexElementType type)](#createElement-com.aspose.threed.VertexElementType-) | Creates a vertex element with specified type and add it to the geometry. |
| [createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)](#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Creates a vertex element with specified type and add it to the geometry. |
| [createElementUV(TextureMapping uvMapping)](#createElementUV-com.aspose.threed.TextureMapping-) | 指定されたテクスチャマッピングタイプで [VertexElementUV](../../com.aspose.threed/vertexelementuv) を作成します。 |
| [createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)](#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | 指定されたテクスチャマッピングタイプで [VertexElementUV](../../com.aspose.threed/vertexelementuv) を作成します。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | プロパティを検索します。 |
| [getBoundingBox()](#getBoundingBox--) | 現在のエンティティのオブジェクト空間座標系におけるバウンディングボックスを取得します。 |
| [getCastShadows()](#getCastShadows--) | このジオメトリが影を落とすかどうかを取得します |
| [getClass()](#getClass--) |  |
| [getControlPoints()](#getControlPoints--) | すべての制御点を取得します。 |
| [getDeformers()](#getDeformers--) | このジオメトリに関連付けられたすべてのデフォーマーを取得します。 |
| [getElement(VertexElementType type)](#getElement-com.aspose.threed.VertexElementType-) | 指定されたタイプの頂点要素を取得します |
| [getEntityRendererKey()](#getEntityRendererKey--) | レンダラーに登録されたエンティティレンダラーのキーを取得します |
| [getExcluded()](#getExcluded--) | エクスポート時にこのエンティティを除外するかどうかを取得します。 |
| [getName()](#getName--) | 名前を取得します。 |
| [getParentNode()](#getParentNode--) | 最初の親ノードを取得します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。 |
| [getParentNodes()](#getParentNodes--) | すべての親ノードを取得します。エンティティはジオメトリインスタンシングのために複数の親ノードにアタッチできます。 |
| [getProperties()](#getProperties--) | すべてのプロパティのコレクションを取得します。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 指定されたプロパティの値を取得します |
| [getReceiveShadows()](#getReceiveShadows--) | このジオメトリが影を受け取るかどうかを取得します。 |
| [getScene()](#getScene--) | このオブジェクトが属するシーンを取得します |
| [getU()](#getU--) | NURBS サーフェスの U 方向を取得します。 |
| [getV()](#getV--) | NURBS サーフェスの V 方向を取得します。 |
| [getVertexElementOfUV(TextureMapping textureMapping)](#getVertexElementOfUV-com.aspose.threed.TextureMapping-) | 指定されたテクスチャマッピングタイプで [VertexElementUV](../../com.aspose.threed/vertexelementuv) インスタンスを取得します |
| [getVertexElements()](#getVertexElements--) | すべての頂点要素を取得します |
| [getVisible()](#getVisible--) | ジオメトリが可視かどうかを取得します |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 動的プロパティを削除します。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 名前で識別される指定されたプロパティを削除します |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | このジオメトリが影を落とすかどうかを設定します |
| [setExcluded(boolean value)](#setExcluded-boolean-) | エクスポート時にこのエンティティを除外するかどうかを設定します。 |
| [setName(String value)](#setName-java.lang.String-) | 名前を設定します。 |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 最初の親ノードを設定します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 指定されたプロパティの値を設定します |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | このジオメトリが影を受け取るかどうかを設定します。 |
| [setVisible(boolean value)](#setVisible-boolean-) | ジオメトリが可視かどうかを設定します |
| [toMesh()](#toMesh--) | NURBS サーフェスをメッシュに変換します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NurbsSurface() {#NurbsSurface--}
```
public NurbsSurface()
```


[NurbsSurface](../../com.aspose.threed/nurbssurface) クラスの新しいインスタンスを初期化します。

### NurbsSurface(String name) {#NurbsSurface-java.lang.String-}
```
public NurbsSurface(String name)
```


[NurbsSurface](../../com.aspose.threed/nurbssurface) クラスの新しいインスタンスを初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String | 名前。 |

### <T>getDeformers2() {#-T-getDeformers2--}
```
public Collection<T> <T>getDeformers2()
```


Gets all deformers with specified deformer types

**Returns:**
java.util.Collection<T> - デフォーマーコレクション
### addElement(VertexElement element) {#addElement-com.aspose.threed.VertexElement-}
```
public void addElement(VertexElement element)
```


Adds an existing vertex element to current geometry

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| element | [VertexElement](../../com.aspose.threed/vertexelement) | 追加する頂点要素 |

### createElement(VertexElementType type) {#createElement-com.aspose.threed.VertexElementType-}
```
public VertexElement createElement(VertexElementType type)
```


Creates a vertex element with specified type and add it to the geometry.

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | 頂点要素のタイプ |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - Created element. **Remarks:** If type is [VertexElementType.UV](../../com.aspose.threed/vertexelementtype\#UV), a [VertexElementUV](../../com.aspose.threed/vertexelementuv) with texture mapping type to [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE) will be created.
### createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode) {#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-}
```
public VertexElement createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)
```


Creates a vertex element with specified type and add it to the geometry.

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | 頂点要素のタイプ |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | デフォルトのマッピングモード |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | デフォルトの参照モード |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - Created element. **Remarks:** If type is [VertexElementType.UV](../../com.aspose.threed/vertexelementtype\#UV), a [VertexElementUV](../../com.aspose.threed/vertexelementuv) with texture mapping type to [TextureMapping.DIFFUSE](../../com.aspose.threed/texturemapping\#DIFFUSE) will be created.
### createElementUV(TextureMapping uvMapping) {#createElementUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV createElementUV(TextureMapping uvMapping)
```


指定されたテクスチャマッピングタイプで [VertexElementUV](../../com.aspose.threed/vertexelementuv) を作成します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | 作成するテクスチャマッピングタイプ |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Created element uv
### createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode) {#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-}
```
public VertexElementUV createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)
```


指定されたテクスチャマッピングタイプで [VertexElementUV](../../com.aspose.threed/vertexelementuv) を作成します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| uvMapping | [TextureMapping](../../com.aspose.threed/texturemapping) | 作成するテクスチャマッピングタイプ |
| mappingMode | [MappingMode](../../com.aspose.threed/mappingmode) | デフォルトのマッピングモード |
| referenceMode | [ReferenceMode](../../com.aspose.threed/referencemode) | デフォルトの参照モード |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - Created element uv
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


プロパティを検索します。動的プロパティ（CreateDynamicProperty/SetProperty により作成）またはネイティブプロパティ（名前で識別）になる可能性があります。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| propertyName | java.lang.String | プロパティ名。 |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


現在のエンティティのオブジェクト空間座標系におけるバウンディングボックスを取得します。

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - the bounding box of current entity in its object space coordinate system. **Example:** The following code shows how to calculate the bounding box of a shape

```
Entity entity = new Sphere();
     entity.setRadius(10);
     var bbox = entity.getBoundingBox();
     System.out.printf("The bounding box of the entity is %s ~ %s", bbox.getMinimum(), bbox.getMaximum());
```
### getCastShadows() {#getCastShadows--}
```
public boolean getCastShadows()
```


このジオメトリが影を落とすかどうかを取得します

**Returns:**
boolean - このジオメトリが影を落とすかどうか
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getControlPoints() {#getControlPoints--}
```
public List<Vector4> getControlPoints()
```


すべての制御点を取得します。

**Returns:**
java.util.List<com.aspose.threed.Vector4> - すべての制御点
### getDeformers() {#getDeformers--}
```
public List<Deformer> getDeformers()
```


このジオメトリに関連付けられたすべてのデフォーマーを取得します。

**Returns:**
java.util.List<com.aspose.threed.Deformer> - このジオメトリに関連付けられたすべてのデフォーマー。
### getElement(VertexElementType type) {#getElement-com.aspose.threed.VertexElementType-}
```
public VertexElement getElement(VertexElementType type)
```


指定されたタイプの頂点要素を取得します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| type | [VertexElementType](../../com.aspose.threed/vertexelementtype) | 検索する頂点要素のタイプ |

**Returns:**
[VertexElement](../../com.aspose.threed/vertexelement) - [VertexElement](../../com.aspose.threed/vertexelement) instance if found, otherwise null will be returned.
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


レンダラーに登録されたエンティティレンダラーのキーを取得します

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey) - the key of the entity renderer registered in the renderer
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


エクスポート時にこのエンティティを除外するかどうかを取得します。

**Returns:**
boolean - エクスポート時にこのエンティティを除外するかどうか。
### getName() {#getName--}
```
public String getName()
```


名前を取得します。

**Returns:**
java.lang.String - 名前です。
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


最初の親ノードを取得します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


すべての親ノードを取得します。エンティティはジオメトリインスタンシングのために複数の親ノードにアタッチできます。

**Returns:**
java.util.ArrayList<com.aspose.threed.Node> - すべての親ノード、エンティティはジオメトリ インスタンシングのために複数の親ノードにアタッチできます
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


すべてのプロパティのコレクションを取得します。

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


指定されたプロパティの値を取得します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| プロパティ | java.lang.String | プロパティ名 |

**Returns:**
java.lang.Object - 見つかったプロパティの値
### getReceiveShadows() {#getReceiveShadows--}
```
public boolean getReceiveShadows()
```


このジオメトリが影を受け取るかどうかを取得します。

**Returns:**
boolean - このジオメトリが影を受け取れるかどうか。
### getScene() {#getScene--}
```
public Scene getScene()
```


このオブジェクトが属するシーンを取得します

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getU() {#getU--}
```
public NurbsDirection getU()
```


NURBS サーフェスの U 方向を取得します。

**Returns:**
[NurbsDirection](../../com.aspose.threed/nurbsdirection) - the NURBS surface's U direction
### getV() {#getV--}
```
public NurbsDirection getV()
```


NURBS サーフェスの V 方向を取得します。

**Returns:**
[NurbsDirection](../../com.aspose.threed/nurbsdirection) - the NURBS surface's V direction
### getVertexElementOfUV(TextureMapping textureMapping) {#getVertexElementOfUV-com.aspose.threed.TextureMapping-}
```
public VertexElementUV getVertexElementOfUV(TextureMapping textureMapping)
```


指定されたテクスチャマッピングタイプで [VertexElementUV](../../com.aspose.threed/vertexelementuv) インスタンスを取得します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| textureMapping | [TextureMapping](../../com.aspose.threed/texturemapping) |  |

**Returns:**
[VertexElementUV](../../com.aspose.threed/vertexelementuv) - VertexElementUV with the texture mapping type
### getVertexElements() {#getVertexElements--}
```
public List<VertexElement> getVertexElements()
```


すべての頂点要素を取得します

**Returns:**
java.util.List<com.aspose.threed.VertexElement> - すべての頂点要素
### getVisible() {#getVisible--}
```
public boolean getVisible()
```


ジオメトリが可視かどうかを取得します

**Returns:**
boolean - ジオメトリが可視かどうか
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




### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


動的プロパティを削除します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | 削除するプロパティ |

**Returns:**
boolean - プロパティが正常に削除された場合は true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


名前で識別される指定されたプロパティを削除します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| プロパティ | java.lang.String | 削除するプロパティ |

**Returns:**
boolean - プロパティが正常に削除された場合は true
### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


このジオメトリが影を落とすかどうかを設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


エクスポート時にこのエンティティを除外するかどうかを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


名前を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


最初の親ノードを設定します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | 新しい値 |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


指定されたプロパティの値を設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| プロパティ | java.lang.String | プロパティ名 |
| 値 | java.lang.Object | プロパティの値 |

### setReceiveShadows(boolean value) {#setReceiveShadows-boolean-}
```
public void setReceiveShadows(boolean value)
```


このジオメトリが影を受け取るかどうかを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setVisible(boolean value) {#setVisible-boolean-}
```
public void setVisible(boolean value)
```


ジオメトリが可視かどうかを設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


NURBS サーフェスをメッシュに変換します。

**Returns:**
[Mesh](../../com.aspose.threed/mesh)
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

