![ipt](./images/ipt.png)
# Architekturdokumentation

## Qualitätsziele


| Qualitätskategorie      | Qualitätsziel        | Beschreibung        | Szenario     | Stakeholder                    |
|--------------|----------------|-----------------|--------------|--------------------------------|
| *Performance* | *Zeitverhalten* | *Der Benutzer erhält schnell Feedback auf seine ausgeführten Aktionen.* | *Szenario 1* | *Teamlead Fachbereich Einkauf* |


## Qualitätsszenarien

### User-Szenarien

Die Entscheidung, welche Daten geteilt werden, liegt beim Enduser.

Ein Zugriff auf andere Userdaten ist nicht ohne deren Einwilligung möglich.

Ein gemeldetes Datenleak / Issue muss innerhalb von 24h geschlossen sein.

Auf Userwunsch müssen Daten innerhalb von 24h gelöscht werden können.

Als Werbepartner kann ich mich selbstständig registrieren.

### Änderungs-Szenarien

Änderungen an bestehenden Systemen werden innerhalb von 6 Monaten nachgezogen.

### Ausfall-Szenarien

Bei einem Systemausfall ist das System in 98% der Fälle nach spätestens 30min wieder verfügbar.

Wenn ein User eine Strecke aufzeichnen möchte, ist dies in 99.99% der Fälle ohne Einschränkung möglich.

Wenn ein User offline ist, können Daten lokal gespeichert werden, bis wieder eine Verbindung zum Server besteht.

Bei einem Systemausfall greift ein Backup-System, es gehen maximal 24h an Daten verloren.





## Stakeholder

| Rolle                     | Kontakt | Relevanz | Erwartungshaltung                                            |
| ------------------------- | ------- | -------- | ------------------------------------------------------------ |
| *Wearable-Hersteller*     |         | Tief     | Gute Integration ihrer Produkte                              |
| *Werbepartner*            |         | Hoch     | Hohes Engagement<br />Conversion-Rate<br />Qualitative Daten<br /> |
| *User (free)*             |         | Mittel   | User Experience<br />Verfügbarkeit<br />Features<br />Social Networking |
| *User (premium)*          |         | Hoch     | Same as User<br />Mehr Features<br />Price/Value             |
| *Geldgeber*               |         | Hoch     | Wachstum oder Return on Investment                           |
| *Entwicklungsteam*        |         | Tief     | Spannendes Projekt<br />Coole Technologien                   |
| *Datenschutzbeauftragter* |         | Mittel   | Einhaltung der geltenden Rechte<br />Daten vor Zugriff schützen<br /> |
| *Datenkonsumenten*        |         | Tief     | Aussagekräftige Daten<br />viele User / repräsentativ        |



# Architekturentscheidungen

* [ADR-0000](./adr/0000-nygard-example.md) - Example Nygard
* [ADR-0001](./adr/0001-MADR-example.md) - Example MADR
* [ADR-0002](./adr/0002-Y-example.md) - Example Y


# Qualitätsanforderungen

## Qualitätsbaum

## Qualitätsszenarien
