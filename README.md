# Operació NordTec Yelyzaveta Sadova ASIX1B
## Índex

- [Operació NordTec Yelyzaveta Sadova ASIX1B](#operació-nordtec-yelyzaveta-sadova-asix1b)
  - [Índex](#índex)
      - [Estat del projecte](#estat-del-projecte)
  - [Arquitectura de xarxa](#arquitectura-de-xarxa)
    - [Configuracions](#configuracions)
    - [1. Fitxer `.gitignore`](#1-fitxer-gitignore)
    - [2. Fitxer de configuració `.git/config`](#2-fitxer-de-configuració-gitconfig)
    - [3. Configuració de l'usuari](#3-configuració-de-lusuari)
  - [Incidències i solucions](#incidències-i-solucions)
    - [Incidència 1: La imatge no es mostra al document](#incidència-1-la-imatge-no-es-mostra-al-document)
  - [Reflexions tècniques](#reflexions-tècniques)
    - [Altres incidències](#altres-incidències)
#### Estat del projecte

**_Fet_**

* S'ha creat el document del projecte.

* S'ha creat l'índex amb enllaços als diferents apartats.

**_Pendent_**

* Completar l'arquitectura de xarxa.

* Afegir les configuracions i explicar els fitxers de configuració.

* Documentar les incidències i les seves solucions.

* Explicar les decisions tècniques.

* Escriure les reflexions tècniques.
## Arquitectura de xarxa

![Arquitectura de xarxa](./images/diagrama_xarxa.png)

### Configuracions

En aquest apartat s'expliquen els fitxers de configuració utilitzats per gestionar el projecte amb Git.

### 1. Fitxer `.gitignore`

- **Funció:** Indica quins fitxers o directoris Git ha d'ignorar i no ha de tenir en compte per al seguiment de canvis.
- **Ús:** Permet evitar que s'afegeixin al repositori fitxers temporals o informació que no cal compartir.

### 2. Fitxer de configuració `.git/config`

- **Funció:** Emmagatzema la configuració específica del repositori local.
- **Ús:** Pot contenir informació sobre el repositori remot, com ara `origin`, i altres opcions de configuració.

### 3. Configuració de l'usuari

Git permet configurar el nom i el correu electrònic que apareixen als commits mitjançant les ordres:

```bash
git config --global user.name "Nom Cognom"
git config --global user.email "correu@example.com"
```

Aquesta configuració s'utilitza per identificar l'autor dels commits.

## Incidències i solucions

### Incidència 1: La imatge no es mostra al document

- **Missatge d'error exacte:** La imatge no es mostra al document Markdown.
- **Quan:** Durant l'elaboració de l'apartat «Arquitectura de xarxa».
- **Causa:** La ruta de la imatge o la sintaxi Markdown podia ser incorrecta.
- **Solució:** S'ha revisat la sintaxi Markdown i s'ha comprovat que la ruta i el nom del fitxer coincideixin amb la ubicació real de la imatge.
- **Detectada per:** @lisapark9
- ## Decisions tècniques

- **Eina:** Git i GitHub per gestionar i guardar els canvis del projecte.
- **Format:** Markdown per organitzar la documentació amb títols, enllaços i imatges.
- **Alternatives:** GitLab o Bitbucket.

## Reflexions tècniques

He après a utilitzar Markdown i GitHub per documentar un projecte. He tingut dificultats per mostrar correctament les imatges i he après a revisar-ne les rutes.

### Altres incidències

Si sorgeixen altres problemes durant el projecte, es documentaran seguint la mateixa estructura.

:shipit::shipit::shipit::shipit::shipit::shipit::shipit::shipit::shipit::shipit::shipit::shipit::shipit::shipit::shipit::shipit::shipit::shipit::shipit::shipit::shipit::shipit::shipit:

