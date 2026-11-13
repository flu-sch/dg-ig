<!--
  Schritt 7: Startseite eures IG
  Diese Seite ist die erste, die man auf GitHub Pages sieht.
-->

### Use Case

In diesem Implementation Guide erfassen Hausarztpraxen Arzneimittelallergien strukturiert. So kann die Notfallstation im Ernstfall sofort sehen, welche Medikamente problematisch sind, und sicher reagieren.

### Scope

Das IG deckt die wichtigsten Angaben zu Arzneimittelallergien ab: den auslösenden Wirkstoff, die Gefährlichkeit (Kritikalität), den Beginn und bekannte Reaktionen. Nahrungsmittel- und Umweltallergien sowie allgemeine Unverträglichkeiten gehören nicht dazu.

### Artefakte

* [DG Arzneimittelallergie](StructureDefinition-dg-medication-allergy.html): Profil auf Basis von CH Core AllergyIntolerance, legt die Regeln für Arzneimittelallergien fest.
* Invariante dg-allergy-1: Eine bestätigte Allergie muss mindestens eine Reaktion dokumentieren.
* [Penicillin-Allergie bei Anna Muster](AllergyIntolerance-PenicillinAllergieAnna.html): Beispiel einer bestätigten Penicillin-Allergie mit Urtikaria.

### Abhängigkeiten

Dieses IG baut auf [CH Core 6.0.0](https://fhir.ch/ig/ch-core/6.0.0/) auf.

### Autor

Flurin Schmed

<p style="font-size:smaller">Erstellt im Lab des Moduls Data Standards in Healthcare, ZHAW, HS26. Kein offizieller Standard.</p>