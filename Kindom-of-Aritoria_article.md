# Creare un articolo usando la tecnica RAG

Questo documento ha lo scopo di illustrare, passo dopo passo, come utilizzare la tecnica RAG (Retrieval-Augmented Generation) per analizzare, sintetizzare e verificare informazioni provenienti da più fonti testuali. Attraverso una serie di prompt e risposte simulate, guida l’utente nella creazione di un articolo strutturato sull'esempio del Regno di Aridoria, mostrando come estrarre riassunti, punti chiave, domande tematiche e riferimenti puntuali alle fonti, con l’obiettivo di produrre contenuti informativi rigorosi e trasparenti.

> NOTA: Questo progetto è stato realizatto  per Codecademy.

## Punto 1 - Creare il contesto

**Prompt**
```
[Documenti in allegato a ChatGPT]
Sono un ricercatore e sto indagando su un argomento riguardo il Regno di Aridoria. Ho bisogno del tuo aiuto per analizzare questi documenti sull'argomento. Capito?
```

**Rispsota**
Perfettamente chiaro. Hai caricato tre documenti fondamentali per analizzare la storia del Regno di Aridoria:

1.	The Rise of Aridoria: descrive la fondazione del regno da parte di Re Zahar, il suo sviluppo tecnologico, culturale e politico.
2.	The King’s Challenge: narra la sfida proposta da Zahar ai suoi tre figli per decidere chi sarà il successore al trono.
3.	The Youngest Prince’s Journey: racconta il viaggio di Calem, il più giovane dei principi, e il motivo per cui è stato scelto come erede.

Se vuoi, posso aiutarti a:
•	Fare un riassunto comparativo dei tre principi.
•	Analizzare i temi principali (leadership, tradizione vs innovazione, redenzione).
•	Estrarre citazioni rilevanti.
•	Costruire una linea temporale degli eventi.
•	Ricostruire l’ideologia politica e morale che guida Aridoria.

Dimmi tu da dove vuoi cominciare.

## Punto 2 - Definisci gli obiettivi

**Prompt**
```
Ho bisogno delle seguenti cose:

- un riassunto
- i punti importanti di ogni foglio
- una sessione di domanda-e-risposta sulle informazioni

Hai capito?
```

**Risposta**

Sì, ho capito perfettamente. Procederò in tre fasi:
	1.	Riassunto generale dei tre documenti.
	2.	Punti importanti divisi per documento (The Rise of Aridoria, The King’s Challenge, The Youngest Prince’s Journey).
	3.	Sessione di domanda-e-risposta dove potrai chiedere liberamente dettagli, chiarimenti o analisi su qualsiasi aspetto.

#### Fase 1 – Riassunto generale

Il Regno di Aridoria, un’oasi fiorente nel deserto, fu costruito con visione e resilienza da Re Zahar. Conscio della fragilità del suo regno e dell’importanza della leadership, Zahar decide di non seguire la tradizione della successione automatica al figlio maggiore. Invece, propone una sfida ai suoi tre figli – Adar, Baral e Calem – affinché dimostrino, con un pericoloso viaggio nel deserto alla ricerca di un artefatto leggendario, di essere degni di governare.

Adar fallisce per la sua freddezza e ambizione cieca, trattando male il suo team. Baral crolla sotto il peso della sua superficialità e manipolazione. Solo Calem dimostra leadership compassionevole, intelligenza collaborativa e altruismo. Alla fine, Calem non solo trova l’artefatto (che decide di non prendere), ma riesce anche a redimere i suoi fratelli e riportarli a casa. Re Zahar lo proclama successore, e Calem diventerà un sovrano amato e illuminato.

#### Fase 2 – Punti importanti per documento

📘 **The Rise of Aridoria**

• Aridoria è un regno costruito nel deserto, grazie alla visione ecologica e tecnologica di Zahar.
• Zahar inventa un sistema di acquedotti sotterranei, ispirandosi alla natura.
• Sotto il suo regno, Aridoria diventa un centro di cultura, commercio e sapere.
• Zahar ha tre figli: Adar (stratega ambizioso), Baral (carismatico ma superficiale), Calem (empatico e riflessivo).
• Per scegliere il successore, Zahar indìce una sfida: chi dimostrerà di possedere leadership, saggezza e compassione guiderà Aridoria.

📘 **The King’s Challenge**

• Adar, il maggiore, fallisce per la sua leadership autoritaria. Ignora i consigli del team, abbandona dei viaggiatori in difficoltà, poi viene abbandonato dal suo stesso gruppo.
• Baral, il secondogenito, è inizialmente carismatico, ma fa promesse false, avvelena un’oasi e abbandona i suoi compagni durante un attacco di banditi.
• I due fratelli, incontratisi nel deserto, stringono un patto oscuro per tornare ad Aridoria e conquistare il trono con la forza.

