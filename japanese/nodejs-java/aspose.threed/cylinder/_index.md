---
title: "Cylinder"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/cylinder/
---
## Cylinder class

パラメータ化されたシリンダーです。 radiusTop または radiusBottom のいずれかがゼロの場合、円錐を表すためにも使用できます。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() | Cylinder クラスの新しいインスタンスを初期化します。 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名前 | 説明 |
| --- | --- |
| constructor_overload(radius, height) | Cylinder クラスの新しいインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| 半径 | 数 | 上部と下部のキャップの半径。 |
| height | 数 | 高さ。 |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 名前 | 説明 |
| --- | --- |
| constructor_overload2(radiusTop, radiusBottom, height) | Cylinder クラスの新しいインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| radiusTop | 数 | 上部の半径。 |
| radiusBottom | 数 | 下部の半径。 |
| height | 数 | 高さ。 |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| 名前 | 説明 |
| --- | --- |
| constructor_overload3(radiusTop, radiusBottom, height, radialSegments, heightSegments, openEnded) | Cylinder クラスの新しいインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| radiusTop | 数 | Cylinder の上部キャップの半径。 |
| radiusBottom | 数 | Cylinder の下部キャップの半径。 |
| height | 数 | Cylinder の高さ。 |
| radialSegments | 数 | 上部と下部の円のラジアルセグメント.. |
| heightSegments | 数 | 高さセグメント。 |
| openEnded | boolean | 設定する場合は |

 **Result:**



---


### constructor_overload4{#constructor_overload4}

| 名前 | 説明 |
| --- | --- |
| constructor_overload4(name, radiusTop, radiusBottom, height, radialSegments, heightSegments, openEnded, thetaStart, thetaLength) | Cylinder クラスの新しいインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| name | 文字列 | このオブジェクトの名前 |
| radiusTop | 数 | Cylinder の上部キャップの半径。 |
| radiusBottom | 数 | Cylinder の下部キャップの半径。 |
| height | 数 | Cylinder の高さ。 |
| radialSegments | 数 | 上部と下部の円のラジアルセグメント.. |
| heightSegments | 数 | 高さセグメント。 |
| openEnded | boolean | 設定する場合は |
| thetaStart | 数 | Theta の開始。 |
| thetaLength | 数 | Theta の長さ。 |

 **Result:**



---


### getOffsetBottom{#getOffsetBottom}

| 名前 | 説明 |
| --- | --- |
| getOffsetBottom() | 底面側の頂点変換オフセットを取得または設定します。 |

 **Result:**



---


### setOffsetBottom{#setOffsetBottom}

| 名前 | 説明 |
| --- | --- |
| setOffsetBottom(value) | 底面側の頂点変換オフセットを取得または設定します。 |

 **Result:**



---


### getOffsetTop{#getOffsetTop}

| 名前 | 説明 |
| --- | --- |
| getOffsetTop() | 上面側の頂点変換オフセットを取得または設定します。 |

 **Result:**



---


### setOffsetTop{#setOffsetTop}

| 名前 | 説明 |
| --- | --- |
| setOffsetTop(value) | 上面側の頂点変換オフセットを取得または設定します。 |

 **Result:**



---


### getGenerateFanCylinder{#getGenerateFanCylinder}

| 名前 | 説明 |
| --- | --- |
| getGenerateFanCylinder() | ThetaLength が 2π 未満のときにファン形シリンダーを生成するかどうかを取得または設定します。そうでない場合、モデルはカットされません。 |

 **Result:**



---


### setGenerateFanCylinder{#setGenerateFanCylinder}

| 名前 | 説明 |
| --- | --- |
| setGenerateFanCylinder(value) | ThetaLength が 2π 未満のときにファン形シリンダーを生成するかどうかを取得または設定します。そうでない場合、モデルはカットされません。 |

 **Result:**



---


### getShearBottom{#getShearBottom}

| 名前 | 説明 |
| --- | --- |
| getShearBottom() | 底面のせん断変換を取得または設定します。ベクトルはラジアンで測定された (x 軸, z 軸) のせん断値を格納し、デフォルト値は (0, 0) です。 |

 **Result:**



---


### setShearBottom{#setShearBottom}

| 名前 | 説明 |
| --- | --- |
| setShearBottom(value) | 底面のせん断変換を取得または設定します。ベクトルはラジアンで測定された (x 軸, z 軸) のせん断値を格納し、デフォルト値は (0, 0) です。 |

 **Result:**



---


### getShearTop{#getShearTop}

| 名前 | 説明 |
| --- | --- |
| getShearTop() | 上面のせん断変換を取得または設定します。ベクトルはラジアンで測定された (x 軸, z 軸) のせん断値を格納し、デフォルト値は (0, 0) です。 |

 **Result:**



---


### setShearTop{#setShearTop}

| 名前 | 説明 |
| --- | --- |
| setShearTop(value) | 上面のせん断変換を取得または設定します。ベクトルはラジアンで測定された (x 軸, z 軸) のせん断値を格納し、デフォルト値は (0, 0) です。 |

 **Result:**



