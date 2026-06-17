---
title: select_single_object method
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 130
url: /zh/python-net/aspose.threed/node/select_single_object/
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

# 创建用于测试的场景
s = Scene()
a = s.root_node.create_child_node("a")
a.create_child_node("a1")
a.create_child_node("a2")
s.root_node.create_child_node("b")
c = s.root_node.create_child_node("c")
c.create_child_node("c1").add_entity(Camera("cam"))
c.create_child_node("c2").add_entity(Light("light"))
# 在根节点下名为 'c' 的节点的子节点中选择单个相机对象
c1 = s.root_node.select_single_object("/c/*/<Camera>")
#  在根节点下选择名为 'a1' 的节点，即使 'a1' 不是直接子节点
obj = s.root_node.select_single_object("a1")
# 选择节点本身，因为 '/' 直接在根节点上被选中，所以根节点被选中。
obj = s.root_node.select_single_object("/")

```



### See Also
* module [`aspose.threed`](../../)
* class [`Node`](/3d/python-net/aspose.threed/node)
* class [`ParseException`](/3d/python-net/aspose.threed.utilities/parseexception)
