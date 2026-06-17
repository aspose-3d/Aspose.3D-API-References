---
title: select_single_object method
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 130
url: /nl/python-net/aspose.threed/node/select_single_object/
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

# Maak een scène voor testen
s = Scene()
a = s.root_node.create_child_node("a")
a.create_child_node("a1")
a.create_child_node("a2")
s.root_node.create_child_node("b")
c = s.root_node.create_child_node("c")
c.create_child_node("c1").add_entity(Camera("cam"))
c.create_child_node("c2").add_entity(Light("light"))
# Selecteer een enkel camera-object onder de kindknopen van de node met de naam 'c' onder de hoofdnode
c1 = s.root_node.select_single_object("/c/*/<Camera>")
#  Selecteer de node met de naam 'a1' onder de hoofdnode, zelfs als 'a1' geen direct kind van de is
obj = s.root_node.select_single_object("a1")
# Selecteer de node zelf, aangezien de '/' direct op de hoofdnode is geselecteerd, waardoor de hoofdnode wordt geselecteerd.
obj = s.root_node.select_single_object("/")

```



### See Also
* module [`aspose.threed`](../../)
* class [`Node`](/3d/python-net/aspose.threed/node)
* class [`ParseException`](/3d/python-net/aspose.threed.utilities/parseexception)
