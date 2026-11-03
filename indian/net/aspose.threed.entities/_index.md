---
title: "Aspose.ThreeD.Entities"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "सभी ज्यामिति और इकाइयाँ इस नामस्थान में परिभाषित हैं।"
type: docs
weight: 40
url: /hi/net/aspose.threed.entities/
---
सभी ज्यामिति और इकाइयाँ इस नामस्थान में परिभाषित हैं।

## क्लासेस

| क्लास | विवरण |
| --- | --- |
| [BooleanOperand](./booleanoperand/) | यह क्लास ट्रांसफ़ॉर्म किए गए मेष को बूलियन ऑपरेशन के ऑपरेण्ड के रूप में संलग्न करती है। |
| [BooleanOperator](./booleanoperator/) | बूलियन ऑपरेटर आपको दो [`IMeshConvertible`](../aspose.threed.entities/imeshconvertible/) इंस्टेंसेज़ पर बूलियन ऑपरेशन लागू करने की अनुमति देता है। |
| [Box](./box/) | बॉक्स। |
| [Camera](./camera/) | कैमरा दृश्य को देख रहे दर्शक के आँख बिंदु का वर्णन करता है। |
| [Circle](./circle/) | एक [`Circle`](../aspose.threed.entities/circle/) वक्र वृत्त के किनारे पर बिंदुओं के सेट से बना होता है। |
| [CompositeCurve](./compositecurve/) | एक [`CompositeCurve`](../aspose.threed.entities/compositecurve/) कई वक्र खंडों से बना होता है। |
| [Curve](./curve/) | सभी वक्र कार्यान्वयनों की बेस क्लास। |
| [Cylinder](./cylinder/) | पैरामीटरयुक्त सिलिंडर। जब radiusTop या radiusBottom में से कोई एक शून्य हो तो इसे शंकु के रूप में भी उपयोग किया जा सकता है। |
| [Dish](./dish/) | पैरामीटरयुक्त डिश। |
| [Ellipse](./ellipse/) | एक [`Ellipse`](../aspose.threed.entities/ellipse/) बिंदुओं का सेट परिभाषित करता है जो दीर्घवृत्त के आकार बनाते हैं। |
| [Frustum](./frustum/) | [`Camera`](../aspose.threed.entities/camera/) और [`Light`](../aspose.threed.entities/light/) की बेस क्लास। |
| [Geometry](./geometry/) | सभी रेंडर करने योग्य ज्यामितीय वस्तुओं (जैसे [`Mesh`](../aspose.threed.entities/mesh/), [`NurbsSurface`](../aspose.threed.entities/nurbssurface/), [`Patch`](../aspose.threed.entities/patch/) आदि) की बेस क्लास। |
| [HalfSpace](./halfspace/) | [`HalfSpace`](../aspose.threed.entities/halfspace/) अनंत स्थान को दर्शाता है जिसे एक तल द्वारा विभाजित किया जाता है, इसे [`BooleanOperator`](../aspose.threed.entities/booleanoperator/) के साथ उपयोग किया जा सकता है। |
| [Light](./light/) | रोशनी दृश्य को प्रकाशित करती है। |
| [Line](./line/) | एक पॉलीलाइन वह पथ है जो बिंदुओं के सेट के साथ [`ControlPoints`](../aspose.threed.entities/geometry/controlpoints/) परिभाषित किया जाता है, और [`Segments`](../aspose.threed.entities/line/segments/) द्वारा जुड़ा होता है, जिसका अर्थ है कि यह जुड़ी हुई रेखा खंडों का सेट भी हो सकता है। रेखा आमतौर पर एक रैखिक वस्तु होती है, जिसका अर्थ है कि इसे वक्र को दर्शाने के लिए उपयोग नहीं किया जा सकता; वक्र को दर्शाने के लिए, [`NurbsCurve`](../aspose.threed.entities/nurbscurve/) का उपयोग करता है। |
| [LinearExtrusion](./linearextrusion/) | रैखिक एक्सट्रूज़न 2D आकार को इनपुट के रूप में लेता है और आकार को तीसरे आयाम में विस्तारित करता है। |
| [Mesh](./mesh/) | एक मेष कई n-भुजाओं वाले बहुभुजों से बना होता है। |
| [NurbsCurve](./nurbscurve/) | [NURBS curve](https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline) एक कर्व है जो NURBS (Non-uniform rational basis spline) द्वारा दर्शाया जाता है। एक NURBS कर्व उसके [`Order`](../aspose.threed.entities/nurbscurve/order/) एक सेट वज़नयुक्त [`ControlPoints`](../aspose.threed.entities/geometry/controlpoints/) और एक [`KnotVectors`](../aspose.threed.entities/nurbscurve/knotvectors/) द्वारा परिभाषित होता है। नियंत्रण बिंदु में w घटक को नियंत्रण बिंदु के वजन के रूप में उपयोग किया जाता है, चाहे वह दो-आयामी हो या तीन-आयामी। |
| [NurbsDirection](./nurbsdirection/) | एक 3D [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) में दो दिशाएँ होती हैं, [`U`](../aspose.threed.entities/nurbssurface/u/) और [`V`](../aspose.threed.entities/nurbssurface/v/), और [`NurbsDirection`](../aspose.threed.entities/nurbsdirection/) प्रत्येक दिशा के डेटा को परिभाषित करता है। एक दिशा वास्तव में एक NURBS कर्व है, जिसका अर्थ है कि यह भी उसके [`Order`](../aspose.threed.entities/nurbsdirection/order/) एक [`KnotVectors`](../aspose.threed.entities/nurbsdirection/knotvectors/) और वज़नयुक्त नियंत्रण बिंदुओं के सेट (जो [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) में परिभाषित हैं) द्वारा परिभाषित होती है। |
| [NurbsSurface](./nurbssurface/) | [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) एक सतह है जो [NURBS(Non-uniform rational basis spline)](https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline) द्वारा दर्शाई जाती है। एक [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) दो [`NurbsDirection`](../aspose.threed.entities/nurbsdirection/)[`U`](../aspose.threed.entities/nurbssurface/u/) और [`V`](../aspose.threed.entities/nurbssurface/v/) द्वारा परिभाषित होती है। नियंत्रण बिंदु में w घटक को नियंत्रण बिंदु के वजन के रूप में उपयोग किया जाता है, चाहे दिशा का प्रकार दो-आयामी हो या तीन-आयामी। |
| [Patch](./patch/) | [`Patch`](../aspose.threed.entities/patch/) एक पैरामीट्रिक मॉडलिंग सतह है, जो [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) के समान है, यह भी दो [`PatchDirection`](../aspose.threed.entities/patchdirection/) अर्थात [`U`](../aspose.threed.entities/patch/u/) और [`V`](../aspose.threed.entities/patch/v/) द्वारा परिभाषित होती है। लेकिन [`Patch`](../aspose.threed.entities/patch/) और [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) के बीच अंतर यह है कि [`PatchDirection`](../aspose.threed.entities/patchdirection/) कर्व Bezier, QuadraticBezier, BasisSpline, CardinalSpline और Linear में से कोई एक हो सकता है। |
| [PatchDirection](./patchdirection/) | Patch की U और V दिशा। |
| [Plane](./plane/) | पैरामीटरयुक्त तल। |
| [PointCloud](./pointcloud/) | पॉइंट क्लाउड में कोई टोपोलॉजी जानकारी नहीं होती, केवल नियंत्रण बिंदु और वर्टेक्स तत्व होते हैं। |
| [PolygonBuilder](./polygonbuilder/) | [`Mesh`](../aspose.threed.entities/mesh/) के लिए बहुभुज बनाने के लिए एक हेल्पर क्लास। |
| [PolygonModifier](./polygonmodifier/) | बहुभुजों को संशोधित करने के लिए उपयोगिताएँ |
| [Primitive](./primitive/) | सभी प्रिमिटिव्स के लिए बेस क्लास |
| [Pyramid](./pyramid/) | पैरामीटरयुक्त पिरामिड। |
| [RectangularTorus](./rectangulartorus/) | पैरामीटरयुक्त आयताकार टॉरस। |
| [RevolvedAreaSolid](./revolvedareasolid/) | यह क्लास एक प्रोफ़ाइल द्वारा प्रदान किए गए क्रॉस‑सेक्शन को धुरी के चारों ओर घुमाकर एक ठोस मॉडल का प्रतिनिधित्व करती है। |
| [Shape](./shape/) | आकार नियंत्रण बिंदुओं के सेट पर विकृति का वर्णन करता है, जो Maya में क्लस्टर डिफॉर्मर के समान है। उदाहरण के लिए, हम एक बनाए गए ज्यामिति में एक आकार जोड़ सकते हैं। और आकार तथा ज्यामिति में समान टोपोलॉजिकल जानकारी होती है लेकिन नियंत्रण बिंदुओं की स्थितियाँ अलग होती हैं। प्रभाव की विभिन्न मात्रा के साथ, ज्यामिति एक विकृति प्रभाव प्रदर्शित करती है। |
| [Skeleton](./skeleton/) | यह [`Skeleton`](../aspose.threed.entities/skeleton/) मुख्यतः CAD सॉफ़्टवेयर द्वारा उपयोग किया जाता है ताकि डिज़ाइनर को कंकाल संरचना के परिवर्तन को नियंत्रित करने में मदद मिल सके, यह आमतौर पर CAD सॉफ़्टवेयर के बाहर बेकार होता है। कंकाल पदानुक्रम को CAD सॉफ़्टवेयर में एक वस्तु की तरह कार्य करने के लिए, शीर्ष [`Skeleton`](../aspose.threed.entities/skeleton/) नोड को रूट बनाना आवश्यक है, जिसके लिए [`Type`](../aspose.threed.entities/skeleton/type/) को Skeleton सेट किया जाता है, और सभी चाइल्ड को Bone सेट किया जाता है |
| [Sphere](./sphere/) | पैरामीटरयुक्त गोला। |
| [SweptAreaSolid](./sweptareasolid/) | एक [`SweptAreaSolid`](../aspose.threed.entities/sweptareasolid/) एक प्रोफ़ाइल को डायरेक्ट्रिक्स के साथ स्वेप करके ज्यामिति बनाता है। |
| [Torus](./torus/) | पैरामीटरयुक्त टोरस। |
| [TransformedCurve](./transformedcurve/) | एक [`TransformedCurve`](../aspose.threed.entities/transformedcurve/) एक ट्रांसफ़ॉर्मेशन मैट्रिक्स का उपयोग करके वक्र को स्थान देता है। यह एक [`TrimmedCurve`](../aspose.threed.entities/trimmedcurve/) या [`CompositeCurve`](../aspose.threed.entities/compositecurve/) के भीतर ट्रांसफ़ॉर्मेशन करने की अनुमति देता है। |
| [TriMesh](./trimesh/) | एक TriMesh कच्चा डेटा रखता है जिसे GPU सीधे उपयोग कर सकता है। यह क्लास एक उपयोगिता है जो केवल प्रति-वर्टेक्स डेटा वाले मेष को बनाने में मदद करती है। |
| [TriMesh&lt;T&gt;](./trimesh-1/) | उपयोगकर्ता के स्थैतिक-परिभाषित वर्टेक्स प्रकार के लिए [`TriMesh`](../aspose.threed.entities/trimesh/) का सामान्य संस्करण |
| [TrimmedCurve](./trimmedcurve/) | एक सीमित वक्र जो दोनों सिरों पर आधार वक्र को ट्रिम करता है। |
| [VertexElement](./vertexelement/) | वर्टेक्स तत्वों की बेस क्लास। एक वर्टेक्स तत्व प्रकार को VertexElementType द्वारा पहचाना जाता है। एक VertexElement वर्णन करता है कि वर्टेक्स तत्व को ज्यामिति सतह पर कैसे मैप किया जाता है और मैपिंग जानकारी मेमोरी में कैसे व्यवस्थित होती है। एक VertexElement में Normals, UVs या अन्य प्रकार की जानकारी होती है। |
| [VertexElementBinormal](./vertexelementbinormal/) | निर्दिष्ट घटकों के लिए बाइनॉर्मल वेक्टर को परिभाषित करता है। |
| [VertexElementDoublesTemplate](./vertexelementdoublestemplate/) | कंक्रीट [`VertexElement`](../aspose.threed.entities/vertexelement/) कार्यान्वयन को परिभाषित करने के लिए एक सहायक क्लास। |
| [VertexElementEdgeCrease](./vertexelementedgecrease/) | निर्दिष्ट घटकों के लिए एज क्रीज़ को परिभाषित करता है |
| [VertexElementHole](./vertexelementhole/) | निर्दिष्ट बहुभुज छेद है या नहीं को परिभाषित करता है |
| [VertexElementIntsTemplate](./vertexelementintstemplate/) | कंक्रीट [`VertexElement`](../aspose.threed.entities/vertexelement/) कार्यान्वयन को परिभाषित करने के लिए एक सहायक क्लास। |
| [VertexElementMaterial](./vertexelementmaterial/) | निर्दिष्ट घटकों के लिए मैटेरियल इंडेक्स को परिभाषित करता है। एक नोड के पास कई मैटेरियल हो सकते हैं, [`VertexElementMaterial`](../aspose.threed.entities/vertexelementmaterial/) का उपयोग ज्यामिति के विभिन्न भागों को विभिन्न मैटेरियल में रेंडर करने के लिए किया जाता है। |
| [VertexElementNormal](./vertexelementnormal/) | निर्दिष्ट घटकों के लिए नॉर्मल वेक्टर को परिभाषित करता है। |
| [VertexElementPolygonGroup](./vertexelementpolygongroup/) | निर्दिष्ट घटकों के लिए बहुभुज समूह को परिभाषित करता है ताकि संबंधित बहुभुज एक साथ समूहित हों। |
| [VertexElementSmoothingGroup](./vertexelementsmoothinggroup/) | एक स्मूदिंग ग्रुप बहुभुज मेष में बहुभुजों का समूह है जो एक स्मूद सतह बनाता हुआ दिखना चाहिए। कुछ प्रारंभिक 3D मॉडलिंग सॉफ़्टवेयर जैसे DOS के लिए 3D Studio Max ने प्रत्येक मेष वर्टेक्स के लिए नॉर्मल वेक्टर को संग्रहीत करने से बचने के लिए स्मूदिंग ग्रुप का उपयोग किया। |
| [VertexElementSpecular](./vertexelementspecular/) | निर्दिष्ट घटकों के लिए स्पेक्युलर रंग को परिभाषित करता है। |
| [VertexElementTangent](./vertexelementtangent/) | निर्दिष्ट घटकों के लिए टैन्जेंट वेक्टर को परिभाषित करता है। |
| [VertexElementTemplate&lt;T&gt;](./vertexelementtemplate-1/) | कंक्रीट [`VertexElement`](../aspose.threed.entities/vertexelement/) कार्यान्वयन को परिभाषित करने के लिए एक सहायक क्लास। |
| [VertexElementUserData](./vertexelementuserdata/) | निर्दिष्ट घटकों के लिए कस्टम उपयोगकर्ता डेटा को परिभाषित करता है। आमतौर पर यह विशेष उद्देश्य के लिए एप्लिकेशन-विशिष्ट डेटा होता है। |
| [VertexElementUV](./vertexelementuv/) | निर्दिष्ट घटकों के लिए UV निर्देशांक को परिभाषित करता है। एक ज्यामिति में कई [`VertexElementUV`](../aspose.threed.entities/vertexelementuv/) तत्व हो सकते हैं, और प्रत्येक का अलग-अलग [`TextureMapping`](../aspose.threed.entities/texturemapping/) हो सकता है। |
| [VertexElementVector4](./vertexelementvector4/) | कंक्रीट [`VertexElement`](../aspose.threed.entities/vertexelement/) कार्यान्वयन को परिभाषित करने के लिए एक सहायक क्लास। |
| [VertexElementVertexColor](./vertexelementvertexcolor/) | निर्दिष्ट घटकों के लिए वर्टेक्स रंग को परिभाषित करता है |
| [VertexElementVertexCrease](./vertexelementvertexcrease/) | निर्दिष्ट घटकों के लिए वर्टेक्स क्रीज़ को परिभाषित करता है |
| [VertexElementVisibility](./vertexelementvisibility/) | निर्दिष्ट घटकों के दृश्य होने को परिभाषित करता है |
| [VertexElementWeight](./vertexelementweight/) | निर्दिष्ट घटकों के लिए ब्लेंड वेट को परिभाषित करता है। |
## Structures

