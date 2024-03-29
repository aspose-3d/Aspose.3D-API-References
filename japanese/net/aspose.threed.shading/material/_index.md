---
title: Material
second_title: Aspose.3D for.NETAPIリファレンス
description: マテリアルはジオメトリの外観に必要なパラメーターを定義します Aspose.3D はシェーディング モデルを提供しますLambertMaterial./lambertmaterial/ PhongMaterial./phongmaterial/とShaderMaterial./shadermaterial/
type: docs
weight: 2290
url: /ja/net/aspose.threed.shading/material/
---
## Material class

マテリアルは、ジオメトリの外観に必要なパラメーターを定義します。 Aspose.3D は、シェーディング モデルを提供します。[`LambertMaterial`](../lambertmaterial/) 、[`PhongMaterial`](../phongmaterial/)と[`ShaderMaterial`](../shadermaterial/)

```csharp
public abstract class Material : A3DObject, IEnumerable<TextureSlot>
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 名前を取得または設定します。 |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | すべてのプロパティのコレクションを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | プロパティを検索します。 動的プロパティ (CreateDynamicProperty/SetProperty で作成) またはネイティブ プロパティ (名前で識別) を指定できます。 |
| [GetEnumerator](../../aspose.threed.shading/material/getenumerator/)() | 内部テクスチャ スロットを列挙する列挙子を取得します。 |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 指定したプロパティの値を取得 |
| [GetTexture](../../aspose.threed.shading/material/gettexture/)(string) | 指定されたスロットからテクスチャを取得します。マテリアルのプロパティ名またはシェーダのパラメータ名にすることができます |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 動的プロパティを削除します。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | name で識別される指定されたプロパティを削除します |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 指定されたプロパティの値を設定します |
| [SetTexture](../../aspose.threed.shading/material/settexture/)(string, TextureBase) | 指定されたスロットにテクスチャを設定します |
| override [ToString](../../aspose.threed.shading/material/tostring/)() | オブジェクトを string にフォーマットします |

## 田畑

| 名前 | 説明 |
| --- | --- |
| const [MapAmbient](../../aspose.threed.shading/material/mapambient/) | で使用[`SetTexture`](./settexture/)アンビエント テクスチャ マッピングを割り当てます。 |
| const [MapDiffuse](../../aspose.threed.shading/material/mapdiffuse/) | で使用[`SetTexture`](./settexture/)拡散テクスチャ マッピングを割り当てます。 |
| const [MapEmissive](../../aspose.threed.shading/material/mapemissive/) | で使用[`SetTexture`](./settexture/)エミッシブ テクスチャ マッピングを割り当てます。 |
| const [MapNormal](../../aspose.threed.shading/material/mapnormal/) | で使用[`SetTexture`](./settexture/)通常のテクスチャ マッピングを割り当てます。 |
| const [MapSpecular](../../aspose.threed.shading/material/mapspecular/) | で使用[`SetTexture`](./settexture/)スペキュラ テクスチャ マッピングを割り当てます。 |

### 関連項目

* class [A3DObject](../../aspose.threed/a3dobject/)
* class [TextureSlot](../textureslot/)
* 名前空間 [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* 組み立て [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
