---
title: "クラス Group"
second_title: "Aspose.3D for .NET API リファレンス"
description: "Aspose.ThreeD.Group クラス。Group は Node の論理的関係を表します"
type: docs
weight: 1570
url: /ja/net/aspose.threed/group/
---
## Group class

`Group` は [`Node`](../node/) の論理的関係を表します。

```csharp
public class Group : A3DObject
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [Group](group/)(string) | `Group` の新しいインスタンスを構築します |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Groups](../../aspose.threed/group/groups/) { get; } | サブグループ |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | 名前を取得または設定します。 |
| [Nodes](../../aspose.threed/group/nodes/) { get; } | このグループ内のノード |
| [Parent](../../aspose.threed/group/parent/) { get; } | 現在のグループの親グループ |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | すべてのプロパティのコレクションを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | プロパティを検索します。動的プロパティ（CreateDynamicProperty/SetProperty によって作成）またはネイティブプロパティ（名前で識別）になる可能性があります。 |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | 指定されたプロパティの値を取得します。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | 動的プロパティを削除します。 |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | 名前で識別される指定されたプロパティを削除します。 |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | 指定されたプロパティの値を設定します |
| override [ToString](../../aspose.threed/group/tostring/)() | `Group` の文字列表現を取得します |

### 関連項目

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


