# Fondamenti dell'Intelligenza Artificiale

!!! info "Scopo del capitolo"

    Questo capitolo introduce i concetti fondamentali dell'Intelligenza Artificiale con un taglio rivolto alla professione ingegneristica.  
    L'obiettivo non è formare data scientist, ma fornire agli ingegneri le basi necessarie per comprendere, utilizzare e valutare criticamente gli strumenti di AI.

---

## Che cos'è l'Intelligenza Artificiale

L'Intelligenza Artificiale può essere definita come l'insieme di metodi, modelli e sistemi informatici capaci di svolgere attività che, se eseguite da un essere umano, richiederebbero forme di intelligenza quali apprendimento, ragionamento, percezione, pianificazione, comunicazione e supporto alle decisioni.

Negli standard internazionali, l'AI viene descritta come la capacità di un sistema di generare output quali previsioni, raccomandazioni, contenuti o decisioni, a partire da dati, modelli e obiettivi definiti.

Per l'ingegnere, questa definizione ha una conseguenza immediata: l'AI non deve essere considerata una "macchina pensante", ma un sistema tecnico che elabora informazioni e produce risultati che devono essere compresi, verificati e validati.

---

## Breve evoluzione storica

Le radici dell'Intelligenza Artificiale possono essere ricondotte agli studi di Alan Turing sulla calcolabilità e alla domanda, posta nel 1950, se una macchina possa mostrare un comportamento intelligente.

Il termine "Artificial Intelligence" viene formalmente introdotto nel 1956 durante la conferenza di Dartmouth, evento generalmente considerato il punto di nascita della disciplina.

Nel corso dei decenni l'AI ha attraversato diverse fasi:

- la stagione dell'AI simbolica, basata su regole e rappresentazione della conoscenza;
- lo sviluppo dei sistemi esperti;
- la diffusione del Machine Learning;
- l'affermazione del Deep Learning;
- l'attuale fase dell'AI generativa e dei Large Language Models.

Questa evoluzione ha trasformato l'AI da disciplina prevalentemente accademica a tecnologia abilitante trasversale, oggi utilizzata in progettazione, automazione, diagnostica, simulazione, analisi documentale e supporto alle decisioni.

---

## Le principali famiglie dell'AI

### AI simbolica

L'AI simbolica si basa sulla rappresentazione esplicita della conoscenza attraverso regole, logica e simboli.  
È l'approccio tipico dei sistemi esperti, nei quali il comportamento del sistema è definito da conoscenza formalizzata da esperti umani.

Questo approccio è utile quando le regole sono note, stabili e verificabili, come in alcune procedure tecniche, controlli di conformità o sistemi decisionali basati su normative.

### Machine Learning

Il Machine Learning è un sottoinsieme dell'AI nel quale il sistema non viene programmato con tutte le regole operative, ma apprende dai dati.

Un modello di Machine Learning individua relazioni, schemi e regolarità all'interno di un dataset e li utilizza per effettuare previsioni, classificazioni o raccomandazioni su nuovi dati.

### Deep Learning

Il Deep Learning è una famiglia di tecniche di Machine Learning basata su reti neurali artificiali profonde.  
È particolarmente efficace nell'elaborazione di dati complessi come immagini, audio, testo, segnali e grandi quantità di dati non strutturati.

Molte applicazioni moderne dell'AI, dalla visione artificiale al riconoscimento del linguaggio naturale, si basano su modelli di Deep Learning.

### Generative AI

L'Intelligenza Artificiale Generativa comprende sistemi capaci di generare nuovi contenuti, come testi, immagini, codice, audio, video o modelli tridimensionali, a partire da dati appresi durante l'addestramento.

Gli strumenti conversazionali oggi più diffusi, come i chatbot basati su Large Language Models, appartengono a questa famiglia.

---

## Come impara una macchina

Il processo di apprendimento di un modello di AI può essere descritto attraverso alcune fasi fondamentali.

### Dataset

Il dataset è l'insieme dei dati utilizzati per addestrare, validare e testare un modello.  
La qualità del dataset incide direttamente sulla qualità del modello.

Dati incompleti, non rappresentativi o distorti possono generare risultati errati o discriminatori.

### Training

Il training è la fase in cui il modello apprende dai dati.  
Durante questa fase il sistema modifica progressivamente i propri parametri interni per ridurre l'errore tra il risultato previsto e quello atteso.

### Validazione

La validazione serve a controllare il comportamento del modello durante lo sviluppo e a regolare le sue configurazioni.

### Test

Il test valuta le prestazioni del modello su dati non utilizzati durante l'addestramento.

### Inferenza

L'inferenza è la fase operativa, nella quale il modello viene utilizzato per produrre risultati su nuovi dati.

### Generalizzazione

La generalizzazione è la capacità del modello di funzionare correttamente su dati nuovi e diversi da quelli usati in fase di addestramento.

Per l'ingegnere, questo concetto è essenziale: un modello che funziona bene solo sui dati storici, ma fallisce su casi reali, non è affidabile.

---

## I principali paradigmi di apprendimento

### Apprendimento supervisionato

