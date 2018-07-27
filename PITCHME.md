---?image=https://rawgit.com/open-prevo/openprevo/master/doc/assets/img/logo.svg&size=contain&opacity=20

### Review #06
# OpenPrevo
### 30.07.2018

---

### topics today

#### Kontext von OpenPrevo
#### Ziele des MVP
#### Demo MVP
#### OpenSource Vorgehen
#### Security and data protection
#### new this sprint
#### Ausblick

---

### Intro
# OpenPrevo

+++?image=bigPic.png&size=contain&color=white @title[Big Picture]
#### shared open-(source) platform

+++?image=mvpPic.png&size=contain&color=white @title[MVP]
#### minimal viable product (MVP)

+++?image=https://thecrmteam.com/wp-content/uploads/2018/03/MVP.png&size=contain

## Agile: step-by-step

---

### MVP
### business context

+++?image=https://rawgit.com/open-prevo/openprevo/master/doc/arc42/images/businessContext.svg

+++?image=https://rawgit.com/open-prevo/openprevo/master/doc/arc42/images/mvpBusinessContext.svg


---

## Die drei Ziele des MVP
### 1. MVP
- Excel → Excel
- Excel → PAKT
- PAKT → Excel
- PAKT → PAKT

+++

### 2. Demo
- einfache Demonstrierbarkeit
- ohne IT Skills

+++

### 3. 'P' im MVP
- P = produktivsetzungsfähig
- weitere Schritte sind dokumentiert
- muss noch nicht weltweit erreichbar sein

---

### Demo

- Demo läuft auf Prevo Laptop
- Teilnehmer sind Zurich, Helvetia und Basler
- Kompletter Durchlauf
- PAKT, Nodes und Hub laufen auf einem PC
- Validierung und Ergebnis in PAKT und Excel

+++

*Demo*

+++

![Video](https://www.youtube.com/embed/NvY_j6zk-zE)

---

## Resources

### [OpenPrevo @ Github](https://github.com/open-prevo)
### [Travis Build](https://travis-ci.org/open-prevo/openprevo)
### [Releases](https://github.com/open-prevo/openprevo/releases)
### [Gitter Chat](https://gitter.im/open-prevo/Lobby)
### [Slides](https://github.com/open-prevo/slides)

---

### Security and data protection

* Symmetric Encryption for data, AES 256
* Asymmetric Encryption for Key-Exchange, RSA
  * private and public-key
* Hashing AHV (SHA-512)
* Signing 
  * data integrity 

+++

### out-of-scope for MVP
- Authentication
- Transport-Layer Security (HTTPS)
- Public Key Registry

- Details in [arc42](https://open-prevo.github.io/openprevo/#_security_and_data_protection)
---

#### new this sprint

* Validate Input from adapter 
* Write notifications about bad input data to Excel
* Signing of capital transfer information
* Improve demo 
* Cleanup Code / Documentation

---

### Ausblick

- MVP ist zu Ende
- Produkt befindet sich auf GitHub
- Steering Committee tagt am 14.08.

---
### Questions?

<img src="https://staffino.com/blog/wp-content/uploads/2016/09/594042-2.jpg"/>
