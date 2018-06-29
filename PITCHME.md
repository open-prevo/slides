---?image=https://www.prevo.ch/images/prevo/prevo-logo.svg&size=contain

### Review #02
# Open

---

### topics today

#### OpenPrevo Node v0
#### OpenPrevo Hub v0
#### PAKT integration
#### License change
#### Naming / Glossary

---

### OpenPrevo Node v0

Provide REST Endpoints for: 

* Job-Start 
* Job-End
* Match Notification 

Consumes static data for the moment.

+++

### Demo

Start two different node instances: 

``` bash
 ./gradlew clean build
 cd docker
 docker-compose up --build ve_node pakt_node
```
They're configured to serve pre-defined static data.

---

### OpenPrevo Hub v0

Provides a list of hard-coded nodes. 
Consume insurant data from nodes. 
Execute simple matching based on OASI number. 
Notify nodes for a given match.  
 
+++

### Demo

Start the hub and verify the matching:

``` bash
 ./gradlew clean build
 cd docker
 docker-compose up --build hub
```
Should match have two matches.

---

### PAKT integration

+++

### details

---

### [License change](https://github.com/open-prevo/openprevo/issues/5)

Change from MIT to EPL-2.0 + GPL

Business friendly license

EPL is weak copyleft

Secondary license: GPL with strong copyleft

idea: choose for best fit

+++

### details

[EPL-2.0 license](https://www.eclipse.org/legal/epl-2.0/)

[License header](https://github.com/open-prevo/openprevo/blob/master/build.gradle) in **each** file

---

### Naming / Glossary

primary language is english

idea: no swiss primary language has a lead

[glossary](https://open-prevo.github.io/openprevo/#section-glossary) covers 4 languages: en, de, fr, it

acronyms where applicable in english

+++

### details

please review / comment!

add issues / pull requests!
