# Testi dei librogame

Qui vivono le revisioni pubblicate dei libri, e il manifesto che l'app legge all'apertura.

```
books/manifest.json
books/<id edizione>/v<versione>/librogame.xml
books/<id edizione>/v<versione>/items.xml
```

## Regole

**Una versione non si riscrive mai.** Una partita già cominciata resta legata alla versione con
cui è nata e continua a leggere quei file: cambiarli sotto di lei significa spostare il lettore in
un testo che non ha scelto. Una correzione, anche di una virgola, è una versione nuova.

**Ogni riga dichiara quale applicazione serve.** `minAppBuild` è il numero di build minimo,
`minAppVersion` la stessa cosa scritta per una persona. Il formato dei libri ha un vocabolario
chiuso: un'app che incontra una parola nata dopo di lei rifiuta il volume intero, e senza questa
riga chi ha l'app vecchia riceve un errore tecnico in mezzo allo scaricamento invece di un «non
ancora disponibile». Il numero si sceglie guardando qual è la parola più recente del formato che
quel volume usa.

**Il manifesto indica versioni precise, non «l'ultima».** Pubblicare è un gesto deliberato:
aggiungere i file non basta, la riga nel manifesto va scritta a mano. Un manifesto che puntasse al
ramo corrente farebbe arrivare a tutti, in un istante, qualunque cosa sia stata appena scritta.

**La fase sta nel libro**, nell'attributo `phase` di `<Librogame>`, e il manifesto la copia. Vale
`bozza`, `test` o `pubblico`, e ogni compilazione dell'app decide quali accetta: una bozza non
raggiunge un lettore per una svista nella configurazione della distribuzione.

**Titolo, autore e lingua stanno anche nel manifesto**, oltre che dentro il libro. Servono a
mostrare un volume prima di averlo scaricato: senza di essi lo scaffale dell'app saprebbe elencare
soltanto degli identificatori. Il campo `workId` tiene insieme le edizioni della stessa opera —
capitoli e traduzioni — e la `language` decide in quale scaffale il volume compare.

**Una lingua è un'edizione a sé**, con il proprio `id`, il proprio file e la propria riga nel
manifesto: chi legge in italiano non scarica il tedesco. Le traduzioni della stessa opera
condividono `workId` e devono avere la stessa struttura — stessi numeri di scena, stesse scelte,
stesse destinazioni — perché è la struttura, non il testo, a far funzionare i salvataggi.

**Le impronte sono obbligatorie.** L'app scarica, calcola lo sha256 e installa soltanto se
corrisponde: un file alterato lungo la strada non entra nella libreria.

## Questi file sono pubblici

Chiunque conosca l'indirizzo può scaricarli e leggere il testo del libro. È inevitabile: l'app li
prende senza credenziali, e qualunque cosa raggiungibile senza credenziali è pubblica. La `phase`
decide chi li **installa**, non chi può **leggerli**.
