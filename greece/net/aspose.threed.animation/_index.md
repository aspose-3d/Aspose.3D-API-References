---
title: "Aspose.ThreeD.Animation"
second_title: "Αναφορά API Aspose.3D για .NET"
description: "Ο χώρος ονομάτων animation του Aspose.3D, όλες οι κλάσεις σχετικές με animation ορίζονται σε αυτόν τον χώρο ονομάτων"
type: docs
weight: 20
url: /el/net/aspose.threed.animation/
---
Ο χώρος ονομάτων animation του Aspose.3D, όλες οι κλάσεις που σχετίζονται με την κίνηση ορίζονται σε αυτόν τον χώρο ονομάτων

## Κλάσεις

| Κλάση | Περιγραφή |
| --- | --- |
| [AnimationChannel](./animationchannel/) | Ένα κανάλι αντιστοιχίζει το πεδίο συνιστώσας της ιδιότητας σε ένα σύνολο ακολουθιών keyframe |
| [AnimationClip](./animationclip/) | Το κλιπ Animation είναι μια συλλογή από animations. Η σκηνή μπορεί να έχει ένα ή περισσότερα κλιπ animation. |
| [AnimationNode](./animationnode/) | Το Aspose.3D υποστηρίζει ιεραρχία animation, κάθε animation μπορεί να αποτελείται από πολλά animations και τον ορισμό key-frame του animation. [`AnimationNode`](../aspose.threed.animation/animationnode/) ορίζει τη μετασχηματισμό μιας τιμής ιδιότητας με την πάροδο του χρόνου, για παράδειγμα, το animation node μπορεί να χρησιμοποιηθεί για να ελέγξει τον μετασχηματισμό ενός κόμβου ή άλλες αριθμητικές ιδιότητες του [`A3DObject`](../aspose.threed/a3dobject/). |
| [BindPoint](./bindpoint/) | Ένα [`BindPoint`](../aspose.threed.animation/bindpoint/) συνήθως δημιουργείται σε μια ιδιότητα αντικειμένου, ορισμένοι τύποι ιδιοτήτων περιέχουν πολλαπλά πεδία συνιστωσών (όπως ένα πεδίο Vector3), το [`BindPoint`](../aspose.threed.animation/bindpoint/) θα δημιουργήσει κανάλι για κάθε πεδίο συνιστωσών και θα συνδέσει το πεδίο με μία ή περισσότερες εμφανίσεις ακολουθίας keyframe μέσω των καναλιών. |
| [Extrapolation](./extrapolation/) | Η εξώθηση (Extrapolation) ορίζει τι γίνεται όταν η δειγματοληπτική τιμή βρίσκεται εκτός του εύρους που ορίζεται από τα πρώτα και τα τελευταία key-frames. |
| [KeyFrame](./keyframe/) | Ένα key frame ορίζεται κυρίως από χρόνο και τιμή, για ορισμένους τύπους παρεμβολής, τα tangent/tension/bias/continuity χρησιμοποιούνται επίσης για τον υπολογισμό της τελικής δειγματοληπτικής τιμής. Οι δειγματοληπτικές τιμές σε θέση χρόνου που δεν είναι key-frame παρεμβάλλονται από τα key-frames μεταξύ του προηγούμενου και του επόμενου key-frame. Οι τιμές πριν/μετά το πρώτο/τελευταίο key-frame υπολογίζονται από την κλάση [`Extrapolation`](../aspose.threed.animation/extrapolation/). |
| [KeyframeSequence](./keyframesequence/) | Η ακολουθία των key-frames, περιγράφει τη μετασχηματισμό μιας δειγματοληπτικής τιμής με την πάροδο του χρόνου. |
## Απαρίθμηση

| Απαρίθμηση | Περιγραφή |
| --- | --- |
| [ExtrapolationType](./extrapolationtype/) | Τύπος Extrapolation. |
| [Interpolation](./interpolation/) | Ο τύπος παρεμβολής του βασικού πλαισίου. |
| [StepMode](./stepmode/) | Λειτουργία βήματος παρεμβολής. |
| [WeightedMode](./weightedmode/) | Λειτουργία βαρών. |


