---
title: "Texture"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/texture/
---
## Texture class

このクラスは外部ファイルからテクスチャを定義します。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() | Texture クラスの新しいインスタンスを初期化します。 |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名前 | 説明 |
| --- | --- |
| constructor_overload(name) | Texture クラスの新しいインスタンスを初期化します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| name | 文字列 | 名前 |

 **Result:**



---


### getEnableMipMap{#getEnableMipMap}

| 名前 | 説明 |
| --- | --- |
| getEnableMipMap() | このテクスチャでミップマップが有効かどうかを取得または設定します |

 **Result:**



---


### setEnableMipMap{#setEnableMipMap}

| 名前 | 説明 |
| --- | --- |
| setEnableMipMap(value) | このテクスチャでミップマップが有効かどうかを取得または設定します |

 **Result:**



---


### getContent{#getContent}

| 名前 | 説明 |
| --- | --- |
| getContent() | テクスチャのバイナリコンテンツを取得または設定します。埋め込みテクスチャコンテンツはオプションであり、欠如している場合は外部ファイルからテクスチャをロードする必要があります。 |

 **Result:**



---


### setContent{#setContent}

| 名前 | 説明 |
| --- | --- |
| setContent(value) | テクスチャのバイナリコンテンツを取得または設定します。埋め込みテクスチャコンテンツはオプションであり、欠如している場合は外部ファイルからテクスチャをロードする必要があります。 |

 **Result:**



---


### getFileName{#getFileName}

| 名前 | 説明 |
| --- | --- |
| getFileName() | 関連付けられたテクスチャファイルを取得または設定します。ファイル名です。 |

 **Result:**



---


### setFileName{#setFileName}

| 名前 | 説明 |
| --- | --- |
| setFileName(value) | 関連付けられたテクスチャファイルを取得または設定します。ファイル名です。 |

 **Result:**



---


### getAlpha{#getAlpha}

| 名前 | 説明 |
| --- | --- |
| getAlpha() | テクスチャのデフォルトアルファ値を取得または設定します。これは AlphaSource が AlphaSource.PIXEL_ALPHA のときに有効です。デフォルト値は 1.0 で、有効な範囲は 0 から 1 です。 |

 **Result:**



---


### setAlpha{#setAlpha}

| 名前 | 説明 |
| --- | --- |
| setAlpha(value) | テクスチャのデフォルトアルファ値を取得または設定します。これは AlphaSource が AlphaSource.PIXEL_ALPHA のときに有効です。デフォルト値は 1.0 で、有効な範囲は 0 から 1 です。 |

 **Result:**



---


### getAlphaSource{#getAlphaSource}

| 名前 | 説明 |
| --- | --- |
| getAlphaSource() | テクスチャがアルファチャンネルを定義するかどうかを取得または設定します。デフォルト値は AlphaSource.NONE です。このプロパティの値は AlphaSource の整数定数です。 |

 **Result:**



---


### setAlphaSource{#setAlphaSource}

| 名前 | 説明 |
| --- | --- |
| setAlphaSource(value) | テクスチャがアルファチャンネルを定義するかどうかを取得または設定します。デフォルト値は AlphaSource.NONE です。このプロパティの値は AlphaSource の整数定数です。 |

 **Result:**



---


### getWrapModeU{#getWrapModeU}

| 名前 | 説明 |
| --- | --- |
| getWrapModeU() | U 方向のテクスチャラップモードを取得または設定します。このプロパティの値は WrapMode の整数定数です。 |

 **Result:**



---


### setWrapModeU{#setWrapModeU}

| 名前 | 説明 |
| --- | --- |
| setWrapModeU(value) | U 方向のテクスチャラップモードを取得または設定します。このプロパティの値は WrapMode の整数定数です。 |

 **Result:**



---


### getWrapModeV{#getWrapModeV}

| 名前 | 説明 |
| --- | --- |
| getWrapModeV() | V 方向のテクスチャラップモードを取得または設定します。このプロパティの値は WrapMode の整数定数です。 |

 **Result:**



---


### setWrapModeV{#setWrapModeV}

