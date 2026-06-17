---
title: select_objects method
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 120
url: /ko/python-net/aspose.threed/node/select_objects/
is_root: false
---

## select_objects(self, path) {#System.String}

Select multiple objects under current node using XPath-like query syntax.


### Returns 


Multiple object matches the XPath-like query.


```python

def select_objects(self, path):
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
# 타입이 Camera이거나 이름이 'light'인 객체를 위치와 관계없이 선택합니다.
objects = s.root_node.select_objects("//*[(@Type = 'Camera') or (@Name = 'light')]")

```



### See Also
* module [`aspose.threed`](../../)
* class [`Node`](/3d/python-net/aspose.threed/node)
* class [`ParseException`](/3d/python-net/aspose.threed.utilities/parseexception)
