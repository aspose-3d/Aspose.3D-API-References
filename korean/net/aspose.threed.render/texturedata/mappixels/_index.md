---
title: "TextureData.MapPixels"
second_title: "Aspose.3D for .NET API 참조"
description: "TextureData 메서드. 읽기/쓰기를 위해 모든 픽셀을 매핑합니다"
type: docs
weight: 100
url: /ko/net/aspose.threed.render/texturedata/mappixels/
---
## MapPixels(PixelMapMode) {#mappixels}

읽기/쓰기를 위해 모든 픽셀을 매핑합니다

```csharp
public PixelMapping MapPixels(PixelMapMode mapMode)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mapMode | PixelMapMode | 매핑 모드 |

### 또 보기

* class [PixelMapping](../../pixelmapping/)
* enum [PixelMapMode](../../pixelmapmode/)
* class [TextureData](../)
* namespace [Aspose.ThreeD.Render](../../texturedata/)
* assembly [Aspose.3D](../../../)

---

## MapPixels(PixelMapMode, PixelFormat) {#mappixels_1}

지정된 픽셀 형식으로 읽기/쓰기를 위해 모든 픽셀을 매핑합니다

```csharp
public PixelMapping MapPixels(PixelMapMode mapMode, PixelFormat format)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mapMode | PixelMapMode | 매핑 모드 |
| 형식 | PixelFormat | 픽셀 형식 |

### 또 보기

* class [PixelMapping](../../pixelmapping/)
* enum [PixelMapMode](../../pixelmapmode/)
* enum [PixelFormat](../../pixelformat/)
* class [TextureData](../)
* namespace [Aspose.ThreeD.Render](../../texturedata/)
* assembly [Aspose.3D](../../../)

---

## MapPixels(Rect, PixelMapMode, PixelFormat) {#mappixels_2}

주어진 픽셀 형식으로 rect에 의해 지정된 픽셀을 읽기/쓰기를 위해 매핑합니다

```csharp
public PixelMapping MapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format)
```

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rect | Rect | 액세스할 픽셀 영역 |
| mapMode | PixelMapMode | 매핑 모드 |
| 형식 | PixelFormat | 픽셀 형식 |

### 반환 값

매핑 객체를 반환합니다. 더 이상 필요하지 않을 때는 해제해야 합니다.

### 예외

| 예외 | 조건 |
| --- | --- |
| NotSupportedException |  |

### 또 보기

* class [PixelMapping](../../pixelmapping/)
* struct [Rect](../../../aspose.threed.utilities/rect/)
* enum [PixelMapMode](../../pixelmapmode/)
* enum [PixelFormat](../../pixelformat/)
* class [TextureData](../)
* namespace [Aspose.ThreeD.Render](../../texturedata/)
* assembly [Aspose.3D](../../../)


