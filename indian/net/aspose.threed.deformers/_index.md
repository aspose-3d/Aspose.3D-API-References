---
title: "Aspose.ThreeD.Deformers"
second_title: "Aspose.3D के लिए .NET API संदर्भ"
description: "सभी डिफॉर्मर क्लासेस इस नामस्थान में परिभाषित हैं।"
type: docs
weight: 30
url: /hi/net/aspose.threed.deformers/
---
सभी डिफॉर्मर क्लासेस इस नामस्थान में परिभाषित हैं।

## क्लासेस

| क्लास | विवरण |
| --- | --- |
| [Bone](./bone/) | एक हड्डी ज्यामिति के नियंत्रण बिंदु के उपसमुच्चय को परिभाषित करती है, और प्रत्येक नियंत्रण बिंदु के लिए मिश्रण वजन निर्धारित करती है। [`Bone`](../aspose.threed.deformers/bone/) ऑब्जेक्ट को सीधे उपयोग नहीं किया जा सकता, एक [`SkinDeformer`](../aspose.threed.deformers/skindeformer/) इंस्टेंस का उपयोग ज्यामिति को डिफॉर्म करने के लिए किया जाता है, और [`SkinDeformer`](../aspose.threed.deformers/skindeformer/) कई हड्डियों के सेट के साथ आता है, प्रत्येक हड्डी एक नोड से जुड़ी होती है। नोट: ज्यामिति का एक नियंत्रण बिंदु एक से अधिक हड्डियों से बंधा हो सकता है। |
| [Deformer](./deformer/) | [`SkinDeformer`](../aspose.threed.deformers/skindeformer/) और [`MorphTargetDeformer`](../aspose.threed.deformers/morphtargetdeformer/) के लिए बेस क्लास |
| [MorphTargetChannel](./morphtargetchannel/) | एक MorphTargetChannel [`MorphTargetDeformer`](../aspose.threed.deformers/morphtargetdeformer/) द्वारा लक्ष्य ज्यामितियों को व्यवस्थित करने के लिए उपयोग किया जाता है। FBX जैसे कुछ फ़ाइल फ़ॉर्मेट समानांतर में कई चैनलों का समर्थन करते हैं। |
| [MorphTargetDeformer](./morphtargetdeformer/) | MorphTargetDeformer प्रति-शिखर एनीमेशन प्रदान करता है। MorphTargetDeformer सभी लक्ष्यों को [`MorphTargetChannel`](../aspose.threed.deformers/morphtargetchannel/) के माध्यम से व्यवस्थित करता है, प्रत्येक चैनल कई लक्ष्यों को व्यवस्थित कर सकता है। मोर्फ़ टार्गेट डिफॉर्मर का सामान्य उपयोग एक चरित्र पर चेहरे की अभिव्यक्ति लागू करना है। अधिक विवरण https://en.wikipedia.org/wiki/Morph_target_animation पर पाया जा सकता है। |
| [SkinDeformer](./skindeformer/) | एक स्किन डिफॉर्मर में काम करने के लिए कई हड्डियाँ होती हैं, प्रत्येक हड्डी नियंत्रण बिंदु के वजन द्वारा ज्यामिति के एक भाग को मिश्रित करती है। |
## एन्यूमरेशन

| एन्यूमरेशन | विवरण |
| --- | --- |
| [BoneLinkMode](./bonelinkmode/) | हड्डी का लिंक मोड उस तरीके को दर्शाता है जिसमें एक हड्डी को पदानुक्रमित संरचना में उसकी पैरेंट हड्डी से जोड़ा या लिंक किया जाता है। |


