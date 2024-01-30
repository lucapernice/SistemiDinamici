# SistemiDinamici

Questo Jupyter notebook fa parte di un progetto per un corso su Sistemi Dinamici. Si concentra principalmente sulla Mappa Logistica, un'equazione differenziale non lineare spesso utilizzata nella scienza della complessità e nella biologia teorica per modellare la crescita della popolazione.

Il notebook è diviso in diverse sezioni:

1. **Iterazione delle Mappe**: La prima parte del notebook definisce una funzione per iterare la mappa logistica con un parametro specifico. I risultati delle iterazioni vengono poi rappresentati graficamente.

2. **Diagramma di Biforcazione**: La seconda parte modifica la funzione per accettare il parametro come input. Genera quindi un diagramma di biforcazione, che mostra i valori stabili della mappa logistica man mano che il parametro cambia.

3. **Periodicità**: La terza parte introduce una funzione per verificare se un dato array di numeri è periodico, e in caso affermativo, restituisce il periodo. Questo viene utilizzato per analizzare la periodicità delle iterazioni della mappa logistica.

4. **Numero di Feigenbaum**: L'ultima parte del notebook stima il numero di Feigenbaum, una costante matematica che appare nei diagrammi di biforcazione. Lo fa calcolando il rapporto delle differenze tra i punti di biforcazione successivi.

Il notebook utilizza Python e librerie come NumPy e Matplotlib per i calcoli e le visualizzazioni. 
