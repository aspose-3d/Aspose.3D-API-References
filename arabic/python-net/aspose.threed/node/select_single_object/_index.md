---
title: select_single_object method
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 130
url: /ar/python-net/aspose.threed/node/select_single_object/
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

# إنشاء مشهد للاختبار
s = Scene()
a = s.root_node.create_child_node("a")
a.create_child_node("a1")
a.create_child_node("a2")
s.root_node.create_child_node("b")
c = s.root_node.create_child_node("c")
c.create_child_node("c1").add_entity(Camera("cam"))
c.create_child_node("c2").add_entity(Light("light"))
# حدد كائن كاميرا واحد تحت العقد الفرعية للعقدة المسماة 'c' تحت العقدة الجذرية
c1 = s.root_node.select_single_object("/c/*/<Camera>")
#  حدد العقدة المسماة 'a1' تحت العقدة الجذرية، حتى إذا لم تكن 'a1' عقدة فرعية مباشرة لـ
obj = s.root_node.select_single_object("a1")
# حدد العقدة نفسها، لأن '/' تم تحديده مباشرةً على العقدة الجذرية، لذا تم اختيار العقدة الجذرية.
obj = s.root_node.select_single_object("/")

```



### See Also
* module [`aspose.threed`](../../)
* class [`Node`](/3d/python-net/aspose.threed/node)
* class [`ParseException`](/3d/python-net/aspose.threed.utilities/parseexception)
