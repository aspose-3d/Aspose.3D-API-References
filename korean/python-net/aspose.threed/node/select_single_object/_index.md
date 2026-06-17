---
title: select_single_object method
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 130
url: /ko/python-net/aspose.threed/node/select_single_object/
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

# 테스트용 씬을 생성합니다.
s = Scene()
a = s.root_node.create_child_node("a")
a.create_child_node("a1")
a.create_child_node("a2")
s.root_node.create_child_node("b")
c = s.root_node.create_child_node("c")
c.create_child_node("c1").add_entity(Camera("cam"))
c.create_child_node("c2").add_entity(Light("light"))
# 루트 노드 아래의 'c'라는 이름을 가진 노드의 자식 노드들 중 단일 카메라 객체를 선택합니다.
c1 = s.root_node.select_single_object("/c/*/<Camera>")
#  루트 노드 아래의 'a1'이라는 이름을 가진 노드를 선택합니다, 비록 'a1'이 직접적인 자식 노드가 아니더라도
obj = s.root_node.select_single_object("a1")
# 노드 자체를 선택합니다. '/'가 루트 노드에서 직접 선택되었기 때문에 루트 노드가 선택됩니다.
obj = s.root_node.select_single_object("/")

```



### See Also
* module [`aspose.threed`](../../)
* class [`Node`](/3d/python-net/aspose.threed/node)
* class [`ParseException`](/3d/python-net/aspose.threed.utilities/parseexception)
