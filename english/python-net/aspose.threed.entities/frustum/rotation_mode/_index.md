﻿---
title: rotation_mode property
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 200
url: /python-net/aspose.threed.entities/frustum/rotation_mode/
is_root: false
---

## rotation_mode property


Gets or sets the frustum's orientation mode
This property only works when the [`Frustum.target`](/3d/python-net/aspose.threed.entities/frustum#target) is null.
If the value is [`RotationMode.FIXED_TARGET`](/3d/python-net/aspose.threed.entities/rotationmode#FIXED_TARGET), the direction is always calculated by the property [`Frustum.look_at`](/3d/python-net/aspose.threed.entities/frustum#look_at)
Otherwise the [`Frustum.look_at`](/3d/python-net/aspose.threed.entities/frustum#look_at) is always calculated by the [`Frustum.direction`](/3d/python-net/aspose.threed.entities/frustum#direction)
### Definition:
```python
@property
def rotation_mode(self):
    ...
@rotation_mode.setter
def rotation_mode(self, value):
    ...
```

### See Also
* module [`aspose.threed.entities`](../../)
* class [`Frustum`](/3d/python-net/aspose.threed.entities/frustum)
* class [`RotationMode`](/3d/python-net/aspose.threed.entities/rotationmode)
