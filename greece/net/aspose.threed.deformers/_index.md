---
title: "Aspose.ThreeD.Deformers"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Όλες οι κλάσεις deformer ορίζονται σε αυτόν τον χώρο ονομάτων"
type: docs
weight: 30
url: /el/net/aspose.threed.deformers/
---
Όλες οι κλάσεις deformer ορίζονται σε αυτόν τον χώρο ονομάτων

## Κλάσεις

| Κλάση | Περιγραφή |
| --- | --- |
| [Bone](./bone/) | Ένα οστό ορίζει το υποσύνολο των σημείων ελέγχου της γεωμετρίας και καθορίζει το βάρος ανάμειξης για κάθε σημείο ελέγχου. Το αντικείμενο [`Bone`](../aspose.threed.deformers/bone/) δεν μπορεί να χρησιμοποιηθεί άμεσα, μια παρουσία [`SkinDeformer`](../aspose.threed.deformers/skindeformer/) χρησιμοποιείται για την παραμόρφωση της γεωμετρίας, και το [`SkinDeformer`](../aspose.threed.deformers/skindeformer/) έρχεται με ένα σύνολο οστών, κάθε οστό συνδεδεμένο με έναν κόμβο. ΣΗΜΕΙΩΣΗ: Ένα σημείο ελέγχου μιας γεωμετρίας μπορεί να δεσμευτεί σε περισσότερα από ένα οστά. |
| [Deformer](./deformer/) | Βασική κλάση για το [`SkinDeformer`](../aspose.threed.deformers/skindeformer/) και το [`MorphTargetDeformer`](../aspose.threed.deformers/morphtargetdeformer/) |
| [MorphTargetChannel](./morphtargetchannel/) | Ένα MorphTargetChannel χρησιμοποιείται από το [`MorphTargetDeformer`](../aspose.threed.deformers/morphtargetdeformer/) για την οργάνωση των γεωμετριών-στόχων. Ορισμένες μορφές αρχείων όπως το FBX υποστηρίζουν πολλαπλά κανάλια παράλληλα. |
| [MorphTargetDeformer](./morphtargetdeformer/) | Το MorphTargetDeformer παρέχει animation ανά κορυφή. Το MorphTargetDeformer οργανώνει όλους τους στόχους μέσω του [`MorphTargetChannel`](../aspose.threed.deformers/morphtargetchannel/), κάθε κανάλι μπορεί να οργανώσει πολλαπλούς στόχους. Μία κοινή χρήση του morph target deformer είναι η εφαρμογή εκφράσεων προσώπου σε έναν χαρακτήρα. Περισσότερες λεπτομέρειες μπορούν να βρεθούν στο https://en.wikipedia.org/wiki/Morph_target_animation |
| [SkinDeformer](./skindeformer/) | Ένας skin deformer περιέχει πολλαπλά οστά για λειτουργία, κάθε οστό συνδυάζει ένα μέρος της γεωμετρίας βάσει των βαρών των σημείων ελέγχου. |
## Απαρίθμηση

| Απαρίθμηση | Περιγραφή |
| --- | --- |
| [BoneLinkMode](./bonelinkmode/) | Η λειτουργία σύνδεσης ενός οστού αναφέρεται στον τρόπο με τον οποίο ένα οστό συνδέεται ή συνδέεται με το γονικό του οστό μέσα σε μια ιεραρχική δομή. |


