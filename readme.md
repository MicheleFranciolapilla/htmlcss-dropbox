# RIPRODUZIONE DELLA HOME PAGE DROPBOX

---

### Strumenti utilizzati:
#### - Contenitori flessibili (*flexbox*)
#### - Posizionamenti flottanti (*float e clearfix*)
#### - Posizionamenti (*fixed, relative, absolute*)
#### - Animazioni (*@keyframes*)
#### - Transizioni di attributi (*transition*)
#### - Fogli di stile multipli
#### - Icone (*fontawesome*)

---

### Strutturazione della pagina:

**La pagina presenta una sezione `<header>` al cui interno sono posizionati la barra del menu, il titolo ed un blocco centrale. All'interno del `<nav>` (barra dei menu), posizionata con `position:fixed` sono presenti le voci del menu, il logo ed un pulsante, suddivisi in due raggruppamenti laterali. Il blocco centrale ha al suo interno del testo, un pulsante, un'immagine (sporgente al di fuori dell'area colorata dello header) ed alcune frecce (animate) che saltano alle sezioni successive. Il salto di sezione è eseguito in maniera rallentata (attributo `html{scroll-behavior: smooth}`).**
**La pagina prosegue con 4 `<section>` più il `<footer>`, tutti raggiungibili direttamente cliccando sulla relativa "freccia-link". Tutte le `<section>` sono allineate al centro della pagina mentre il `<footer>` è allineato con il blocco al centro dello `<header>`.**
**Nella prima sezione spicca un set di card (3) realizzate con l'utilizzo del *flexbox*.**
**La seconda sezione consiste in un contenitore *flexbox* con attributo `flex-wrap: wrap` i cui items sono cards costituite da immagini miste a testo.**
**Il fulcro della terza sezione è un contenitore *flexbox* con *main-axis orizzontale* ai cui lati (`<aside>`) sono presenti altri due *flexbox* (uno per ciascun `<aside>`) costituiti dai loghi dei partners ed al centro un contenitore con logo e testi. La caratteristica di questo contenitore è che, al ridimensionamento della viewport, i loghi negli `<aside>` devono mantenere la loro forma quadrata mentre nell'elemento centrale deve comparire, al bisogno, una scrollbar.**
**La quarta sezione è la sezione delle "FAQ", nella quale sono stati inserite transizioni ed animazioni al passaggio del mouse e al click.**
**Il footer presenta dei menu a colonna (*flexbox con main-axis verticale*) ed una casella di input di tipo `select`.**

---

### Bonus:

**Sono stati realizzati i seguenti bonus:**
1 Comparsa di un bordo sotto le voci di menu, (hover)
2 Schiarimento del background dei pulsanti blu (hover)
3 Schiarimento del testo dei pulsanti bianchi (hover)
4 Freccia di link alla prima sezione
5 Apertura di uno spazio "risposte" (hover) nella sezione FAQ

### Bonus extra:
1 Cinque frecce di link presenti nello `<header>`, ciascuna ad una sezione o al `<footer>`. Le frecce sono animate (`animation-iteration-count: infinite`).
2 Comparsa di un bordo (in hover) sui loghi dei partners e cambio di colore del logo stesso.
3 Reattività della sezione FAQ non solo al passaggio del mouse se non anche al click.
4 Input `select` nel footer ed input `radio` nella prima sezione.

