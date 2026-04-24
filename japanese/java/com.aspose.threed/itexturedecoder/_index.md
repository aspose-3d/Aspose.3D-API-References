---
title: ITextureDecoder
second_title: Aspose.3D for Java API リファレンス
description: 外部テクスチャデコーダはデコードのためにこのインターフェイスを実装すべきです。
type: docs
weight: 256
url: /ja/java/com.aspose.threed/itexturedecoder/
---
```
public interface ITextureDecoder
```

外部テクスチャデコーダはデコードのためにこのインターフェイスを実装すべきです。
## Methods

| Method | 説明 |
| --- | --- |
| [decode(Stream stream, boolean reverseY)](#decode-com.aspose.threed.Stream-boolean-) | ストリームからテクスチャをデコードし、デコードに失敗した場合は null を返します。 |
### decode(Stream stream, boolean reverseY) {#decode-com.aspose.threed.Stream-boolean-}
```
public abstract TextureData decode(Stream stream, boolean reverseY)
```


ストリームからテクスチャをデコードし、デコードに失敗した場合は null を返します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | テクスチャ データ ソース ストリーム |
| reverseY | boolean | テクスチャを反転する |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata) - Decoded texture data or null if not supported.