| 名前 | 説明 |
| --- | --- |
| setWrapModeV(value) | V 方向のテクスチャラップモードを取得または設定します。このプロパティの値は WrapMode の整数定数です。 |

 **Result:**



---


### getWrapModeW{#getWrapModeW}

| 名前 | 説明 |
| --- | --- |
| getWrapModeW() | W 方向のテクスチャラップモードを取得または設定します。このプロパティの値は WrapMode の整数定数です。 |

 **Result:**



---


### setWrapModeW{#setWrapModeW}

| 名前 | 説明 |
| --- | --- |
| setWrapModeW(value) | W 方向のテクスチャラップモードを取得または設定します。このプロパティの値は WrapMode の整数定数です。 |

 **Result:**



---


### getMinFilter{#getMinFilter}

| 名前 | 説明 |
| --- | --- |
| getMinFilter() | 縮小時のフィルタを取得または設定します。このプロパティの値は TextureFilter の整数定数です。 |

 **Result:**



---


### setMinFilter{#setMinFilter}

| 名前 | 説明 |
| --- | --- |
| setMinFilter(value) | 縮小時のフィルタを取得または設定します。このプロパティの値は TextureFilter の整数定数です。 |

 **Result:**



---


### getMagFilter{#getMagFilter}

| 名前 | 説明 |
| --- | --- |
| getMagFilter() | 拡大用のフィルタを取得または設定します。プロパティの値は TextureFilter の整数定数です。 |

 **Result:**



---


### setMagFilter{#setMagFilter}

| 名前 | 説明 |
| --- | --- |
| setMagFilter(value) | 拡大用のフィルタを取得または設定します。プロパティの値は TextureFilter の整数定数です。 |

 **Result:**



---


### getMipFilter{#getMipFilter}

| 名前 | 説明 |
| --- | --- |
| getMipFilter() | ミップレベルサンプリング用のフィルタを取得または設定します。プロパティの値は TextureFilter の整数定数です。 |

 **Result:**



---


### setMipFilter{#setMipFilter}

| 名前 | 説明 |
| --- | --- |
| setMipFilter(value) | ミップレベルサンプリング用のフィルタを取得または設定します。プロパティの値は TextureFilter の整数定数です。 |

 **Result:**



---


### getUVRotation{#getUVRotation}

| 名前 | 説明 |
| --- | --- |
| getUVRotation() | テクスチャの回転を取得または設定します |

 **Result:**



---


### setUVRotation{#setUVRotation}

| 名前 | 説明 |
| --- | --- |
| setUVRotation(value) | テクスチャの回転を取得または設定します |

 **Result:**



---


### getUVScale{#getUVScale}

| 名前 | 説明 |
| --- | --- |
| getUVScale() | UV スケールを取得または設定します。UV スケールです。 |

 **Result:**



---


### setUVScale{#setUVScale}

| 名前 | 説明 |
| --- | --- |
| setUVScale(value) | UV スケールを取得または設定します。UV スケールです。 |

 **Result:**



---


### getUVTranslation{#getUVTranslation}

| 名前 | 説明 |
| --- | --- |
| getUVTranslation() | UV 平行移動を取得または設定します。UV 平行移動です。 |

 **Result:**



---


### setUVTranslation{#setUVTranslation}

| 名前 | 説明 |
| --- | --- |
| setUVTranslation(value) | UV 平行移動を取得または設定します。UV 平行移動です。 |

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


### setTranslation{#setTranslation}

| 名前 | 説明 |
| --- | --- |
| setTranslation(u, v) | UV 平行移動を設定します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| u | 数 | U. |
| v | 数 | V. |

 **Result:**



---


### setScale{#setScale}

| 名前 | 説明 |
| --- | --- |
| setScale(u, v) | UV スケールを設定します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| u | 数 | U. |
| v | 数 | V. |

 **Result:**



---


### setRotation{#setRotation}

| 名前 | 説明 |
| --- | --- |
| setRotation(u, v) | UV 回転を設定します。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| u | 数 | U. |
| v | 数 | V. |

 **Result:**



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



