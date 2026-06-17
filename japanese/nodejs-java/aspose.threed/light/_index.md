---
title: "Light"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/light/
---
## Light class

光はシーンを照らします。光の総減衰を計算する式は次のとおりです:  A = ConstantAttenuation + (Dist  LinearAttenuation) + ((Dist^2)  QuadraticAttenuation)


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() | Light クラスの新しいインスタンスを初期化します。 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名前 | 説明 |
| --- | --- |
| constructor_overload(name) | Light クラスの新しいインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| name | 文字列 | 名前 |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 名前 | 説明 |
| --- | --- |
| constructor_overload2(name, type) | Light クラスの新しいインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| name | 文字列 | 名前 |
| type | LightType | LightType |

 **Result:**



---


### getColor{#getColor}

| 名前 | 説明 |
| --- | --- |
| getColor() | 光の色を取得または設定します。 |

 **Result:**



---


### setColor{#setColor}

| 名前 | 説明 |
| --- | --- |
| setColor(value) | 光の色を取得または設定します。 |

 **Result:**



---


### getLightType{#getLightType}

| 名前 | 説明 |
| --- | --- |
| getLightType() | 光のタイプを取得または設定します。このプロパティの値は LightType の整数定数です。 |

 **Result:**



---


### setLightType{#setLightType}

| 名前 | 説明 |
| --- | --- |
| setLightType(value) | 光のタイプを取得または設定します。このプロパティの値は LightType の整数定数です。 |

 **Result:**



---


### getCastLight{#getCastLight}

| 名前 | 説明 |
| --- | --- |
| getCastLight() | 現在の光インスタンスが他のオブジェクトを照らすかどうかを取得または設定します。 |

 **Result:**



---


### setCastLight{#setCastLight}

| 名前 | 説明 |
| --- | --- |
| setCastLight(value) | 現在の光インスタンスが他のオブジェクトを照らすかどうかを取得または設定します。 |

 **Result:**



---


### getIntensity{#getIntensity}

| 名前 | 説明 |
| --- | --- |
| getIntensity() | 光の強度を取得または設定します。デフォルト値は 100 です。 |

 **Result:**



---


### setIntensity{#setIntensity}

| 名前 | 説明 |
| --- | --- |
| setIntensity(value) | 光の強度を取得または設定します。デフォルト値は 100 です。 |

 **Result:**



---


### getHotSpot{#getHotSpot}

| 名前 | 説明 |
| --- | --- |
| getHotSpot() | ホットスポットの円錐角（度）を取得または設定します。 |

 **Result:**



---


### setHotSpot{#setHotSpot}

| 名前 | 説明 |
| --- | --- |
| setHotSpot(value) | ホットスポットの円錐角（度）を取得または設定します。 |

 **Result:**



---


### getFalloff{#getFalloff}

| 名前 | 説明 |
| --- | --- |
| getFalloff() | 減衰円錐角（度）を取得または設定します。 |

 **Result:**



---


### setFalloff{#setFalloff}

| 名前 | 説明 |
| --- | --- |
| setFalloff(value) | 減衰円錐角（度）を取得または設定します。 |

 **Result:**



---


### getConstantAttenuation{#getConstantAttenuation}

| 名前 | 説明 |
| --- | --- |
| getConstantAttenuation() | 光の総減衰を計算するための定数減衰を取得または設定します。 |

 **Result:**



---


### setConstantAttenuation{#setConstantAttenuation}

| 名前 | 説明 |
| --- | --- |
| setConstantAttenuation(value) | 光の総減衰を計算するための定数減衰を取得または設定します。 |

 **Result:**



---


### getLinearAttenuation{#getLinearAttenuation}

| 名前 | 説明 |
| --- | --- |
| getLinearAttenuation() | 光の総減衰を計算するための線形減衰を取得または設定します。 |

 **Result:**



---


### setLinearAttenuation{#setLinearAttenuation}

| 名前 | 説明 |
| --- | --- |
| setLinearAttenuation(value) | 光の総減衰を計算するための線形減衰を取得または設定します。 |

 **Result:**



---


### getQuadraticAttenuation{#getQuadraticAttenuation}

| 名前 | 説明 |
| --- | --- |
| getQuadraticAttenuation() | 光の総減衰を計算するための二次減衰を取得または設定します。 |

 **Result:**



---


### setQuadraticAttenuation{#setQuadraticAttenuation}

| 名前 | 説明 |
| --- | --- |
| setQuadraticAttenuation(value) | 光の総減衰を計算するための二次減衰を取得または設定します。 |

 **Result:**



---


### getCastShadows{#getCastShadows}

| 名前 | 説明 |
| --- | --- |
| getCastShadows() | 光が他のオブジェクトに影を落とすかどうかを取得または設定します。 |

 **Result:**



---


### setCastShadows{#setCastShadows}

| 名前 | 説明 |
| --- | --- |
| setCastShadows(value) | 光が他のオブジェクトに影を落とすかどうかを取得または設定します。 |

 **Result:**



---


### getShadowColor{#getShadowColor}

| 名前 | 説明 |
| --- | --- |
| getShadowColor() | 影の色を取得または設定します。 |

 **Result:**



---


### setShadowColor{#setShadowColor}

| 名前 | 説明 |
| --- | --- |
| setShadowColor(value) | 影の色を取得または設定します。 |

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



