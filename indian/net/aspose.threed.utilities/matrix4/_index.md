---
title: "संरचना Matrix4"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "Aspose.ThreeD.Utilities.Matrix4 struct. 4x4 मैट्रिक्स कार्यान्वयन"
type: docs
weight: 2790
url: /hi/net/aspose.threed.utilities/matrix4/
---
## Matrix4 structure

4x4 मैट्रिक्स कार्यान्वयन।

```csharp
public struct Matrix4
```

## कन्स्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [Matrix4](matrix4/#constructor_3)(double[]) | `Matrix4` struct का एक नया उदाहरण प्रारंभ करता है। |
| [Matrix4](matrix4/#constructor)(FMatrix4) | `Matrix4` को एक [`FMatrix4`](../fmatrix4/) उदाहरण से बनाएं |
| [Matrix4](matrix4/#constructor_1)(Vector4, Vector4, Vector4, Vector4) | 4 पंक्तियों से मैट्रिक्स बनाता है। |
| [Matrix4](matrix4/#constructor_2)(double, double, double, double, double, double, double, double, double, double, double, double, double, double, double, double) | `Matrix4` struct का एक नया उदाहरण प्रारंभ करता है। |

## प्रॉपर्टीज़

| नाम | विवरण |
| --- | --- |
| static [Identity](../../aspose.threed.utilities/matrix4/identity/) { get; } | पहचान मैट्रिक्स प्राप्त करता है। |
| [Determinant](../../aspose.threed.utilities/matrix4/determinant/) { get; } | मैट्रिक्स का डिटरमिनेंट प्राप्त करता है। |

## मेथड्स

| नाम | विवरण |
| --- | --- |
| static [Rotate](../../aspose.threed.utilities/matrix4/rotate/#rotate)(Quaternion) | क्वाटरनियन से एक रोटेशन मैट्रिक्स बनाएं |
| static [Rotate](../../aspose.threed.utilities/matrix4/rotate/#rotate_1)(double, Vector3) | रोटेशन कोण और अक्ष द्वारा एक रोटेशन मैट्रिक्स बनाएं |
| static [RotateFromEuler](../../aspose.threed.utilities/matrix4/rotatefromeuler/#rotatefromeuler)(Vector3) | ऑयलर कोण से एक रोटेशन मैट्रिक्स बनाएं |
| static [RotateFromEuler](../../aspose.threed.utilities/matrix4/rotatefromeuler/#rotatefromeuler_1)(double, double, double) | ऑयलर कोण से एक रोटेशन मैट्रिक्स बनाएं |
| static [Scale](../../aspose.threed.utilities/matrix4/scale/#scale_1)(double) | एक मैट्रिक्स बनाता है जो x-अक्ष, y-अक्ष और z-अक्ष के साथ स्केल करता है। |
| static [Scale](../../aspose.threed.utilities/matrix4/scale/#scale)(Vector3) | एक मैट्रिक्स बनाता है जो x-अक्ष, y-अक्ष और z-अक्ष के साथ स्केल करता है। |
| static [Scale](../../aspose.threed.utilities/matrix4/scale/#scale_2)(double, double, double) | एक मैट्रिक्स बनाता है जो x-अक्ष, y-अक्ष और z-अक्ष के साथ स्केल करता है। |
| static [Translate](../../aspose.threed.utilities/matrix4/translate/#translate)(Vector3) | एक मैट्रिक्स बनाता है जो x-अक्ष, y-अक्ष और z-अक्ष के साथ ट्रांसलेट करता है। |
| static [Translate](../../aspose.threed.utilities/matrix4/translate/#translate_1)(double, double, double) | एक मैट्रिक्स बनाता है जो x-अक्ष, y-अक्ष और z-अक्ष के साथ ट्रांसलेट करता है। |
| [Concatenate](../../aspose.threed.utilities/matrix4/concatenate/)(Matrix4) | दोनों मैट्रिक्स को जोड़ता है |
| [Decompose](../../aspose.threed.utilities/matrix4/decompose/)(out Vector3, out Vector3, out Quaternion) |  |
| [Inverse](../../aspose.threed.utilities/matrix4/inverse/)() | इस उदाहरण को उलटता है। |
| [Normalize](../../aspose.threed.utilities/matrix4/normalize/)() | इस उदाहरण को सामान्यीकृत करता है। |
| [SetTRS](../../aspose.threed.utilities/matrix4/settrs/)(Vector3, Vector3, Vector3) | मैट्रिक्स को ट्रांसलेशन/रोटेशन/स्केल के साथ प्रारंभ करता है। |
| [ToArray](../../aspose.threed.utilities/matrix4/toarray/)() | मैट्रिक्स को एरे में परिवर्तित करता है। |
| override [ToString](../../aspose.threed.utilities/matrix4/tostring/)() | वर्तमान `Matrix4` का प्रतिनिधित्व करने वाली स्ट्रिंग लौटाता है। |
| [Transpose](../../aspose.threed.utilities/matrix4/transpose/)() | इस उदाहरण को ट्रांसपोज़ करें। |
| [operator *](../../aspose.threed.utilities/matrix4/op_multiply/#op_multiply) | दो मैट्रिक्स को गुणा करें (4 ऑपरेटर) |

## फ़ील्ड्स

| नाम | विवरण |
| --- | --- |
| [m00](../../aspose.threed.utilities/matrix4/m00/) | m00। |
| [m01](../../aspose.threed.utilities/matrix4/m01/) | m01। |
| [m02](../../aspose.threed.utilities/matrix4/m02/) | m02। |
| [m03](../../aspose.threed.utilities/matrix4/m03/) | m03। |
| [m10](../../aspose.threed.utilities/matrix4/m10/) | m10। |
| [m11](../../aspose.threed.utilities/matrix4/m11/) | m11। |
| [m12](../../aspose.threed.utilities/matrix4/m12/) | m12। |
| [m13](../../aspose.threed.utilities/matrix4/m13/) | m13। |
| [m20](../../aspose.threed.utilities/matrix4/m20/) | m20। |
| [m21](../../aspose.threed.utilities/matrix4/m21/) | m21। |
| [m22](../../aspose.threed.utilities/matrix4/m22/) | m22। |
| [m23](../../aspose.threed.utilities/matrix4/m23/) | m23। |
| [m30](../../aspose.threed.utilities/matrix4/m30/) | m30। |
| [m31](../../aspose.threed.utilities/matrix4/m31/) | m31। |
| [m32](../../aspose.threed.utilities/matrix4/m32/) | m32। |
| [m33](../../aspose.threed.utilities/matrix4/m33/) | m33। |

## उदाहरण

```csharp
Matrix4 mat = Matrix4.RotateFromEuler(90, 0, 0);
Matrix4 mat2 = Matrix4.Translate(0, 10, -50);
Matrix4 transform = mat2 * mat;
Vector4 pos = new Vector4(10, 9, 0, 1);
Vector4 transformed = transform * pos;

```

### देखें भी

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


