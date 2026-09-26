# Privacy Policy – Paths of Inks

**Ultimo aggiornamento: 27 settembre 2026**

Titolare del trattamento: Emanuele Sinagra (sviluppatore indipendente), contattabile all'indirizzo email indicato al punto 8.

## 1. Introduzione

Paths of Inks è un'app per leggere librogame (libri-gioco a bivi, "choose your own adventure"). Questa informativa descrive quali dati vengono trattati, come vengono utilizzati e quali diritti ha l'utente, in conformità al Regolamento (UE) 2016/679 ("GDPR").

In sintesi: **Paths of Inks non richiede la creazione di un account e non raccoglie dati che ti identifichino**. Lettura, salvataggi e tutte le funzionalità di gioco funzionano interamente offline. L'accesso alla rete serve a tre cose: **completare gli acquisti tramite Google Play**, **scaricare i librogame e le loro revisioni**, e — solo se decidi di farlo — **mandare il voto in stelle che dai a un libro**, che è anonimo e si somma a quelli degli altri lettori. Le condizioni d'uso dell'app sono descritte nei [Termini e Condizioni](terms_it.md).

## 2. Dati trattati

### 2.1 Dati creati dall'utente e conservati sul dispositivo

- **Profili di gioco**: nome del personaggio scelto dall'utente, caratteristiche, abilità, punti vita, inventario ed equipaggiamento.
- **Progressi narrativi**: pagina corrente, scelte compiute, flag e variabili della storia, checkpoint di combattimento.
- **Preferenze dell'app**: tema, font, dimensione del testo, lingua dell'interfaccia, ultimo profilo e libro utilizzati.
- **Libri presenti in libreria**: i file XML dei librogame (`librogame.xml` e `items.xml`) scaricati, inclusi nell'app o importati dall'utente.
- **Il tuo voto per ciascun libro**, conservato anche sul telefono perché l'app ti mostri quello che hai dato.

Tutti questi dati sono salvati **nella memoria privata dell'app sul dispositivo dell'utente**. L'unico che lascia il dispositivo è il voto in stelle, e solo come descritto al punto 2.4.

### 2.2 Dati raccolti tramite servizi di terze parti

L'app non integra **alcun servizio di autenticazione, analytics, crash reporting o pubblicità**.

Per la vendita di libri o contenuti aggiuntivi l'app usa **Google Play Billing**. Gli acquisti sono gestiti interamente da Google Play secondo la [propria informativa privacy](https://policies.google.com/privacy): il Fornitore riceve soltanto un token di acquisto anonimo che conferma il diritto al contenuto e **non riceve né conserva alcun dato di pagamento** (numero di carta, indirizzo di fatturazione, intestatario).

### 2.3 Download dei libri e delle loro revisioni

L'app scarica i librogame, e le loro revisioni più recenti, da un **deposito riservato ospitato su GitHub**. La richiesta è una lettura di file, fatta con una chiave uguale per tutte le copie dell'app: **non contiene alcun dato dell'utente**, né identificatori, né informazioni sulla partita in corso.

