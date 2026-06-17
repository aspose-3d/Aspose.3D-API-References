---
title: "カメラ"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/camera/
---
## Camera class

カメラはシーンを見る視聴者の視点（アイポイント）を表します。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() | Camera クラスの新しいインスタンスを初期化します。 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名前 | 説明 |
| --- | --- |
| constructor_overload(projectionType) | Camera クラスの新しいインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| projectionType | ProjectionType | ProjectionType |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 名前 | 説明 |
| --- | --- |
| constructor_overload2(name) | Camera クラスの新しいインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| name | 文字列 | 名前。 |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| 名前 | 説明 |
| --- | --- |
| constructor_overload3(name, projectionType) | Camera クラスの新しいインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| name | 文字列 | 名前。 |
| projectionType | ProjectionType | ProjectionType |

 **Result:**



---


### getApertureMode{#getApertureMode}

| 名前 | 説明 |
| --- | --- |
| getApertureMode() | カメラの絞りモードを取得または設定します。このプロパティの値は ApertureMode 整数定数です。 |

 **Result:**



---


### setApertureMode{#setApertureMode}

| 名前 | 説明 |
| --- | --- |
| setApertureMode(value) | カメラの絞りモードを取得または設定します。このプロパティの値は ApertureMode 整数定数です。 |

 **Result:**



---


### getFieldOfView{#getFieldOfView}

| 名前 | 説明 |
| --- | --- |
| getFieldOfView() | カメラの視野角（度）を取得または設定します。このプロパティは、ApertureMode が ApertureMode.HORIZONTAL または ApertureMode.VERTICAL の場合にのみ使用されます。 |

 **Result:**



---


### setFieldOfView{#setFieldOfView}

| 名前 | 説明 |
| --- | --- |
| setFieldOfView(value) | カメラの視野角（度）を取得または設定します。このプロパティは、ApertureMode が ApertureMode.HORIZONTAL または ApertureMode.VERTICAL の場合にのみ使用されます。 |

 **Result:**



---


### getFieldOfViewX{#getFieldOfViewX}

| 名前 | 説明 |
| --- | --- |
| getFieldOfViewX() | カメラの水平視野角（度）を取得または設定します。このプロパティは、ApertureMode が ApertureMode.HORIZ_AND_VERT の場合にのみ使用されます。 |

 **Result:**



---


### setFieldOfViewX{#setFieldOfViewX}

| 名前 | 説明 |
| --- | --- |
| setFieldOfViewX(value) | カメラの水平視野角（度）を取得または設定します。このプロパティは、ApertureMode が ApertureMode.HORIZ_AND_VERT の場合にのみ使用されます。 |

 **Result:**



---


### getFieldOfViewY{#getFieldOfViewY}

| 名前 | 説明 |
| --- | --- |
| getFieldOfViewY() | カメラの垂直視野角（度）を取得または設定します。このプロパティは、ApertureMode が ApertureMode.HORIZ_AND_VERT の場合にのみ使用されます。 |

 **Result:**



---


### setFieldOfViewY{#setFieldOfViewY}

| 名前 | 説明 |
| --- | --- |
| setFieldOfViewY(value) | カメラの垂直視野角（度）を取得または設定します。このプロパティは、ApertureMode が ApertureMode.HORIZ_AND_VERT の場合にのみ使用されます。 |

 **Result:**



---


### getWidth{#getWidth}

| 名前 | 説明 |
| --- | --- |
| getWidth() | ビュー平面の幅（インチ）を取得または設定します。 |

 **Result:**



---


### setWidth{#setWidth}

| 名前 | 説明 |
| --- | --- |
| setWidth(value) | ビュー平面の幅（インチ）を取得または設定します。 |

 **Result:**



---


### getHeight{#getHeight}

| 名前 | 説明 |
| --- | --- |
| getHeight() | ビュー平面の高さ（インチ）を取得または設定します。 |

 **Result:**



---


### setHeight{#setHeight}

| 名前 | 説明 |
| --- | --- |
| setHeight(value) | ビュー平面の高さ（インチ）を取得または設定します。 |

 **Result:**



---


### getAspectRatio{#getAspectRatio}

| 名前 | 説明 |
| --- | --- |
| getAspectRatio() | ビュー平面のアスペクト比を取得または設定します。 |

 **Result:**



---


### setAspectRatio{#setAspectRatio}

| 名前 | 説明 |
| --- | --- |
| setAspectRatio(value) | ビュー平面のアスペクト比を取得または設定します。 |

 **Result:**



