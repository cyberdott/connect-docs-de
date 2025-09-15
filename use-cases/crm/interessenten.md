---
description: Synchronisierung von Interessenten aus dem Partnersystem in das ERP
---

# Interessenten

* **Intervall**: Standard: Täglich; maximal Stündlich / Echtzeit (via Webhook)
* **Richtung**: Partnersystem → ERP
* **Entitäten**:
  * [Interessenten](../../entitaeten/interessenten.md)

## Wie aktiviere ich die Übertragung von Interessenten aus meiner Partnerlösung ins ERP?

### Yuneo

Unter „Planung Arbeitsaufträge“ lässt sich ein Job eingerichtet, der in festem Intervall die Interessentendaten nach Yuneo importiert (Empfehlung = Job stündlich oder halbstündlich laufen lassen).

<figure><img src="../../.gitbook/assets/image (3) (1).png" alt=""><figcaption></figcaption></figure>

Alternativ kann dieser Job manuell unter **Interessenten** gestartet werden.

<figure><img src="../../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

Nachdem der Job gelaufen ist, findet sich der Interessent in der Maske „Angebote“. Diesen über **Doppelklick** oder den Button **Öffnen** öffnen.

<figure><img src="../../.gitbook/assets/image (5).png" alt=""><figcaption></figcaption></figure>

Im Angebot auf **Annehmen und Mietvertrag erstellen** klicken, damit nun automatisch der Mietvertrag angelegt wird.

<figure><img src="../../.gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

### Sigma

#### Datenabruf

Unter dem Modul „Vermarktung / Wohnungsvermittlung / Verarbeitung / Schnittstelle Immobilienbörsen / Interessenten Import“. Wie im untenstehenden Bild abgebildet, wählen Sie das Portal „XYZ“ aus. Abschließend klicken Sie in oberer Symbolleiste auf **Ausführen**.

<figure><img src="../../.gitbook/assets/image (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

#### Interessentenimport

Gehen Sie nun im Modulmenü links unter „Vermarktung / Wohnungsvermittlung / Stammdaten / Angebot“. Drücken Sie dort die **F6**-Taste (aktualisieren/suchen) Anschließend werden alle importierten Mieter angezeigt. Unter Datensatznavigation können Sie das/den entsprechende Angebot/Mieter auswählen/markieren.

<figure><img src="../../.gitbook/assets/image (1) (1) (1) (1) (1).png" alt=""><figcaption></figcaption></figure>

Anschließend den „Status“ auf „angenommen“ setzen und Speichern. Hinweis: Beim Import eines Geschäftspartners wird eine sogenannte Dubletten Prüfung durchgeführt. Das bedeutet, es wird überprüft, ob der Geschäftspartner bereits besteht, um eine fälschliche erneute Anlage zu verhindern. Standardmäßig wird nach Vorname, Nachname und Geburtsdatum geprüft. Dies kann aber auch geändert werden. Sprechen Sie uns dazu gerne an. Es ist wichtig zu wissen, dass die Überprüfung sensibel auf Leerzeichen reagiert.

<figure><img src="../../.gitbook/assets/image (2) (1).png" alt=""><figcaption></figcaption></figure>

## Beschreibung

Mit der Interessentenintegration können sie **neue Interessenten aus einem Partner System in ihr ERP übertragen**. Sollte ein neuer Interessent verfügbar sein wird dieser samt seiner verfügbaren Informationen wie z.B. Name, E-Mail und Telefonnummer übertragen.
