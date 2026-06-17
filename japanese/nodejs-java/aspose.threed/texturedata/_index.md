---
title: "TextureData"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/texturedata/
---
## TextureData class

このクラスはテクスチャの生データとフォーマット定義を含みます。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor(width, height, stride, bytesPerPixel, pixelFormat, data) | TextureData のコンストラクタ |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| 幅 | 数 | null |
| 高さ | 数 | null |
| strid | 数 | null |
| bytesPerPixe | 数 | null |
| pixelFormat | PixelFormat | PixelFormat |
| dat | byte[] | null |

 **Result:**



---


### constructor_overload{#constructor_overload}

| 名前 | 説明 |
| --- | --- |
| constructor_overload(width, height, pixelFormat) | 新しい TextureData を作成し、ピクセルデータを割り当てます。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| 幅 | 数 | null |
| 高さ | 数 | null |
| pixelFormat | PixelFormat | PixelFormat |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| 名前 | 説明 |
| --- | --- |
| constructor_overload2() | TextureData のコンストラクタ |

 **Result:**



---


### getData{#getData}

| 名前 | 説明 |
| --- | --- |
| getData() | ピクセルデータの生バイト |

 **Result:**



---


### getWidth{#getWidth}

| 名前 | 説明 |
| --- | --- |
| getWidth() | 水平ピクセル数 |

 **Result:**



---


### getHeight{#getHeight}

| 名前 | 説明 |
| --- | --- |
| getHeight() | 垂直ピクセル数 |

 **Result:**



---


### getStride{#getStride}

| 名前 | 説明 |
| --- | --- |
| getStride() | 走査線あたりのバイト数。 |

 **Result:**



---


### getBytesPerPixel{#getBytesPerPixel}

| 名前 | 説明 |
| --- | --- |
| getBytesPerPixel() | ピクセルあたりのバイト数 |

 **Result:**



---


### getPixelFormat{#getPixelFormat}

| 名前 | 説明 |
| --- | --- |
| getPixelFormat() | ピクセルのフォーマットです。このプロパティの値は PixelFormat の整数定数です。 |

 **Result:**



---


### fromFile{#fromFile}

| 名前 | 説明 |
| --- | --- |
| fromFile(fileName) | ファイルからテクスチャを読み込みます |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| fileNam | 文字列 | null |

 **Result:**
TextureData


---


### save{#save}

| 名前 | 説明 |
| --- | --- |
| save(fileName) | テクスチャ データを画像ファイルに保存する |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| fileName | 文字列 | 画像が保存される場所のファイル名です。 |

 **Result:**
TextureData


---


### save{#save}

| 名前 | 説明 |
| --- | --- |
| save(fileName, format) | テクスチャ データを画像ファイルに保存する |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| fileName | 文字列 | 画像が保存される場所のファイル名です。 |
| format | 文字列 | 出力ファイルの画像形式です。 |

 **Result:**
TextureData


---


### mapPixels{#mapPixels}

| 名前 | 説明 |
| --- | --- |
| mapPixels(mapMode) | 読み取り/書き込み用にすべてのピクセルをマップする |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| mapMode | PixelMapMode | PixelMapMode |

 **Result:**
PixelMapping


---


### mapPixels{#mapPixels}

| 名前 | 説明 |
| --- | --- |
| mapPixels(mapMode, format) | 指定されたピクセル形式で読み取り/書き込み用にすべてのピクセルをマップする |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| mapMode | PixelMapMode | PixelMapMode |
| format | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---


### mapPixels{#mapPixels}

| 名前 | 説明 |
| --- | --- |
| mapPixels(rect, mapMode, format) | rect で指定されたピクセルを、指定されたピクセル形式で読み取り/書き込み用にマップする |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| rect | Rect | アクセスされるピクセル領域 |
| mapMode | PixelMapMode | PixelMapMode |
| format | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---


### transformPixelFormat{#transformPixelFormat}

| 名前 | 説明 |
| --- | --- |
| transformPixelFormat(pixelFormat) | ピクセルのレイアウトを新しいピクセル形式に変換する。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| pixelFormat | PixelFormat | PixelFormat |

 **Result:**
PixelMapping


---