---


### getMagnification{#getMagnification}

| 名前 | 説明 |
| --- | --- |
| getMagnification() | 正射影カメラで使用される倍率を取得または設定します。 |

 **Result:**



---


### setMagnification{#setMagnification}

| 名前 | 説明 |
| --- | --- |
| setMagnification(value) | 正射影カメラで使用される倍率を取得または設定します。 |

 **Result:**



---


### getProjectionType{#getProjectionType}

| 名前 | 説明 |
| --- | --- |
| getProjectionType() | カメラの投影タイプを取得または設定します。デフォルトではパースペクティブ投影が使用されます。このプロパティの値は ProjectionType 整数定数です。 |

 **Result:**



---


### setProjectionType{#setProjectionType}

| 名前 | 説明 |
| --- | --- |
| setProjectionType(value) | カメラの投影タイプを取得または設定します。デフォルトではパースペクティブ投影が使用されます。このプロパティの値は ProjectionType 整数定数です。 |

 **Result:**



---


### getRotationMode{#getRotationMode}

| 名前 | 説明 |
| --- | --- |
| getRotationMode() | 視錐台の向きモードを取得または設定します。このプロパティは Target が null の場合にのみ機能します。値が RotationMode.FIXED_TARGET の場合、方向は常に LookAt プロパティによって計算されます。それ以外の場合、LookAt は常に Direction によって計算されます。プロパティの値は RotationMode の整数定数です。 |

 **Result:**



---


### setRotationMode{#setRotationMode}

| 名前 | 説明 |
| --- | --- |
| setRotationMode(value) | 視錐台の向きモードを取得または設定します。このプロパティは Target が null の場合にのみ機能します。値が RotationMode.FIXED_TARGET の場合、方向は常に LookAt プロパティによって計算されます。それ以外の場合、LookAt は常に Direction によって計算されます。プロパティの値は RotationMode の整数定数です。 |

 **Result:**



---


### getNearPlane{#getNearPlane}

| 名前 | 説明 |
| --- | --- |
| getNearPlane() | 視錐台の近接平面距離を取得または設定します。 |

 **Result:**



---


### setNearPlane{#setNearPlane}

| 名前 | 説明 |
| --- | --- |
| setNearPlane(value) | 視錐台の近接平面距離を取得または設定します。 |

 **Result:**



---


### getFarPlane{#getFarPlane}

| 名前 | 説明 |
| --- | --- |
| getFarPlane() | フラスタムの遠平面距離を取得または設定します。 |

 **Result:**



---


### setFarPlane{#setFarPlane}

| 名前 | 説明 |
| --- | --- |
| setFarPlane(value) | フラスタムの遠平面距離を取得または設定します。 |

 **Result:**



---


### getAspect{#getAspect}

| 名前 | 説明 |
| --- | --- |
| getAspect() | フラスタムのアスペクト比を取得または設定します。 |

 **Result:**



---


### setAspect{#setAspect}

| 名前 | 説明 |
| --- | --- |
| setAspect(value) | フラスタムのアスペクト比を取得または設定します。 |

 **Result:**



---


### getOrthoHeight{#getOrthoHeight}

| 名前 | 説明 |
| --- | --- |
| getOrthoHeight() | フラスタムが正射影の場合の高さを取得または設定します。 |

 **Result:**



---


### setOrthoHeight{#setOrthoHeight}

| 名前 | 説明 |
| --- | --- |
| setOrthoHeight(value) | フラスタムが正射影の場合の高さを取得または設定します。 |

 **Result:**



---


### getUp{#getUp}

| 名前 | 説明 |
| --- | --- |
| getUp() | カメラの上方向ベクトルを取得または設定します。 |

 **Result:**



---


### setUp{#setUp}

| 名前 | 説明 |
| --- | --- |
| setUp(value) | カメラの上方向ベクトルを取得または設定します。 |

 **Result:**



---


### getLookAt{#getLookAt}

| 名前 | 説明 |
| --- | --- |
| getLookAt() | カメラが注目している位置を取得または設定します。 |

 **Result:**



---


### setLookAt{#setLookAt}

| 名前 | 説明 |
| --- | --- |
| setLookAt(value) | カメラが注目している位置を取得または設定します。 |

 **Result:**



---


### getDirection{#getDirection}

| 名前 | 説明 |
| --- | --- |
| getDirection() | カメラが向いている方向を取得または設定します。このプロパティの変更は LookAt と Target にも影響します。 |

 **Result:**



---


### setDirection{#setDirection}

