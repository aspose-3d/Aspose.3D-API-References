---
title: "ITextureEncoder"
second_title: "Aspose.3D for Java API リファレンス"
description: "外部テクスチャエンコーダは、エンコードのためにこのインターフェイスを実装すべきです。"
type: docs
weight: 257
url: /ja/java/com.aspose.threed/itextureencoder/
---
```
public interface ITextureEncoder
```

外部テクスチャエンコーダは、エンコードのためにこのインターフェイスを実装すべきです。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [encode(TextureData texture, Stream stream)](#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-) | テクスチャデータをストリームにエンコードする |
| [getFileExtension()](#getFileExtension--) | このエンコーダーのファイル拡張子名（ドットなし） |
### encode(TextureData texture, Stream stream) {#encode-com.aspose.threed.TextureData-com.aspose.threed.Stream-}
```
public abstract void encode(TextureData texture, Stream stream)
```


テクスチャデータをストリームにエンコードする

**Parameters:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| texture | [TextureData](../../com.aspose.threed/texturedata) | エンコードされるテクスチャデータ |
| stream | [Stream](../../com.aspose.threed/stream) | 出力ストリーム |

### getFileExtension() {#getFileExtension--}
```
public abstract String getFileExtension()
```


このエンコーダーのファイル拡張子名（ドットなし）

**Returns:**
java.lang.String - このエンコーダーのファイル拡張子名（ドットなし）