| संरचना | विवरण |
| --- | --- |
| [EndPoint](./endpoint/) | वक्र को ट्रिम करने के लिए अंतिम बिंदु, पैरामीटर मान या कार्टेशियन बिंदु हो सकता है। |
## इंटरफ़ेस

| इंटरफ़ेस | विवरण |
| --- | --- |
| [IIndexedVertexElement](./iindexedvertexelement/) | इंडेक्स डेटा के साथ VertexElement। |
| [IMeshConvertible](./imeshconvertible/) | इस इंटरफ़ेस को लागू करने वाले एंटिटीज़ को [`Mesh`](../aspose.threed.entities/mesh/) में परिवर्तित किया जा सकता है। |
| [IOrientable](./iorientable/) | ओरिएंटेबल एंटिटीज़ को इस इंटरफ़ेस को लागू करना चाहिए। |
## एन्यूमरेशन

| एन्यूमरेशन | विवरण |
| --- | --- |
| [ApertureMode](./aperturemode/) | कैमरा एपर्चर मोड। एपर्चर मोड निर्धारित करता है कि कौन से मान कैमरा एपर्चर को नियंत्रित करते हैं। यदि एपर्चर मोड HorizAndVert, Horizontal, या Vertical है, तो फील्ड ऑफ़ व्यू का उपयोग किया जाता है। यदि एपर्चर मोड FocalLength है, तो फोकल लंबाई का उपयोग किया जाता है। |
| [BooleanOperation](./booleanoperation/) | Mesh का बूलियन ऑपरेशन |
| [CurveDimension](./curvedimension/) | वक्रों का आयाम। |
| [LightType](./lighttype/) | लाइट प्रकार। |
| [MappingMode](./mappingmode/) | निर्धारित करता है कि तत्व सतह पर कैसे मैप किया जाता है। [`MappingMode`](../aspose.threed.entities/mappingmode/) परिभाषित करता है कि [`VertexElement`](../aspose.threed.entities/vertexelement/) ज्यामिति की सतह पर कैसे मैप किया जाता है। |
| [NurbsType](./nurbstype/) | NURBS प्रकार। |
| [PatchDirectionType](./patchdirectiontype/) | पैच दिशा के प्रकार। |
| [ProjectionType](./projectiontype/) | कैमरा की प्रोजेक्शन प्रकार। |
| [ReferenceMode](./referencemode/) | [`ReferenceMode`](../aspose.threed.entities/referencemode/) परिभाषित करता है कि मैपिंग जानकारी कैसे संग्रहीत और संदर्भित की जाती है। |
| [RotationMode](./rotationmode/) | फ्रस्टम का रोटेशन मोड |
| [SkeletonType](./skeletontype/) | [`Skeleton`](../aspose.threed.entities/skeleton/) के प्रकार। |
| [SplitMeshPolicy](./splitmeshpolicy/) | सब-मेश के बीच वर्टेक्स/कंट्रोल पॉइंट डेटा साझा करें या प्रत्येक सब-मेश का अपना संकुचित डेटा हो। |
| [TextureMapping](./texturemapping/) | [`VertexElementUV`](../aspose.threed.entities/vertexelementuv/) के लिए टेक्सचर मैपिंग प्रकार बताता है कि किस प्रकार की टेक्सचर मैपिंग उपयोग की जाती है। |
| [VertexElementType](./vertexelementtype/) | वर्टेक्स तत्व का प्रकार, जो निर्धारित करता है कि इसे मॉडलिंग में कैसे उपयोग किया जाएगा। |


