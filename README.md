# DT224G - Laboration 2

Detta är en webbplats som handlar om mig, Isac Larsson. Den är skapad som en del av mina studier på webbutvecklingsprogrammet vid Mittuniversitetet. 


## Innehåll
- Introduktion av mig :smiley:
- Information om mitt intresse, bouldering :climbing:
- Kontaktinformation :email:

## Tekniker
Tekniker som använts i detta projekt är
- HTML
- CSS

## Besök webbplatsen
Sidan finns publicerad på [GitHub Pages](https://isla2401.github.io/dt224g-labb2/) och [Netlify](https://dt224g-labb2.netlify.app/).

---

## Svar på frågor

### 1. Vad är skillnaden mellan git add och git commit?
**Svar:** ``git add`` lägger till filen/filerna i *staging area* där de sedan är redo att committas. ``git commit`` sparar en "snapshot" (ögonblicksbild) av filerna i *staging area* till det lokala repositoryt. 

### 2. Varför använder man branches istället för att jobba direkt i main?
**Svar:** För att man vill kunna utveckla nya funktioner och fixa buggar utan att påverka resten av projektet. Det gör det även möjligt för flera personer att arbeta med olika delar av samma projekt utan att ändringarna krockar under utvecklingsprocessen. Dessutom är det lättare att felsöka och om något går snett så har man inte förstört den kod som redan fungerar.

### 3. Vad händer rent praktiskt när man gör en merge?
**Svar:** Merge betyder att man slår ihop två branches. Det innebär att ändringarna man gjort i en branch även görs i den branchen man slår ihop den med. Alltså, du ändrar kod i en branch, sedan mergar du den med t.ex. huvudbranchen (main) och då kombineras ändringarna med koden i main.

### 4. Vad är skillnaden mellan att pusha till GitHub och att publicera direkt på t.ex. Netlify?
**Svar:** När man pushar kod till GitHub så sparas koden och versionshistoriken i ett remote repository. Det betyder att din kod är lagrad på GitHub och finns tillgänglig på andra platser än bara din dator. För att sidan ska finnas på webben där andra människor kan besöka den så måste den publiceras. Det kan man göra med t.ex. Netlify eller GitHub Pages. Så alltså kan man säga att pusha till GitHub innebär att du lagrar koden och historiken i ett remote repository medan publicering med t.ex. Netlify gör att sidan blir tillgänglig via internet.

### 5. Om du vill exkludera någon fil i projektet från versionshanteringen, hur gör du då?
**Svar:** Man skapar en textfil som heter *.gitignore* i projektets rotmapp. I den listar man namnen på filerna man vill exkludera.
