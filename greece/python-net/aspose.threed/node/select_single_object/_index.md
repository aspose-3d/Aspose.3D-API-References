---
title: select_single_object method
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 130
url: /el/python-net/aspose.threed/node/select_single_object/
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

# Δημιουργήστε μια σκηνή για δοκιμή
s = Scene()
a = s.root_node.create_child_node("a")
a.create_child_node("a1")
a.create_child_node("a2")
s.root_node.create_child_node("b")
c = s.root_node.create_child_node("c")
c.create_child_node("c1").add_entity(Camera("cam"))
c.create_child_node("c2").add_entity(Light("light"))
# Επιλέξτε ένα μόνο αντικείμενο κάμερας κάτω από τους υποκόμβους του κόμβου με όνομα 'c' κάτω από τον ριζικό κόμβο
c1 = s.root_node.select_single_object("/c/*/<Camera>")
#  Επιλέξτε τον κόμβο με όνομα 'a1' κάτω από τον ριζικό κόμβο, ακόμη και αν το 'a1' δεν είναι άμεσα υποκόμβο του
obj = s.root_node.select_single_object("a1")
# Επιλέξτε τον ίδιο τον κόμβο, επειδή το '/' είναι επιλεγμένο απευθείας στον ριζικό κόμβο, έτσι ο ριζικός κόμβος επιλέγεται.
obj = s.root_node.select_single_object("/")

```



### See Also
* module [`aspose.threed`](../../)
* class [`Node`](/3d/python-net/aspose.threed/node)
* class [`ParseException`](/3d/python-net/aspose.threed.utilities/parseexception)