Come per qualunque richiesta web, il fornitore dell'infrastruttura (GitHub, Inc.) può registrare nei propri log tecnici l'indirizzo IP e il tipo di applicazione che effettua la richiesta, secondo la [propria informativa](https://docs.github.com/site-policy/privacy-policies/github-privacy-statement). Il Fornitore non ha accesso a quei log.

Il download non è necessario per giocare: senza rete l'app continua a funzionare con i testi già presenti sul dispositivo, e le partite già cominciate restano comunque sulla versione del testo con cui sono nate.

### 2.4 Voto in stelle dei libri

Puoi dare a un libro da una a cinque stelle. Il voto parte **solo quando tocchi le stelle**: se non voti, non viene mandato niente.

Quando voti, l'app invia:

- **quale libro** stai votando (l'identificativo dell'opera, uguale in tutte le lingue);
- **quante stelle** gli dai, da 1 a 5;
- un **identificativo casuale dell'installazione**, che l'app genera da sé la prima volta che voti e conserva sul telefono. Serve soltanto a far sì che lo stesso telefono conti una volta sola per ogni libro: se cambi voto, il nuovo sostituisce il vecchio invece di aggiungersi.

Quell'identificativo **non è collegato al tuo nome, alla tua email, al tuo account Google né ad alcun dato che ti riguardi**, e non viene usato per nient'altro. Se disinstalli l'app l'identificativo sparisce con lei, e da quel momento nessuno — nemmeno il Fornitore — può più ricondurre i voti già dati al tuo telefono.

Dei voti si mostrano agli altri lettori **soltanto la media e il numero**: nessuno può vedere chi ha votato che cosa, né quanti libri ha votato una singola installazione.

I voti sono conservati su **Supabase** (Supabase, Inc.), in un database ospitato **nell'Unione europea** (Irlanda), secondo la [propria informativa](https://supabase.com/privacy). Come ogni servizio web, Supabase può registrare nei propri log tecnici l'indirizzo IP da cui arriva la richiesta.

### 2.5 Cosa Paths of Inks non fa

- Non richiede la creazione di un account e non raccoglie email, nome reale o credenziali.
- Non raccoglie dati di geolocalizzazione.
- Non accede a contatti, fotocamera, microfono o file personali del dispositivo, al di fuori dei file che l'utente sceglie esplicitamente di importare come libro.
- Non profila l'utente, non mostra pubblicità e non raccoglie identificativi pubblicitari.
- Non vende né cede dati a terzi.

### 2.6 Dati trattati dagli store di distribuzione

Se l'app viene installata tramite Google Play (o un altro store), il gestore dello store può raccogliere autonomamente dati relativi a download, installazione ed eventuali crash, secondo le proprie informative privacy, sulle quali il Fornitore non ha controllo:

- Google Play: https://policies.google.com/privacy

## 3. Base giuridica e finalità del trattamento

I dati indicati al punto 2.1 sono trattati unicamente sul dispositivo dell'utente e sotto il suo controllo, per la sola finalità di **fornire le funzionalità dell'app** (salvare la partita, riprendere la lettura, applicare le preferenze). La base giuridica è l'esecuzione del rapporto d'uso richiesto dall'utente (art. 6.1.b GDPR).

Il voto in stelle (punto 2.4) è trattato per la finalità di **mostrare agli altri lettori quanto è piaciuto un libro**. Parte soltanto per una tua azione esplicita — toccare le stelle — e la base giuridica è il consenso che dai votando (art. 6.1.a GDPR), che puoi ritirare come descritto al punto 7.

## 4. Conservazione dei dati

- Profili, progressi, preferenze e libri restano sul dispositivo finché l'utente non li elimina.
- L'utente può cancellare singoli profili dall'app, oppure rimuovere tutti i dati **disinstallando l'app** o svuotando i dati dell'applicazione dalle impostazioni del sistema operativo.
- I voti in stelle restano nel database finché il libro è nel catalogo, perché la media che vedono gli altri lettori è fatta di quelli. Non sono collegati a te, come spiegato al punto 2.4.
- Il Fornitore non conserva copie di backup dei dati dell'utente. Eventuali backup automatici del dispositivo (es. backup di sistema Android o iCloud) sono gestiti dal sistema operativo secondo le impostazioni scelte dall'utente.

## 5. Condivisione dei dati

I dati **non vengono venduti né ceduti a terzi**. Dei voti in stelle si mostrano ad altri lettori solo la media e il numero, mai il voto di un singolo.

## 6. Pubblico di destinazione

Paths of Inks è un'app di narrativa interattiva con contenuti avventurosi che possono includere combattimenti descritti testualmente. **Non è destinata a bambini di età inferiore ai 13 anni.** Se hai tra 13 e 18 anni, puoi usare l'app con il consenso di un genitore o tutore. L'app non raccoglie consapevolmente dati di minori: non raccoglie, in generale, dati identificativi di alcun utente.

## 7. Diritti dell'utente

In quanto interessato ai sensi degli artt. 15-22 GDPR, hai diritto ad accedere ai tuoi dati, richiederne la rettifica, la cancellazione o la limitazione, opporti al trattamento e ottenerne la portabilità.

Per i dati che stanno sul tuo dispositivo puoi esercitare direttamente questi diritti:

- consultando e modificando profili e preferenze dall'interno dell'app;
- cancellando i profili dall'app;
- disinstallando l'app o cancellando i dati dell'applicazione dalle impostazioni di sistema, per rimuovere tutto;
- copiando i file dei libri e dei profili tramite gli strumenti di backup o condivisione del dispositivo, dove disponibili.

Per il voto in stelle: puoi **cambiarlo o toglierlo** quando vuoi dall'app, dalla scheda del libro; toglierlo lo cancella dal database e dalla media. Disinstallando l'app, invece, i voti già dati restano nella media ma smettono di essere riconducibili al tuo telefono, perché l'identificativo sparisce con l'app: per toglierli davvero, fallo prima di disinstallare.

Per qualsiasi richiesta puoi comunque scrivere all'indirizzo indicato al punto 8. Hai inoltre diritto a proporre reclamo all'Autorità Garante per la Protezione dei Dati Personali (www.garanteprivacy.it) se ritieni che il trattamento violi il GDPR.

## 8. Contatti

Per domande sulla privacy o per esercitare i tuoi diritti:

📧 email: pathsofinks.app@gmail.com

## 9. Modifiche a questa informativa

Questa informativa può essere aggiornata quando l'app introduce funzionalità nuove. La data di "ultimo aggiornamento" in cima al documento riflette l'ultima revisione. In caso di modifiche sostanziali — in particolare l'introduzione di un nuovo invio di dati verso l'esterno — l'app ne darà evidenza e potrà richiedere una nuova accettazione.

*Revisione del 27 settembre 2026: aggiunto il voto in stelle dei libri (punto 2.4), e corretta la descrizione del download dei libri, che non avviene più da pagine pubbliche ma da un deposito riservato.*

---

*Vedi anche: [Termini e Condizioni](terms_it.md)*
