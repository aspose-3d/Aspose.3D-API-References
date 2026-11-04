---
title: "ITextureDecoder.Decode"
second_title: "Aspose.3D for .NET API リファレンス"
description: "ITextureDecoder メソッド。ストリームからテクスチャをデコードし、デコードに失敗した場合は null を返します"
type: docs
weight: 10
url: /ja/net/aspose.threed.render/itexturedecoder/decode/
---
## ITextureDecoder.Decode method

ストリームからテクスチャをデコードし、デコードに失敗した場合は null を返します。

```csharp
public TextureData Decode(Stream stream, bool reverseY)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| ストリーム | ストリーム | テクスチャデータソースストリーム |
| reverseY | Boolean | テクスチャを反転する |

### 戻り値

デコードされたテクスチャデータ、またはサポートされていない場合は null

### 例外

| 例外 | 条件 |
| --- | --- |
| IOException | ストリームからデータの読み取りに失敗したときにスローされます |

### 関連項目

* class [TextureData](../../texturedata/)
* interface [ITextureDecoder](../)
* namespace [Aspose.ThreeD.Render](../../itexturedecoder/)
* assembly [Aspose.3D](../../../)


