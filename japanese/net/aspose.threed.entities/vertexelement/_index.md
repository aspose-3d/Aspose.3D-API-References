---
title: VertexElement
second_title: Aspose.3D for.NETAPIリファレンス
description: 頂点要素の基本クラス 頂点要素タイプはVertexElementType によって識別されます VertexElement は頂点要素がジオメトリ サーフェスにどのようにマップされるかおよびマッピング情報がメモリ内でどのように配置されるかを記述します VertexElement には法線UVまたはその他の種類の情報が含まれています
type: docs
weight: 760
url: /ja/net/aspose.threed.entities/vertexelement/
---
## VertexElement class

頂点要素の基本クラス。 頂点要素タイプは、VertexElementType によって識別されます。 VertexElement は、頂点要素がジオメトリ サーフェスにどのようにマップされるか、およびマッピング情報がメモリ内でどのように配置されるかを記述します。 VertexElement には、法線、UV、またはその他の種類の情報が含まれています。

```csharp
public abstract class VertexElement : IIndexedVertexElement
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Indices](../../aspose.threed.entities/vertexelement/indices/) { get; } | インデックスを取得します data |
| [MappingMode](../../aspose.threed.entities/vertexelement/mappingmode/) { get; set; } | 要素のマッピング方法を取得または設定します。 |
| [Name](../../aspose.threed.entities/vertexelement/name/) { get; set; } | 名前を取得または設定します。 |
| [ReferenceMode](../../aspose.threed.entities/vertexelement/referencemode/) { get; set; } | 要素の参照方法を取得または設定します。 |
| [VertexElementType](../../aspose.threed.entities/vertexelement/vertexelementtype/) { get; } | のタイプを取得します`VertexElement` |

## メソッド

| 名前 | 説明 |
| --- | --- |
| abstract [Clear](../../aspose.threed.entities/vertexelement/clear/)() | この頂点要素からすべてのデータをクリアします。 |
| [SetIndices](../../aspose.threed.entities/vertexelement/setindices/)(int[]) | インデックスを読み込む |
| override [ToString](../../aspose.threed.entities/vertexelement/tostring/)() | 頂点要素の文字列表現. |

### 関連項目

* interface [IIndexedVertexElement](../iindexedvertexelement/)
* 名前空間 [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* 組み立て [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->