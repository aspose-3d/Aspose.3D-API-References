---
title: Camera
second_title: Aspose.3D for Java API Reference
description: कैमरा दृश्य को देख रहे दर्शक के नेत्र बिंदु का वर्णन करता है।
type: docs
weight: 28
url: /hi/java/com.aspose.threed/camera/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Frustum](../../com.aspose.threed/frustum)

**All Implemented Interfaces:**
[com.aspose.threed.IOrientable](../../com.aspose.threed/iorientable)
```
public class Camera extends Frustum implements IOrientable
```

कैमरा दृश्य को देख रहे दर्शक के नेत्र बिंदु का वर्णन करता है।
## Constructors

| Constructor | विवरण |
| --- | --- |
| [Camera()](#Camera--) | नए [Camera](../../com.aspose.threed/camera) वर्ग का एक नया उदाहरण आरंभ करता है। |
| [Camera(ProjectionType projectionType)](#Camera-com.aspose.threed.ProjectionType-) | नए [Camera](../../com.aspose.threed/camera) वर्ग का एक नया उदाहरण आरंभ करता है। |
| [Camera(String name)](#Camera-java.lang.String-) | नए [Camera](../../com.aspose.threed/camera) वर्ग का एक नया उदाहरण आरंभ करता है। |
| [Camera(String name, ProjectionType projectionType)](#Camera-java.lang.String-com.aspose.threed.ProjectionType-) | नए [Camera](../../com.aspose.threed/camera) वर्ग का एक नया उदाहरण आरंभ करता है। |
## Methods

| Method | विवरण |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | प्रॉपर्टी को खोजता है। |
| [getApertureMode()](#getApertureMode--) | कैमरा का एपर्चर मोड प्राप्त करता है |
| [getAspect()](#getAspect--) | Frustum का आस्पेक्ट रेशियो प्राप्त करता है |
| [getAspectRatio()](#getAspectRatio--) | व्यू प्लेन का आस्पेक्ट रेशियो प्राप्त करता है। |
| [getBoundingBox()](#getBoundingBox--) | वर्तमान एंटिटी का बाउंडिंग बॉक्स उसके ऑब्जेक्ट स्पेस कॉर्डिनेट सिस्टम में प्राप्त करता है। |
| [getClass()](#getClass--) |  |
| [getDirection()](#getDirection--) | कैमरा जिस दिशा में देख रहा है, वह दिशा प्राप्त करता है। |
| [getEntityRendererKey()](#getEntityRendererKey--) | रेंडरर में पंजीकृत एंटिटी रेंडरर की कुंजी प्राप्त करता है |
| [getExcluded()](#getExcluded--) | निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में प्राप्त करता है। |
| [getFarPlane()](#getFarPlane--) | Frustum की फार प्लेन दूरी प्राप्त करता है। |
| [getFieldOfView()](#getFieldOfView--) | कैमरा का फील्ड ऑफ व्यू डिग्री में प्राप्त करता है, यह प्रॉपर्टी केवल तब उपयोग की जाती है जब ApertureMode है [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) या [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL) |
| [getFieldOfViewX()](#getFieldOfViewX--) | कैमरा का हॉरिज़ॉन्टल फील्ड ऑफ व्यू डिग्री में प्राप्त करता है, यह प्रॉपर्टी केवल तब उपयोग की जाती है जब ApertureMode है [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) |
| [getFieldOfViewY()](#getFieldOfViewY--) | कैमरा का वर्टिकल फील्ड ऑफ व्यू डिग्री में प्राप्त करता है, यह प्रॉपर्टी केवल तब उपयोग की जाती है जब ApertureMode है [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) |
| [getHeight()](#getHeight--) | व्यू प्लेन की ऊँचाई इंच में प्राप्त करता है |
| [getLookAt()](#getLookAt--) | कैमरा जिस रुचिकर स्थिति की ओर देख रहा है, उसे प्राप्त करता है। |
| [getMagnification()](#getMagnification--) | ऑर्थोग्राफिक कैमरा में उपयोग किए गए मैग्निफिकेशन को प्राप्त करता है |
| [getName()](#getName--) | नाम प्राप्त करता है। |
| [getNearPlane()](#getNearPlane--) | फ्रस्टम के निकट प्लेन की दूरी प्राप्त करता है। |
| [getOrthoHeight()](#getOrthoHeight--) | ऑर्थोग्राफिक प्रोजेक्शन में फ्रस्टम की ऊँचाई प्राप्त करता है। |
| [getParentNode()](#getParentNode--) | पहला पैरेंट नोड प्राप्त करता है, यदि पहला पैरेंट नोड सेट किया गया है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [getParentNodes()](#getParentNodes--) | सभी पैरेंट नोड्स प्राप्त करता है, एक एंटिटी जियोमेट्री इंस्टेंसिंग के लिए कई पैरेंट नोड्स से जुड़ी हो सकती है |
| [getProjectionType()](#getProjectionType--) | कैमरा का प्रोजेक्शन टाइप प्राप्त करता है। |
| [getProperties()](#getProperties--) | सभी प्रॉपर्टीज़ का संग्रह प्राप्त करता है। |
| [getProperty(String property)](#getProperty-java.lang.String-) | निर्दिष्ट प्रॉपर्टी का मान प्राप्त करें |
| [getRotationMode()](#getRotationMode--) | फ्रस्टम की अभिविन्यास मोड प्राप्त करता है। यह प्रॉपर्टी केवल तब काम करती है जब [getTarget](../../com.aspose.threed/frustum\#getTarget) null हो। |
| [getScene()](#getScene--) | उस सीन को प्राप्त करता है जिससे यह ऑब्जेक्ट संबंधित है |
| [getTarget()](#getTarget--) | कैमरा जिस लक्ष्य की ओर देख रहा है, उसे प्राप्त करता है। |
| [getUp()](#getUp--) | कैमरा की ऊपर की दिशा प्राप्त करता है। |
| [getWidth()](#getWidth--) | व्यू प्लेन की चौड़ाई इंच में प्राप्त करता है |
| [hashCode()](#hashCode--) |  |
| [moveForward(double distance)](#moveForward-double-) | कैमरा को उसकी दिशा या लक्ष्य की ओर आगे ले जाएँ। |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | डायनामिक प्रॉपर्टी को हटाता है। |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | नाम द्वारा पहचानी गई निर्दिष्ट प्रॉपर्टी को हटाएँ |
| [setApertureMode(ApertureMode value)](#setApertureMode-com.aspose.threed.ApertureMode-) | कैमरा का एपर्चर मोड सेट करता है |
| [setAspect(double value)](#setAspect-double-) | फ्रस्टम का आस्पेक्ट रेशियो सेट करता है। |
| [setAspectRatio(double value)](#setAspectRatio-double-) | व्यू प्लेन का आस्पेक्ट रेशियो सेट करता है। |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | कैमरा जिस दिशा की ओर देख रहा है, उसे सेट करता है। |
| [setExcluded(boolean value)](#setExcluded-boolean-) | निर्यात के दौरान इस एंटिटी को बाहर रखने के बारे में सेट करता है। |
| [setFarPlane(double value)](#setFarPlane-double-) | फ्रस्टम के दूरस्थ प्लेन की दूरी सेट करता है। |
| [setFieldOfView(double value)](#setFieldOfView-double-) | कैमरा का फील्ड ऑफ व्यू डिग्री में सेट करता है, यह प्रॉपर्टी केवल तब उपयोग की जाती है जब ApertureMode है [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) या [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL) |
| [setFieldOfViewX(double value)](#setFieldOfViewX-double-) | कैमरा का हॉरिज़ॉन्टल फील्ड ऑफ व्यू डिग्री में सेट करता है, यह प्रॉपर्टी केवल तब उपयोग की जाती है जब ApertureMode है [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) |
| [setFieldOfViewY(double value)](#setFieldOfViewY-double-) | कैमरा का वर्टिकल फील्ड ऑफ व्यू डिग्री में सेट करता है, यह प्रॉपर्टी केवल तब उपयोग की जाती है जब ApertureMode है [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT) |
| [setHeight(double value)](#setHeight-double-) | व्यू प्लेन की ऊँचाई इंच में सेट करता है |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | कैमरा जिस रुचिकर स्थिति की ओर देख रहा है, उसे सेट करता है। |
| [setMagnification(Vector2 value)](#setMagnification-com.aspose.threed.Vector2-) | ऑर्थोग्राफिक कैमरा में उपयोग किए गए मैग्निफिकेशन को सेट करता है |
| [setName(String value)](#setName-java.lang.String-) | नाम सेट करता है। |
| [setNearPlane(double value)](#setNearPlane-double-) | फ़्रस्टम की निकटतम प्लेन दूरी सेट करता है। |
| [setOrthoHeight(double value)](#setOrthoHeight-double-) | ऑर्थोग्राफिक प्रोजेक्शन में फ़्रस्टम के लिए ऊँचाई सेट करता है। |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | पहला पैरेंट नोड सेट करता है, यदि पहला पैरेंट नोड सेट किया गया है, तो यह एंटिटी अन्य पैरेंट नोड्स से अलग हो जाएगी। |
| [setProjectionType(ProjectionType value)](#setProjectionType-com.aspose.threed.ProjectionType-) | कैमरा का प्रोजेक्शन टाइप सेट करता है। |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | निर्दिष्ट प्रॉपर्टी का मान सेट करता है |
| [setRotationMode(RotationMode value)](#setRotationMode-com.aspose.threed.RotationMode-) | फ़्रस्टम की ओरिएंटेशन मोड सेट करता है। यह प्रॉपर्टी केवल तब काम करती है जब [getTarget](../../com.aspose.threed/frustum\#getTarget) null हो। |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | कैमरा जिस लक्ष्य की ओर देख रहा है उसे सेट करता है। |
| [setUp(Vector3 value)](#setUp-com.aspose.threed.Vector3-) | कैमरा की ऊपर की दिशा सेट करता है। |
| [setWidth(double value)](#setWidth-double-) | व्यू प्लेन की चौड़ाई इंच में सेट करता है |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Camera() {#Camera--}
```
public Camera()
```


नए [Camera](../../com.aspose.threed/camera) वर्ग का एक नया उदाहरण आरंभ करता है।

### Camera(ProjectionType projectionType) {#Camera-com.aspose.threed.ProjectionType-}
```
public Camera(ProjectionType projectionType)
```


नए [Camera](../../com.aspose.threed/camera) वर्ग का एक नया उदाहरण आरंभ करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| projectionType | [ProjectionType](../../com.aspose.threed/projectiontype) | प्रोजेक्शन टाइप। |

### Camera(String name) {#Camera-java.lang.String-}
```
public Camera(String name)
```


नए [Camera](../../com.aspose.threed/camera) वर्ग का एक नया उदाहरण आरंभ करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String | नाम। |

### Camera(String name, ProjectionType projectionType) {#Camera-java.lang.String-com.aspose.threed.ProjectionType-}
```
public Camera(String name, ProjectionType projectionType)
```


नए [Camera](../../com.aspose.threed/camera) वर्ग का एक नया उदाहरण आरंभ करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| name | java.lang.String | नाम। |
| projectionType | [ProjectionType](../../com.aspose.threed/projectiontype) | प्रोजेक्शन टाइप। |

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
### getApertureMode() {#getApertureMode--}
```
public ApertureMode getApertureMode()
```


कैमरा का एपर्चर मोड प्राप्त करता है

**Returns:**
[ApertureMode](../../com.aspose.threed/aperturemode) - the camera's aperture mode
### getAspect() {#getAspect--}
```
public double getAspect()
```


Frustum का आस्पेक्ट रेशियो प्राप्त करता है

**Returns:**
double - फ़्रस्टम का आस्पेक्ट रेशियो
### getAspectRatio() {#getAspectRatio--}
```
public double getAspectRatio()
```


व्यू प्लेन का आस्पेक्ट रेशियो प्राप्त करता है।

**Returns:**
डबल - व्यू प्लेन का आस्पेक्ट रेशियो।
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getFarPlane() {#getFarPlane--}
```
public double getFarPlane()
```


Frustum की फार प्लेन दूरी प्राप्त करता है।

**Returns:**
double - फ़्रस्टम की दूरस्थ प्लेन दूरी।
### getFieldOfView() {#getFieldOfView--}
```
public double getFieldOfView()
```


कैमरा का फील्ड ऑफ व्यू डिग्री में प्राप्त करता है, यह प्रॉपर्टी केवल तब उपयोग की जाती है जब ApertureMode है [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) या [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL)

**Returns:**
डबल - कैमरा का फील्ड ऑफ व्यू डिग्री में, यह प्रॉपर्टी केवल तब उपयोग की जाती है जब ApertureMode है [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) या [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL)
### getFieldOfViewX() {#getFieldOfViewX--}
```
public double getFieldOfViewX()
```


कैमरा का हॉरिज़ॉन्टल फील्ड ऑफ व्यू डिग्री में प्राप्त करता है, यह प्रॉपर्टी केवल तब उपयोग की जाती है जब ApertureMode है [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)

**Returns:**
डबल - कैमरा का हॉरिज़ॉन्टल फील्ड ऑफ व्यू डिग्री में, यह प्रॉपर्टी केवल तब उपयोग की जाती है जब ApertureMode है [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)
### getFieldOfViewY() {#getFieldOfViewY--}
```
public double getFieldOfViewY()
```


कैमरा का वर्टिकल फील्ड ऑफ व्यू डिग्री में प्राप्त करता है, यह प्रॉपर्टी केवल तब उपयोग की जाती है जब ApertureMode है [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)

**Returns:**
डबल - कैमरा का वर्टिकल फील्ड ऑफ व्यू डिग्री में, यह प्रॉपर्टी केवल तब उपयोग की जाती है जब ApertureMode है [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)
### getHeight() {#getHeight--}
```
public double getHeight()
```


व्यू प्लेन की ऊँचाई इंच में प्राप्त करता है

**Returns:**
डबल - व्यू प्लेन की ऊँचाई इंच में।
### getLookAt() {#getLookAt--}
```
public Vector3 getLookAt()
```


कैमरा जिस रुचिकर स्थिति की ओर देख रहा है, उसे प्राप्त करता है।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the the interested position that the camera is looking at.
### getMagnification() {#getMagnification--}
```
public Vector2 getMagnification()
```


ऑर्थोग्राफिक कैमरा में उपयोग किए गए मैग्निफिकेशन को प्राप्त करता है

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the magnification used in orthographic camera
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
### getProjectionType() {#getProjectionType--}
```
public ProjectionType getProjectionType()
```


कैमरा की प्रोजेक्शन प्रकार प्राप्त करता है। डिफ़ॉल्ट रूप से पर्स्पेक्टिव प्रोजेक्शन उपयोग किया जाता है।

**Returns:**
[ProjectionType](../../com.aspose.threed/projectiontype) - the camera's projection type. By default the perspective projection is used.
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
### getWidth() {#getWidth--}
```
public double getWidth()
```


व्यू प्लेन की चौड़ाई इंच में प्राप्त करता है

**Returns:**
double - व्यू प्लेन की चौड़ाई इंच में मापी गई
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### moveForward(double distance) {#moveForward-double-}
```
public void moveForward(double distance)
```


कैमरा को उसकी दिशा या लक्ष्य की ओर आगे ले जाएँ।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| दूरी | double | आगे कितनी देर तक चलना है |

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
### setApertureMode(ApertureMode value) {#setApertureMode-com.aspose.threed.ApertureMode-}
```
public void setApertureMode(ApertureMode value)
```


कैमरा का एपर्चर मोड सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [ApertureMode](../../com.aspose.threed/aperturemode) | नया मान |

### setAspect(double value) {#setAspect-double-}
```
public void setAspect(double value)
```


फ्रस्टम का आस्पेक्ट रेशियो सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setAspectRatio(double value) {#setAspectRatio-double-}
```
public void setAspectRatio(double value)
```


व्यू प्लेन का आस्पेक्ट रेशियो सेट करता है।

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

### setFarPlane(double value) {#setFarPlane-double-}
```
public void setFarPlane(double value)
```


फ्रस्टम के दूरस्थ प्लेन की दूरी सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setFieldOfView(double value) {#setFieldOfView-double-}
```
public void setFieldOfView(double value)
```


कैमरा का फील्ड ऑफ व्यू डिग्री में सेट करता है, यह प्रॉपर्टी केवल तब उपयोग की जाती है जब ApertureMode है [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) या [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL)

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setFieldOfViewX(double value) {#setFieldOfViewX-double-}
```
public void setFieldOfViewX(double value)
```


कैमरा का हॉरिज़ॉन्टल फील्ड ऑफ व्यू डिग्री में सेट करता है, यह प्रॉपर्टी केवल तब उपयोग की जाती है जब ApertureMode है [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setFieldOfViewY(double value) {#setFieldOfViewY-double-}
```
public void setFieldOfViewY(double value)
```


कैमरा का वर्टिकल फील्ड ऑफ व्यू डिग्री में सेट करता है, यह प्रॉपर्टी केवल तब उपयोग की जाती है जब ApertureMode है [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


व्यू प्लेन की ऊँचाई इंच में सेट करता है

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

### setMagnification(Vector2 value) {#setMagnification-com.aspose.threed.Vector2-}
```
public void setMagnification(Vector2 value)
```


ऑर्थोग्राफिक कैमरा में उपयोग किए गए मैग्निफिकेशन को सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | नया मान |

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

### setProjectionType(ProjectionType value) {#setProjectionType-com.aspose.threed.ProjectionType-}
```
public void setProjectionType(ProjectionType value)
```


कैमरा की प्रोजेक्शन प्रकार सेट करता है। डिफ़ॉल्ट रूप से पर्स्पेक्टिव प्रोजेक्शन उपयोग किया जाता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [ProjectionType](../../com.aspose.threed/projectiontype) | नया मान |

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

### setRotationMode(RotationMode value) {#setRotationMode-com.aspose.threed.RotationMode-}
```
public void setRotationMode(RotationMode value)
```


फ़्रस्टम की ओरिएंटेशन मोड सेट करता है। यह प्रॉपर्टी केवल तब काम करती है जब [getTarget](../../com.aspose.threed/frustum\#getTarget) null हो। यदि मान [RotationMode.FIXED_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET) है, तो दिशा हमेशा प्रॉपर्टी [getLookAt](../../com.aspose.threed/frustum\#getLookAt) द्वारा गणना की जाती है। अन्यथा [getLookAt](../../com.aspose.threed/frustum\#getLookAt) हमेशा [getDirection](../../com.aspose.threed/frustum\#getDirection) द्वारा गणना की जाती है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [RotationMode](../../com.aspose.threed/rotationmode) | नया मान |

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

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


व्यू प्लेन की चौड़ाई इंच में सेट करता है

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| मान | double | नया मान |

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

