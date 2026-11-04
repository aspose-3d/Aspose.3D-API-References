---
title: "TextureData.MapPixels"
second_title: "Aspose.3D for .NET API リファレンス"
description: "TextureData メソッド。すべてのピクセルを読み書き用にマッピングします"
type: docs
weight: 100
url: /ja/net/aspose.threed.render/texturedata/mappixels/
---
## MapPixels(PixelMapMode) {#mappixels}

読み取り/書き込み用にすべてのピクセルをマップする

```csharp
public PixelMapping MapPixels(PixelMapMode mapMode)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| mapMode | PixelMapMode | マップモード |

### 関連項目

* class [PixelMapping](../../pixelmapping/)
* enum [PixelMapMode](../../pixelmapmode/)
* class [TextureData](../)
* namespace [Aspose.ThreeD.Render](../../texturedata/)
* assembly [Aspose.3D](../../../)

---

## MapPixels(PixelMapMode, PixelFormat) {#mappixels_1}

指定されたピクセル形式で読み取り/書き込み用にすべてのピクセルをマップする

```csharp
public PixelMapping MapPixels(PixelMapMode mapMode, PixelFormat format)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| mapMode | PixelMapMode | マップモード |
| format | PixelFormat | ピクセル形式 |

### 関連項目

* class [PixelMapping](../../pixelmapping/)
* enum [PixelMapMode](../../pixelmapmode/)
* enum [PixelFormat](../../pixelformat/)
* class [TextureData](../)
* namespace [Aspose.ThreeD.Render](../../texturedata/)
* assembly [Aspose.3D](../../../)

---

## MapPixels(Rect, PixelMapMode, PixelFormat) {#mappixels_2}

指定されたピクセル形式で、rect で指定されたピクセルを読み取り/書き込み用にマップする

```csharp
public PixelMapping MapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| rect | Rect | アクセス対象となるピクセル領域 |
| mapMode | PixelMapMode | マップモード |
| format | PixelFormat | ピクセル形式 |

### 戻り値

マッピングオブジェクトを返します。不要になったら破棄すべきです。

### 例外

| 例外 | 条件 |
| --- | --- |
| NotSupportedException |  |

### 関連項目

* class [PixelMapping](../../pixelmapping/)
* struct [Rect](../../../aspose.threed.utilities/rect/)
* enum [PixelMapMode](../../pixelmapmode/)
* enum [PixelFormat](../../pixelformat/)
* class [TextureData](../)
* namespace [Aspose.ThreeD.Render](../../texturedata/)
* assembly [Aspose.3D](../../../)


