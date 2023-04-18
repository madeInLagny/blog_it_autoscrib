---
title: "Ecco cosa rende un buon assistente vocale"
show_date: true
last_modified_at: 2023-04-18
excerpt: "La facilità d'uso del riconoscimento vocale non deve mettere in ombra le tecnologie avanzate che utilizza: algoritmo di riconoscimento vocale, capacità di rilevare accenti e dialetto, gestione del 'rumore di fondo', velocità di trascrizione del dettato..."
tags:
  - Technologia
  - Natural Language Processing
header:
  teaser: "/assets/images/posts/20230418-hero.jpg"
image_path: "/assets/images/posts/20230418-hero.jpg"
---

<figure>
<img src="{{ site.url }}{{ site.baseurl }}/assets/images/posts/20230418-hero.jpg" alt="several people around a table" class="full" loading="lazy">
<figcaption style="color:grey; font-size:10px;">Foto di <a href="https://unsplash.com/@jasonrosewell">Jason Rosewell</a> su <a href="https://unsplash.com">Unsplash</a>
  </figcaption>
</figure>

_La facilità d'uso del riconoscimento vocale non dovrebbe mettere in ombra le tecnologie avanzate che utilizza. Algoritmo di riconoscimento vocale, capacità di rilevare accenti e dialetto, gestione del 'rumore di fondo', velocità di trascrizione del dettato... una soluzione di trascrizione vocale ad alte prestazioni non deve nulla al caso._

Il software di riconoscimento vocale si basa su 3 categorie di tecnologia: "Speech to Text" (STT), "Natural Language Processing" (NLP) e intelligenza artificiale (IA).

## Speech to Text (STT), identificazione e trascrizione della voce in testo
Una volta avviato il riconoscimento vocale utilizzando la parola chiave, è necessario utilizzare la voce. Per questo, è prima indispensabile registrarlo e digitalizzarlo con la tecnologia Speech to Text (nota anche come riconoscimento vocale automatico).
Durante questa fase, la voce viene catturata in frequenze sonore (sotto forma di file audio, come musica o qualsiasi altro rumore) che possono essere utilizzate successivamente.
A seconda dell'ambiente di ascolto, l'inquinamento acustico è presente o meno. Per migliorare la registrazione di tali frequenze e quindi contemporaneamente la loro affidabilità, possono essere effettuate diverse operazioni di elaborazione.
- Normalizzazione per rimuovere picchi e cali nelle frequenze per armonizzare il tutto
- Soppressione del rumore di fondo per migliorare la qualità audio
- La suddivisione dei segmenti in fonemi (che sono unità distintive all'interno delle frequenze, espresse in millesimi di secondo, che permettono di distinguere le parole l'una dall'altra
Le frequenze, una volta registrate, possono essere analizzate per associare ogni fonema a una parola oa un gruppo di parole per costituire un testo. Questo passaggio può essere svolto in diversi modi, ma un metodo in particolare è lo stato dell'arte oggi: il Machine Learning.
Una sottoparte di questa tecnologia si chiama Deep Learning: un algoritmo che ricrea una rete neurale, in grado di analizzare una grande quantità di informazioni e costruire un database di associazioni tra frequenze e parole. Pertanto, ogni associazione creerà un neurone che verrà utilizzato per dedurre nuove corrispondenze.
Pertanto, più informazioni ci sono, più il modello è statisticamente accurato e in grado di tenere conto del contesto generale per assegnare la parola migliore rispetto alle altre già definite.
Limitare gli errori dell'STT è essenziale per ottenere le informazioni più affidabili per procedere ai passaggi successivi.

## NLP (Natural Language Processing), traduzione del linguaggio umano in linguaggio macchina
Completati i passaggi precedenti, i dati testuali vengono inviati direttamente al modulo NLP (Natural Language Processing). Lo scopo principale di questa tecnologia è analizzare la frase ed estrarre quanti più dati linguistici possibile.
 
Per fare ciò, inizia associando i tag alle parole della frase, questa si chiama tokenizzazione. Si tratta in realtà di “etichette” che vengono apposte su ogni parola per caratterizzarle. Ad esempio “Open” sarà definito come il verbo che definisce un'azione, “le” come determinante relativo a “Voice Development Kit” che è un nome proprio ma anche un COD ecc… e questo per ciascuno degli elementi della frase .
Una volta individuati questi primi elementi, è necessario dare significato agli ordini risultanti dal riconoscimento vocale. Per questo vengono effettuate due analisi complementari.
In primo luogo, l'analisi sintattica che mira a modellare la struttura della frase. Si tratta qui di individuare il posto delle parole all'interno del tutto ma anche la loro posizione relativa rispetto alle altre per comprenderne le relazioni.
Per completare e finire, l'analisi semantica che, una volta individuata la natura e la posizione delle parole, cercherà di comprenderne il significato singolarmente ma anche quando sono assemblate nella frase per tradurre un'intenzione generale dell'utente.
L'importanza della PNL nel riconoscimento vocale risiede nella sua capacità di tradurre elementi testuali (cioè parole e frasi) in ordini standardizzati, inclusi significato e intento, che possono essere interpretati dall'intelligenza artificiale associata ed eseguiti.

## Intelligenza artificiale, alleata necessaria del riconoscimento vocale
Innanzitutto, l'intelligenza artificiale, sebbene integrata nel processo delle tecnologie precedenti, non è sempre essenziale per realizzare casi d'uso. Infatti, se parliamo di tecnologie connesse (quindi Cloud), l'IA avrà i suoi usi. Tanto più che la complessità di alcuni casi d'uso, in particolare sulle informazioni da correlare per produrli, lo rende obbligatorio.
Ad esempio, a volte è necessario confrontare più informazioni con azioni da svolgere, integrazione di servizi esterni o interni o banche dati da consultare.
In altre parole, l'intelligenza artificiale è il caso d'uso stesso, l'azione concreta che risulterà dall'interfaccia vocale. A seconda del contesto di utilizzo e della natura dell'ordine, gli elementi richiesti ei risultati forniti saranno diversi.
L'intelligenza artificiale è il fulcro in molte situazioni. Tuttavia, per le funzionalità embedded (quindi offline), le esigenze sono minori, più vicine alla realizzazione di semplici comandi come la navigazione su un'interfaccia o il report di azioni. Questo per avere casi d'uso specifici che non richiedono la consultazione di più informazioni.

## Come testare la tecnologia di trascrizione vocale.
[autoScrib](https://autoscrib.com/) è una soluzione di trascrizione semplice ed efficiente. Trascrive fedelmente il parlato e funziona su un computer o uno smartphone. A differenza di altri prodotti, [autoScrib](https://autoscrib.com/) consente di salvare tutti i testi trascritti in una directory e di accedervi da qualsiasi dispositivo.
Prova gratuitamente la tecnologia di trascrizione vocale su [autoscrib.com](https://autoscrib.com/)