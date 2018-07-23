---?image=https://rawgit.com/open-prevo/openprevo/master/doc/assets/img/logo.svg&size=contain&opacity=20

### Review #05
# OpenPrevo

---

### topics today

#### Aktueller Stand 
#### Verschlüsselung 
#### Diverse Verbesserungen
#### Ausblick letzter Sprint

---

### Aktueller Stand (1/2)

- Vorbereitete Ausgangslage für Dienstaustritt in PAKT

- Download des demo.zip auf meinen PC

- Anpassen der Configurationsdateien für den NodeBaloisePakt

+++

### Aktueller Stand (2/2)

- Durchführen Dienstaustritt in PAKT

- Match mit Diensteintritt Swisscanto

- Verschlüsselte Übermittlung der Zahlungsinformationen und automatische Auszahlung der FZL in PAKT

---

### Verschlüsselung

Hub kennt nur noch Ein- / Austrittsdatum und UID der VE.

AHV-Nummer verschlüsselt.

Zahlungsinformationen kann nur von der alten VE gelesen werden.

+++

### AHV-Nummer

Verlassen die VEs nur noch verschlüsselt (einwegs-Hash-Wert).

Die verschlüsselte AHV-Nummer ist für das Matching ausreichend.

Rückschlüsse nicht direkt möglich.

Beispiel: 
```
mJvKLoFIa7rFOm7joyRbcm0PNcZPXKv6ke4Kz3eTQAYYEqWEO/9yr2nW8IahN6fjgIRUFGIq/zG1U1vQfEzPWQ==
```
+++

### Zahlungsinformationen

Verlassen die VEs auch nur noch verschlüsselt.

Werden mit public-Key der alten VE verschlüsselt.

Nur von der alten VE lesbar.

Beispiel
```
uE6x2OljjvEXFclVzVYGYuBE6uUKyvmDAm2VlfYn/tw49v8Ip8Hz9tAjt7lKBIdXOSdA4E8tAaX5s+
WlFW1edWUe9/QT/15KTIIh0ZdF0amQHRxt3zfoGYHWJ4u6XU70vmam2vr8emQCOpDRgSHJyo6mDzdl
RQ5gvDpi/ihHBKrPwXJRpFScocf5I7BJhi7x/MhktqXLAJHRm+PjpOG0BP3ELn3ncfyK6XZTGkg0g3
95y7d9SXs25vwpB4X62rO0IqMkvFZy0Zb0mNOpSL4aJcKEHqfqDzzOO+rXNx/mp0k=
```

---

### Diverse Verbesserungen

Automatisches Testen Node - Hub - Node. (Real End-to-End)

Automatische Releases der Demo: [demo.zip](https://github.com/open-prevo/openprevo/releases)

---

### Ausblick letzte Sprint

