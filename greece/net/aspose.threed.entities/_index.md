---
title: "Aspose.ThreeD.Entities"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Όλη η γεωμετρία και οι οντότητες ορίζονται σε αυτόν τον χώρο ονομάτων."
type: docs
weight: 40
url: /el/net/aspose.threed.entities/
---
Όλη η γεωμετρία και οι οντότητες ορίζονται σε αυτόν τον χώρο ονομάτων.

## Κλάσεις

| Κλάση | Περιγραφή |
| --- | --- |
| [BooleanOperand](./booleanoperand/) | Αυτή η κλάση ενσωματώνει το μετασχηματισμένο mesh ως τελεστή της Boolean λειτουργίας. |
| [BooleanOperator](./booleanoperator/) | Ο Boolean operator σας επιτρέπει να εφαρμόσετε Boolean operation σε δύο [`IMeshConvertible`](../aspose.threed.entities/imeshconvertible/) στιγμιότυπα. |
| [Box](./box/) | Κουτί. |
| [Camera](./camera/) | Η camera περιγράφει το σημείο ματιού του θεατή που κοιτάζει τη σκηνή. |
| [Circle](./circle/) | Μια [`Circle`](../aspose.threed.entities/circle/) καμπύλη αποτελείται από ένα σύνολο σημείων στην άκρη του σχήματος του κύκλου. |
| [CompositeCurve](./compositecurve/) | Μια [`CompositeCurve`](../aspose.threed.entities/compositecurve/) αποτελείται από αρκετά τμήματα καμπύλης. |
| [Curve](./curve/) | Η βασική κλάση όλων των υλοποιήσεων curve. |
| [Cylinder](./cylinder/) | Παραμετρικός Κύλινδρος. Μπορεί επίσης να χρησιμοποιηθεί για την αναπαράσταση του κώνου όταν ένα από τα radiusTop/radiusBottom είναι μηδέν. |
| [Dish](./dish/) | Παραμετρική λεκάνη. |
| [Ellipse](./ellipse/) | Ένα [`Ellipse`](../aspose.threed.entities/ellipse/) ορίζει ένα σύνολο σημείων που σχηματίζουν το σχήμα της έλλειψης. |
| [Frustum](./frustum/) | Η βασική κλάση του [`Camera`](../aspose.threed.entities/camera/) και του [`Light`](../aspose.threed.entities/light/) |
| [Geometry](./geometry/) | Η βασική κλάση όλων των αναπαραγώσιμων γεωμετρικών αντικειμένων (όπως [`Mesh`](../aspose.threed.entities/mesh/), [`NurbsSurface`](../aspose.threed.entities/nurbssurface/), [`Patch`](../aspose.threed.entities/patch/) κ.λπ.). |
| [HalfSpace](./halfspace/) | [`HalfSpace`](../aspose.threed.entities/halfspace/) αντιπροσωπεύει έναν άπειρο χώρο που χωρίζεται από ένα επίπεδο, αυτό μπορεί να χρησιμοποιηθεί με [`BooleanOperator`](../aspose.threed.entities/booleanoperator/) |
| [Light](./light/) | Το φως φωτίζει τη σκηνή. |
| [Line](./line/) | Μια πολυγραμμή είναι μια διαδρομή που ορίζεται από ένα σύνολο σημείων με [`ControlPoints`](../aspose.threed.entities/geometry/controlpoints/), και συνδέεται από [`Segments`](../aspose.threed.entities/line/segments/), κάτι που σημαίνει ότι μπορεί επίσης να είναι ένα σύνολο συνδεδεμένων τμημάτων γραμμής. Η γραμμή είναι συνήθως ένα γραμμικό αντικείμενο, κάτι που σημαίνει ότι δεν μπορεί να χρησιμοποιηθεί για την αναπαράσταση μιας καμπύλης· για την αναπαράσταση μιας καμπύλης, χρησιμοποιεί το [`NurbsCurve`](../aspose.threed.entities/nurbscurve/). |
| [LinearExtrusion](./linearextrusion/) | Η γραμμική εξώθηση λαμβάνει ένα 2D σχήμα ως είσοδο και επεκτείνει το σχήμα στην τρίτη διάσταση. |
| [Mesh](./mesh/) | Ένα πλέγμα αποτελείται από πολλά n-πλευρά πολύγωνα. |
| [NurbsCurve](./nurbscurve/) | [Καμπύλη NURBS](https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline) είναι μια καμπύλη που αναπαρίσταται από NURBS(Non-uniform rational basis spline), μια καμπύλη NURBS ορίζεται από το [`Order`](../aspose.threed.entities/nurbscurve/order/), ένα σύνολο σταθμισμένων [`ControlPoints`](../aspose.threed.entities/geometry/controlpoints/) και ένα [`KnotVectors`](../aspose.threed.entities/nurbscurve/knotvectors/) Το συστατικό w στο σημείο ελέγχου χρησιμοποιείται ως βάρος του σημείου ελέγχου, ανεξαρτήτως του αν είναι TwoDimensional ή ThreeDimensional |
| [NurbsDirection](./nurbsdirection/) | Ένα 3D [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) έχει δύο κατευθύνσεις, το [`U`](../aspose.threed.entities/nurbssurface/u/) και το [`V`](../aspose.threed.entities/nurbssurface/v/), το [`NurbsDirection`](../aspose.threed.entities/nurbsdirection/) ορίζει δεδομένα για κάθε κατεύθυνση. Μια κατεύθυνση είναι στην πραγματικότητα μια καμπύλη NURBS, που σημαίνει ότι ορίζεται επίσης από το [`Order`](../aspose.threed.entities/nurbsdirection/order/), ένα [`KnotVectors`](../aspose.threed.entities/nurbsdirection/knotvectors/), και ένα σύνολο σταθμισμένων σημείων ελέγχου (ορισμένα στο [`NurbsSurface`](../aspose.threed.entities/nurbssurface/)). |
| [NurbsSurface](./nurbssurface/) | [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) είναι μια επιφάνεια που αναπαρίσταται από [NURBS(Non-uniform rational basis spline)](https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline), ένα [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) ορίζεται από δύο [`NurbsDirection`](../aspose.threed.entities/nurbsdirection/)[`U`](../aspose.threed.entities/nurbssurface/u/) και [`V`](../aspose.threed.entities/nurbssurface/v/). Το συστατικό w στο σημείο ελέγχου χρησιμοποιείται ως βάρος του σημείου ελέγχου, ανεξαρτήτως του αν ο τύπος της κατεύθυνσης είναι TwoDimensional ή ThreeDimensional |
| [Patch](./patch/) | Ένα [`Patch`](../aspose.threed.entities/patch/) είναι μια παραμετρική επιφάνεια μοντελοποίησης, παρόμοια με το [`NurbsSurface`](../aspose.threed.entities/nurbssurface/), ορίζεται επίσης από δύο [`PatchDirection`](../aspose.threed.entities/patchdirection/), το [`U`](../aspose.threed.entities/patch/u/) και το [`V`](../aspose.threed.entities/patch/v/). Αλλά η διαφορά μεταξύ του [`Patch`](../aspose.threed.entities/patch/) και του [`NurbsSurface`](../aspose.threed.entities/nurbssurface/) είναι ότι η καμπύλη [`PatchDirection`](../aspose.threed.entities/patchdirection/) μπορεί να είναι μία από τις Bezier, QuadraticBezier, BasisSpline, CardinalSpline και Linear |
| [PatchDirection](./patchdirection/) | Κατεύθυνση U και V του Patch. |
| [Plane](./plane/) | Παραμετρικώς ορισμένο επίπεδο. |
| [PointCloud](./pointcloud/) | Το σύννεφο σημείων δεν περιέχει πληροφορίες τοπολογίας, αλλά μόνο τα σημεία ελέγχου και τα στοιχεία κορυφών. |
| [PolygonBuilder](./polygonbuilder/) | Μια βοηθητική κλάση για τη δημιουργία πολύγωνου για το [`Mesh`](../aspose.threed.entities/mesh/) |
| [PolygonModifier](./polygonmodifier/) | Εργαλεία για την τροποποίηση πολύγωνων. |
| [Primitive](./primitive/) | Βασική κλάση για όλα τα primitives. |
| [Pyramid](./pyramid/) | Παραμετρική πυραμίδα. |
| [RectangularTorus](./rectangulartorus/) | Παραμετρικός ορθογώνιος δακτύλιος. |
| [RevolvedAreaSolid](./revolvedareasolid/) | Αυτή η κλάση αντιπροσωπεύει ένα στερεό μοντέλο περιστρέφοντας μια διατομή που παρέχεται από ένα προφίλ γύρω από έναν άξονα. |
| [Shape](./shape/) | Το σχήμα περιγράφει την παραμόρφωση σε ένα σύνολο σημείων ελέγχου, κάτι που είναι παρόμοιο με το cluster deformer στο Maya. Για παράδειγμα, μπορούμε να προσθέσουμε ένα σχήμα σε μια δημιουργημένη γεωμετρία. Και το σχήμα και η γεωμετρία έχουν τις ίδιες πληροφορίες τοπολογίας αλλά διαφορετική θέση των σημείων ελέγχου. Με διαφορετικά επίπεδα επιρροής, η γεωμετρία εκτελεί ένα εφέ παραμόρφωσης. |
| [Skeleton](./skeleton/) | Το [`Skeleton`](../aspose.threed.entities/skeleton/) χρησιμοποιείται κυρίως από λογισμικό CAD για να βοηθήσει τον σχεδιαστή να χειριστεί τον μετασχηματισμό της σκελετικής δομής, συνήθως δεν έχει χρησιμότητα εκτός των λογισμικών CAD. Για να λειτουργεί η ιεραρχία του σκελετού ως ένα αντικείμενο στο λογισμικό CAD, είναι απαραίτητο να σημειωθεί ο κορυφαίος κόμβος [`Skeleton`](../aspose.threed.entities/skeleton/) ως ριζικός, ορίζοντας το [`Type`](../aspose.threed.entities/skeleton/type/) σε Skeleton, και όλα τα παιδιά να οριστούν σε Bone |
| [Sphere](./sphere/) | Παραμετροποιημένη σφαίρα. |
| [SweptAreaSolid](./sweptareasolid/) | Ένα [`SweptAreaSolid`](../aspose.threed.entities/sweptareasolid/) δημιουργεί γεωμετρία σαρώντας ένα προφίλ κατά μήκος μιας γραμμής οδηγού. |
| [Torus](./torus/) | Παραμετροποιημένος δακτύλιος. |
| [TransformedCurve](./transformedcurve/) | Ένα [`TransformedCurve`](../aspose.threed.entities/transformedcurve/) δίνει σε μια καμπύλη θέση χρησιμοποιώντας έναν πίνακα μετασχηματισμού. Αυτό επιτρέπει την εκτέλεση μετασχηματισμού μέσα σε ένα [`TrimmedCurve`](../aspose.threed.entities/trimmedcurve/) ή [`CompositeCurve`](../aspose.threed.entities/compositecurve/). |
| [TriMesh](./trimesh/) | Ένα TriMesh περιέχει ακατέργαστα δεδομένα που μπορούν να χρησιμοποιηθούν απευθείας από την GPU. Αυτή η κλάση είναι ένα βοηθητικό εργαλείο για την κατασκευή ενός πλέγματος που περιέχει μόνο δεδομένα ανά κορυφή. |
| [TriMesh&lt;T&gt;](./trimesh-1/) | Γενική έκδοση του [`TriMesh`](../aspose.threed.entities/trimesh/) για τον στατικά ορισμένο τύπο κορυφής του χρήστη |
| [TrimmedCurve](./trimmedcurve/) | Μια περιορισμένη καμπύλη που περικόπτει την βασική καμπύλη και στα δύο άκρα. |
| [VertexElement](./vertexelement/) | Βασική κλάση των στοιχείων κορυφής. Ένας τύπος στοιχείου κορυφής προσδιορίζεται από το VertexElementType. Ένα VertexElement περιγράφει πώς το στοιχείο κορυφής αντιστοιχίζεται σε μια επιφάνεια γεωμετρίας και πώς οι πληροφορίες αντιστοίχισης διατάσσονται στη μνήμη. Ένα VertexElement περιέχει Normals, UVs ή άλλου είδους πληροφορίες. |
| [VertexElementBinormal](./vertexelementbinormal/) | Ορίζει τα διπλά διανύσματα για τα καθορισμένα στοιχεία. |
| [VertexElementDoublesTemplate](./vertexelementdoublestemplate/) | Μια βοηθητική κλάση για τον ορισμό συγκεκριμένων υλοποιήσεων του [`VertexElement`](../aspose.threed.entities/vertexelement/). |
| [VertexElementEdgeCrease](./vertexelementedgecrease/) | Ορίζει την τσαλακιά άκρη για τα καθορισμένα στοιχεία |
| [VertexElementHole](./vertexelementhole/) | Ορίζει αν το καθορισμένο πολύγωνο είναι τρύπα |
| [VertexElementIntsTemplate](./vertexelementintstemplate/) | Μια βοηθητική κλάση για τον ορισμό συγκεκριμένων υλοποιήσεων του [`VertexElement`](../aspose.threed.entities/vertexelement/). |
| [VertexElementMaterial](./vertexelementmaterial/) | Ορίζει το δείκτη υλικού για τα καθορισμένα στοιχεία. Ένας κόμβος μπορεί να έχει πολλαπλά υλικά, το [`VertexElementMaterial`](../aspose.threed.entities/vertexelementmaterial/) χρησιμοποιείται για την απόδοση διαφορετικών τμημάτων της γεωμετρίας σε διαφορετικά υλικά. |
| [VertexElementNormal](./vertexelementnormal/) | Ορίζει τα κανονικά διανύσματα για τα καθορισμένα στοιχεία. |
| [VertexElementPolygonGroup](./vertexelementpolygongroup/) | Ορίζει ομάδα πολύγωνων για τα καθορισμένα στοιχεία ώστε να ομαδοποιεί σχετικά πολύγωνα μαζί. |
| [VertexElementSmoothingGroup](./vertexelementsmoothinggroup/) | Μια ομάδα εξομάλυνσης είναι μια ομάδα πολυγώνων σε ένα πλέγμα πολυγώνων που πρέπει να εμφανίζεται ως μια ομαλή επιφάνεια. Ορισμένα πρώιμα λογισμικά 3D μοντελοποίησης όπως το 3D Studio Max για DOS χρησιμοποιούσαν την ομάδα εξομάλυνσης για να αποφύγουν την αποθήκευση του κανονικού διανύσματος για κάθε κορυφή του πλέγματος. |
| [VertexElementSpecular](./vertexelementspecular/) | Ορίζει το καθρεπτικό χρώμα για τα καθορισμένα στοιχεία. |
| [VertexElementTangent](./vertexelementtangent/) | Ορίζει τα εφαπτόμενα διανύσματα για τα καθορισμένα στοιχεία. |
| [VertexElementTemplate&lt;T&gt;](./vertexelementtemplate-1/) | Μια βοηθητική κλάση για τον ορισμό συγκεκριμένων υλοποιήσεων του [`VertexElement`](../aspose.threed.entities/vertexelement/). |
| [VertexElementUserData](./vertexelementuserdata/) | Ορίζει προσαρμοσμένα δεδομένα χρήστη για τα καθορισμένα στοιχεία. Συνήθως είναι δεδομένα ειδικά για την εφαρμογή για ειδικό σκοπό. |
| [VertexElementUV](./vertexelementuv/) | Ορίζει τις συντεταγμένες UV για τα καθορισμένα στοιχεία. Μια γεωμετρία μπορεί να έχει πολλαπλά στοιχεία [`VertexElementUV`](../aspose.threed.entities/vertexelementuv/), και το καθένα έχει διαφορετικά [`TextureMapping`](../aspose.threed.entities/texturemapping/)s. |
| [VertexElementVector4](./vertexelementvector4/) | Μια βοηθητική κλάση για τον ορισμό συγκεκριμένων υλοποιήσεων του [`VertexElement`](../aspose.threed.entities/vertexelement/). |
| [VertexElementVertexColor](./vertexelementvertexcolor/) | Ορίζει το χρώμα κορυφής για τα καθορισμένα στοιχεία |
| [VertexElementVertexCrease](./vertexelementvertexcrease/) | Ορίζει την τσαλακιά κορυφής για τα καθορισμένα στοιχεία |
| [VertexElementVisibility](./vertexelementvisibility/) | Ορίζει αν τα καθορισμένα στοιχεία είναι ορατά |
| [VertexElementWeight](./vertexelementweight/) | Ορίζει το βάρος ανάμειξης για τα καθορισμένα στοιχεία. |
## Structures

