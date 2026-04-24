---
title: TriMesh
second_title: Aspose.3D for Java API リファレンス
description: TriMeshはGPUで直接使用できる生データを含みます。
type: docs
weight: 194
url: /ja/java/com.aspose.threed/trimesh/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)

**All Implemented Interfaces:**
java.lang.Iterable
```
public class TriMesh extends Entity implements Iterable<Vertex>
```

TriMesh は GPU が直接使用できる生データを含みます。このクラスは、頂点ごとのデータのみを含むメッシュを構築するためのユーティリティです。 **Example:** 次のコードは、カスタムメモリレイアウトの TriMesh を作成し、ファイルにエクスポートする方法を示しています。

```
//Define a vertex declaration as {FVector3 Position; FVector3 Normal; FVector2 UV}
              VertexDeclaration vd = new VertexDeclaration();
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.NORMAL);
              vd.addField(VertexFieldDataType.F_VECTOR2, VertexFieldSemantic.UV);
              //convert a mesh to tri-mesh using specified memory layout
              var mesh = (new Sphere()).toMesh();
              var triMesh = TriMesh.fromMesh(vd, mesh);
              //save it to a stream, 115 vertices * 32bytes per vertex
              try(var s = new FileOutputStream("output.bin")) {
                  triMesh.writeVerticesTo(s);
                  //save indices as ushort to stream, 504 indices * 2 bytes per index
                  triMesh.write16bIndicesTo(s);
              }
```
## Constructors

