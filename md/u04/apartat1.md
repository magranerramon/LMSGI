# Introducció

En aquest capítol anem a estudiar conceptes relacionats amb XML (eXtensible markup language), llenguatge que que serveix com a format d'emmagatzemament i intercanvi d'informació. Estudiarem la seua estructura i sintaxi, les instruccions de processament, marques, elements i atributs, així com altres aspectes importants. 

A més, verificarem que un XML està escrit de manera correcta i si el podem considerar vàlid, ja que la validació comprova que un document XML està ben format i que s'ajudta a les regles establertes en la DTD (Document Type Definition) o XSD (XML schema definition).

XML deriva de SGML (standard generalized markup language), el que fa que siga llegible i comprensible per a qualsevol usuari i, a diferència d'HTML, les marques de XML transmeten significat al contingut que emmagatzema. 

<figure markdown="span">

``` mermaid
graph TB
  A[SGML] --> B[XML];
  B[XML] --> D[XHTML]
  A[SGML] --> C[HTML];

```
<figcaption>Figura 4.1. Jerarquia SGML</figcaption>
</figure>




