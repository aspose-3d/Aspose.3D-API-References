---
title: "Node.Accept"
second_title: "مرجع Aspose.3D for .NET API"
description: "طريقة Node. تتجول عبر جميع العقد التابعة بما في ذلك العقدة الحالية وتستدعي الزائر مع العقدة. يمكن للزائر إيقاف التجول بإرجاع false"
type: docs
weight: 140
url: /ar/net/aspose.threed/node/accept/
---
## Node.Accept method

يتجول عبر جميع العقد التابعة (بما في ذلك العقدة الحالية) ويستدعي الزائر مع العقدة. يمكن للزائر إيقاف التجول بإرجاع false

```csharp
public bool Accept(NodeVisitor visitor)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| زائر | NodeVisitor | استدعاء رد النداء للزائر لزيارة العقدة |

### قيمة الإرجاع

true يعني أن الزائر قد كسر عملية التجول.

## أمثلة

الكود التالي يوضح كيفية الحصول على جميع الشبكات من المشهد

```csharp
Scene scene = Scene.FromFile("input.fbx");
List<Mesh> meshes = new List<Mesh>();
scene.RootNode.Accept((node) =>
{
    if(node.Entity is Mesh)
        meshes.Add((Mesh)node.Entity);
    //متابعة البحث
    return true;
});
```

### انظر أيضًا

* delegate [NodeVisitor](../../nodevisitor/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


