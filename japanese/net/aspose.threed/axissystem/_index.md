---
title: "クラス AxisSystem"
second_title: "Aspose.3D for .NET API リファレンス"
description: "Aspose.ThreeD.AxisSystem クラス。軸システムは座標系の上ベクトルと前ベクトルの組み合わせです"
type: docs
weight: 150
url: /ja/net/aspose.threed/axissystem/
---
## AxisSystem class

軸システムは座標系、上ベクトル、前ベクトルの組み合わせです。

```csharp
public class AxisSystem
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [AxisSystem](axissystem/#constructor)(Axis, Axis?) |  |
| [AxisSystem](axissystem/#constructor_1)(CoordinateSystem, Axis) | 新しい軸システムを構築します |
| [AxisSystem](axissystem/#constructor_2)(CoordinateSystem, Axis, Axis) | 新しい軸システムを構築します |
| [AxisSystem](axissystem/#constructor_3)(CoordinateSystem?, Axis?, Axis?) |  |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [CoordinateSystem](../../aspose.threed/axissystem/coordinatesystem/) { get; } | この軸システムの座標系を取得します。 |
| [Front](../../aspose.threed/axissystem/front/) { get; } | この軸システムの前ベクトルを取得します |
| [Up](../../aspose.threed/axissystem/up/) { get; } | この軸システムの上ベクトルを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| static [FromAssetInfo](../../aspose.threed/axissystem/fromassetinfo/)(AssetInfo) | `AxisSystem` を [`AssetInfo`](../assetinfo/) から作成します |
| [TransformTo](../../aspose.threed/axissystem/transformto/)(AxisSystem) | 現在の軸システムから対象の軸システムへ変換するために使用される行列を作成します。 |

### 関連項目

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


