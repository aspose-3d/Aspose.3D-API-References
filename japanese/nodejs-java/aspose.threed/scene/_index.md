---
title: "Scene"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/scene/
---
## Scene class

シーンは、ノード、ジオメトリ、マテリアル、テクスチャ、アニメーション、ポーズ、サブシーンなどを含むトップレベルオブジェクトです。シーンはサブシーンを持つことができ、collada/blender/fbx などのファイルにおけるマルチドキュメントサポートとして機能します。ノード階層は RootNodeLibrary を通じてアクセスでき、シリアライズ中（メタデータやカスタムオブジェクトなど）に未接続オブジェクトへの参照を保持するために使用され、ライブラリとして利用できます。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() | Scene クラスの新しいインスタンスを初期化します。 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名前 | 説明 |
| --- | --- |
| constructor_overload(entity) | 新しいノードにエンティティがアタッチされた状態で、Scene クラスの新しいインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| エンティティ | エンティティ | シーンにアタッチされた初期エンティティ |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 名前 | 説明 |
| --- | --- |
| constructor_overload2(parentScene, name) | Scene クラスの新しいインスタンスをサブシーンとして初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| parentScene | Scene | 親シーンです。 |
| name | 文字列 | Scene の名前です。 |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| 名前 | 説明 |
| --- | --- |
| constructor_overload3(fileName) | Scene クラスの新しいインスタンスを初期化し、すぐにファイルを開きます。このコンストラクタは廃止されました。#Error Cref: M:Aspose.ThreeD.Scene.FromFile(System.String,System.Threading.CancellationToken) を使用してください。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| fileName | 文字列 | 開くファイルの名前です。 |

 **Result:**



---


### getSubScenes{#getSubScenes}

| 名前 | 説明 |
| --- | --- |
| getSubScenes() | すべてのサブシーンを取得します |

 **Result:**



---


### getLibrary{#getLibrary}

| 名前 | 説明 |
| --- | --- |
| getLibrary() | シーン階層で直接使用されないオブジェクトは Library に定義できます。サブシーンを使用し、再利用可能なコンポーネントをサブシーンの下に配置する場合に便利です。 |

 **Result:**



---


### getAnimationClips{#getAnimationClips}

| 名前 | 説明 |
| --- | --- |
| getAnimationClips() | シーンで定義されたすべての AnimationClip を取得します。 |

 **Result:**



---


### getCurrentAnimationClip{#getCurrentAnimationClip}

| 名前 | 説明 |
| --- | --- |
| getCurrentAnimationClip() | アクティブな AnimationClip を取得または設定します |

 **Result:**



---


### setCurrentAnimationClip{#setCurrentAnimationClip}

| 名前 | 説明 |
| --- | --- |
| setCurrentAnimationClip(value) | アクティブな AnimationClip を取得または設定します |

 **Result:**



---


### getAssetInfo{#getAssetInfo}

| 名前 | 説明 |
| --- | --- |
| getAssetInfo() | トップレベルのアセット情報であるドキュメント情報を取得または設定します。 |

 **Result:**



---


### setAssetInfo{#setAssetInfo}

| 名前 | 説明 |
| --- | --- |
| setAssetInfo(value) | トップレベルのアセット情報であるドキュメント情報を取得または設定します。 |

 **Result:**



---


### getPoses{#getPoses}

| 名前 | 説明 |
| --- | --- |
| getPoses() | このシーンで使用されているすべての Pose を取得します。 |

 **Result:**



---


### getRootNode{#getRootNode}

| 名前 | 説明 |
| --- | --- |
| getRootNode() | シーンのルートノードを取得します。 |

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


### getAnimationClip{#getAnimationClip}

| 名前 | 説明 |
| --- | --- |
| getAnimationClip(name) | 指定された名前の AnimationClip を取得します |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| name | 文字列 | その |

 **Result:**
AnimationClip


---


### clear{#clear}

| 名前 | 説明 |
| --- | --- |
| clear() | シーンの内容をクリアし、デフォルト設定を復元します。 |

 **Result:**
AnimationClip


---


### createAnimationClip{#createAnimationClip}

| 名前 | 説明 |
| --- | --- |
| createAnimationClip(name) | AnimationClip を作成し登録するための省略形関数です。最初の AnimationClip は CurrentAnimationClip に割り当てられます。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| name | 文字列 | Animation clip の名前 |

 **Result:**