| 名前 | 説明 |
| --- | --- |
| setDirection(value) | カメラが向いている方向を取得または設定します。このプロパティの変更は LookAt と Target にも影響します。 |

 **Result:**



---


### getTarget{#getTarget}

| 名前 | 説明 |
| --- | --- |
| getTarget() | カメラが向いているターゲットを取得または設定します。ユーザーがこのプロパティをサポートしている場合、LookAt プロパティよりも先に設定すべきです。 |

 **Result:**



---


### setTarget{#setTarget}

| 名前 | 説明 |
| --- | --- |
| setTarget(value) | カメラが向いているターゲットを取得または設定します。ユーザーがこのプロパティをサポートしている場合、LookAt プロパティよりも先に設定すべきです。 |

 **Result:**



---


### getParentNodes{#getParentNodes}

| 名前 | 説明 |
| --- | --- |
| getParentNodes() | すべての親ノードを取得します。エンティティはジオメトリインスタンシングのために複数の親ノードにアタッチできます。 |

 **Result:**



---


### getExcluded{#getExcluded}

| 名前 | 説明 |
| --- | --- |
| getExcluded() | エクスポート時にこのエンティティを除外するかどうかを取得または設定します。 |

 **Result:**



---


### setExcluded{#setExcluded}

| 名前 | 説明 |
| --- | --- |
| setExcluded(value) | エクスポート時にこのエンティティを除外するかどうかを取得または設定します。 |

 **Result:**



---


### getParentNode{#getParentNode}

| 名前 | 説明 |
| --- | --- |
| getParentNode() | 最初の親ノードを取得または設定します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。親ノード。 |

 **Result:**



---


### setParentNode{#setParentNode}

| 名前 | 説明 |
| --- | --- |
| setParentNode(value) | 最初の親ノードを取得または設定します。最初の親ノードを設定すると、このエンティティは他の親ノードから切り離されます。親ノード。 |

 **Result:**



---


### getScene{#getScene}

| 名前 | 説明 |
| --- | --- |
| getScene() | このオブジェクトが属するシーンを取得します。 |

 **Result:**



---


### getName{#getName}

| 名前 | 説明 |
| --- | --- |
| getName() | 名前を取得または設定します。名前。 |

 **Result:**



---


### setName{#setName}

| 名前 | 説明 |
| --- | --- |
| setName(value) | 名前を取得または設定します。名前。 |

 **Result:**



---


### getProperties{#getProperties}

| 名前 | 説明 |
| --- | --- |
| getProperties() | すべてのプロパティのコレクションを取得します。 |

 **Result:**



---


### moveForward{#moveForward}

| 名前 | 説明 |
| --- | --- |
| moveForward(distance) | カメラをその方向またはターゲットに向かって前方に移動します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| distance | 数 | 前方にどれだけ移動するか |

 **Result:**



---


### getBoundingBox{#getBoundingBox}

| 名前 | 説明 |
| --- | --- |
| getBoundingBox() | 現在のエンティティのオブジェクト空間座標系におけるバウンディングボックスを取得します。 |

 **Result:**



---


### getEntityRendererKey{#getEntityRendererKey}

| 名前 | 説明 |
| --- | --- |
| getEntityRendererKey() | レンダラーに登録されたエンティティレンダラーのキーを取得します。 |

 **Result:**
EntityRendererKey


---


### removeProperty{#removeProperty}

| 名前 | 説明 |
| --- | --- |
| removeProperty(property) | 動的プロパティを削除します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| property | Property | 削除するプロパティはどれですか |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| 名前 | 説明 |
| --- | --- |
| removeProperty(property) | 名前で識別された指定されたプロパティを削除します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| propert | 文字列 | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| 名前 | 説明 |
| --- | --- |
| getProperty(property) | 指定されたプロパティの値を取得します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| property | 文字列 | プロパティ名 |

 **Result:**
オブジェクト


---


### setProperty{#setProperty}

| 名前 | 説明 |
| --- | --- |
| setProperty(property, value) | 指定されたプロパティの値を設定します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| property | 文字列 | プロパティ名 |
| 値 | オブジェクト | プロパティの値 |

 **Result:**
オブジェクト


---


### findProperty{#findProperty}

| 名前 | 説明 |
| --- | --- |
| findProperty(propertyName) | プロパティを検索します。動的プロパティ（CreateDynamicProperty/SetProperty によって作成）またはネイティブプロパティ（名前で識別）になる可能性があります |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| propertyName | 文字列 | プロパティ名。 |

 **Result:**
Property


---