| Δομή | Περιγραφή |
| --- | --- |
| [EndPoint](./endpoint/) | Το σημείο λήξης για περικοπή της καμπύλης, μπορεί να είναι μια τιμή παραμέτρου ή ένα καρτεσιανό σημείο. |
## Διεπαφές

| Διεπαφή | Περιγραφή |
| --- | --- |
| [IIndexedVertexElement](./iindexedvertexelement/) | VertexElement με δεδομένα δεικτών. |
| [IMeshConvertible](./imeshconvertible/) | Οι οντότητες που υλοποίησαν αυτό το interface μπορούν να μετατραπούν σε [`Mesh`](../aspose.threed.entities/mesh/) |
| [IOrientable](./iorientable/) | Οι προσανατολίσιμες οντότητες πρέπει να υλοποιήσουν αυτό το interface. |
## Απαρίθμηση

| Απαρίθμηση | Περιγραφή |
| --- | --- |
| [ApertureMode](./aperturemode/) | Λειτουργίες διαφράγματος κάμερας. Η λειτουργία διαφράγματος καθορίζει ποιες τιμές ελέγχουν το διάφραγμα της κάμερας. Εάν η λειτουργία διαφράγματος είναι HorizAndVert, Horizontal ή Vertical, τότε χρησιμοποιείται το πεδίο θέασης. Εάν η λειτουργία διαφράγματος είναι FocalLength, τότε χρησιμοποιείται το εστιακό μήκος. |
| [BooleanOperation](./booleanoperation/) | Λογική λειτουργία του Mesh |
| [CurveDimension](./curvedimension/) | Η διάσταση των καμπύλων. |
| [LightType](./lighttype/) | Τύποι φωτός. |
| [MappingMode](./mappingmode/) | Καθορίζει πώς το στοιχείο αντιστοιχίζεται σε μια επιφάνεια. Το [`MappingMode`](../aspose.threed.entities/mappingmode/) ορίζει πώς το [`VertexElement`](../aspose.threed.entities/vertexelement/) αντιστοιχίζεται στην επιφάνεια της γεωμετρίας. |
| [NurbsType](./nurbstype/) | Τύποι NURBS. |
| [PatchDirectionType](./patchdirectiontype/) | Τύποι κατεύθυνσης patch. |
| [ProjectionType](./projectiontype/) | Τύποι προβολής της κάμερας. |
| [ReferenceMode](./referencemode/) | `[ReferenceMode`](../aspose.threed.entities/referencemode/) ορίζει πώς αποθηκεύονται και αναφέρονται οι πληροφορίες αντιστοίχισης. |
| [RotationMode](./rotationmode/) | Η λειτουργία περιστροφής του frustum |
| [SkeletonType](./skeletontype/) | `[Skeleton](../aspose.threed.entities/skeleton/)'s τύποι. |
| [SplitMeshPolicy](./splitmeshpolicy/) | Κοινή χρήση δεδομένων κορυφής/σημείου ελέγχου μεταξύ sub-meshes ή κάθε sub-mesh έχει τα δικά του συμπιεσμένα δεδομένα. |
| [TextureMapping](./texturemapping/) | Ο τύπος αντιστοίχισης υφής για το [`VertexElementUV`](../aspose.threed.entities/vertexelementuv/) περιγράφει ποιος τύπος αντιστοίχισης υφής χρησιμοποιείται. |
| [VertexElementType](./vertexelementtype/) | Ο τύπος του στοιχείου κορυφής, ορίζει πώς θα χρησιμοποιηθεί στην μοντελοποίηση. |


