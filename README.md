Ecco il mio progetto per Moove.
Il sistema è stato suddiviso in tre entità principali, ciascuna definita da un’interfaccia e una relativa classe.
Le unità principali sono: 1) "IMezzo", che rappresenta un mezzo della flotta (bici, scooter o monopattino), con metodo assegnaUtente(). 
2) "IUtente", che rappresenta un utente registrato, con metodo prenotaMezzo()
3) "ICitta", che rappresenta una città in cui Moove è operativa, con metodo aggiungiMezzo()
Ogni mezzo può essere prenotato da un solo utente alla volta. Il suo stato passa da "disponibile" a "in uso".
Ogni utente può prenotare un mezzo, se disponibile, tramite il metodo "prenotaMezzo".
Ogni città può avere un numero qualsiasi di mezzi, aggiunti con "aggiungiMezzo".

Ecco il link al codice Codepen: https://codepen.io/Gabricos/pen/raaYvvW?editors=1111
