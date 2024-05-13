

Gioco dei dadi
Il giocatore gioca contro il computer.
Generare un numero random da 1 a 6, sia per il giocatore sia per il computer.
Stabilire il vincitore, in base a chi fa il punteggio più alto.Mail

--------------------------------------------------------------------------------

Chiedi all’utente la sua email,
controlla che sia nella lista di chi può accedere,
stampa un messaggio appropriato sull’esito del controllo.Saltare a piè dispari [Bonus]

------------------------------------------------------------------------------------------

Crea un array vuoto. Chiedi per 6 volte all’utente di inserire un numero, se è pari inseriscilo nell’array.

----------------------------------------Svolgimento Gioco Dei Dadi------------------------------------------
 
 Creo una variabile NumUtente e NumBot le do il valore math random() *7 per generare un numero casuale da 1 a 6, poi creo un if else per capire quale valore è più alto e stampo hai vinto Utente se NumUtente è il più alto oppure stampo ha vinto il bot se è il contrario.

 -----------------------------------------------Svolgimento Mail---------------------------------------------------

 creo la variabile MailUtente che permette all'utente di inserire la propria mail, poi creo un array con delle mail, infine creo un if else per capire se la mail è presente nell array e quindi permettere l'accesso all'utente
 usando come condizione NomeArray.includes(Mail.Utente).

-----------------------------------------------------Pie Pari-------------------------------------------------------

Creo un array vuoto poi creo un ciclo for che si ripete 6 volte, dentro al ciclo for inserisco la variabile per permettere all utente di inserire i numeri e verificano se siano pari o dispari con un if else se sono pari li inserisco nell'array, dopo il ciclo for stampo l'array.