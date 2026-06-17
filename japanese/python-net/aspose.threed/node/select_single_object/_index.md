---
title: select_single_object method
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 130
url: /ja/python-net/aspose.threed/node/select_single_object/
is_root: false
---

## select_single_object(self, path) {#System.String}

Select single object under current node using XPath-like query syntax.


### Returns 


Object located by the XPath-like query.


```python

def select_single_object(self, path):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| path | System.String | The XPath-like query |
### Exceptions
| Exception | Description |
| :- | :- |
| [`ParseException`](/3d/python-net/aspose.threed.utilities/parseexception) | ParseException will be thrown if the path contains malformed query. |



### Example 


Select a single node using XPath-like expression

```python
from aspose.threed import Scene
from aspose.threed.entities import Camera, Light

# テスト用のシーンを作成する
s = Scene()
a = s.root_node.create_child_node("a")
a.create_child_node("a1")
a.create_child_node("a2")
s.root_node.create_child_node("b")
c = s.root_node.create_child_node("c")
c.create_child_node("c1").add_entity(Camera("cam"))
c.create_child_node("c2").add_entity(Light("light"))
# ルートノードの下にある 'c' という名前のノードの子ノードの中から、単一のカメラオブジェクトを選択する
c1 = s.root_node.select_single_object("/c/*/<Camera>")
#  ルートノードの下にある 'a1' という名前のノードを選択する、たとえ 'a1' が直接の子ノードでなくても
obj = s.root_node.select_single_object("a1")
# ルートノード上で '/' が直接選択されているため、ノード自体を選択し、結果としてルートノードが選択されます。
obj = s.root_node.select_single_object("/")

```



### See Also
* module [`aspose.threed`](../../)
* class [`Node`](/3d/python-net/aspose.threed/node)
* class [`ParseException`](/3d/python-net/aspose.threed.utilities/parseexception)