📘 **The Youngest Prince’s Journey**

• Calem, il più giovane, parte con un approccio umile e collaborativo.
• Aiuta un caravan abbandonato da Adar, guadagnandosi alleanza e conoscenze vitali sul deserto.
• Supera prove fisiche e mentali (come le Dune Sussurranti) grazie alla cooperazione del gruppo.
• Trova il Wisdom Chalice, ma decide di non usarlo, ritenendo che la vera saggezza stia nel viaggio e nell’esperienza.
• Scopre il complotto dei fratelli, ma invece di punirli offre loro una via di redenzione.
• Tornato ad Aridoria, viene proclamato erede al trono per la sua compassione, visione e leadership.
• Da re, Calem promuove educazione, giustizia e inclusività, trasformando Aridoria in un regno ancora più prospero.

#### Fase 3 - Sessione Domande & Risposte

Ora che hai il quadro completo, puoi farmi qualsiasi domanda riguardo:
• Eventi specifici
• Analisi dei personaggi
• Temi (es. leadership, moralità, eredità)
• Simboli (es. Wisdom Chalice, Desert Tear)
• Dettagli storici, geografici, narrativi

Vai pure con la prima domanda quando vuoi.

---
**Prompt**
```
Creami tu queste domande con le risposte secondo i temi che mi hai consigliato.
```

**Risposta**

##### TEMA 1: Leadership

❓ Qual è la differenza tra la leadership di Calem e quella dei suoi fratelli?

✅ Calem guida con empatia e collaborazione, ascolta il suo team e si mette al servizio degli altri. Adar impone la sua volontà con arroganza e rigidità. Baral manipola e seduce, ma abbandona i suoi ideali appena messo alla prova.

❓ Come dimostra Calem la vera leadership nelle Dune Sussurranti?

✅ Nonostante le allucinazioni che lo tentano con gloria personale, Calem resiste grazie al Desert Tear e ai valori acquisiti nel viaggio. Ricorda al gruppo lo scopo comune e li salva dalla follia collettiva, guidandoli fuori insieme.

⸻

##### TEMA 2: Tradizione vs Innovazione

❓ Perché Re Zahar rifiuta la tradizione della successione automatica?

✅ Perché sa che la leadership richiede merito e carattere, non solo sangue reale. Decide di innovare creando una prova che metta alla luce i veri valori dei figli, come aveva fatto lui stesso per costruire Aridoria.

❓ In che modo il regno stesso riflette questa tensione tra tradizione e innovazione?

✅ Aridoria è nata dalla tradizione del rispetto per il deserto unita a soluzioni nuove (acquedotti sotterranei, coltivazioni resistenti, apertura al commercio). È un simbolo vivente di equilibrio tra passato e futuro.

⸻

##### TEMA 3: Redenzione

❓ Come reagisce Calem al tradimento dei fratelli?

✅ Invece di vendicarsi, offre comprensione e una possibilità di riscatto. Questo gesto dimostra grandezza morale e rompe il ciclo di rivalità, trasformando due nemici in alleati futuri.

❓ Adar e Baral riescono a redimersi davvero?

✅ Sì. Dopo il ritorno, accettano le conseguenze e mettono le loro capacità al servizio del regno: Adar nei commerci, Baral nella diplomazia. Il loro cambiamento è possibile solo grazie alla misericordia di Calem.

⸻

##### TEMA 4: Saggezza e Potere

❓ Perché Calem rinuncia al Wisdom Chalice?

✅ Perché capisce che la vera saggezza non viene da oggetti magici, ma da esperienze vissute, empatia e collaborazione. È un rifiuto simbolico del potere facile e una lezione sulla maturità del vero leader.

❓ Che significato ha il Desert Tear?

✅ È un talismano simbolico che rappresenta lucidità, memoria e guida nei momenti difficili. Aiuta Calem a restare saldo nei suoi valori e diventa un segno della sua crescita spirituale.

⸻

##### TEMA 5: Costruzione del Regno

❓ Cosa rende Aridoria un regno prospero nonostante l’ambiente ostile?

✅ La visione di Zahar, che ha saputo imparare dal deserto invece di combatterlo. Ha costruito infrastrutture innovative, valorizzato l’istruzione e la cultura, e creato una società coesa fondata sulla meritocrazia.

❓ Quali valori Zahar ha cercato di trasmettere nel lasciare il trono?

✅ Giustizia, saggezza, servizio al popolo, umiltà e resilienza. Il test ai figli non era solo per scegliere un re, ma per lasciare al regno un’eredità morale e politica solida.


## Verificare l'output