AnimationClip


---


### open{#open}

| 名前 | 説明 |
| --- | --- |
| open(fileName, options) | 指定されたファイル形式を使用して、指定されたパスからシーンを開きます。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| fileName | 文字列 | ファイル名。 |
| オプション | LoadOptions | ストリームを開くための詳細な構成です。 |

 **Result:**
AnimationClip


---


### open{#open}

| 名前 | 説明 |
| --- | --- |
| open(fileName) | 指定されたパスからシーンを開きます |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| fileName | 文字列 | ファイル名。 |

 **Result:**
AnimationClip


---


### fromFile{#fromFile}

| 名前 | 説明 |
| --- | --- |
| fromFile(fileName) | 指定されたパスからシーンを開きます |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| fileName | 文字列 | ファイル名。 |

 **Result:**
AnimationClip


---


### save{#save}

| 名前 | 説明 |
| --- | --- |
| save(fileName) | 指定されたファイル形式を使用して、指定されたパスにシーンを保存します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| fileName | 文字列 | ファイル名。 |

 **Result:**
AnimationClip


---


### save{#save}

| 名前 | 説明 |
| --- | --- |
| save(fileName, format) | 指定されたファイル形式を使用して、指定されたパスにシーンを保存します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| fileName | 文字列 | ファイル名。 |
| format | ファイル形式 | 形式。 |

 **Result:**
AnimationClip


---


### save{#save}

| 名前 | 説明 |
| --- | --- |
| save(fileName, options) | 指定されたファイル形式を使用して、指定されたパスにシーンを保存します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| fileName | 文字列 | ファイル名。 |
| オプション | SaveOptions | ストリームを保存するための詳細な構成です。 |

 **Result:**
AnimationClip


---


### render{#render}

| 名前 | 説明 |
| --- | --- |
| render(camera, fileName) | 指定されたカメラの視点からシーンを外部ファイルにレンダリングします。デフォルトの出力サイズは 1024x768 で、出力形式は png です。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| カメラ | カメラ | シーンをレンダリングするカメラの視点を指定します |
| fileName | 文字列 | 出力ファイルのファイル名 |

 **Result:**
AnimationClip


---


### render{#render}

| 名前 | 説明 |
| --- | --- |
| render(camera, fileName, size, format) | 指定されたカメラの視点からシーンを外部ファイルにレンダリングします。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| カメラ | カメラ | シーンをレンダリングするカメラの視点を指定します |
| fileName | 文字列 | 出力ファイルのファイル名 |
| サイズ | Vector2 | 最終的にレンダリングされた画像のサイズ |
| format | 文字列 | 出力ファイルの画像形式 |

 **Result:**
AnimationClip


---


### render{#render}

| 名前 | 説明 |
| --- | --- |
| render(camera, fileName, size, format, options) | 指定されたカメラの視点からシーンを外部ファイルにレンダリングします。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| カメラ | カメラ | シーンをレンダリングするカメラの視点を指定します |
| fileName | 文字列 | 出力ファイルのファイル名 |
| サイズ | Vector2 | 最終的にレンダリングされた画像のサイズ |
| format | 文字列 | 出力ファイルの画像形式 |
| オプション | ImageRenderOptions | 内部設定のいくつかをカスタマイズするオプション。 |

 **Result:**
AnimationClip


---


### render{#render}

| 名前 | 説明 |
| --- | --- |
| render(camera, bitmap) | 指定されたカメラの視点からシーンをビットマップにレンダリングします。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| カメラ | カメラ | シーンをレンダリングするカメラの視点を指定します |
| ビットマップ | TextureData | レンダリング結果のターゲット |

 **Result:**
AnimationClip


---


### render{#render}

| 名前 | 説明 |
| --- | --- |
| render(camera, bitmap, options) | 指定されたカメラの視点からシーンをビットマップにレンダリングします。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| カメラ | カメラ | シーンをレンダリングするカメラの視点を指定します |
| ビットマップ | TextureData | レンダリング結果のターゲット |
| オプション | ImageRenderOptions | 内部設定のいくつかをカスタマイズするオプション。 |

 **Result:**
AnimationClip


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



