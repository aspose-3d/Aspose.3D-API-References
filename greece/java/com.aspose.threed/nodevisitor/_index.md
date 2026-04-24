---
title: NodeVisitor
second_title: Aspose.3D for Java API Reference
description: Μια callback για να διασχίσει ολόκληρη τη ιεραρχία κόμβων.
type: docs
weight: 261
url: /el/java/com.aspose.threed/nodevisitor/
---
```
public interface NodeVisitor
```

Μια callback για να διασχίσει ολόκληρη τη ιεραρχία κόμβων.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [call(Node node)](#call-com.aspose.threed.Node-) | Μια callback για να διασχίσει ολόκληρη τη ιεραρχία κόμβων. |
### call(Node node) {#call-com.aspose.threed.Node-}
```
public abstract boolean call(Node node)
```


Μια callback για να διασχίσει ολόκληρη τη ιεραρχία κόμβων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| node | [Node](../../com.aspose.threed/node) | Node being visited |

**Returns:**
boolean - Return false to stop traveling
