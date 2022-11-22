﻿---
title: Matrix4 class
second_title: Aspose.3D for Python via .NET API References
description: 
type: docs
weight: 120
url: /python-net/aspose.threed.utilities/matrix4/
is_root: false
---

## Matrix4 class

4x4 matrix implementation.



The Matrix4 type exposes the following members:

### Constructors
| Constructor | Description |
| :- | :- |
| [Matrix4(r0, r1, r2, r3)](/3d/python-net/aspose.threed.utilities/matrix4/__init__/#Vector4-Vector4-Vector4-Vector4) | Constructs matrix from 4 rows. |
| [Matrix4(m00, m01, m02, m03, m10, m11, m12, m13, m20, m21, m22, m23, m30, m31, m32, m33)](/3d/python-net/aspose.threed.utilities/matrix4/__init__/#float-float-float-float-float-float-float-float-float-float-float-float-float-float-float-float) | Initializes a new instance of the [Matrix4](/3d/python-net/aspose.threed.utilities/matrix4) struct. |
| [Matrix4(m)](/3d/python-net/aspose.threed.utilities/matrix4/__init__/#FMatrix4) |  |
| [Matrix4(m)](/3d/python-net/aspose.threed.utilities/matrix4/__init__/#double[]) |  |
| [Matrix4()](/3d/python-net/aspose.threed.utilities/matrix4/__init__/#) |  |


### Properties
| Property | Description |
| :- | :- |
| [identity](/3d/python-net/aspose.threed.utilities/matrix4/identity) | Gets the identity matrix. |
| [determinant](/3d/python-net/aspose.threed.utilities/matrix4/determinant) | Gets the determinant of the matrix. |
| [m00](/3d/python-net/aspose.threed.utilities/matrix4/m00) |  |
| [m01](/3d/python-net/aspose.threed.utilities/matrix4/m01) |  |
| [m02](/3d/python-net/aspose.threed.utilities/matrix4/m02) |  |
| [m03](/3d/python-net/aspose.threed.utilities/matrix4/m03) |  |
| [m10](/3d/python-net/aspose.threed.utilities/matrix4/m10) |  |
| [m11](/3d/python-net/aspose.threed.utilities/matrix4/m11) |  |
| [m12](/3d/python-net/aspose.threed.utilities/matrix4/m12) |  |
| [m13](/3d/python-net/aspose.threed.utilities/matrix4/m13) |  |
| [m20](/3d/python-net/aspose.threed.utilities/matrix4/m20) |  |
| [m21](/3d/python-net/aspose.threed.utilities/matrix4/m21) |  |
| [m22](/3d/python-net/aspose.threed.utilities/matrix4/m22) |  |
| [m23](/3d/python-net/aspose.threed.utilities/matrix4/m23) |  |
| [m30](/3d/python-net/aspose.threed.utilities/matrix4/m30) |  |
| [m31](/3d/python-net/aspose.threed.utilities/matrix4/m31) |  |
| [m32](/3d/python-net/aspose.threed.utilities/matrix4/m32) |  |
| [m33](/3d/python-net/aspose.threed.utilities/matrix4/m33) |  |


### Methods
| Method | Description |
| :- | :- |
| [translate(t)](/3d/python-net/aspose.threed.utilities/matrix4/translate/#Vector3) | Creates a matrix that translates along the x-axis, the y-axis and the z-axis |
| [translate(tx, ty, tz)](/3d/python-net/aspose.threed.utilities/matrix4/translate/#float-float-float) | Creates a matrix that translates along the x-axis, the y-axis and the z-axis |
| [scale(s)](/3d/python-net/aspose.threed.utilities/matrix4/scale/#Vector3) | Creates a matrix that scales along the x-axis, the y-axis and the z-axis. |
| [scale(s)](/3d/python-net/aspose.threed.utilities/matrix4/scale/#float) | Creates a matrix that scales along the x-axis, the y-axis and the z-axis. |
| [scale(sx, sy, sz)](/3d/python-net/aspose.threed.utilities/matrix4/scale/#float-float-float) | Creates a matrix that scales along the x-axis, the y-axis and the z-axis. |
| [rotate_from_euler(eul)](/3d/python-net/aspose.threed.utilities/matrix4/rotate_from_euler/#Vector3) | Create a rotation matrix from Euler angle |
| [rotate_from_euler(rx, ry, rz)](/3d/python-net/aspose.threed.utilities/matrix4/rotate_from_euler/#float-float-float) | Create a rotation matrix from Euler angle |
| [rotate(angle, axis)](/3d/python-net/aspose.threed.utilities/matrix4/rotate/#float-Vector3) | Create a rotation matrix by rotation angle and axis |
| [rotate(q)](/3d/python-net/aspose.threed.utilities/matrix4/rotate/#Quaternion) | Create a rotation matrix from a quaternion |
| [concatenate(m2)](/3d/python-net/aspose.threed.utilities/matrix4/concatenate/#Matrix4) |  |
| [transpose()](/3d/python-net/aspose.threed.utilities/matrix4/transpose/#) | Transposes this instance. |
| [normalize()](/3d/python-net/aspose.threed.utilities/matrix4/normalize/#) | Normalizes this instance. |
| [inverse()](/3d/python-net/aspose.threed.utilities/matrix4/inverse/#) | Inverses this instance. |
| [set_trs(translation, rotation, scale)](/3d/python-net/aspose.threed.utilities/matrix4/set_trs/#Vector3-Vector3-Vector3) | Initializes the matrix with translation/rotation/scale |
| [to_array()](/3d/python-net/aspose.threed.utilities/matrix4/to_array/#) | Converts matrix to array. |
| [decompose(translation, scaling, rotation)](/3d/python-net/aspose.threed.utilities/matrix4/decompose/#Vector3&-Vector3&-Quaternion&) |  |


### See Also

* module [aspose.threed.utilities](../)