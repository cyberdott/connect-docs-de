---
description: >-
  Mit QUIS treffen Sie datenbasierte Entscheidungen für langfristige
  Quartiersentwicklungen
---

# QUIS

## Übersicht

* **Kategorien**: [Valuation & Pricing​](../kategorien/valuation-and-pricing.md)
* **Use Cases**: [Stammdaten](../use-cases/allgemein/stammdaten.md)
* **Marketplace**: [Quis](https://marketplace.aareon.com/de/listings/quis)
* **API Dokumentation**: [Link](https://developer.quis.de/)

## Beschreibung

QUIS ist entstanden aus der Analyse & Konzepte Beratungsgesellschaft und nutzt seine über 25-jährige Erfahrung am Wohnungsmarkt und unzählige Standortgutachten für die Wohnungswirtschaft, um datengestützte Softwarelösungen (SaaS) für Standortbewertungen, Mieten- und Kaufpreisanalysen und prädikative Marktanalysen anzubieten. Unser webbasierter Service bietet täglich Insights zu mehr als 2,2 Millionen Wohnquartieren in Deutschland und über 500.000 Miet- und Kaufpreisen. Bei weiteren Fragen zur Anbindung melden Sie sich direkt bei QUIS.

## Mit QUIS verbinden

1.  Um einen QUIS-Use-Case zu nutzen benötigen Sie zur Aktivierung einen **QUIS API Key**. Diesen finden Sie folgendermaßen:

    1. Klicken Sie auf **Meine Marktdaten > API**
    2. Hier können Sie ihre **API-Keys** einsehen



    <figure><img src="../.gitbook/assets/image (1) (1) (1) (1) (1) (1) (1) (1) (1) (1) (1).png" alt="" width="563"><figcaption><p>QUIS API-Keys</p></figcaption></figure>
2. Nachdem Sie Aareon Connect Kunde geworden sind können Sie die verfügbaren **QUIS Integrationen innerhalb Ihres ERP-Systems** auswählen und aktivieren.

## Use Cases

### 1. Stammdaten

#### Übersicht

* [Allgemeine Informationen](../use-cases/allgemein/stammdaten.md)
* [Feld Mapping](https://docs.google.com/spreadsheets/d/1fLwCGcttemtlDpznO3O00352cZZ5SPJXBPv6IRWQ6Bk/edit?gid=1022321755#gid=1022321755)

#### Entitäten

| ERP                                  | QUIS    |
| ------------------------------------ | ------- |
| [Gebäude](../entitaeten/gebaeude.md) | Exposés |

#### Einstellungen

Im Zuge der Aktivierung des Stammdaten Use Cases, können Sie folgende Einstellungen nutzen:

<table><thead><tr><th width="165">Name</th><th width="450.33333333333326">Beschreibung</th><th>Optionen</th></tr></thead><tbody><tr><td>Separator für zusammengesetzte IDs</td><td>Dieser Separator wird genutzt um die IDs in dem Partner System aus den ERP Nummern zusammenzusetzen, sodass die IDs eindeutig sind.</td><td><code>-</code>, <code>_</code>, <code>.</code>, <code>/</code>, <code>|</code></td></tr><tr><td>Mandanten Nummern</td><td>Es werden nur Daten für die eingetragenen Mandanten synchronisiert.</td><td></td></tr></tbody></table>

#### Voraussetzungen

* Es werden nur Mieter mit einer hinterlegten E-Mail Adresse synchronisiert
  * Mietverträge von Mietern, die dies nicht erfüllen, werden ebenfalls nicht synchronisiert