| Constructor | 説明 |
| --- | --- |
| [TriMesh(String name, VertexDeclaration declaration)](#TriMesh-java.lang.String-com.aspose.threed.VertexDeclaration-) | [TriMesh](../../com.aspose.threed/trimesh) のインスタンスを初期化する |
## Methods

| Method | 説明 |
| --- | --- |
| [addTriangle(int a, int b, int c)](#addTriangle-int-int-int-) | 新しい三角形を追加する |
| [beginVertex()](#beginVertex--) | 頂点の追加を開始する |
| [copyFrom(TriMesh input, VertexDeclaration vd)](#copyFrom-com.aspose.threed.TriMesh-com.aspose.threed.VertexDeclaration-) | 入力から新しい頂点レイアウトで [TriMesh](../../com.aspose.threed/trimesh) をコピーする |
| [endVertex()](#endVertex--) | 頂点の追加を終了する |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | プロパティを検索します。 |
| [fromMesh(Mesh mesh)](#fromMesh-com.aspose.threed.Mesh-) | 指定されたメッシュオブジェクトから TriMesh を作成します。頂点宣言は入力メッシュの構造に基づきます。 |
| [fromMesh(Mesh mesh, boolean useFloat)](#fromMesh-com.aspose.threed.Mesh-boolean-) | 指定されたメッシュオブジェクトから TriMesh を作成します。頂点宣言は入力メッシュの構造に基づきます。 |
| [fromMesh(VertexDeclaration declaration, Mesh mesh)](#fromMesh-com.aspose.threed.VertexDeclaration-com.aspose.threed.Mesh-) | 指定された頂点レイアウトを使用して、指定されたメッシュオブジェクトから TriMesh を作成する。 |
| [fromRawData(VertexDeclaration vd, byte[] vertices, int[] indices, boolean generateVertexMapping)](#fromRawData-com.aspose.threed.VertexDeclaration-byte---int---boolean-) | 生データから TriMesh を作成する |
| [getBoundingBox()](#getBoundingBox--) | 現在のエンティティのオブジェクト空間座標系におけるバウンディングボックスを取得します。 |
| [getCapacity()](#getCapacity--) | 事前割り当てされた頂点の容量。 |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | レンダラーに登録されたエンティティレンダラーのキーを取得します |
| [getExcluded()](#getExcluded--) | エクスポート時にこのエンティティを除外するかどうかを取得します。 |
| [getIndicesCount()](#getIndicesCount--) | この [TriMesh](../../com.aspose.threed/trimesh) のインデックス数。 |
| [getIntIndices()](#getIntIndices--) | インデックスを 32 ビット整数配列に変換する |
| [getName()](#getName--) | 名前を取得します。 |
| [getParentNode()](#getParentNode--) | 最初の親ノードを取得します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。 |
| [getParentNodes()](#getParentNodes--) | すべての親ノードを取得します。エンティティはジオメトリインスタンシングのために複数の親ノードにアタッチできます。 |
| [getProperties()](#getProperties--) | すべてのプロパティのコレクションを取得します。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 指定されたプロパティの値を取得します |
| [getScene()](#getScene--) | このオブジェクトが属するシーンを取得します |
| [getShortIndices()](#getShortIndices--) | インデックスを 16 ビット整数配列に変換する |
| [getUnmergedVerticesCount()](#getUnmergedVerticesCount--) | [beginVertex](../../com.aspose.threed/trimesh\#beginVertex) と [endVertex](../../com.aspose.threed/trimesh\#endVertex) によって渡された未マージ頂点の数。 |
| [getVertexDeclaration()](#getVertexDeclaration--) | [TriMesh](../../com.aspose.threed/trimesh) の頂点レイアウト。 |
| [getVerticesCount()](#getVerticesCount--) | この [TriMesh](../../com.aspose.threed/trimesh) の頂点数。 |
| [getVerticesSizeInBytes()](#getVerticesSizeInBytes--) | すべての頂点の合計サイズ（バイト） |
| [hashCode()](#hashCode--) |  |
| [indicesToArray(int[][] result)](#indicesToArray-int-----) | インデックスを 32 ビット整数配列に変換する |
| [indicesToArray(short[][] result)](#indicesToArray-short-----) | インデックスを 16 ビット整数配列に変換する |
| [iterator()](#iterator--) | [Vertex](../../com.aspose.threed/vertex) を列挙するための列挙子を取得する |
| [loadVerticesFromBytes(byte[] verticesInBytes)](#loadVerticesFromBytes-byte---) | バイトから頂点をロードします。バイト長は頂点サイズの整数倍である必要があります。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readDouble(int idx, VertexField field)](#readDouble-int-com.aspose.threed.VertexField-) | double フィールドを読み取る |
| [readFVector2(int idx, VertexField field)](#readFVector2-int-com.aspose.threed.VertexField-) | vector2 フィールドを読み取る |
| [readFVector3(int idx, VertexField field)](#readFVector3-int-com.aspose.threed.VertexField-) | vector3 フィールドを読み取る |
| [readFVector4(int idx, VertexField field)](#readFVector4-int-com.aspose.threed.VertexField-) | vector4 フィールドを読み取ります |
| [readFloat(int idx, VertexField field)](#readFloat-int-com.aspose.threed.VertexField-) | float フィールドを読み取ります |
| [readVector2(int idx, VertexField field)](#readVector2-int-com.aspose.threed.VertexField-) | vector2 フィールドを読み取る |
| [readVector3(int idx, VertexField field)](#readVector3-int-com.aspose.threed.VertexField-) | vector3 フィールドを読み取る |
| [readVector4(int idx, VertexField field)](#readVector4-int-com.aspose.threed.VertexField-) | vector4 フィールドを読み取ります |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 動的プロパティを削除します。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 名前で識別される指定されたプロパティを削除します |
| [setExcluded(boolean value)](#setExcluded-boolean-) | エクスポート時にこのエンティティを除外するかどうかを設定します。 |
| [setName(String value)](#setName-java.lang.String-) | 名前を設定します。 |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 最初の親ノードを設定します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 指定されたプロパティの値を設定します |
| [toString()](#toString--) | [TriMesh](../../com.aspose.threed/trimesh) の文字列表現を取得します |
| [verticesToArray()](#verticesToArray--) | 頂点データをバイト配列に変換します |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [write16bIndicesTo(Stream stream)](#write16bIndicesTo-com.aspose.threed.Stream-) | インデックスデータを 16 ビット整数としてストリームに書き込みます **Example:** |
| [write16bIndicesTo(OutputStream stream)](#write16bIndicesTo-java.io.OutputStream-) | インデックスデータを 16 ビット整数としてストリームに書き込みます |
| [write32bIndicesTo(Stream stream)](#write32bIndicesTo-com.aspose.threed.Stream-) | インデックスデータを 32 ビット整数としてストリームに書き込みます **Example:** |
| [write32bIndicesTo(OutputStream stream)](#write32bIndicesTo-java.io.OutputStream-) | インデックスデータを 32 ビット整数としてストリームに書き込みます |
| [writeVerticesTo(Stream stream)](#writeVerticesTo-com.aspose.threed.Stream-) | 指定されたストリームに頂点データを書き込みます |
| [writeVerticesTo(OutputStream stream)](#writeVerticesTo-java.io.OutputStream-) | 指定されたストリームに頂点データを書き込みます |
### TriMesh(String name, VertexDeclaration declaration) {#TriMesh-java.lang.String-com.aspose.threed.VertexDeclaration-}
```
public TriMesh(String name, VertexDeclaration declaration)
```


[TriMesh](../../com.aspose.threed/trimesh) のインスタンスを初期化する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String | この TriMesh の名前 |
| declaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | 頂点の宣言 |

### addTriangle(int a, int b, int c) {#addTriangle-int-int-int-}
```
public void addTriangle(int a, int b, int c)
```


新しい三角形を追加する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| a | int | 最初の頂点のインデックス |
| b | int | 2 番目の頂点のインデックス |
| c | int | 3 番目の頂点のインデックス |

### beginVertex() {#beginVertex--}
```
public Vertex beginVertex()
```


頂点の追加を開始する

**Returns:**
[Vertex](../../com.aspose.threed/vertex) - The reference of internal vertex object in type [Vertex](../../com.aspose.threed/vertex)
### copyFrom(TriMesh input, VertexDeclaration vd) {#copyFrom-com.aspose.threed.TriMesh-com.aspose.threed.VertexDeclaration-}
```
public static TriMesh copyFrom(TriMesh input, VertexDeclaration vd)
```


入力から新しい頂点レイアウトで [TriMesh](../../com.aspose.threed/trimesh) をコピーする

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| input | [TriMesh](../../com.aspose.threed/trimesh) | コピー用の入力 TriMesh |
| vd | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | 出力 TriMesh の新しい頂点宣言 |

**Returns:**
[TriMesh](../../com.aspose.threed/trimesh) - A new TriMesh instance with new vertex declaration. **Example:**

```
//Define a vertex declaration as {FVector3 Position; FVector3 Normal; FVector2 UV}
  VertexDeclaration vd = new VertexDeclaration();
  vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
  vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.NORMAL);
  vd.addField(VertexFieldDataType.F_VECTOR2, VertexFieldSemantic.UV);
  //convert a mesh to TriMesh, the layout is automatically inferred from input mesh
  var oldTriMesh = TriMesh.fromMesh((new Sphere()).toMesh());
  //now create a new TriMesh from old TriMesh, using explicit memory layout defined by vd
  var newTriMesh = TriMesh.copyFrom(oldTriMesh, vd);
```
### endVertex() {#endVertex--}
```
public int endVertex()
```


頂点の追加を終了する

**Returns:**
int
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
### fromMesh(Mesh mesh) {#fromMesh-com.aspose.threed.Mesh-}
```
public static TriMesh fromMesh(Mesh mesh)
```


指定されたメッシュオブジェクトから TriMesh を作成します。頂点宣言は入力メッシュの構造に基づきます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |

**Returns:**
[TriMesh](../../com.aspose.threed/trimesh) - The [TriMesh](../../com.aspose.threed/trimesh) generated from given [Mesh](../../com.aspose.threed/mesh) **Example:** The following code shows how to create a TriMesh with custom memory layout, and export it to file.

```
//Define a vertex declaration as {FVector3 Position; FVector3 Normal; FVector2 UV}
              VertexDeclaration vd = new VertexDeclaration();
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.NORMAL);
              vd.addField(VertexFieldDataType.F_VECTOR2, VertexFieldSemantic.UV);
              //convert a mesh to tri-mesh using specified memory layout
              var mesh = (new Sphere()).toMesh();
              var triMesh = TriMesh.fromMesh(vd, mesh);
              //save it to a stream, 115 vertices * 32bytes per vertex
              try(var s = new FileOutputStream("output.bin")) {
                  triMesh.writeVerticesTo(s);
                  //save indices as ushort to stream, 504 indices * 2 bytes per index
                  triMesh.write16bIndicesTo(s);
              }
```
### fromMesh(Mesh mesh, boolean useFloat) {#fromMesh-com.aspose.threed.Mesh-boolean-}
```
public static TriMesh fromMesh(Mesh mesh, boolean useFloat)
```


指定されたメッシュオブジェクトから TriMesh を作成します。頂点宣言は入力メッシュの構造に基づきます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) |  |
| useFloat | boolean | 各頂点要素コンポーネントに対して、double 型の代わりに float 型を使用します。 |

**Returns:**
[TriMesh](../../com.aspose.threed/trimesh) - The [TriMesh](../../com.aspose.threed/trimesh) generated from given [Mesh](../../com.aspose.threed/mesh) **Example:** The following code shows how to create a TriMesh with custom memory layout, and export it to file.

```
//Define a vertex declaration as {FVector3 Position; FVector3 Normal; FVector2 UV}
              VertexDeclaration vd = new VertexDeclaration();
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.NORMAL);
              vd.addField(VertexFieldDataType.F_VECTOR2, VertexFieldSemantic.UV);
              //convert a mesh to tri-mesh using specified memory layout
              var mesh = (new Sphere()).toMesh();
              var triMesh = TriMesh.fromMesh(vd, mesh);
              //save it to a stream, 115 vertices * 32bytes per vertex
              try(var s = new FileOutputStream("output.bin")) {
                  triMesh.writeVerticesTo(s);
                  //save indices as ushort to stream, 504 indices * 2 bytes per index
                  triMesh.write16bIndicesTo(s);
              }
```
### fromMesh(VertexDeclaration declaration, Mesh mesh) {#fromMesh-com.aspose.threed.VertexDeclaration-com.aspose.threed.Mesh-}
```
public static TriMesh fromMesh(VertexDeclaration declaration, Mesh mesh)
```


指定された頂点レイアウトを使用して、指定されたメッシュオブジェクトから TriMesh を作成する。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| declaration | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | 頂点の型定義、またはメモリレイアウト |
| mesh | [Mesh](../../com.aspose.threed/mesh) | ソースメッシュ |

**Returns:**
[TriMesh](../../com.aspose.threed/trimesh) - Instance of TriMesh converted from input mesh with specified vertex's memory layout **Example:** The following code shows how to create a TriMesh with custom memory layout, and export it to file.

```
//Define a vertex declaration as {FVector3 Position; FVector3 Normal; FVector2 UV}
              VertexDeclaration vd = new VertexDeclaration();
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
              vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.NORMAL);
              vd.addField(VertexFieldDataType.F_VECTOR2, VertexFieldSemantic.UV);
              //convert a mesh to tri-mesh using specified memory layout
              var mesh = (new Sphere()).toMesh();
              var triMesh = TriMesh.fromMesh(vd, mesh);
              //save it to a stream, 115 vertices * 32bytes per vertex
              try(var s = new FileOutputStream("output.bin")) {
                  triMesh.writeVerticesTo(s);
                  //save indices as ushort to stream, 504 indices * 2 bytes per index
                  triMesh.write16bIndicesTo(s);
              }
```
### fromRawData(VertexDeclaration vd, byte[] vertices, int[] indices, boolean generateVertexMapping) {#fromRawData-com.aspose.threed.VertexDeclaration-byte---int---boolean-}
```
public static TriMesh fromRawData(VertexDeclaration vd, byte[] vertices, int[] indices, boolean generateVertexMapping)
```


生データから TriMesh を作成する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| vd | [VertexDeclaration](../../com.aspose.threed/vertexdeclaration) | 頂点宣言は、少なくとも 1 つのフィールドを含む必要があります。 |
| vertices | byte[] | 入力頂点データ、頂点の最小長さは頂点宣言のサイズ以上である必要があります |
| インデックス | int[] | 三角形インデックス |
| generateVertexMapping | boolean | 各頂点に対して [Vertex](../../com.aspose.threed/vertex) を生成しますが、シリアライズ/デシリアライズだけの場合は必要ありません。 |

**Returns:**
[TriMesh](../../com.aspose.threed/trimesh) - The [TriMesh](../../com.aspose.threed/trimesh) instance that encapsulated the input byte array. **Remarks:** The returned TriMesh will not copy the input byte array for performance, external changes on the array will be reflected to this instance. **Example:** The following code shows how to construct a TriMesh from raw bytes, this is useful when build your own 3D format

```
var indices = new int[] { 0,  1,  2 };
  var vertices = new byte[]{
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 191,
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 63,
      0, 0, 0, 63,
      0, 0, 0, 0The string representation,
      0, 0, 0, 63
  };
  VertexDeclaration vd = new VertexDeclaration();
  vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
  var triMesh = TriMesh.FromRawData(vd, vertices, indices, true);
```
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
### getCapacity() {#getCapacity--}
```
public int getCapacity()
```


事前割り当てされた頂点の容量。

**Returns:**
int - 事前割り当てされた頂点の容量
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getIndicesCount() {#getIndicesCount--}
```
public int getIndicesCount()
```


この [TriMesh](../../com.aspose.threed/trimesh) のインデックス数。

**Returns:**
int - この [TriMesh](../../com.aspose.threed/trimesh) のインデックス数
### getIntIndices() {#getIntIndices--}
```
public int[] getIntIndices()
```


インデックスを 32 ビット整数配列に変換する

**Returns:**
int[]
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
### getScene() {#getScene--}
```
public Scene getScene()
```


このオブジェクトが属するシーンを取得します

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getShortIndices() {#getShortIndices--}
```
public short[] getShortIndices()
```


インデックスを 16 ビット整数配列に変換する

**Returns:**
short[]
### getUnmergedVerticesCount() {#getUnmergedVerticesCount--}
```
public int getUnmergedVerticesCount()
```


[beginVertex](../../com.aspose.threed/trimesh\#beginVertex) と [endVertex](../../com.aspose.threed/trimesh\#endVertex) によって渡された未マージ頂点の数。

**Returns:**
int - [beginVertex](../../com.aspose.threed/trimesh\#beginVertex) と [endVertex](../../com.aspose.threed/trimesh\#endVertex) によって渡された未マージ頂点の数。
### getVertexDeclaration() {#getVertexDeclaration--}
```
public VertexDeclaration getVertexDeclaration()
```


[TriMesh](../../com.aspose.threed/trimesh) の頂点レイアウト。

**Returns:**
[VertexDeclaration](../../com.aspose.threed/vertexdeclaration) - The vertex layout of the [TriMesh](../../com.aspose.threed/trimesh).
### getVerticesCount() {#getVerticesCount--}
```
public int getVerticesCount()
```


この [TriMesh](../../com.aspose.threed/trimesh) の頂点数。

**Returns:**
int - この [TriMesh](../../com.aspose.threed/trimesh) の頂点数
### getVerticesSizeInBytes() {#getVerticesSizeInBytes--}
```
public int getVerticesSizeInBytes()
```


すべての頂点の合計サイズ（バイト）

**Returns:**
int - すべての頂点の合計サイズ（バイト単位）
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### indicesToArray(int[][] result) {#indicesToArray-int-----}
```
public void indicesToArray(int[][] result)
```


インデックスを 32 ビット整数配列に変換する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 結果 | int[][] |  |

### indicesToArray(short[][] result) {#indicesToArray-short-----}
```
public void indicesToArray(short[][] result)
```


インデックスを 16 ビット整数配列に変換する

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 結果 | short[][] |  |

### iterator() {#iterator--}
```
public Iterator<Vertex> iterator()
```


[Vertex](../../com.aspose.threed/vertex) を列挙するための列挙子を取得する

**Returns:**
java.util.Iterator<com.aspose.threed.Vertex>
### loadVerticesFromBytes(byte[] verticesInBytes) {#loadVerticesFromBytes-byte---}
```
public void loadVerticesFromBytes(byte[] verticesInBytes)
```


バイトから頂点をロードします。バイトの長さは頂点サイズの整数倍である必要があります。**Example:** 以下のコードは、空の TriMesh を作成し、生のバイトから手動で頂点をロードする方法を示しています。

```
var indices = new int[] { 0,  1,  2 };
  var vertices = new byte[]{
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 191,
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 63,
      0, 0, 0, 63,
      0, 0, 0, 0,
      0, 0, 0, 63
  };
  VertexDeclaration vd = new VertexDeclaration();
  vd.AddField(VertexFieldDataType.FVector3, VertexFieldSemantic.Position);
  //create an empty TriMesh with specified vertex declaration
  var triMesh = new TriMesh("", vd);
  //load vertices directly from bytes
  triMesh.LoadVerticesFromBytes(vertices);
  triMesh.AddTriangle(0, 1, 2);
```

```
int[] indices = new int[] { 0,  1,  2 };
  byte[] vertices = new byte[]{
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 191,
      0, 0, 0, 191,
      0, 0, 0, 0,
      0, 0, 0, 63,
      0, 0, 0, 63,
      0, 0, 0, 0,
      0, 0, 0, 63
  };
  VertexDeclaration vd = new VertexDeclaration();
  vd.addField(VertexFieldDataType.F_VECTOR3, VertexFieldSemantic.POSITION);
  //create an empty TriMesh with specified vertex declaration
  var triMesh = new TriMesh("", vd);
  //load vertices directly from bytes
  triMesh.loadVerticesFromBytes(vertices);
  triMesh.addTriangle(0, 1, 2);
```

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| verticesInBytes | byte[] |  |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### readDouble(int idx, VertexField field) {#readDouble-int-com.aspose.threed.VertexField-}
```
public double readDouble(int idx, VertexField field)
```


double フィールドを読み取る

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| idx | int | 読み取る頂点のインデックス |
| field | [VertexField](../../com.aspose.threed/vertexfield) | float/double 互換のデータ型を持つフィールド |

**Returns:**
double - 指定された頂点のフィールドの Double 値
### readFVector2(int idx, VertexField field) {#readFVector2-int-com.aspose.threed.VertexField-}
```
public FVector2 readFVector2(int idx, VertexField field)
```


vector2 フィールドを読み取る

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| idx | int | 読み取る頂点のインデックス |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector2/FVector2 データ型を持つフィールド |

**Returns:**
[FVector2](../../com.aspose.threed/fvector2) - FVector2 of specified vertex's field
### readFVector3(int idx, VertexField field) {#readFVector3-int-com.aspose.threed.VertexField-}
```
public FVector3 readFVector3(int idx, VertexField field)
```


vector3 フィールドを読み取る

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| idx | int | 読み取る頂点のインデックス |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector3/FVector3 データ型を持つフィールド |

**Returns:**
[FVector3](../../com.aspose.threed/fvector3)
### readFVector4(int idx, VertexField field) {#readFVector4-int-com.aspose.threed.VertexField-}
```
public FVector4 readFVector4(int idx, VertexField field)
```


vector4 フィールドを読み取ります

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| idx | int | 読み取る頂点のインデックス |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector4/FVector4 データ型を持つフィールド |

**Returns:**
[FVector4](../../com.aspose.threed/fvector4)
### readFloat(int idx, VertexField field) {#readFloat-int-com.aspose.threed.VertexField-}
```
public float readFloat(int idx, VertexField field)
```


float フィールドを読み取ります

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| idx | int | 読み取る頂点のインデックス |
| field | [VertexField](../../com.aspose.threed/vertexfield) | float/double 互換のデータ型を持つフィールド |

**Returns:**
float - 指定された頂点のフィールドの Float 値
### readVector2(int idx, VertexField field) {#readVector2-int-com.aspose.threed.VertexField-}
```
public Vector2 readVector2(int idx, VertexField field)
```


vector2 フィールドを読み取る

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| idx | int | 読み取る頂点のインデックス |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector2/FVector2 データ型を持つフィールド |

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - Vector2 of specified vertex's field
### readVector3(int idx, VertexField field) {#readVector3-int-com.aspose.threed.VertexField-}
```
public Vector3 readVector3(int idx, VertexField field)
```


vector3 フィールドを読み取る

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| idx | int | 読み取る頂点のインデックス |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector3/FVector3 データ型を持つフィールド |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### readVector4(int idx, VertexField field) {#readVector4-int-com.aspose.threed.VertexField-}
```
public Vector4 readVector4(int idx, VertexField field)
```


vector4 フィールドを読み取ります

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| idx | int | 読み取る頂点のインデックス |
| field | [VertexField](../../com.aspose.threed/vertexfield) | Vector4/FVector4 データ型を持つフィールド |

**Returns:**
[Vector4](../../com.aspose.threed/vector4)
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

### toString() {#toString--}
```
public String toString()
```


[TriMesh](../../com.aspose.threed/trimesh) の文字列表現を取得します

**Returns:**
java.lang.String - 文字列表現
### verticesToArray() {#verticesToArray--}
```
public byte[] verticesToArray()
```


頂点データをバイト配列に変換します

**Returns:**
byte[]
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

### write16bIndicesTo(Stream stream) {#write16bIndicesTo-com.aspose.threed.Stream-}
```
public void write16bIndicesTo(Stream stream)
```


インデックスデータを 16 ビット整数としてストリームに書き込みます **Example:**

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh
      var mesh = (new Sphere()).toMesh();
      var triMesh = TriMesh.fromMesh(mesh);
      //save it to a stream, 115 vertices * 32bytes per vertex
      var stream = new ByteArrayOutputStream();
      try(var s = Stream.wrap(stream)) {
          triMesh.writeVerticesTo(s);
          //save indices as ushort to stream, 504 indices * 2 bytes per index
          triMesh.write16bIndicesTo(s);
      }
```

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |

### write16bIndicesTo(OutputStream stream) {#write16bIndicesTo-java.io.OutputStream-}
```
public void write16bIndicesTo(OutputStream stream)
```


インデックスデータを 16 ビット整数としてストリームに書き込みます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | ストリーム | java.io.OutputStream | **Example:** |

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh    
     var mesh = (new Sphere()).toMesh();    
     var triMesh = TriMesh.fromMesh(mesh);    
     //save it to a stream, 115 vertices * 32bytes per vertex    
     var stream = new ByteArrayOutputStream();    
     triMesh.writeVerticesTo(stream);    
     //save indices as ushort to stream, 504 indices * 2 bytes per index    
     triMesh.write16bIndicesTo(stream);
``` |

### write32bIndicesTo(Stream stream) {#write32bIndicesTo-com.aspose.threed.Stream-}
```
public void write32bIndicesTo(Stream stream)
```


インデックスデータを 32 ビット整数としてストリームに書き込みます **Example:**

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh
      var mesh = (new Sphere()).toMesh();
      var triMesh = TriMesh.fromMesh(mesh);
      //save it to a stream, 115 vertices * 32bytes per vertex
      var stream = new ByteArrayOutputStream();
      try(var s = Stream.wrap(stream)) {
          triMesh.writeVerticesTo(s);
          //save indices as ushort to stream, 504 indices * 2 bytes per index
          triMesh.write32bIndicesTo(s);
      }
```

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |

### write32bIndicesTo(OutputStream stream) {#write32bIndicesTo-java.io.OutputStream-}
```
public void write32bIndicesTo(OutputStream stream)
```


インデックスデータを 32 ビット整数としてストリームに書き込みます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | ストリーム | java.io.OutputStream | **Example:** |

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh    
      var mesh = (new Sphere()).toMesh();    
      var triMesh = TriMesh.fromMesh(mesh);    
      //save it to a stream, 115 vertices * 32bytes per vertex    
      var stream = new ByteArrayOutputStream();    
      triMesh.writeVerticesTo(stream);    
      //save indices as ushort to stream, 504 indices * 2 bytes per index    
      triMesh.write32bIndicesTo(stream);
``` |

### writeVerticesTo(Stream stream) {#writeVerticesTo-com.aspose.threed.Stream-}
```
public void writeVerticesTo(Stream stream)
```


指定されたストリームに頂点データを書き込みます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | stream | [Stream](../../com.aspose.threed/stream) | The stream that the vertices data will be written to **Example:** |

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh
      var mesh = (new Sphere()).toMesh();
      var triMesh = TriMesh.fromMesh(mesh);
      //save it to a stream, 115 vertices * 32bytes per vertex
      var stream = new ByteArrayOutputStream();
      try(var s = Stream.wrap(stream)) {
          triMesh.writeVerticesTo(s);
          //save indices as ushort to stream, 504 indices * 2 bytes per index
          triMesh.write16bIndicesTo(s);
      }
``` |

### writeVerticesTo(OutputStream stream) {#writeVerticesTo-java.io.OutputStream-}
```
public void writeVerticesTo(OutputStream stream)
```


指定されたストリームに頂点データを書き込みます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | ストリーム | java.io.OutputStream | The stream that the vertices data will be written to **Example:** |

```
//convert a mesh to TriMesh, the layout is automatically inferred from input mesh    
      var mesh = (new Sphere()).toMesh();    
      var triMesh = TriMesh.fromMesh(mesh);    
      //save it to a stream, 115 vertices * 32bytes per vertex    
      var stream = new ByteArrayOutputStream();    
      triMesh.writeVerticesTo(stream);    
      //save indices as ushort to stream, 504 indices * 2 bytes per index    
      triMesh.write16bIndicesTo(stream);
``` |

