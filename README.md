# Activitat: Crea una presentació interactiva sobre Markdown dins un README
## 🎯 Objectiu de l’activitat
En aquesta activitat et convertiràs en **presentador/a tècnic**. Crearàs una mena de *mini-presentació* visual i atractiva dins del fitxer `README.md`, com si haguessis de presentar Markdown a un públic que no el coneix.

Aprofitaràs totes les funcionalitats del Markdown per fer que el teu README sigui dinàmic, didàctic i professional. A més, afegiràs un element nou: **Badges** (insígnies) per mostrar versions, estat del projecte, o autor.

## Que has de fer?

Recorda, per crear el teu repositori:

 1. **NO marcar** "Add a README file".
 
 1. Clicar **Create repository**.
 
1. Convidar al col·laborador **`joanpardogine`** al teu repositori remot.

 1. Per clonar el repositori a la carpeta **`/c/projectes`** del teu ordinador.
 
 1. Copia l'enllaç que proporciona **GitHub** (**`https://github.com/<el-teu-usuari>/<PrimerCognomAlumne>-presentacio-markdown`**).

 1. Obre el terminal de **`Git Bash`** dins de VS Code.

 1. Escriure la següent comanda per anar a `C:\`:
       ```bash
       cd /c/projectes
       ```
 1. Clonar el repositori:
       <pre>git clone https://github.com/<b>&lt;el-teu-usuari></b>/<b>&lt;PrimerCognomAlumne></b>-presentacio-markdown</pre>
 1. Entra a la carpeta del projecte que acaba de crear el **`git clone`** que has fet:
       <pre>cd <b>&lt;PrimerCognomAlumne>-presentacio-markdown</b></pre>
 
## 📝 Descripció de l’activitat

Simularàs que has de fer una **introducció visual al Markdown** per una xerrada tècnica. El teu README serà com una *diapositiva interactiva* on expliques:

- Què és Markdown
- Per què s’utilitza
- Com s’escriu (amb exemples)
- Trucs visuals útils
- Taules, quotes, codis, enllaços i més

I ho faràs de forma creativa, com si estiguessis preparant una presentació per a un públic no expert.

## ✅ Passos a seguir

1. **Crea el repositori** amb el nom indicat.
2. Afegeix un `.gitignore` (pots utilitzar un de general).
3. Crea un fitxer `README.md` amb l’estructura següent:

### 🧩 Estructura recomanada

#### 1. **Portada**
- Títol gran (`#`)
- El teu nom i data
- Un o més **badges** (nova funcionalitat!)
  Els badges són imatges dinàmiques que mostren informació útil del projecte: versió, estat, autor, llicència, etc.  
  Exemple:
  ```markdown
  ![Status](https://img.shields.io/badge/estat-actiu-brightgreen)
  ![Autor](https://img.shields.io/badge/autor-TuNom-blue)
  
## Índex
- [Què és Markdown](#què-és-markdown)
- [Exemples de format](#exemples-de-format)
- [Trucs visuals](#trucs-visuals)
- [Taules i codis](#taules-i-codis)
- [Quotes i consells](#quotes-i-consells)
- [Recursos externs](#recursos-externs)
 
### 📝 Exemples de format

Aqui tens alguns dels formats bàsics més utilitzats a Markdown:

| Format | Sintaxi | Resultat |
|--------|---------|----------|
| Cursiva | `*Cursiva*` | *Cursiva* |
| Negreta | `**Negreta**` | **Negreta** |
| Codi en línia | `` `Codi en línia` `` | `Codi en línia` |

També pots combinar formats:
```markdown
**_Negreta i cursiva_**

## Temps de dedicació:

* 2 hores

## Lliurament

1. Comprova que el teu `README.md` sigui **entenedor** i estigui **ben estructurat**.
2. Comprova que hi hagi com a mínim **7 commits**, amb missatges **clars**.

## 📊 Criteris d’Avaluació

| Criteri                                                  | Punts |
|----------------------------------------------------------|-------|
| Claredat i estructura de les instruccions                | 2     |
| Dificultat i originalitat de la proposta                 | 2     |
| Ús correcte i complet del Markdown                       | 2     |
| Explicació d’un concepte nou (investigació pròpia)       | 2     |
| Organització del repositori i qualitat dels commits      | 2     |
| **Total**                                                | **10** |