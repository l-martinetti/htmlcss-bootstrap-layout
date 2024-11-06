Bootstrap Grid Layout
===

## Consegna

Riprodurre un layout con griglia responsive utilizzando Bootstrap 5! Aiutatevi con gli screenshot in allegato e le classi di Bootstrap per riprodurre il giusto layout a seconda dello spazio a disposizione sui diversi dispositivi

**Bonus**

Esercitarsi sulla centralizzazione
E’ possibile centralizzare in qualche punto il fatto che il testo sia bianco?

E’ possibile centralizzare il layout delle colonne di qualche riga utilizzando la classe row-cols?

## Mio approccio

Per prima cosa vedo che abbiamo una singola section che sarà il container, posso concentrarmi quindi sui singoli blocchi che saranno dei div con un titolo e del testo sotto.
Usando bootstrap parto dal viewport mobile e lo confronto con gli altri. 
le prime due colonne sono separate nel mobile, ma vicine nei viewport più grandi quindi darò dimensioni direttamente alle due colonne, nel mobile col-12, tablet col-6 e nel desktop la prima colonna col-4 e la seconta col-8.

Riguardo al secondo blocco, le tre colonne al centro, per il vieport mobile penso sia sufficiente dare delle dimensioni alle colonne con le prime due col-sm-6 e la terza col-sm-12, mentre per i viewport più grandi penso di lasciare delle semplici col, così dovrebbero disporsi in modo da occupare tutto lo spazio del container.

Per l'ultimo blocco le istruzioni le vado a mettere alla row, con un row-cols-2 per il mobile e row-cols-4 per i due viewport più grandi.