**Promt**
```Per ogni affermazione o informazione che hai fornito nelle tue risposte, indica il documento e la sezione specifica da cui è tratta. Usa il seguente formato:

Affermazione: [Inserisci qui l’informazione o l’affermazione]
Fonte: [Numero del documento, Nome o numero della sezione]

Ad esempio:

Affermazione: Aridoria fu fondata in un ambiente desertico ostile.
Fonte: Documento 1, ‘Origini del Regno’

Applica questo formato alle tue risposte precedenti riguardo le missioni dei tre figli e la previsione per il futuro del figlio più giovane.
Se qualche informazione non può essere direttamente attribuita ai documenti, indicalo chiaramente come deduzione o speculazione basata sulle informazioni disponibili.
```

**Risposta**

Ecco l’elenco delle affermazioni chiave riguardo le missioni dei tre figli e la previsione per il futuro del figlio più giovane, con indicazione puntuale delle fonti (titolo documento e sezione specifica, quando presente):

⸻

ADAR – Il primogenito

Affermazione: Adar fallisce la missione a causa della sua freddezza e ambizione cieca.
Fonte: Documento 2 (The King’s Challenge), sezione The Failed Journeys of Adar and Baral

Affermazione: Rifiuta di aiutare un caravan in difficoltà per non perdere tempo.
Fonte: Documento 2, The Failed Journeys of Adar and Baral

Affermazione: Tratta il suo team con durezza e ignora i consigli, causando la rottura della fiducia.
Fonte: Documento 2, The Failed Journeys of Adar and Baral

Affermazione: Viene abbandonato dal proprio gruppo nel deserto.
Fonte: Documento 2, The Failed Journeys of Adar and Baral

⸻

BARAL – Il secondogenito

Affermazione: Baral inizia con carisma e ottimismo, ma mostra insicurezza e opportunismo.
Fonte: Documento 2, The Failed Journeys of Adar and Baral

Affermazione: Fa promesse irrealistiche ai nomadi per ottenere vantaggi.
Fonte: Documento 2, The Failed Journeys of Adar and Baral

Affermazione: Decide di avvelenare un’oasi per rallentare gli altri.
Fonte: Documento 2, The Failed Journeys of Adar and Baral

Affermazione: Durante un attacco di banditi, fugge e abbandona il suo team.
Fonte: Documento 2, The Failed Journeys of Adar and Baral

Affermazione: Baral e Adar si ritrovano, entrambi falliti, e tramano insieme un colpo di stato.
Fonte: Documento 2, The Failed Journeys of Adar and Baral

⸻

CALEM – Il più giovane

Affermazione: Calem parte per la missione con umiltà e spirito collaborativo.
Fonte: Documento 1 (The Youngest Prince’s Journey), sezione Calem’s Triumph and Aridoria’s Salvation

Affermazione: Aiuta un caravan abbandonato dal fratello Adar.
Fonte: Documento 1, Calem’s Triumph and Aridoria’s Salvation

Affermazione: Riceve il “Desert Tear”, oggetto simbolico che lo guiderà nel momento critico.
Fonte: Documento 1, Calem’s Triumph and Aridoria’s Salvation

Affermazione: Supera le Dune Sussurranti resistendo a visioni di potere e gloria.
Fonte: Documento 1, Calem’s Triumph and Aridoria’s Salvation

Affermazione: Trova il “Wisdom Chalice” ma sceglie di non prenderlo, ritenendo più importante la saggezza acquisita nel viaggio.
Fonte: Documento 1, Calem’s Triumph and Aridoria’s Salvation

Affermazione: Affronta i fratelli quando lo attaccano, ma sceglie il perdono e offre loro una via di redenzione.
Fonte: Documento 1, Calem’s Triumph and Aridoria’s Salvation

Affermazione: Calem viene scelto da Zahar come successore per la sua saggezza, compassione e leadership.
Fonte: Documento 1, Calem’s Triumph and Aridoria’s Salvation

⸻

PREVISIONE FUTURA DI CALEM

Affermazione: Calem diventa un re amato e innovatore, investe in infrastrutture e cultura.
Fonte: Documento 1, Calem’s Triumph and Aridoria’s Salvation

Affermazione: Crea una biblioteca sul luogo del Wisdom Chalice, rendendo il sapere accessibile.
Fonte: Documento 1, Calem’s Triumph and Aridoria’s Salvation

Affermazione: I fratelli redenti servono il regno nei loro rispettivi ambiti: Adar nel commercio, Baral nella diplomazia.
Fonte: Documento 1, Calem’s Triumph and Aridoria’s Salvation

Affermazione: Calem istituisce una tradizione di “viaggi formativi” per i futuri nobili, ispirata alla sua esperienza.
Fonte: Documento 1, Calem’s Triumph and Aridoria’s Salvation