---


### getRadiusTop{#getRadiusTop}

| 名前 | 説明 |
| --- | --- |
| getRadiusTop() | シリンダーの上部キャップの半径を取得または設定します。上部キャップの半径です。 |

 **Result:**



---


### setRadiusTop{#setRadiusTop}

| 名前 | 説明 |
| --- | --- |
| setRadiusTop(value) | シリンダーの上部キャップの半径を取得または設定します。上部キャップの半径です。 |

 **Result:**



---


### getRadiusBottom{#getRadiusBottom}

| 名前 | 説明 |
| --- | --- |
| getRadiusBottom() | シリンダーの下部キャップの半径を取得または設定します。下部キャップの半径です。 |

 **Result:**



---


### setRadiusBottom{#setRadiusBottom}

| 名前 | 説明 |
| --- | --- |
| setRadiusBottom(value) | シリンダーの下部キャップの半径を取得または設定します。下部キャップの半径です。 |

 **Result:**



---


### getHeight{#getHeight}

| 名前 | 説明 |
| --- | --- |
| getHeight() | シリンダーの高さを取得または設定します。高さです。 |

 **Result:**



---


### setHeight{#setHeight}

| 名前 | 説明 |
| --- | --- |
| setHeight(value) | シリンダーの高さを取得または設定します。高さです。 |

 **Result:**



---


### getRadialSegments{#getRadialSegments}

| 名前 | 説明 |
| --- | --- |
| getRadialSegments() | ラジアルセグメントを取得または設定します。ラジアルセグメントです。 |

 **Result:**



---


### setRadialSegments{#setRadialSegments}

| 名前 | 説明 |
| --- | --- |
| setRadialSegments(value) | ラジアルセグメントを取得または設定します。ラジアルセグメントです。 |

 **Result:**



---


### getHeightSegments{#getHeightSegments}

| 名前 | 説明 |
| --- | --- |
| getHeightSegments() | 高さセグメントを取得または設定します。高さセグメント。 |

 **Result:**



---


### setHeightSegments{#setHeightSegments}

| 名前 | 説明 |
| --- | --- |
| setHeightSegments(value) | 高さセグメントを取得または設定します。高さセグメント。 |

 **Result:**



---


### getOpenEnded{#getOpenEnded}

| 名前 | 説明 |
| --- | --- |
| getOpenEnded() | このシリンダーが開口部かどうかを示す値を取得または設定します。デフォルト値は false です。開口部の場合は true、そうでなければ上部/下部のキャップが存在します。 |

 **Result:**



---


### setOpenEnded{#setOpenEnded}

| 名前 | 説明 |
| --- | --- |
| setOpenEnded(value) | このシリンダーが開口部かどうかを示す値を取得または設定します。デフォルト値は false です。開口部の場合は true、そうでなければ上部/下部のキャップが存在します。 |

 **Result:**



---


### getThetaStart{#getThetaStart}

| 名前 | 説明 |
| --- | --- |
| getThetaStart() | シータ開始角度を取得または設定します。デフォルト値は 0 です。シータ開始角度です。 |

 **Result:**



---


### setThetaStart{#setThetaStart}

| 名前 | 説明 |
| --- | --- |
| setThetaStart(value) | シータ開始角度を取得または設定します。デフォルト値は 0 です。シータ開始角度です。 |

 **Result:**



---


### getThetaLength{#getThetaLength}

| 名前 | 説明 |
| --- | --- |
| getThetaLength() | シータの長さを取得または設定します。デフォルト値は 2π です。シータの長さです。 |

 **Result:**



---


### setThetaLength{#setThetaLength}

| 名前 | 説明 |
| --- | --- |
| setThetaLength(value) | シータの長さを取得または設定します。デフォルト値は 2π です。シータの長さです。 |

 **Result:**



---


### getCastShadows{#getCastShadows}

| 名前 | 説明 |
| --- | --- |
| getCastShadows() | このジオメトリが影を落とすかどうかを取得または設定します |

 **Result:**



---


### setCastShadows{#setCastShadows}

| 名前 | 説明 |
| --- | --- |
| setCastShadows(value) | このジオメトリが影を落とすかどうかを取得または設定します |

 **Result:**



---


### getReceiveShadows{#getReceiveShadows}

| 名前 | 説明 |
| --- | --- |
| getReceiveShadows() | このジオメトリが影を受け取るかどうかを取得または設定します。 |

 **Result:**



---


### setReceiveShadows{#setReceiveShadows}

| 名前 | 説明 |
| --- | --- |
| setReceiveShadows(value) | このジオメトリが影を受け取るかどうかを取得または設定します。 |

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


### toMesh{#toMesh}

| 名前 | 説明 |
| --- | --- |
| toMesh() | 現在のオブジェクトをメッシュに変換します |

 **Result:**
Mesh


---


### getBoundingBox{#getBoundingBox}

| 名前 | 説明 |
| --- | --- |
| getBoundingBox() | 現在のエンティティのオブジェクト空間座標系におけるバウンディングボックスを取得します。 |

 **Result:**
Mesh


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



