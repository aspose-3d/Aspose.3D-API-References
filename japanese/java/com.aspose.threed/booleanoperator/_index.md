---
title: BooleanOperator
second_title: Aspose.3D for Java API リファレンス
description: ブール演算子を使用すると、2つのインスタンスに対してブール演算を適用できます。
type: docs
weight: 23
url: /ja/java/com.aspose.threed/booleanoperator/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity)

**All Implemented Interfaces:**
[com.aspose.threed.IMeshConvertible](../../com.aspose.threed/imeshconvertible)
```
public class BooleanOperator extends Entity implements IMeshConvertible
```

Boolean operator は、2つの [IMeshConvertible](../../com.aspose.threed/imeshconvertible) インスタンスに対して Boolean 操作を適用できるようにします。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [BooleanOperator()](#BooleanOperator--) | [BooleanOperator](../../com.aspose.threed/booleanoperator) のコンストラクタ |
| [BooleanOperator(BooleanOperation operation, A3DObject first, A3DObject second)](#BooleanOperator-com.aspose.threed.BooleanOperation-com.aspose.threed.A3DObject-com.aspose.threed.A3DObject-) | 2つのオペランドを使用して [BooleanOperator](../../com.aspose.threed/booleanoperator) の新しいインスタンスを構築します |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | プロパティを検索します。 |
| [getBoundingBox()](#getBoundingBox--) | 現在のエンティティのオブジェクト空間座標系におけるバウンディングボックスを取得します。 |
| [getClass()](#getClass--) |  |
| [getEntityRendererKey()](#getEntityRendererKey--) | レンダラーに登録されたエンティティレンダラーのキーを取得します |
| [getExcluded()](#getExcluded--) | エクスポート時にこのエンティティを除外するかどうかを取得します。 |
| [getFirst()](#getFirst--) | Boolean operator の最初のオペランド |
| [getName()](#getName--) | 名前を取得します。 |
| [getOperator()](#getOperator--) | 結果メッシュを作成する操作で使用される Boolean operator |
| [getParentNode()](#getParentNode--) | 最初の親ノードを取得します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。 |
| [getParentNodes()](#getParentNodes--) | すべての親ノードを取得します。エンティティはジオメトリインスタンシングのために複数の親ノードにアタッチできます。 |
| [getProperties()](#getProperties--) | すべてのプロパティのコレクションを取得します。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 指定されたプロパティの値を取得します |
| [getScene()](#getScene--) | このオブジェクトが属するシーンを取得します |
| [getSecond()](#getSecond--) | Boolean operator の2番目のオペランド |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 動的プロパティを削除します。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 名前で識別される指定されたプロパティを削除します |
| [setExcluded(boolean value)](#setExcluded-boolean-) | エクスポート時にこのエンティティを除外するかどうかを設定します。 |
| [setFirst(BooleanOperand value)](#setFirst-com.aspose.threed.BooleanOperand-) | Boolean operator の最初のオペランド |
| [setName(String value)](#setName-java.lang.String-) | 名前を設定します。 |
| [setOperator(BooleanOperation value)](#setOperator-com.aspose.threed.BooleanOperation-) | 結果メッシュを作成する操作で使用される Boolean operator |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 最初の親ノードを設定します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 指定されたプロパティの値を設定します |
| [setSecond(BooleanOperand value)](#setSecond-com.aspose.threed.BooleanOperand-) | Boolean operator の2番目のオペランド |
| [toMesh()](#toMesh--) | 2つのオペランドに対して Boolean 操作を実行します |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### BooleanOperator() {#BooleanOperator--}
```
public BooleanOperator()
```


[BooleanOperator](../../com.aspose.threed/booleanoperator) のコンストラクタ

### BooleanOperator(BooleanOperation operation, A3DObject first, A3DObject second) {#BooleanOperator-com.aspose.threed.BooleanOperation-com.aspose.threed.A3DObject-com.aspose.threed.A3DObject-}
```
public BooleanOperator(BooleanOperation operation, A3DObject first, A3DObject second)
```


2つのオペランドを使用して [BooleanOperator](../../com.aspose.threed/booleanoperator) の新しいインスタンスを構築します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| operation | [BooleanOperation](../../com.aspose.threed/booleanoperation) | Boolean 操作の種類 |
| first | [A3DObject](../../com.aspose.threed/a3dobject) | [IMeshConvertible](../../com.aspose.threed/imeshconvertible)、[HalfSpace](../../com.aspose.threed/halfspace) または [Node](../../com.aspose.threed/node) のインスタンス |
| second | [A3DObject](../../com.aspose.threed/a3dobject) | [IMeshConvertible](../../com.aspose.threed/imeshconvertible)、[HalfSpace](../../com.aspose.threed/halfspace) または [Node](../../com.aspose.threed/node) のインスタンス |

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
### getFirst() {#getFirst--}
```
public BooleanOperand getFirst()
```


Boolean operator の最初のオペランド

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - The first operand of the Boolean operator
### getName() {#getName--}
```
public String getName()
```


名前を取得します。

**Returns:**
java.lang.String - 名前です。
### getOperator() {#getOperator--}
```
public BooleanOperation getOperator()
```


結果メッシュを作成する操作で使用される Boolean operator

**Returns:**
[BooleanOperation](../../com.aspose.threed/booleanoperation) - The Boolean operator used in the operation to create the result mesh.
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
### getSecond() {#getSecond--}
```
public BooleanOperand getSecond()
```


Boolean operator の2番目のオペランド

**Returns:**
[BooleanOperand](../../com.aspose.threed/booleanoperand) - The second operand of the Boolean operator
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
### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


エクスポート時にこのエンティティを除外するかどうかを設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | boolean | 新しい値 |

### setFirst(BooleanOperand value) {#setFirst-com.aspose.threed.BooleanOperand-}
```
public void setFirst(BooleanOperand value)
```


Boolean operator の最初のオペランド

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [BooleanOperand](../../com.aspose.threed/booleanoperand) | 新しい値 |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


名前を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setOperator(BooleanOperation value) {#setOperator-com.aspose.threed.BooleanOperation-}
```
public void setOperator(BooleanOperation value)
```


結果メッシュを作成する操作で使用される Boolean operator

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [BooleanOperation](../../com.aspose.threed/booleanoperation) | 新しい値 |

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

### setSecond(BooleanOperand value) {#setSecond-com.aspose.threed.BooleanOperand-}
```
public void setSecond(BooleanOperand value)
```


Boolean operator の2番目のオペランド

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [BooleanOperand](../../com.aspose.threed/booleanoperand) | 新しい値 |

### toMesh() {#toMesh--}
```
public Mesh toMesh()
```


2つのオペランドに対して Boolean 操作を実行します

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

