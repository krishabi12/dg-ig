<!--
  Schritt 7: Startseite eures IG
  Ersetzt die TODOs durch eigenen Text. Markdown ist erlaubt.
  Diese Seite ist die erste, die man auf GitHub Pages sieht.
-->

### Use Case

In einer Hausarztpraxis werden Arzneimittelallergien von Ärztinnen und Ärzten erfasst und dokumentiert. Bei einer späteren Behandlung in einer Notfallstation können diese Informationen abgerufen werden, um mögliche allergische Reaktionen auf Medikamente zu berücksichtigen und die Patientensicherheit zu erhöhen.

### Scope

Dieser Implementation Guide beschreibt die standardisierte Erfassung und den Austausch von Arzneimittelallergien auf Basis von HL7 FHIR R4 und CH Core. Er definiert Anforderungen an den klinischen Status, die Codierung, die Kritikalität, den Beginn der Allergie, die erfassende Person sowie die Dokumentation von Reaktionen.

Die Behandlung von Allergien und die Dokumentation von Allergien gegen Lebensmittel oder andere nichtmedikamentöse Stoffe gehören nicht zum Anwendungsbereich.

### Artefakte

* [DG Arzneimittelallergie](StructureDefinition-dg-medication-allergy.html): Dieses FHIR-Profil definiert die Anforderungen an die standardisierte Dokumentation von Arzneimittelallergien auf Basis von CH Core AllergyIntolerance.

* [Penicillinallergie bei Anna Muster](AllergyIntolerance-PenicillinAllergieAnna.html): Dieses Beispiel zeigt eine bestätigte Penicillinallergie bei einer fiktiven Patientin mit hoher Kritikalität und Urtikaria als dokumentierter Reaktion.


### Abhängigkeiten

Dieses IG baut auf [CH Core 6.0.0](https://fhir.ch/ig/ch-core/6.0.0/) auf.

### Autorin oder Autor

Abiramy Krishnakumar

<p style="font-size:smaller">Erstellt im Lab des Moduls Data Standards in Healthcare, ZHAW, HS26. Kein offizieller Standard.</p>
