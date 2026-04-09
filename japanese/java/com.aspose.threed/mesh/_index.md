---
title: Mesh
second_title: Aspose.3D for Java API リファレンス
description: メッシュは多数の n 辺ポリゴンで構成されています。
type: docs
weight: 102
url: /ja/java/com.aspose.threed/mesh/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Geometry](../../com.aspose.threed/geometry)

**All Implemented Interfaces:**
java.lang.Iterable, [com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class Mesh extends Geometry implements Iterable<int[]>, IMeshConvertible
```

A mesh is made of many n-sided polygons. **Example:** To add a polygon in mesh:

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
```

Travel through all polygons in mesh:

```
Mesh mesh = new Mesh();
  for(int[] polygon : mesh)
  {
      //deal with polygon
  }
```
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Mesh()](#Mesh--) | Initializes a new instance of the [Mesh](../../com.aspose.threed/mesh) class. |
| [Mesh(String name)](#Mesh-java.lang.String-) | Initializes a new instance of the [Mesh](../../com.aspose.threed/mesh) class. |
## Methods

| Method | 説明 |
| --- | --- |
| [<T>getDeformers2()](#-T-getDeformers2--) | Gets all deformers with specified deformer types |
| [addControlPoint(double x, double y, double z)](#addControlPoint-double-double-double-) | Add a new control point to the mesh, this is more efficient. |
| [addControlPoint(double x, double y, double z, double w)](#addControlPoint-double-double-double-double-) | Add a new control point to the mesh, this is more efficient. |
| [addElement(VertexElement element)](#addElement-com.aspose.threed.VertexElement-) | Adds an existing vertex element to current geometry |
| [clone()](#clone--) |  |
| [createElement(VertexElementType type)](#createElement-com.aspose.threed.VertexElementType-) | Creates a vertex element with specified type and add it to the geometry. |
| [createElement(VertexElementType type, MappingMode mappingMode, ReferenceMode referenceMode)](#createElement-com.aspose.threed.VertexElementType-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | Creates a vertex element with specified type and add it to the geometry. |
| [createElementUV(TextureMapping uvMapping)](#createElementUV-com.aspose.threed.TextureMapping-) | 指定されたテクスチャマッピングタイプで [VertexElementUV](../../com.aspose.threed/vertexelementuv) を作成します。 |
| [createElementUV(TextureMapping uvMapping, MappingMode mappingMode, ReferenceMode referenceMode)](#createElementUV-com.aspose.threed.TextureMapping-com.aspose.threed.MappingMode-com.aspose.threed.ReferenceMode-) | 指定されたテクスチャマッピングタイプで [VertexElementUV](../../com.aspose.threed/vertexelementuv) を作成します。 |
| [createPolygon(int v1, int v2, int v3)](#createPolygon-int-int-int-) | 3つの頂点（三角形）でポリゴンを作成します |
| [createPolygon(int v1, int v2, int v3, int v4)](#createPolygon-int-int-int-int-) | 4つの頂点（四角形）でポリゴンを作成します |
| [createPolygon(int[] indices)](#createPolygon-int---) | `indices` で定義されたすべての頂点を使用して新しいポリゴンを作成します。 |
| [createPolygon(int[] indices, int offset, int length)](#createPolygon-int---int-int-) | `indices` で定義されたすべての頂点を使用して新しいポリゴンを作成します。 |
| [difference(Mesh a, Mesh b)](#difference-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | 2つのメッシュの差分を計算します |
| [doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB)](#doBoolean-com.aspose.threed.BooleanOperation-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-) | 2つのメッシュに対してブール演算を実行します |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | プロパティを検索します。 |
| [getBoundingBox()](#getBoundingBox--) | 現在のエンティティのオブジェクト空間座標系におけるバウンディングボックスを取得します。 |
| [getCastShadows()](#getCastShadows--) | このジオメトリが影を落とすかどうかを取得します |
| [getClass()](#getClass--) |  |
| [getControlPoints()](#getControlPoints--) | すべての制御点を取得します。 |
| [getDeformers()](#getDeformers--) | このジオメトリに関連付けられたすべてのデフォーマーを取得します。 |
| [getEdges()](#getEdges--) | メッシュのエッジを取得します。 |
| [getElement(VertexElementType type)](#getElement-com.aspose.threed.VertexElementType-) | 指定されたタイプの頂点要素を取得します |
| [getEntityRendererKey()](#getEntityRendererKey--) | レンダラーに登録されたエンティティレンダラーのキーを取得します |
| [getExcluded()](#getExcluded--) | エクスポート時にこのエンティティを除外するかどうかを取得します。 |
| [getName()](#getName--) | 名前を取得します。 |
| [getParentNode()](#getParentNode--) | 最初の親ノードを取得します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。 |
| [getParentNodes()](#getParentNodes--) | すべての親ノードを取得します。エンティティはジオメトリインスタンシングのために複数の親ノードにアタッチできます。 |
| [getPolygonCount()](#getPolygonCount--) | ポリゴンの数を取得します |
| [getPolygonSize(int index)](#getPolygonSize-int-) | 指定されたポリゴンの頂点数を取得します。 |
| [getPolygons()](#getPolygons--) | メッシュのポリゴン定義を取得します |
| [getProperties()](#getProperties--) | すべてのプロパティのコレクションを取得します。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 指定されたプロパティの値を取得します |
| [getReceiveShadows()](#getReceiveShadows--) | このジオメトリが影を受け取るかどうかを取得します。 |
| [getScene()](#getScene--) | このオブジェクトが属するシーンを取得します |
| [getVertexElementOfUV(TextureMapping textureMapping)](#getVertexElementOfUV-com.aspose.threed.TextureMapping-) | 指定されたテクスチャマッピングタイプで [VertexElementUV](../../com.aspose.threed/vertexelementuv) インスタンスを取得します |
| [getVertexElements()](#getVertexElements--) | すべての頂点要素を取得します |
| [getVisible()](#getVisible--) | ジオメトリが可視かどうかを取得します |
| [hashCode()](#hashCode--) |  |
| [intersect(Mesh a, Mesh b)](#intersect-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | 2つのメッシュの交差を計算します |
| [isManifold()](#isManifold--) | 現在のメッシュがマニホールドメッシュかどうかを確認します。 |
| [iterator()](#iterator--) | 各内部ポリゴンの列挙子を取得します。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [optimize(boolean vertexElements)](#optimize-boolean-) | 重複した制御点を削除してメッシュのメモリ使用量を最適化します |
| [optimize(boolean vertexElements, float toleranceControlPoint)](#optimize-boolean-float-) | 重複した制御点を削除してメッシュのメモリ使用量を最適化します |
| [optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal)](#optimize-boolean-float-float-) | 重複した制御点を削除してメッシュのメモリ使用量を最適化します |
| [optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV)](#optimize-boolean-float-float-float-) | 重複した制御点を削除してメッシュのメモリ使用量を最適化します |
| [optimize2(boolean vertexElements)](#optimize2-boolean-) | 重複した制御点を削除してメッシュのメモリ使用量を最適化します |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 動的プロパティを削除します。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 名前で識別される指定されたプロパティを削除します |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | このジオメトリが影を落とすかどうかを設定します |
| [setExcluded(boolean value)](#setExcluded-boolean-) | エクスポート時にこのエンティティを除外するかどうかを設定します。 |
| [setName(String value)](#setName-java.lang.String-) | 名前を設定します。 |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 最初の親ノードを設定します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 指定されたプロパティの値を設定します |
| [setReceiveShadows(boolean value)](#setReceiveShadows-boolean-) | このジオメトリが影を受け取るかどうかを設定します。 |
| [setVisible(boolean value)](#setVisible-boolean-) | ジオメトリが可視かどうかを設定します |
| [toMesh()](#toMesh--) | 現在のエンティティから Mesh インスタンスを取得します。 |
| [toString()](#toString--) |  |
| [triangulate()](#triangulate--) | 三角形化されたメッシュを返します |
| [union(Mesh a, Mesh b)](#union-com.aspose.threed.Mesh-com.aspose.threed.Mesh-) | 2つのメッシュの合成を計算します |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Mesh() {#Mesh--}
```
public Mesh()
```


Initializes a new instance of the [Mesh](../../com.aspose.threed/mesh) class.

### Mesh(String name) {#Mesh-java.lang.String-}
```
public Mesh(String name)
```


Initializes a new instance of the [Mesh](../../com.aspose.threed/mesh) class.

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
### addControlPoint(double x, double y, double z) {#addControlPoint-double-double-double-}
```
public void addControlPoint(double x, double y, double z)
```


Add a new control point to the mesh, this is more efficient.

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| x | double | 制御点の x 成分 |
| y | double | 制御点の y 成分 |
| z | double | 制御点の z 成分 |

### addControlPoint(double x, double y, double z, double w) {#addControlPoint-double-double-double-double-}
```
public void addControlPoint(double x, double y, double z, double w)
```


Add a new control point to the mesh, this is more efficient.

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| x | double | 制御点の x 成分 |
| y | double | 制御点の y 成分 |
| z | double | 制御点の z 成分 |
| w | double | 制御点の w 成分 |

### addElement(VertexElement element) {#addElement-com.aspose.threed.VertexElement-}
```
public void addElement(VertexElement element)
```


Adds an existing vertex element to current geometry

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| element | [VertexElement](../../com.aspose.threed/vertexelement) | 追加する頂点要素 |

### clone() {#clone--}
```
public Mesh clone()
```




**Returns:**
[Mesh](../../com.aspose.threed/mesh)
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
### createPolygon(int v1, int v2, int v3) {#createPolygon-int-int-int-}
```
public void createPolygon(int v1, int v2, int v3)
```


3つの頂点（三角形）でポリゴンを作成します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| v1 | int | 最初の頂点のインデックス |
| v2 | int | 2番目の頂点のインデックス |
|  | v3 | int | 第3頂点のインデックス **Example:** 以下のコードは、制御点のインデックスを使用して新しいポリゴンを作成する方法を示しています。 |

```
Mesh mesh = new Mesh();
  mesh.createPolygon(0, 1, 2);
``` |

### createPolygon(int v1, int v2, int v3, int v4) {#createPolygon-int-int-int-int-}
```
public void createPolygon(int v1, int v2, int v3, int v4)
```


4つの頂点（四角形）でポリゴンを作成します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| v1 | int | 最初の頂点のインデックス |
| v2 | int | 2番目の頂点のインデックス |
| v3 | int | 第3頂点のインデックス |
|  | v4 | int | 第4頂点のインデックス **Example:** 以下のコードは、制御点のインデックスを使用して新しいポリゴンを作成する方法を示しています。 |

```
Mesh mesh = new Mesh();
  mesh.createPolygon(0, 1, 2, 3);
``` |

### createPolygon(int[] indices) {#createPolygon-int---}
```
public void createPolygon(int[] indices)
```


`indices` で定義されたすべての頂点を使用して新しいポリゴンを作成します。ポリゴンを頂点ごとに作成するには、[PolygonBuilder](../../com.aspose.threed/polygonbuilder) を使用してください。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | インデックス | int[] | ポリゴンのインデックスの配列で、各インデックスはポリゴンを構成する制御点を指します。 **Example:** |

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
``` |

### createPolygon(int[] indices, int offset, int length) {#createPolygon-int---int-int-}
```
public void createPolygon(int[] indices, int offset, int length)
```


`indices` で定義されたすべての頂点を使用して新しいポリゴンを作成します。ポリゴンを頂点ごとに作成するには、[PolygonBuilder](../../com.aspose.threed/polygonbuilder) を使用してください。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| インデックス | int[] | ポリゴンのインデックスの配列で、各インデックスはポリゴンを構成する制御点を指します。 |
| オフセット | int | 最初のポリゴンインデックスのオフセット |
|  | 長さ | int | インデックスの長さ **Example:** 以下のコードは、制御点のインデックスを使用して新しいポリゴンを作成する方法を示しています。 |

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
``` |

### difference(Mesh a, Mesh b) {#difference-com.aspose.threed.Mesh-com.aspose.threed.Mesh-}
```
public static Mesh difference(Mesh a, Mesh b)
```


2つのメッシュの差分を計算します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | 最初のメッシュ |
| b | [Mesh](../../com.aspose.threed/mesh) | 2番目のメッシュ |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to calculate the difference of two meshes:
### doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB) {#doBoolean-com.aspose.threed.BooleanOperation-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-com.aspose.threed.Mesh-com.aspose.threed.Matrix4-}
```
public static Mesh doBoolean(BooleanOperation op, Mesh a, Matrix4 transformA, Mesh b, Matrix4 transformB)
```


2つのメッシュに対してブール演算を実行します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| op | [BooleanOperation](../../com.aspose.threed/booleanoperation) | ブール演算のタイプです。 |
| a | [Mesh](../../com.aspose.threed/mesh) | 操作対象の最初のメッシュ。 |
| transformA | [Matrix4](../../com.aspose.threed/matrix4) | 最初のメッシュの変換行列 |
| b | [Mesh](../../com.aspose.threed/mesh) | 操作対象の2番目のメッシュ |
| transformB | [Matrix4](../../com.aspose.threed/matrix4) | 2番目のメッシュの変換行列 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - The result mesh **Example:** The following code shows how to calculate the union of two meshes:
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
### getEdges() {#getEdges--}
```
public List<Integer> getEdges()
```


メッシュのエッジを取得します。エッジはメッシュでオプションなので、空になることがあります。

**Returns:**
java.util.List<java.lang.Integer> - メッシュのエッジ。エッジはメッシュでオプションなので、空になることがあります。
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
### getPolygonCount() {#getPolygonCount--}
```
public int getPolygonCount()
```


ポリゴンの数を取得します

**Returns:**
int - ポリゴンの数 **Example:** 以下のコードは、メッシュのポリゴン数を取得する方法を示しています。

```
Mesh mesh = (new Sphere()).toMesh();
      System.out.println("Mesh's polygon count = " + mesh.getPolygonCount());
```
### getPolygonSize(int index) {#getPolygonSize-int-}
```
public int getPolygonSize(int index)
```


指定されたポリゴンの頂点数を取得します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| インデックス | int | インデックスです。 |

**Returns:**
int - ポリゴンのサイズです。
### getPolygons() {#getPolygons--}
```
public List<int[]> getPolygons()
```


メッシュのポリゴン定義を取得します

**Returns:**
java.util.List<int[]> - メッシュのポリゴン定義
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
### intersect(Mesh a, Mesh b) {#intersect-com.aspose.threed.Mesh-com.aspose.threed.Mesh-}
```
public static Mesh intersect(Mesh a, Mesh b)
```


2つのメッシュの交差を計算します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | 最初のメッシュ |
| b | [Mesh](../../com.aspose.threed/mesh) | 2番目のメッシュ |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to calculate the difference of two meshes:
### isManifold() {#isManifold--}
```
public boolean isManifold()
```


現在のメッシュが多様体メッシュかどうかをチェックします。この関数は多様体計算結果をキャッシュしません。

**Returns:**
boolean - メッシュが多様体メッシュの場合は true。
### iterator() {#iterator--}
```
public Iterator<int[]> iterator()
```


各内部ポリゴンの列挙子を取得します。

**Returns:**
java.util.Iterator<int[]> - 列挙子です。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### optimize(boolean vertexElements) {#optimize-boolean-}
```
public Mesh optimize(boolean vertexElements)
```


重複した制御点を削除してメッシュのメモリ使用量を最適化します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| vertexElements | boolean | 重複した頂点要素データを最適化する |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage **Example:** The following code shows how to eliminate duplicated control points from an unoptimized mesh:

```
//Sphere.ToMesh generates 117 control points
  Mesh mesh = (new Sphere()).toMesh();
  //After optimized, there're only 86 control points, polygon indices are also remapped.
  Mesh optimized = mesh.optimize(true);
```
### optimize(boolean vertexElements, float toleranceControlPoint) {#optimize-boolean-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint)
```


重複した制御点を削除してメッシュのメモリ使用量を最適化します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| vertexElements | boolean | 重複した頂点要素データを最適化する |
| toleranceControlPoint | float | 制御点の許容誤差、デフォルト値は 1e-9 です。 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal) {#optimize-boolean-float-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal)
```


重複した制御点を削除してメッシュのメモリ使用量を最適化します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| vertexElements | boolean | 重複した頂点要素データを最適化する |
| toleranceControlPoint | float | 制御点の許容誤差、デフォルト値は 1e-9 です。 |
| toleranceNormal | float | 法線/接線/バイノーマルの許容誤差、デフォルト値は 1e-9 です。 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV) {#optimize-boolean-float-float-float-}
```
public Mesh optimize(boolean vertexElements, float toleranceControlPoint, float toleranceNormal, float toleranceUV)
```


重複した制御点を削除してメッシュのメモリ使用量を最適化します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| vertexElements | boolean | 重複した頂点要素データを最適化する |
| toleranceControlPoint | float | 制御点の許容誤差、デフォルト値は 1e-9 です。 |
| toleranceNormal | float | 法線/接線/バイノーマルの許容誤差、デフォルト値は 1e-9 です。 |
| toleranceUV | float | UV の許容誤差、デフォルト値は 1e-9 です。 |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
### optimize2(boolean vertexElements) {#optimize2-boolean-}
```
public Mesh optimize2(boolean vertexElements)
```


重複した制御点を削除してメッシュのメモリ使用量を最適化します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| vertexElements | boolean | 重複した頂点要素データを最適化する |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - New mesh instance with compact memory usage
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


現在のエンティティから Mesh インスタンスを取得します。

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Returns current instance.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### triangulate() {#triangulate--}
```
public Mesh triangulate()
```


三角形化されたメッシュを返します

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Current mesh if current mesh is already triangulated, otherwise a new triangulated mesh will be calculated and returned **Example:** The following code shows how to triangulate a mesh:

```
//The plane mesh has only one polygon with 4 control points
  var mesh = (new Plane()).ToMesh();
  //After triangulated, the new mesh's rectangle will become 2 triangles.
  var triangulated = mesh.Triangulate();
```
### union(Mesh a, Mesh b) {#union-com.aspose.threed.Mesh-com.aspose.threed.Mesh-}
```
public static Mesh union(Mesh a, Mesh b)
```


2つのメッシュの合成を計算します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| a | [Mesh](../../com.aspose.threed/mesh) | 最初のメッシュ |
| b | [Mesh](../../com.aspose.threed/mesh) | 2番目のメッシュ |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - Result mesh **Example:** The following code shows how to union two meshes into one mesh:
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

