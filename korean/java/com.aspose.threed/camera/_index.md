---
title: Camera
second_title: Aspose.3D for Java API 레퍼런스
description: 카메라는 장면을 바라보는 뷰어의 시점을 설명합니다.
type: docs
weight: 28
url: /ko/java/com.aspose.threed/camera/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject), [com.aspose.threed.Entity](../../com.aspose.threed/entity), [com.aspose.threed.Frustum](../../com.aspose.threed/frustum)

**All Implemented Interfaces:**
[com.aspose.threed.IOrientable](../../com.aspose.threed/iorientable)
```
public class Camera extends Frustum implements IOrientable
```

카메라는 장면을 바라보는 뷰어의 시점을 설명합니다.
## 생성자

| 생성자 | 설명 |
| --- | --- |
| [Camera()](#Camera--) | 새로운 [Camera](../../com.aspose.threed/camera) 클래스 인스턴스를 초기화합니다. |
| [Camera(ProjectionType projectionType)](#Camera-com.aspose.threed.ProjectionType-) | 새로운 [Camera](../../com.aspose.threed/camera) 클래스 인스턴스를 초기화합니다. |
| [Camera(String name)](#Camera-java.lang.String-) | 새로운 [Camera](../../com.aspose.threed/camera) 클래스 인스턴스를 초기화합니다. |
| [Camera(String name, ProjectionType projectionType)](#Camera-java.lang.String-com.aspose.threed.ProjectionType-) | 새로운 [Camera](../../com.aspose.threed/camera) 클래스 인스턴스를 초기화합니다. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | 속성을 찾습니다. |
| [getApertureMode()](#getApertureMode--) | 카메라의 조리개 모드를 가져옵니다 |
| [getAspect()](#getAspect--) | 프러스텀의 종횡비를 가져옵니다. |
| [getAspectRatio()](#getAspectRatio--) | 뷰 평면의 종횡비를 가져옵니다. |
| [getBoundingBox()](#getBoundingBox--) | 현재 엔터티의 객체 공간 좌표계에서 경계 상자를 가져옵니다. |
| [getClass()](#getClass--) |  |
| [getDirection()](#getDirection--) | 카메라가 바라보는 방향을 가져옵니다. |
| [getEntityRendererKey()](#getEntityRendererKey--) | 렌더러에 등록된 엔터티 렌더러의 키를 가져옵니다. |
| [getExcluded()](#getExcluded--) | 내보내기 중에 이 엔터티를 제외할지 여부를 가져옵니다. |
| [getFarPlane()](#getFarPlane--) | 프러스텀의 원거리 평면 거리를 가져옵니다. |
| [getFieldOfView()](#getFieldOfView--) | 카메라의 시야각을 도 단위로 가져옵니다, 이 속성은 ApertureMode가 [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) 또는 [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL)인 경우에만 사용됩니다 |
| [getFieldOfViewX()](#getFieldOfViewX--) | 카메라의 수평 시야각을 도 단위로 가져옵니다, 이 속성은 ApertureMode가 [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)인 경우에만 사용됩니다 |
| [getFieldOfViewY()](#getFieldOfViewY--) | 카메라의 수직 시야각을 도 단위로 가져옵니다, 이 속성은 ApertureMode가 [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)인 경우에만 사용됩니다 |
| [getHeight()](#getHeight--) | 뷰 평면의 높이를 인치 단위로 가져옵니다 |
| [getLookAt()](#getLookAt--) | 카메라가 바라보는 관심 위치를 가져옵니다. |
| [getMagnification()](#getMagnification--) | 정사영 카메라에서 사용되는 배율을 가져옵니다 |
| [getName()](#getName--) | 이름을 가져옵니다. |
| [getNearPlane()](#getNearPlane--) | 시야체적의 근접 평면 거리를 가져옵니다. |
| [getOrthoHeight()](#getOrthoHeight--) | 정사영 투영 시 시야체적의 높이를 가져옵니다. |
| [getParentNode()](#getParentNode--) | 첫 번째 상위 노드를 가져옵니다. 첫 번째 상위 노드를 설정하면 이 엔터티는 다른 상위 노드에서 분리됩니다. |
| [getParentNodes()](#getParentNodes--) | 모든 상위 노드를 가져옵니다. 엔터티는 기하학 인스턴싱을 위해 여러 상위 노드에 연결될 수 있습니다. |
| [getProjectionType()](#getProjectionType--) | 카메라의 투영 유형을 가져옵니다. |
| [getProperties()](#getProperties--) | 모든 속성의 컬렉션을 가져옵니다. |
| [getProperty(String property)](#getProperty-java.lang.String-) | 지정된 속성의 값을 가져옵니다 |
| [getRotationMode()](#getRotationMode--) | 시야체적의 방향 모드를 가져옵니다. 이 속성은 [getTarget](../../com.aspose.threed/frustum\#getTarget) 가 null인 경우에만 작동합니다. |
| [getScene()](#getScene--) | 이 객체가 속한 씬을 가져옵니다. |
| [getTarget()](#getTarget--) | 카메라가 바라보는 대상을 가져옵니다. |
| [getUp()](#getUp--) | 카메라의 위쪽 방향을 가져옵니다. |
| [getWidth()](#getWidth--) | 뷰 평면의 너비를 인치 단위로 가져옵니다 |
| [hashCode()](#hashCode--) |  |
| [moveForward(double distance)](#moveForward-double-) | 카메라를 전방으로 이동시켜 방향이나 목표를 향하게 합니다. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 동적 속성을 제거합니다. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 이름으로 식별되는 지정된 속성을 제거합니다. |
| [setApertureMode(ApertureMode value)](#setApertureMode-com.aspose.threed.ApertureMode-) | 카메라의 조리개 모드를 설정합니다 |
| [setAspect(double value)](#setAspect-double-) | 시야체적의 종횡비를 설정합니다. |
| [setAspectRatio(double value)](#setAspectRatio-double-) | 뷰 평면의 종횡비를 설정합니다. |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | 카메라가 바라보는 방향을 설정합니다. |
| [setExcluded(boolean value)](#setExcluded-boolean-) | 내보내기 중에 이 엔터티를 제외할지 여부를 설정합니다. |
| [setFarPlane(double value)](#setFarPlane-double-) | 시야체적의 원거리 평면 거리를 설정합니다. |
| [setFieldOfView(double value)](#setFieldOfView-double-) | 카메라의 시야각을 도 단위로 설정합니다, 이 속성은 ApertureMode가 [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) 또는 [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL)인 경우에만 사용됩니다 |
| [setFieldOfViewX(double value)](#setFieldOfViewX-double-) | 카메라의 수평 시야각을 도 단위로 설정합니다, 이 속성은 ApertureMode가 [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)인 경우에만 사용됩니다 |
| [setFieldOfViewY(double value)](#setFieldOfViewY-double-) | 카메라의 수직 시야각을 도 단위로 설정합니다, 이 속성은 ApertureMode가 [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)인 경우에만 사용됩니다 |
| [setHeight(double value)](#setHeight-double-) | 뷰 평면의 높이를 인치 단위로 설정합니다 |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | 카메라가 바라보는 관심 위치를 설정합니다. |
| [setMagnification(Vector2 value)](#setMagnification-com.aspose.threed.Vector2-) | 정사영 카메라에서 사용되는 배율을 설정합니다 |
| [setName(String value)](#setName-java.lang.String-) | 이름을 설정합니다. |
| [setNearPlane(double value)](#setNearPlane-double-) | 프러스텀의 근접 평면 거리를 설정합니다. |
| [setOrthoHeight(double value)](#setOrthoHeight-double-) | 프러스텀을 직교 투영으로 사용할 때 높이를 설정합니다. |
| [setParentNode(Node value)](#setParentNode-com.aspose.threed.Node-) | 첫 번째 상위 노드를 설정합니다. 첫 번째 상위 노드를 설정하면 이 엔터티는 다른 상위 노드에서 분리됩니다. |
| [setProjectionType(ProjectionType value)](#setProjectionType-com.aspose.threed.ProjectionType-) | 카메라의 투영 유형을 설정합니다. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 지정된 속성의 값을 설정합니다. |
| [setRotationMode(RotationMode value)](#setRotationMode-com.aspose.threed.RotationMode-) | 프러스텀의 방향 모드를 설정합니다. 이 속성은 [getTarget](../../com.aspose.threed/frustum\#getTarget)이 null인 경우에만 작동합니다. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | 카메라가 바라보는 대상을 설정합니다. |
| [setUp(Vector3 value)](#setUp-com.aspose.threed.Vector3-) | 카메라의 위쪽 방향을 설정합니다. |
| [setWidth(double value)](#setWidth-double-) | 뷰 평면의 너비를 인치 단위로 설정합니다 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Camera() {#Camera--}
```
public Camera()
```


새로운 [Camera](../../com.aspose.threed/camera) 클래스 인스턴스를 초기화합니다.

### Camera(ProjectionType projectionType) {#Camera-com.aspose.threed.ProjectionType-}
```
public Camera(ProjectionType projectionType)
```


새로운 [Camera](../../com.aspose.threed/camera) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| projectionType | [ProjectionType](../../com.aspose.threed/projectiontype) | 투영 유형. |

### Camera(String name) {#Camera-java.lang.String-}
```
public Camera(String name)
```


새로운 [Camera](../../com.aspose.threed/camera) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 이름. |

### Camera(String name, ProjectionType projectionType) {#Camera-java.lang.String-com.aspose.threed.ProjectionType-}
```
public Camera(String name, ProjectionType projectionType)
```


새로운 [Camera](../../com.aspose.threed/camera) 클래스 인스턴스를 초기화합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 이름 | java.lang.String | 이름. |
| projectionType | [ProjectionType](../../com.aspose.threed/projectiontype) | 투영 유형. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


속성을 찾습니다. 동적 속성 (Created by CreateDynamicProperty/SetProperty) 또는 네이티브 속성 (Identified by its name)일 수 있습니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| propertyName | java.lang.String | 속성 이름. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getApertureMode() {#getApertureMode--}
```
public ApertureMode getApertureMode()
```


카메라의 조리개 모드를 가져옵니다

**Returns:**
[ApertureMode](../../com.aspose.threed/aperturemode) - the camera's aperture mode
### getAspect() {#getAspect--}
```
public double getAspect()
```


프러스텀의 종횡비를 가져옵니다.

**Returns:**
double - 프러스텀의 종횡비
### getAspectRatio() {#getAspectRatio--}
```
public double getAspectRatio()
```


뷰 평면의 종횡비를 가져옵니다.

**Returns:**
double - 뷰 평면의 종횡비.
### getBoundingBox() {#getBoundingBox--}
```
public BoundingBox getBoundingBox()
```


현재 엔터티의 객체 공간 좌표계에서 경계 상자를 가져옵니다.

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


카메라가 바라보는 방향을 가져옵니다. 이 속성의 변경은 [getLookAt](../../com.aspose.threed/frustum\#getLookAt) 및 [getTarget](../../com.aspose.threed/frustum\#getTarget)에도 영향을 줍니다.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the direction that the camera is looking at. Changes on this property will also affects the [getLookAt](../../com.aspose.threed/frustum\#getLookAt) and [getTarget](../../com.aspose.threed/frustum\#getTarget).
### getEntityRendererKey() {#getEntityRendererKey--}
```
public EntityRendererKey getEntityRendererKey()
```


렌더러에 등록된 엔터티 렌더러의 키를 가져옵니다.

**Returns:**
[EntityRendererKey](../../com.aspose.threed/entityrendererkey) - the key of the entity renderer registered in the renderer
### getExcluded() {#getExcluded--}
```
public boolean getExcluded()
```


내보내기 중에 이 엔터티를 제외할지 여부를 가져옵니다.

**Returns:**
boolean - 내보내기 중에 이 엔터티를 제외할지 여부.
### getFarPlane() {#getFarPlane--}
```
public double getFarPlane()
```


프러스텀의 원거리 평면 거리를 가져옵니다.

**Returns:**
double - 프러스텀의 원거리 평면 거리.
### getFieldOfView() {#getFieldOfView--}
```
public double getFieldOfView()
```


카메라의 시야각을 도 단위로 가져옵니다, 이 속성은 ApertureMode가 [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) 또는 [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL)인 경우에만 사용됩니다

**Returns:**
double - 카메라의 시야각을 도 단위로, 이 속성은 ApertureMode가 [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) 또는 [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL)인 경우에만 사용됩니다
### getFieldOfViewX() {#getFieldOfViewX--}
```
public double getFieldOfViewX()
```


카메라의 수평 시야각을 도 단위로 가져옵니다, 이 속성은 ApertureMode가 [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)인 경우에만 사용됩니다

**Returns:**
double - 카메라의 수평 시야각을 도 단위로, 이 속성은 ApertureMode가 [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)인 경우에만 사용됩니다
### getFieldOfViewY() {#getFieldOfViewY--}
```
public double getFieldOfViewY()
```


카메라의 수직 시야각을 도 단위로 가져옵니다, 이 속성은 ApertureMode가 [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)인 경우에만 사용됩니다

**Returns:**
double - 카메라의 수직 시야각을 도 단위로, 이 속성은 ApertureMode가 [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)인 경우에만 사용됩니다
### getHeight() {#getHeight--}
```
public double getHeight()
```


뷰 평면의 높이를 인치 단위로 가져옵니다

**Returns:**
double - 뷰 평면의 높이를 인치 단위로
### getLookAt() {#getLookAt--}
```
public Vector3 getLookAt()
```


카메라가 바라보는 관심 위치를 가져옵니다.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the the interested position that the camera is looking at.
### getMagnification() {#getMagnification--}
```
public Vector2 getMagnification()
```


정사영 카메라에서 사용되는 배율을 가져옵니다

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the magnification used in orthographic camera
### getName() {#getName--}
```
public String getName()
```


이름을 가져옵니다.

**Returns:**
java.lang.String - 이름.
### getNearPlane() {#getNearPlane--}
```
public double getNearPlane()
```


시야체적의 근접 평면 거리를 가져옵니다.

**Returns:**
double - 프러스텀의 근접 평면 거리.
### getOrthoHeight() {#getOrthoHeight--}
```
public double getOrthoHeight()
```


정사영 투영 시 시야체적의 높이를 가져옵니다.

**Returns:**
double - 프러스텀을 직교 투영으로 사용할 때 높이.
### getParentNode() {#getParentNode--}
```
public Node getParentNode()
```


첫 번째 상위 노드를 가져옵니다. 첫 번째 상위 노드를 설정하면 이 엔터티는 다른 상위 노드에서 분리됩니다.

**Returns:**
[Node](../../com.aspose.threed/node) - the first parent node, if set the first parent node, this entity will be detached from other parent nodes.
### getParentNodes() {#getParentNodes--}
```
public ArrayList<Node> getParentNodes()
```


모든 상위 노드를 가져옵니다. 엔터티는 기하학 인스턴싱을 위해 여러 상위 노드에 연결될 수 있습니다.

**Returns:**
java.util.ArrayList<com.aspose.threed.Node> - 모든 부모 노드, 엔터티는 기하학 인스턴싱을 위해 여러 부모 노드에 연결될 수 있습니다
### getProjectionType() {#getProjectionType--}
```
public ProjectionType getProjectionType()
```


카메라의 투영 유형을 가져옵니다. 기본적으로 원근 투영이 사용됩니다.

**Returns:**
[ProjectionType](../../com.aspose.threed/projectiontype) - the camera's projection type. By default the perspective projection is used.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


모든 속성의 컬렉션을 가져옵니다.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


지정된 속성의 값을 가져옵니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 속성 | java.lang.String | 속성 이름 |

**Returns:**
java.lang.Object - 찾은 속성의 값
### getRotationMode() {#getRotationMode--}
```
public RotationMode getRotationMode()
```


프러스텀의 방향 모드를 가져옵니다. 이 속성은 [getTarget](../../com.aspose.threed/frustum\#getTarget)이 null인 경우에만 작동합니다. 값이 [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET)인 경우, 방향은 항상 [getLookAt](../../com.aspose.threed/frustum\#getLookAt) 속성에 의해 계산됩니다. 그렇지 않으면 [getLookAt](../../com.aspose.threed/frustum\#getLookAt)은 항상 [getDirection](../../com.aspose.threed/frustum\#getDirection)에 의해 계산됩니다.

**Returns:**
[RotationMode](../../com.aspose.threed/rotationmode) - the frustum's orientation mode This property only works when the [getTarget](../../com.aspose.threed/frustum\#getTarget) is null. If the value is [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET), the direction is always calculated by the property [getLookAt](../../com.aspose.threed/frustum\#getLookAt) Otherwise the [getLookAt](../../com.aspose.threed/frustum\#getLookAt) is always calculated by the [getDirection](../../com.aspose.threed/frustum\#getDirection)
### getScene() {#getScene--}
```
public Scene getScene()
```


이 객체가 속한 씬을 가져옵니다.

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getTarget() {#getTarget--}
```
public Node getTarget()
```


카메라가 바라보는 대상을 가져옵니다. 사용자가 이 속성을 지원하는 경우, [getLookAt](../../com.aspose.threed/frustum\#getLookAt) 속성보다 먼저 설정되어야 합니다.

**Returns:**
[Node](../../com.aspose.threed/node) - the target that the camera is looking at. If the user supports this property, it should be prior to [getLookAt](../../com.aspose.threed/frustum\#getLookAt) property.
### getUp() {#getUp--}
```
public Vector3 getUp()
```


카메라의 위쪽 방향을 가져옵니다.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the up direction of the camera
### getWidth() {#getWidth--}
```
public double getWidth()
```


뷰 평면의 너비를 인치 단위로 가져옵니다

**Returns:**
double - 인치 단위로 측정된 뷰 평면의 너비
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


카메라를 전방으로 이동시켜 방향이나 목표를 향하게 합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 거리 | double | 앞으로 이동할 거리 |

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


동적 속성을 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | 제거할 속성 |

**Returns:**
boolean - 속성이 성공적으로 제거되면 true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


이름으로 식별되는 지정된 속성을 제거합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 속성 | java.lang.String | 제거할 속성 |

**Returns:**
boolean - 속성이 성공적으로 제거되면 true
### setApertureMode(ApertureMode value) {#setApertureMode-com.aspose.threed.ApertureMode-}
```
public void setApertureMode(ApertureMode value)
```


카메라의 조리개 모드를 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ApertureMode](../../com.aspose.threed/aperturemode) | 새 값 |

### setAspect(double value) {#setAspect-double-}
```
public void setAspect(double value)
```


시야체적의 종횡비를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 |

### setAspectRatio(double value) {#setAspectRatio-double-}
```
public void setAspectRatio(double value)
```


뷰 평면의 종횡비를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 |

### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public void setDirection(Vector3 value)
```


카메라가 바라보는 방향을 설정합니다. 이 속성의 변경은 [getLookAt](../../com.aspose.threed/frustum\#getLookAt) 및 [getTarget](../../com.aspose.threed/frustum\#getTarget)에도 영향을 줍니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 새 값 |

### setExcluded(boolean value) {#setExcluded-boolean-}
```
public void setExcluded(boolean value)
```


내보내기 중에 이 엔터티를 제외할지 여부를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | boolean | 새 값 |

### setFarPlane(double value) {#setFarPlane-double-}
```
public void setFarPlane(double value)
```


시야체적의 원거리 평면 거리를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 |

### setFieldOfView(double value) {#setFieldOfView-double-}
```
public void setFieldOfView(double value)
```


카메라의 시야각을 도 단위로 설정합니다, 이 속성은 ApertureMode가 [ApertureMode.HORIZONTAL](../../com.aspose.threed/aperturemode\#HORIZONTAL) 또는 [ApertureMode.VERTICAL](../../com.aspose.threed/aperturemode\#VERTICAL)인 경우에만 사용됩니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 |

### setFieldOfViewX(double value) {#setFieldOfViewX-double-}
```
public void setFieldOfViewX(double value)
```


카메라의 수평 시야각을 도 단위로 설정합니다, 이 속성은 ApertureMode가 [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)인 경우에만 사용됩니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 |

### setFieldOfViewY(double value) {#setFieldOfViewY-double-}
```
public void setFieldOfViewY(double value)
```


카메라의 수직 시야각을 도 단위로 설정합니다, 이 속성은 ApertureMode가 [ApertureMode.HORIZ\_AND\_VERT](../../com.aspose.threed/aperturemode\#HORIZ-AND-VERT)인 경우에만 사용됩니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 |

### setHeight(double value) {#setHeight-double-}
```
public void setHeight(double value)
```


뷰 평면의 높이를 인치 단위로 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 |

### setLookAt(Vector3 value) {#setLookAt-com.aspose.threed.Vector3-}
```
public void setLookAt(Vector3 value)
```


카메라가 바라보는 관심 위치를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 새 값 |

### setMagnification(Vector2 value) {#setMagnification-com.aspose.threed.Vector2-}
```
public void setMagnification(Vector2 value)
```


정사영 카메라에서 사용되는 배율을 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | 새 값 |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


이름을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | java.lang.String | 새 값 |

### setNearPlane(double value) {#setNearPlane-double-}
```
public void setNearPlane(double value)
```


프러스텀의 근접 평면 거리를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 |

### setOrthoHeight(double value) {#setOrthoHeight-double-}
```
public void setOrthoHeight(double value)
```


프러스텀을 직교 투영으로 사용할 때 높이를 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 |

### setParentNode(Node value) {#setParentNode-com.aspose.threed.Node-}
```
public void setParentNode(Node value)
```


첫 번째 상위 노드를 설정합니다. 첫 번째 상위 노드를 설정하면 이 엔터티는 다른 상위 노드에서 분리됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | 새 값 |

### setProjectionType(ProjectionType value) {#setProjectionType-com.aspose.threed.ProjectionType-}
```
public void setProjectionType(ProjectionType value)
```


카메라의 투영 유형을 설정합니다. 기본적으로 원근 투영이 사용됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [ProjectionType](../../com.aspose.threed/projectiontype) | 새 값 |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


지정된 속성의 값을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 속성 | java.lang.String | 속성 이름 |
| 값 | java.lang.Object | 속성의 값 |

### setRotationMode(RotationMode value) {#setRotationMode-com.aspose.threed.RotationMode-}
```
public void setRotationMode(RotationMode value)
```


프러스텀의 방향 모드를 설정합니다. 이 속성은 [getTarget](../../com.aspose.threed/frustum\#getTarget)이 null인 경우에만 작동합니다. 값이 [RotationMode.FIXED\_TARGET](../../com.aspose.threed/rotationmode\#FIXED-TARGET)인 경우, 방향은 항상 [getLookAt](../../com.aspose.threed/frustum\#getLookAt) 속성에 의해 계산됩니다. 그렇지 않으면 [getLookAt](../../com.aspose.threed/frustum\#getLookAt)은 항상 [getDirection](../../com.aspose.threed/frustum\#getDirection)에 의해 계산됩니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [RotationMode](../../com.aspose.threed/rotationmode) | 새 값 |

### setTarget(Node value) {#setTarget-com.aspose.threed.Node-}
```
public void setTarget(Node value)
```


카메라가 바라보는 대상을 설정합니다. 사용자가 이 속성을 지원하는 경우, [getLookAt](../../com.aspose.threed/frustum\#getLookAt) 속성보다 먼저 설정해야 합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | 새 값 |

### setUp(Vector3 value) {#setUp-com.aspose.threed.Vector3-}
```
public void setUp(Vector3 value)
```


카메라의 위쪽 방향을 설정합니다.

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | 새 값 |

### setWidth(double value) {#setWidth-double-}
```
public void setWidth(double value)
```


뷰 평면의 너비를 인치 단위로 설정합니다

**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| 값 | double | 새 값 |

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
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

