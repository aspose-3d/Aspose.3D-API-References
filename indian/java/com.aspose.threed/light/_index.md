---
title: Light
second_title: Aspose.3D for Java API Reference
description: रोशनी दृश्य को प्रकाशित करती है।
type: docs
weight: 94
url: /hi/java/com.aspose.threed/light/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Frustum](../../com.aspose.threed/frustum)
```
public class Light extends Frustum
```

रोशनी दृश्य को प्रकाशित करती है।

लाइट के कुल एटेन्यूएशन की गणना करने का सूत्र है:  A = ConstantAttenuation + (Dist \* LinearAttenuation) + ((Dist^2) \* QuadraticAttenuation)
## Constructors

| Constructor | विवरण |
| --- | --- |
| [Light()](#Light--) | नए [Light](../../com.aspose.threed/light) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Light(String name)](#Light-java.lang.String-) | नए [Light](../../com.aspose.threed/light) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
| [Light(String name, LightType type)](#Light-java.lang.String-com.aspose.threed.LightType-) | नए [Light](../../com.aspose.threed/light) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | प्रॉपर्टी को खोजता है। |
| [getAspect()](#getAspect--) | Frustum का आस्पेक्ट रेशियो प्राप्त करता है |
| [getBoundingBox()](#getBoundingBox--) | वर्तमान एंटिटी का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कॉर्डिनेट सिस्टम में प्राप्त करता है। |
| [getCastLight()](#getCastLight--) | जाँचता है कि वर्तमान Light इंस्टेंस अन्य ऑब्जेक्ट्स को प्रकाशित कर सकता है या नहीं। |
| [getCastShadows()](#getCastShadows--) | जाँचता है कि Light अन्य ऑब्जेक्ट्स पर शैडो डाल सकता है या नहीं। |
| [getClass()](#getClass--) |  |
| [getColor()](#getColor--) | Light का रंग प्राप्त करता है |
| [getConstantAttenuation()](#getConstantAttenuation--) | Light के कुल एटेन्यूएशन की गणना के लिए कॉन्स्टेंट एटेन्यूएशन प्राप्त करता है |
| [getDirection()](#getDirection--) | कैमरा जिस दिशा में देख रहा है, वह दिशा प्राप्त करता है। |
| [getEntityRendererKey()](#getEntityRendererKey--) | रेंडरर में पंजीकृत एंटिटी रेंडरर की कुंजी प्राप्त करता है |
| [getExcluded()](#getExcluded--) | निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में प्राप्त करता है। |
| [getFalloff()](#getFalloff--) | फ़ॉलऑफ़ कोन एंगल (डिग्री में) प्राप्त करता है। |
| [getFarPlane()](#getFarPlane--) | Frustum की फार प्लेन दूरी प्राप्त करता है। |
| [getHotSpot()](#getHotSpot--) | हॉट स्पॉट कोन कोण (डिग्री में) प्राप्त करता है। |
| [getIntensity()](#getIntensity--) | लाइट की तीव्रता प्राप्त करता है, डिफ़ॉल्ट मान 100 है। |
| [getLightType()](#getLightType--) | लाइट का प्रकार प्राप्त करता है। |
| [getLinearAttenuation()](#getLinearAttenuation--) | लाइट के कुल क्षीणन की गणना के लिए रैखिक क्षीणन प्राप्त करता है। |
| [getLookAt()](#getLookAt--) | कैमरा जिस रुचिकर स्थिति की ओर देख रहा है, उसे प्राप्त करता है। |
| [getName()](#getName--) | नाम प्राप्त करता है। |
| [getNearPlane()](#getNearPlane--) | फ्रस्टम के निकट प्लेन की दूरी प्राप्त करता है। |
| [getOrthoHeight()](#getOrthoHeight--) | ऑर्थोग्राफिक प्रोजेक्शन में फ्रस्टम की ऊँचाई प्राप्त करता है। |
| [getParentNode()](#getParentNode--) | पहला पैरेंट नोड प्राप्त करता है, यदि पहला पैरेंट नोड सेट किया गया है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [getParentNodes()](#getParentNodes--) | सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जुड़ी हो सकती है |
| [getProperties()](#getProperties--) | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [getProperty(String property)](#getProperty-java.lang.String-) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [getQuadraticAttenuation()](#getQuadraticAttenuation--) | लाइट के कुल क्षीणन की गणना के लिए द्विघातीय क्षीणन प्राप्त करता है। |
| [getRotationMode()](#getRotationMode--) | फ्रस्टम की अभिविन्यास मोड प्राप्त करता है। यह प्रॉपर्टी केवल तब काम करती है जब [getTarget](../../com.aspose.threed/frustum\#getTarget) null हो। |
| [getScene()](#getScene--) | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [getShadowColor()](#getShadowColor--) | छाया का रंग प्राप्त करता है। |
| [getTarget()](#getTarget--) | कैमरा जिस लक्ष्य की ओर देख रहा है, उसे प्राप्त करता है। |
| [getUp()](#getUp--) | कैमरा की ऊपर की दिशा प्राप्त करता है। |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [setAspect(double value)](#setAspect-double-) | फ्रस्टम का आस्पेक्ट रेशियो सेट करता है। |
| [setCastLight(boolean value)](#setCastLight-boolean-) | निर्धारित करता है कि वर्तमान लाइट इंस्टेंस अन्य वस्तुओं को प्रकाशित कर सकता है या नहीं। |
| [setCastShadows(boolean value)](#setCastShadows-boolean-) | निर्धारित करता है कि लाइट अन्य वस्तुओं पर छाया डाल सकता है या नहीं। |
| [setColor(Vector3 value)](#setColor-com.aspose.threed.Vector3-) | लाइट का रंग सेट करता है। |
| [setConstantAttenuation(double value)](#setConstantAttenuation-double-) | लाइट के कुल क्षीणन की गणना के लिए स्थिर क्षीणन सेट करता है। |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | कैमरा जिस दिशा की ओर देख रहा है, उसे सेट करता है। |
| [setExcluded(boolean value)](#setExcluded-boolean-) | निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में सेट करता है। |
| [setFalloff(double value)](#setFalloff-double-) | फ़ॉलऑफ़ कोन कोण (डिग्री में) सेट करता है। |
| [setFarPlane(double value)](#setFarPlane-double-) | फ्रस्टम के दूरस्थ प्लेन की दूरी सेट करता है। |
| [setHotSpot(double value)](#setHotSpot-double-) | हॉट स्पॉट कोन कोण (डिग्री में) सेट करता है। |
| [setIntensity(double value)](#setIntensity-double-) | लाइट की तीव्रता सेट करता है, डिफ़ॉल्ट मान 100 है। |
| [setLightType(LightType value)](#setLightType-com.aspose.threed.LightType-) | लाइट का प्रकार सेट करता है। |
| [setLinearAttenuation(double value)](#setLinearAttenuation-double-) | लाइट के कुल क्षीणन की गणना के लिए रैखिक क्षीणन सेट करता है। |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | कैमरा जिस रुचिकर स्थिति की ओर देख रहा है, उसे सेट करता है। |
| [setName(String value)](#setName-java.lang.String-) | नाम सेट करता है। |
| [setNearPlane(double value)](#setNearPlane-double-) | फ़्रस्टम की निकटतम प्लेन दूरी सेट करता है। |
| [setOrthoHeight(double value)](#setOrthoHeight-double-) | ऑर्थोग्राफिक प्रोजेक्शन में फ़्रस्टम के लिए ऊँचाई सेट करता है। |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | पहला पैरेंट नोड सेट करता है, यदि पहला पैरेंट नोड सेट किया गया है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [setQuadraticAttenuation(double value)](#setQuadraticAttenuation-double-) | लाइट के कुल क्षीणन की गणना के लिए क्वाड्रेटिक अटेनुएशन सेट करता है। |
| [setRotationMode(RotationMode value)](#setRotationMode-com.aspose.threed.RotationMode-) | फ़्रस्टम की ओरिएंटेशन मोड सेट करता है। यह प्रॉपर्टी केवल तब काम करती है जब [getTarget](../../com.aspose.threed/frustum\#getTarget) null हो। |
| [setShadowColor(Vector3 value)](#setShadowColor-com.aspose.threed.Vector3-) | छाया का रंग सेट करता है। |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | कैमरा जिस लक्ष्य की ओर देख रहा है उसे सेट करता है। |
| [setUp(Vector3 value)](#setUp-com.aspose.threed.Vector3-) | कैमरा की ऊपर की दिशा सेट करता है। |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Light() {#Light--}
```
public Light()
```


नए [Light](../../com.aspose.threed/light) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

### Light(String name) {#Light-java.lang.String-}
```
public Light(String name)
```


नए [Light](../../com.aspose.threed/light) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String | नाम |

### Light(String name, LightType type) {#Light-java.lang.String-com.aspose.threed.LightType-}
```
public Light(String name, LightType type)
```


नए [Light](../../com.aspose.threed/light) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String | नाम |
| type | [LightType](../../com.aspose.threed/lighttype) | नयी लाइट का प्रकार |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


प्रॉपर्टी को खोजता है। यह एक डायनामिक प्रॉपर्टी (CreateDynamicProperty/SetProperty द्वारा बनाई गई) या नेटिव प्रॉपर्टी (नाम द्वारा पहचानी गई) हो सकती है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| propertyName | java.lang.String | प्रॉपर्टी नाम। |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getAspect() {#getAspect--}
```
public double getAspect()
```


Frustum का आस्पेक्ट रेशियो प्राप्त करता है

**Returns:**
double - फ़्रस्टम का आस्पेक्ट रेशियो
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


वर्तमान एंटिटी का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कॉर्डिनेट सिस्टम में प्राप्त करता है।

**Returns:**
[BoundingBox](../../com.aspose.threed/boundingbox) - the bounding box of current entity in its object space coordinate system. **Example:** The following code shows how to calculate the bounding box of a shape

```
Entity entity = new Sphere();
     entity.setRadius(10);
     var bbox = entity.getBoundingBox();
     System.out.printf("The bounding box of the entity is %s ~ %s", bbox.getMinimum(), bbox.getMaximum());
```
### getCastLight() {#getCastLight--}
```
public boolean getCastLight()
```


जाँचता है कि वर्तमान Light इंस्टेंस अन्य ऑब्जेक्ट्स को प्रकाशित कर सकता है या नहीं।

**Returns:**
boolean - यदि वर्तमान लाइट इंस्टेंस अन्य वस्तुओं को प्रकाशित कर सकता है।
### getCastShadows() {#getCastShadows--}
```
public boolean getCastShadows()
```


जाँचता है कि Light अन्य ऑब्जेक्ट्स पर शैडो डाल सकता है या नहीं।

**Returns:**
boolean - यदि लाइट अन्य वस्तुओं पर छाया डाल सकता है।
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColor() {#getColor--}
```
public Vector3 getColor()
```


Light का रंग प्राप्त करता है

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the light's color
### getConstantAttenuation() {#getConstantAttenuation--}
```
public double getConstantAttenuation()
```


Light के कुल एटेन्यूएशन की गणना के लिए कॉन्स्टेंट एटेन्यूएशन प्राप्त करता है

**Returns:**
double - लाइट के कुल क्षीणन की गणना के लिए कॉन्स्टेंट अटेनुएशन
### getDirection() {#getDirection--}
```
public Vector3 getDirection()
```


कैमरा जिस दिशा की ओर देख रहा है उसे प्राप्त करता है। इस प्रॉपर्टी में परिवर्तन [getLookAt](../../com.aspose.threed/frustum\#getLookAt) और [getTarget](../../com.aspose.threed/frustum\#getTarget) को भी प्रभावित करेंगे।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the direction that the camera is looking at. Changes on this property will also affects the [getLookAt](../../com.aspose.threed/frustum\#getLookAt) and [getTarget](../../com.aspose.threed/frustum\#getTarget).
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


रेंडरर में पंजीकृत एंटिटी रेंडरर की कुंजी प्राप्त करता है

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey) - the key of the entity renderer registered in the renderer
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में प्राप्त करता है।

**Returns:**
बूलियन - निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में।
### getFalloff() {#getFalloff--}
```
public double getFalloff()
```


फ़ॉलऑफ़ कोन एंगल (डिग्री में) प्राप्त करता है।

**Returns:**
double - फॉलऑफ़ कोन एंगल (डिग्री में)।
### getFarPlane() {#getFarPlane--}
```
public double getFarPlane()
```


Frustum की फार प्लेन दूरी प्राप्त करता है।

**Returns:**
double - फ़्रस्टम की दूरस्थ प्लेन दूरी।
### getHotSpot() {#getHotSpot--}
```
public double getHotSpot()
```


हॉट स्पॉट कोन कोण (डिग्री में) प्राप्त करता है।

**Returns:**
double - हॉट स्पॉट कोन एंगल (डिग्री में)।
### getIntensity() {#getIntensity--}
```
public double getIntensity()
```


लाइट की तीव्रता प्राप्त करता है, डिफ़ॉल्ट मान 100 है।

**Returns:**
double - लाइट की तीव्रता, डिफ़ॉल्ट मान 100 है।
### getLightType() {#getLightType--}
```
public LightType getLightType()
```


लाइट का प्रकार प्राप्त करता है।

**Returns:**
[LightType](../../com.aspose.threed/lighttype) - the light's type
### getLinearAttenuation() {#getLinearAttenuation--}
```
public double getLinearAttenuation()
```


लाइट के कुल क्षीणन की गणना के लिए रैखिक क्षीणन प्राप्त करता है।

**Returns:**
double - लाइट के कुल क्षीणन की गणना के लिए लीनियर अटेनुएशन।
### getLookAt() {#getLookAt--}
```
public Vector3 getLookAt()
```


कैमरा जिस रुचिकर स्थिति की ओर देख रहा है, उसे प्राप्त करता है।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the the interested position that the camera is looking at.
### getName() {#getName--}
```
public String getName()
```


नाम प्राप्त करता है।

**Returns:**
java.lang.String - नाम।
### getNearPlane() {#getNearPlane--}
```
public double getNearPlane()
```


फ्रस्टम के निकट प्लेन की दूरी प्राप्त करता है।

**Returns:**
double - फ़्रस्टम की निकटतम प्लेन दूरी।
### getOrthoHeight() {#getOrthoHeight--}
```
public double getOrthoHeight()
```


ऑर्थोग्राफिक प्रोजेक्शन में फ्रस्टम की ऊँचाई प्राप्त करता है।

**Returns:**
double - ऑर्थोग्राफिक प्रोजेक्शन में फ़्रस्टम की ऊँचाई।
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


पहला पैरेंट नोड प्राप्त करता है, यदि पहला पैरेंट नोड सेट किया गया है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी।

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जुड़ी हो सकती है

**Returns:**
java.util.ArrayList<com.aspose.threed.Node> - सभी पैरेंट नोड्स, एक इकाई को ज्यामिति इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जोड़ा जा सकता है
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है।

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | प्रॉपर्टी नाम |

**Returns:**
java.lang.Object - मिली हुई प्रॉपर्टी का मान
### getQuadraticAttenuation() {#getQuadraticAttenuation--}
```
public double getQuadraticAttenuation()
```


लाइट के कुल क्षीणन की गणना के लिए द्विघातीय क्षीणन प्राप्त करता है।

**Returns:**
double - लाइट के कुल क्षीणन की गणना के लिए क्वाड्रेटिक अटेनुएशन।
### getRotationMode() {#getRotationMode--}
```
public RotationMode getRotationMode()
```


फ़्रस्टम की ओरिएंटेशन मोड प्राप्त करता है। यह प्रॉपर्टी केवल तब काम करती है जब [getTarget](../../com.aspose.threed/frustum\#getTarget) null हो। यदि मान [RotationMode.FIXED_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET) है, तो दिशा हमेशा प्रॉपर्टी [getLookAt](../../com.aspose.threed/frustum\#getLookAt) द्वारा गणना की जाती है। अन्यथा [getLookAt](../../com.aspose.threed/frustum\#getLookAt) हमेशा [getDirection](../../com.aspose.threed/frustum\#getDirection) द्वारा गणना की जाती है।

**Returns:**
[RotationMode](../../com.aspose.threed/rotationmode) - the frustum's orientation mode This property only works when the [getTarget](../../com.aspose.threed/frustum\#getTarget) is null. If the value is [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), the direction is always calculated by the property [getLookAt](../../com.aspose.threed/frustum\#getLookAt) Otherwise the [getLookAt](../../com.aspose.threed/frustum\#getLookAt) is always calculated by the [getDirection](../../com.aspose.threed/frustum\#getDirection)
### getScene() {#getScene--}
```
public Scene getScene()
```


उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getShadowColor() {#getShadowColor--}
```
public Vector3 getShadowColor()
```


छाया का रंग प्राप्त करता है।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the shadow's color.
### getTarget() {#getTarget--}
```
public Node getTarget()
```


कैमरा जिस लक्ष्य की ओर देख रहा है उसे प्राप्त करता है। यदि उपयोगकर्ता इस प्रॉपर्टी का समर्थन करता है, तो यह [getLookAt](../../com.aspose.threed/frustum\#getLookAt) प्रॉपर्टी से पहले होना चाहिए।

**Returns:**
[Node](../../com.aspose.threed/node) - the target that the camera is looking at. If the user supports this property, it should be prior to [getLookAt](../../com.aspose.threed/frustum\#getLookAt) property.
### getUp() {#getUp--}
```
public Vector3 getUp()
```


कैमरा की ऊपर की दिशा प्राप्त करता है।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the up direction of the camera
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


डायनामिक प्रॉपर्टी को हटाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | कौन सी प्रॉपर्टी हटानी है |

**Returns:**
boolean - यदि प्रॉपर्टी सफलतापूर्वक हटाई गई हो तो true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | कौन सी प्रॉपर्टी हटानी है |

**Returns:**
boolean - यदि प्रॉपर्टी सफलतापूर्वक हटाई गई हो तो true
### setAspect(double value) {#setAspect-double-}
```
public void setAspect(double value)
```


फ्रस्टम का आस्पेक्ट रेशियो सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setCastLight(boolean value) {#setCastLight-boolean-}
```
public void setCastLight(boolean value)
```


निर्धारित करता है कि वर्तमान लाइट इंस्टेंस अन्य वस्तुओं को प्रकाशित कर सकता है या नहीं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setCastShadows(boolean value) {#setCastShadows-boolean-}
```
public void setCastShadows(boolean value)
```


निर्धारित करता है कि लाइट अन्य वस्तुओं पर छाया डाल सकता है या नहीं।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setColor(Vector3 value) {#setColor-com.aspose.threed.Vector3-}
```
public void setColor(Vector3 value)
```


लाइट का रंग सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | नया मान |

### setConstantAttenuation(double value) {#setConstantAttenuation-double-}
```
public void setConstantAttenuation(double value)
```


लाइट के कुल क्षीणन की गणना के लिए स्थिर क्षीणन सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public void setDirection(Vector3 value)
```


कैमरा जिस दिशा की ओर देख रहा है उसे सेट करता है। इस प्रॉपर्टी में परिवर्तन [getLookAt](../../com.aspose.threed/frustum\#getLookAt) और [getTarget](../../com.aspose.threed/frustum\#getTarget) को भी प्रभावित करेंगे।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | नया मान |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | boolean | नया मान |

### setFalloff(double value) {#setFalloff-double-}
```
public void setFalloff(double value)
```


फ़ॉलऑफ़ कोन कोण (डिग्री में) सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setFarPlane(double value) {#setFarPlane-double-}
```
public void setFarPlane(double value)
```


फ्रस्टम के दूरस्थ प्लेन की दूरी सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setHotSpot(double value) {#setHotSpot-double-}
```
public void setHotSpot(double value)
```


हॉट स्पॉट कोन कोण (डिग्री में) सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setIntensity(double value) {#setIntensity-double-}
```
public void setIntensity(double value)
```


लाइट की तीव्रता सेट करता है, डिफ़ॉल्ट मान 100 है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setLightType(LightType value) {#setLightType-com.aspose.threed.LightType-}
```
public void setLightType(LightType value)
```


लाइट का प्रकार सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [LightType](../../com.aspose.threed/lighttype) | नया मान |

### setLinearAttenuation(double value) {#setLinearAttenuation-double-}
```
public void setLinearAttenuation(double value)
```


लाइट के कुल क्षीणन की गणना के लिए रैखिक क्षीणन सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setLookAt(Vector3 value) {#setLookAt-com.aspose.threed.Vector3-}
```
public void setLookAt(Vector3 value)
```


कैमरा जिस रुचिकर स्थिति की ओर देख रहा है, उसे सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | नया मान |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


नाम सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | java.lang.String | नया मान |

### setNearPlane(double value) {#setNearPlane-double-}
```
public void setNearPlane(double value)
```


फ़्रस्टम की निकटतम प्लेन दूरी सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setOrthoHeight(double value) {#setOrthoHeight-double-}
```
public void setOrthoHeight(double value)
```


ऑर्थोग्राफिक प्रोजेक्शन में फ़्रस्टम के लिए ऊँचाई सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


पहला पैरेंट नोड सेट करता है, यदि पहला पैरेंट नोड सेट किया गया है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | नया मान |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


निर्दिष्ट प्रॉपर्टी का मान सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| प्रॉपर्टी | java.lang.String | प्रॉपर्टी नाम |
| मान | java.lang.Object | प्रॉपर्टी का मान |

### setQuadraticAttenuation(double value) {#setQuadraticAttenuation-double-}
```
public void setQuadraticAttenuation(double value)
```


लाइट के कुल क्षीणन की गणना के लिए क्वाड्रेटिक अटेनुएशन सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setRotationMode(RotationMode value) {#setRotationMode-com.aspose.threed.RotationMode-}
```
public void setRotationMode(RotationMode value)
```


फ़्रस्टम की ओरिएंटेशन मोड सेट करता है। यह प्रॉपर्टी केवल तब काम करती है जब [getTarget](../../com.aspose.threed/frustum\#getTarget) null हो। यदि मान [RotationMode.FIXED_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET) है, तो दिशा हमेशा प्रॉपर्टी [getLookAt](../../com.aspose.threed/frustum\#getLookAt) द्वारा गणना की जाती है। अन्यथा [getLookAt](../../com.aspose.threed/frustum\#getLookAt) हमेशा [getDirection](../../com.aspose.threed/frustum\#getDirection) द्वारा गणना की जाती है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [RotationMode](../../com.aspose.threed/rotationmode) | नया मान |

### setShadowColor(Vector3 value) {#setShadowColor-com.aspose.threed.Vector3-}
```
public void setShadowColor(Vector3 value)
```


छाया का रंग सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | नया मान |

### setTarget(Node value) {#setTarget-com.aspose.threed.Node-}
```
public void setTarget(Node value)
```


कैमरा जिस लक्ष्य की ओर देख रहा है, उसे सेट करता है। यदि उपयोगकर्ता इस प्रॉपर्टी का समर्थन करता है, तो यह [getLookAt](../../com.aspose.threed/frustum\#getLookAt) प्रॉपर्टी से पहले होना चाहिए।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | नया मान |

### setUp(Vector3 value) {#setUp-com.aspose.threed.Vector3-}
```
public void setUp(Vector3 value)
```


कैमरा की ऊपर की दिशा सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | नया मान |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