Nell'apprendimento supervisionato il modello viene addestrato utilizzando dati etichettati, cioè esempi nei quali sono noti sia l'input sia l'output corretto.

È utilizzato per classificazione, regressione, diagnostica, previsione e riconoscimento.

### Apprendimento non supervisionato

Nell'apprendimento non supervisionato il modello lavora su dati non etichettati e cerca autonomamente strutture, gruppi o relazioni nascoste.

È utile per clustering, segmentazione, analisi esplorativa e riduzione della dimensionalità.

### Apprendimento semi-supervisionato

L'apprendimento semi-supervisionato combina una quantità limitata di dati etichettati con una quantità più ampia di dati non etichettati.

È utile quando l'etichettatura manuale dei dati è costosa o complessa.

### Apprendimento per rinforzo

Nel Reinforcement Learning un agente apprende interagendo con un ambiente e ricevendo ricompense o penalità in base alle azioni compiute.

È utilizzato in robotica, ottimizzazione, controllo, pianificazione e sistemi autonomi.

---

## Modelli, algoritmi e reti neurali

Un modello di AI è una rappresentazione matematica o computazionale costruita per risolvere un determinato problema.

Tra i modelli più comuni troviamo:

- regressione lineare e logistica;
- alberi decisionali;
- Random Forest;
- Support Vector Machine;
- reti neurali artificiali;
- reti neurali profonde;
- modelli generativi.

La scelta del modello dipende da diversi fattori:

- natura del problema;
- quantità e qualità dei dati;
- requisiti di accuratezza;
- necessità di spiegabilità;
- vincoli computazionali;
- livello di rischio dell'applicazione.

In ambito ingegneristico, non sempre il modello più complesso è il migliore.  
Spesso un modello più semplice, interpretabile e verificabile può essere preferibile a un modello più potente ma opaco.

---

## Large Language Models

I Large Language Models sono modelli di Deep Learning addestrati su grandi quantità di testo e progettati per elaborare e generare linguaggio naturale.

Essi sono alla base di molti strumenti di AI generativa oggi utilizzati per:

- redazione di testi;
- sintesi documentale;
- analisi di contenuti;
- generazione di codice;
- supporto alla ricerca;
- costruzione di assistenti conversazionali.

Dal punto di vista professionale, gli LLM rappresentano una delle tecnologie più immediatamente utilizzabili dagli ingegneri, ma richiedono attenzione particolare.

Il loro output può essere plausibile ma non corretto.  
Per questo motivo ogni risultato deve essere verificato rispetto a fonti, norme, dati tecnici e responsabilità professionali.

---

## Limiti dell'Intelligenza Artificiale

L'AI presenta limiti che l'ingegnere deve conoscere.

### Bias

Un modello può riprodurre o amplificare distorsioni presenti nei dati di addestramento.

### Overfitting

Un modello può adattarsi troppo ai dati di training e perdere capacità di generalizzazione.

### Allucinazioni

Nei modelli generativi, specialmente negli LLM, possono essere prodotte risposte formalmente convincenti ma fattualmente errate.

### Scarsa spiegabilità

Alcuni modelli, soprattutto quelli basati su Deep Learning, possono risultare difficili da interpretare.

### Sicurezza

I sistemi AI possono essere vulnerabili ad attacchi, manipolazioni dei dati, prompt injection o uso improprio.

### Responsabilità

L'AI non elimina la responsabilità del professionista.  
L'ingegnere resta responsabile della verifica, della validazione e dell'uso dei risultati.

---

## Concetti fondamentali da ricordare

- L'AI è uno strumento tecnico, non un soggetto autonomo.
- Il Machine Learning apprende dai dati, ma la qualità dei dati determina la qualità del risultato.
- Il Deep Learning consente prestazioni elevate su dati complessi, ma può essere meno interpretabile.
- L'AI generativa produce contenuti nuovi, ma non garantisce automaticamente correttezza.
- Gli LLM sono utili per produttività, analisi e scrittura, ma richiedono verifica professionale.
- In ingegneria, accuratezza, sicurezza, spiegabilità e responsabilità sono requisiti essenziali.
- L'ingegnere deve mantenere sempre il controllo del processo decisionale.

---

## Bibliografia essenziale

1. ISO/IEC 22989:2022, *Artificial Intelligence — Concepts and terminology*.
2. ISO/IEC 42001:2023, *Artificial Intelligence — Management system*.
3. Regolamento (UE) 2024/1689 del Parlamento Europeo e del Consiglio, *Artificial Intelligence Act*.
4. Russell, S., Norvig, P., *Artificial Intelligence: A Modern Approach*, 4th Edition, Pearson, 2021.
5. Mitchell, T. M., *Machine Learning*, McGraw-Hill, 1997.
6. Bishop, C. M., *Pattern Recognition and Machine Learning*, Springer, 2006.
7. Goodfellow, I., Bengio, Y., Courville, A., *Deep Learning*, MIT Press, 2016.
8. Géron, A., *Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow*, O'Reilly.
9. NIST, *Artificial Intelligence Risk Management Framework (AI RMF 1.0)*, 2023.
10. High-Level Expert Group on Artificial Intelligence, *A definition of AI: Main capabilities and scientific disciplines*, European Commission, 2018.
