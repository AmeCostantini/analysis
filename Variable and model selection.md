#Variable selection.

* includerei sia previous che poutcome, ma sono indeciso.

* non includere duration, è la chiamata di chiusura.

* includerei effetto di interazione tra age e marital

* testeri effetto di interazione tra age e job

* testerei interazione tra loan e housing

* non testerei interazione tra job e education, le includerei tutte e due.

* month: la inserisco ma con riserva, vedi commenti all'analisi bivariata.

#Model selection

Io farei vincere il modello glm3, il binning senza uso di p.value. Posto che l'uso di p.value ha il problema di bonferroni, togliere variabili inutili non da vantaggi di errore standard (p.94 caffo) e che il numero di parametri non è enorme, e che la differenza di AUC è millesima, e che la AUCPR è superiore, io mi terrei il modello 3.
