
`` Università degli Studi di Milano ``
`` Corso di Editoria Digitale`` 
`` Anno Accademico 2022/2023``
`` Nicolò Debiaggi 908971`` 

# Il cambiamento climatico per bambini con ChatGPT

## Introduzione

Il progetto consiste nell'utilizzo di un'intelligenza artificiale per la generazione di un testo per bambini che ha come argomento un topic di tendenza, ovvero il cambiamento climatico.

L'obiettivo principale consiste nel testare i servizi di ChatGPT per provare a definire un workflow di generazione semi-automatica di testo. 
Le tecnologie usate sono le seguenti e nel seguente ordine:
- Google Trends e altri siti di trend topics per individuare un argomento di tendenza 
- ChatGPT per la generazione del testo
- Gencraft, ovvero un'altra intelligenza artificiale ma predisposta alla generazione di elementi grafici a differenza di ChatGPT
- Canva per l'implementazione di questi elementi grafici all'interno del prodotto e per applicare eventuali correzioni grafiche come il font e la grandezza dei caratteri
- Pandoc per convertire il prodotto in formato epub e html per favorirne la distribuzione digitale.

## Obiettivi 

L'obiettivo del lavoro è testare la capacità di un'intelligenza artificiale, ([ChatGPT](https://chat.openai.com/)), nella generazione semiautomatica di un testo indirizzato a un pubblico di bambini ma che, allo stesso tempo, possa avere una qualità di stesura e narrazione pari a quella già presente sul rispettivo mercato.

## Processo di produzione

Come primo passo ho individuato un argomento di tendenza nel cambiamento climatico attraverso l'utilizzo di siti come Google trends e altri simili. Ho poi ricercato i punti chiave del cambiamento climatico su vari siti internet e ho chiesto anche a ChatGPT stessa di fornirmi diverse idee per quanto riguardasse questa analisi del tema.
Prima di passare alla fase di stesura ho effettuato delle ricerche per quanto riguarda la presenza di possibili competitor e ne ho trovati diversi a partire da quelli che richiamano la figura della nota attivista Greta Thunberg ad altri che utilizzano gli animali come principali protagonisti. Essendo un libro per bambini il target era già definito in partenza quindi il pubblico sarà stato dai 9 anni a salire.

Per quanto riguarda un'ipotetica distribuzione non serve fare affidamento su delle grandi case editrici in quanto amazon fornisce la possibilità di auto pubblicare il proprio libro mantenendo i costi bassi dovendo pagare una percentuale ad Amazon stessa che si aggira sul 35% sul prezzo di vendita di ogni singolo libro. Questa scelta ci permette di non avere grosse quantità di copie invedute e, inoltre, ci permette di fare affidamento ad Amazon per quanto riguarda la spedizione.

La già citata presenza di altri libri su questo tema implica un impoverimento dell'originalità in quanto a cosa dire ma non per la forma in cui lo si può raccontare, che essa sia tramite una fiaba, una favola o un'intervista. Il modello di business richiama quello della distribuzione essendo gratuita la pubblicazione tramite Amazon, starà al reparto visivo del libro a fare da marketing per sè stesso, ad esempio si potrebbe puntare su colori un po' più accesi per attirare l'attenzione e all'introduzione in copertina di un animale simbolo, come già sfruttato dai competitor, come ad esempio l'orso polare che appunto va a richiamare il tema dello scioglimento dei ghiacciai che è legato al cambiamento climatico.

Essendo generato da un'intellligenza artificiale, ChatGPT, il problema dell'identificazione delle fonti verrà risolto molto facilmente essendo essa stessa la fonte. Per quanto riguarda diritti e aspetti legali la possibilità di realizzare un guadagno da questo libro andrà verificati nei termini e condizioni d'uso di ChatGPT.

Una volta individuati i punti da discutere, verrà chiesto a ChatGPT di stendere una prima bozza e, successivamente, di portarla a un livello di scrittura simile a quello dei competitor. Questo schema verrà applicato per ogni paragrafo del prodotto.

Essendo un libro per bambini si potrebbero introdurre immagini all'interno del libro per alleviare l'attenzione del lettore e facilitarne l'empatizzazione con il tema, ritornando all'orso polare, potrebbero esserci raffigurazioni grafiche di animali in determinati contesti. Per questo aspetto va utilizzata un'altra intelligenza artificiale, sempre per rimanere su questo tema, poichè ChatGPT si occupa solamente della generazione testuale. Sono presenti diverse opzioni tra cui la più famosa, Midjourney, o anche l'implementazione di Adobe Photshop con il nuovo aggiornamento che include proprio una intelligenza artificiale ma relativa più che altro al context-filling. Rimanendo sempre nell'ottica di dover trarre un guadagno, ci sono diverse opzioni tra cui scegliere e tra queste è stata selezionata Gencraft.

Una volta soddisfatti con la stesura di ogni paragrafo si potranno unire insieme per un'ultima bozza per una revisione finale e, se necessario, ci sarà implementazione di nuovi contenuti.

Per quanto riguarda lo stile grafico e le regole di impaginazione verranno usate quelle standard con l'inserimento di elementi grafici avanzati ma rispettando i requisiti di accessibilità. Verrà utilizzato Canva per implementare le immagini generate da Gencraft e per sistemare altre opzioni grafiche come il font e la grandezza dei caratteri. Questa implementazione abbatte leggermente la parte di automazione del workflow ma permette di ottenere un risultato decisamente migliore a livello visivo.

Per la creazione del formato di distribuzione si potrà convertire il documento in epub e html tramite Pandoc in modo da poterlo fornire anche digitalmente e facilitarne l'automazione.

Una volta terminate le ultime revisioni, la definizione dei metadati descrittivi e la definizione di documentazione e del materiale di supporto si potrà passare alla promozione del libro.

Per quanto riguarda il marketing si potrebbe lanciare una campagna social, su Facebook, TikTok e Instagram, che permetterebbe di raggiungere un pubblico maggiore e un target di età specifico (bambini e genitori) ma che riesce comunque a mantenere bassi i costi di pubblicità, magari promuovendo che ChatGPT sia una parte importante nella realizzazione di questo libro per cercare di rendere virale la notizia. Inoltre sarà utile promuovere l'orso polare, il protagonista del libro, per introdurre un elemento di associazione al libro nel cliente. Una volta effettuato il lancio non ci rimarrà che aspettare e raccogliere i dati, lato vendite e interazioni social, per confrontarli con la campagna marketing per poter fare una revisione degli obiettivi comunicativi e dei contenuti.

## Gestione documentale

Per descrivere il *flusso di gestione documentale* ho utilizzato il linguaggio Mermaid suddividendo il grafo in tre alberi principali: ricerca delle fonti e flusso operativo, trasformazione dei formati e definizione dello stile grafico.

[![](https://mermaid.ink/img/eyJjb2RlIjoiZ3JhcGggVERcbkFbcmljZXJjYSBkZWxsZSBmb250aSBlIGZsdXNzbyBvcGVyYXRpdm9dXG5BIC0tPiBCKEdvb2dsZSBUcmVuZHMpXG5BIC0tPiBDKENoYXRHUFQpXG5BIC0tPiBEKGFsdHJpIHNpdGkgaW50ZXJuZXQpXG5FW3ByaW1hIHN0ZXN1cmEgY29uIENoYXRHUFRdXG5CIC0tPiBFXG5DIC0tPiBFXG5EIC0tPiBFXG5FIC0tPiBGW3JldmlzaW9uZSBkZWkgY29udGVudXRpIGUgYWNjb3JnaW1lbnRpIHRlY25pY2ldXG5GIC0tPiBHKG51b3ZlIHN0ZXN1cmUgY29uIENoYXRHUFQgcHJlbmRlbmRvIGNvbWUgZXNlbXBpIGkgY29tcGV0aXRvciBzdWwgbWVyY2F0bylcbkYgLS0-IEgoc3Rlc3VyYSB0ZXN0byBpbiByaW1hKVxuRiAtLT4gSShJbnRyb2R1emlvbmUgZGkgdW4gb3JzbyBwb2xhcmUgY29tZSBwcm90YWdvbmlzdGEgZGVsbGEgc3RvcmlhKVxuSntudW92ZSByZXZpc2lvbml9XG5HIC0tPiBKXG5KIC0tPiB8cHJvZG90dG8gbm9uIHNvZGRpc2ZhY2VudGV8IEpcbkggLS0-IGgocGVyIGZhdm9yaXJlIHVuYSBsZXR0dXJhIHBpw7kgc2NvcnJldm9sZSlcbkkgLS0-IGkoaW50cm9kb3R0byBwZXIgZmF2b3JpcmUgZW1wYXRpemF6emlvbmUgdmVyc28gaWwgdGVtYSB0cmF0dGF0bylcbkogLS0-IHxwcm9kb3R0dG8gc29kZGlzZmFjZW50ZXxLe2VsZW1lbnRpIGdyYWZpY2kgZ2VuZXJhdGkgZGEgR2VuY3JhZnR9XG5LIC0tPiB8cHJvZG90dHRvIHNvZGRpc2ZhY2VudGV8ayh1dGlsaXp6byBkaSBDYW52YSlcbksgLS0-IHxwcm9kb3R0byBub24gc29kZGlzZmFjZW50ZXxLXG5rIC0tPiBsKGltcGxlbWVudGF6aW9uZSBlbGVtZW50aSBncmFmaWNpKVxuayAtLT4gbShpbXBhZ2luYXppb25lIGUgbW9kaWZpY2EgZGkgZm9udCBlIGdyYW5kZXp6YSBkZWkgY2FyYXR0ZXJpKVxubihzdGVzdXJhIHN1IFZpc3VhbCBTdHVkaW8gQ29kZSBpbiBsaW5ndWFnZ2lvIG1hcmtkb3duKVxubCAtLT4gblxubSAtLT4gblxubiAtLT4gb1t0cmFzZm9ybWF6aW9uZSBkZWkgZm9ybWF0aSB0cmFtaXRlIHBhbmRvY11cbkwoVHJhc2Zvcm1hemlvbmUgZGVpIGZvcm1hdGkpXG5MIC0tPiBOKGVwdWIpXG5MIC0tPiBPKGh0bWwpXG5QKHBlciBmYXZvcmlyZSBkaXN0cmlidXppb25lIGRpZ2l0YWxlKVxuTi0tPlBcbk8tLT5QXG5RW0RlZmluaXppb25lIGRlbGxvIHN0aWxlIGdyYWZpY29dIC0tPiBSKHJlZ29sZSBkaSBpbXBhZ2luYXppb25lIHN0YW5kYXJkKVxuUSAtLT4gUyhwcmVzZW56YSBlbGVtZW50aSBncmFmaWNpIGF2YW56YXRpKVxuUy0tPiBUKG1hbnRlbmVuZG8gcmlzcGV0dG8gZGkgYWNjZXNzaWJpbGl0w6ApIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjpmYWxzZX0)](https://mermaid-js.github.io/docs/mermaid-live-editor-beta/#/edit/eyJjb2RlIjoiZ3JhcGggVERcbkFbcmljZXJjYSBkZWxsZSBmb250aSBlIGZsdXNzbyBvcGVyYXRpdm9dXG5BIC0tPiBCKEdvb2dsZSBUcmVuZHMpXG5BIC0tPiBDKENoYXRHUFQpXG5BIC0tPiBEKGFsdHJpIHNpdGkgaW50ZXJuZXQpXG5FW3ByaW1hIHN0ZXN1cmEgY29uIENoYXRHUFRdXG5CIC0tPiBFXG5DIC0tPiBFXG5EIC0tPiBFXG5FIC0tPiBGW3JldmlzaW9uZSBkZWkgY29udGVudXRpIGUgYWNjb3JnaW1lbnRpIHRlY25pY2ldXG5GIC0tPiBHKG51b3ZlIHN0ZXN1cmUgY29uIENoYXRHUFQgcHJlbmRlbmRvIGNvbWUgZXNlbXBpIGkgY29tcGV0aXRvciBzdWwgbWVyY2F0bylcbkYgLS0-IEgoc3Rlc3VyYSB0ZXN0byBpbiByaW1hKVxuRiAtLT4gSShJbnRyb2R1emlvbmUgZGkgdW4gb3JzbyBwb2xhcmUgY29tZSBwcm90YWdvbmlzdGEgZGVsbGEgc3RvcmlhKVxuSntudW92ZSByZXZpc2lvbml9XG5HIC0tPiBKXG5KIC0tPiB8cHJvZG90dG8gbm9uIHNvZGRpc2ZhY2VudGV8IEpcbkggLS0-IGgocGVyIGZhdm9yaXJlIHVuYSBsZXR0dXJhIHBpw7kgc2NvcnJldm9sZSlcbkkgLS0-IGkoaW50cm9kb3R0byBwZXIgZmF2b3JpcmUgZW1wYXRpemF6emlvbmUgdmVyc28gaWwgdGVtYSB0cmF0dGF0bylcbkogLS0-IHxwcm9kb3R0dG8gc29kZGlzZmFjZW50ZXxLe2VsZW1lbnRpIGdyYWZpY2kgZ2VuZXJhdGkgZGEgR2VuY3JhZnR9XG5LIC0tPiB8cHJvZG90dHRvIHNvZGRpc2ZhY2VudGV8ayh1dGlsaXp6byBkaSBDYW52YSlcbksgLS0-IHxwcm9kb3R0byBub24gc29kZGlzZmFjZW50ZXxLXG5rIC0tPiBsKGltcGxlbWVudGF6aW9uZSBlbGVtZW50aSBncmFmaWNpKVxuayAtLT4gbShpbXBhZ2luYXppb25lIGUgbW9kaWZpY2EgZGkgZm9udCBlIGdyYW5kZXp6YSBkZWkgY2FyYXR0ZXJpKVxubihzdGVzdXJhIHN1IFZpc3VhbCBTdHVkaW8gQ29kZSBpbiBsaW5ndWFnZ2lvIG1hcmtkb3duKVxubCAtLT4gblxubSAtLT4gblxubiAtLT4gb1t0cmFzZm9ybWF6aW9uZSBkZWkgZm9ybWF0aSB0cmFtaXRlIHBhbmRvY11cbkwoVHJhc2Zvcm1hemlvbmUgZGVpIGZvcm1hdGkpXG5MIC0tPiBOKGVwdWIpXG5MIC0tPiBPKGh0bWwpXG5QKHBlciBmYXZvcmlyZSBkaXN0cmlidXppb25lIGRpZ2l0YWxlKVxuTi0tPlBcbk8tLT5QXG5RW0RlZmluaXppb25lIGRlbGxvIHN0aWxlIGdyYWZpY29dIC0tPiBSKHJlZ29sZSBkaSBpbXBhZ2luYXppb25lIHN0YW5kYXJkKVxuUSAtLT4gUyhwcmVzZW56YSBlbGVtZW50aSBncmFmaWNpIGF2YW56YXRpKVxuUy0tPiBUKG1hbnRlbmVuZG8gcmlzcGV0dG8gZGkgYWNjZXNzaWJpbGl0w6ApIiwibWVybWFpZCI6eyJ0aGVtZSI6ImRlZmF1bHQifSwidXBkYXRlRWRpdG9yIjpmYWxzZX0)

## Tecnologie adottate

Le tecnologie adottate sono ChatGPT, Gencraft, Canva, Visual Studio Code e la conversione tramite Pandoc in html e ePub. L'utilizzo di ChatGPT ha abbattuto molto i tempi di gestione documentale essendo l'aspetto nella creazione del prodotto che ha aiutato maggiormente lato automazione del workflow. Le tecnologie html e ePub invece supportano la diffusione digitale del testo e quindi danno la possibilità di raggiungere un pubblico più ampio portando un aumento di qualità nella versione digitale del documento.

Inoltre è presente una [repository github](https://github.com/NicoloDebiaggi/Esame-editoria-digitale) con tutti i documenti nei vari formati, le immagini e gli script utilizzati all'interno della relazione e del progetto.

## Conclusioni

Il risultato ottenuto è il libro per bambini intitolato "Sammy saves the snow" che parla di un orso polare che si ritrova ad affrontare e superare il tema dello scioglimento dei ghiacciai e introduce l'argomento delle fonti di energia rinnovabili. Per ottenere un risultato abbastanza soddisfacente ci sono volute diverse revisioni ma ciò ha permesso di raggiungere gli obiettivi prefissati. La più grande limitazione è l'assenza di immagini in quanto ChatGPT è in grado di generare solo la parte testuale e non quella grafica. Infatti il grande prolema dell'utilizzo di una IA gratuita come Gencraft per la generazione di elementi grafici è la presenza di un watermark su ognuno di esse; questo è risolvibile con l'utilizzo della tecnologia di context-filling fornita da Adobe Photoshop e citata in precedenza ma ovviamnete va ad influire sui costi di produzione essendo necessario un abbonamento mensile ad Adobe.

## Bibliografia e sitografia

[ChatGPT](https://chat.openai.com/) \
[Google Trends](https://trends.google.it/trends/) \
[un](un.org) \
[nasa](nasa.gov) \
[wikipedia](wikipedia.org) \
[bbc](bbc.com)

---
 
 @author [Nicolò Debiaggi](https://github.com/NicoloDebiaggi)
