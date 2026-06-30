# Intelligenza Artificiale, Machine Learning e Deep Learning

!!! info "Obiettivo"

    Comprendere le differenze tra Intelligenza Artificiale (AI), Machine Learning (ML) e Deep Learning (DL), termini spesso utilizzati come sinonimi ma che identificano concetti distinti e gerarchicamente correlati.

---

## Dalla teoria alla pratica

Negli ultimi anni il dibattito sull'Intelligenza Artificiale ha portato alla diffusione di termini come *Machine Learning*, *Deep Learning* e *Generative AI*. Sebbene vengano spesso utilizzati indistintamente, essi rappresentano livelli diversi di una stessa disciplina.

Comprendere queste differenze è fondamentale per l'ingegnere, poiché ogni tecnologia presenta caratteristiche, requisiti e ambiti applicativi differenti.

La relazione tra questi concetti può essere rappresentata come un insieme di cerchi concentrici:

```text
+----------------------------------------------------+
|              Intelligenza Artificiale              |
|                                                    |
|   +--------------------------------------------+   |
|   |           Machine Learning                 |   |
|   |                                            |   |
|   |   +------------------------------------+   |   |
|   |   |         Deep Learning              |   |   |
|   |   +------------------------------------+   |   |
|   +--------------------------------------------+   |
+----------------------------------------------------+
```

Il **Deep Learning** costituisce quindi un sottoinsieme del **Machine Learning**, che a sua volta rappresenta uno dei principali approcci dell'**Intelligenza Artificiale**.

---

# Intelligenza Artificiale

L'Intelligenza Artificiale (Artificial Intelligence, AI) è la disciplina che studia e sviluppa sistemi in grado di svolgere attività che normalmente richiedono capacità cognitive umane, quali apprendimento, ragionamento, pianificazione, percezione e supporto alle decisioni.

Secondo la norma **ISO/IEC 22989:2022**, un sistema di AI è un sistema ingegnerizzato capace di generare, per obiettivi definiti, output quali previsioni, raccomandazioni, contenuti o decisioni che influenzano ambienti fisici o virtuali.

L'AI comprende numerosi approcci, tra cui:

- sistemi basati su regole (AI simbolica);
- sistemi esperti;
- Machine Learning;
- Deep Learning;
- Intelligenza Artificiale Generativa;
- sistemi multi-agente.

L'Intelligenza Artificiale rappresenta quindi il contenitore più ampio all'interno del quale si collocano tutte le altre tecnologie.

---

# Machine Learning

Il Machine Learning (ML) è un sottoinsieme dell'Intelligenza Artificiale che permette ai sistemi di apprendere automaticamente dai dati, senza essere esplicitamente programmati mediante regole predefinite.

In un sistema tradizionale il programmatore descrive tutte le istruzioni necessarie per risolvere un problema.

Nel Machine Learning, invece, il modello identifica autonomamente relazioni statistiche presenti nei dati durante la fase di addestramento (*training*).

Una volta completato l'apprendimento, il modello è in grado di effettuare:

- classificazioni;
- previsioni;
- regressioni;
- rilevamento di anomalie;
- clustering;
- raccomandazioni.

### Principali paradigmi

Il Machine Learning comprende quattro principali modalità di apprendimento:

- apprendimento supervisionato;
- apprendimento non supervisionato;
- apprendimento semi-supervisionato;
- apprendimento per rinforzo (Reinforcement Learning).

---

# Deep Learning

Il Deep Learning (DL) rappresenta un'evoluzione del Machine Learning ed è basato sull'impiego di reti neurali artificiali profonde (*Deep Neural Networks*).

L'aggettivo *deep* deriva dalla presenza di numerosi livelli (*layers*) di neuroni artificiali che consentono di apprendere automaticamente rappresentazioni sempre più complesse dei dati.

Questa tecnologia ha rivoluzionato numerosi ambiti applicativi, tra cui:

- visione artificiale;
- riconoscimento vocale;
- elaborazione del linguaggio naturale;
- robotica;
- diagnostica medica;
- progettazione assistita;
- guida autonoma.

Il Deep Learning richiede generalmente:

- grandi quantità di dati;
- elevata capacità computazionale;
- acceleratori hardware (GPU o TPU);
- tempi di addestramento maggiori rispetto ai modelli tradizionali.

In cambio offre prestazioni spesso superiori nei problemi caratterizzati da dati complessi e non strutturati.

---

# AI Generativa

L'Intelligenza Artificiale Generativa costituisce una delle più recenti applicazioni del Deep Learning.

A differenza dei modelli tradizionali, progettati principalmente per classificare o prevedere, i modelli generativi sono in grado di creare nuovi contenuti coerenti con quelli utilizzati durante l'addestramento.

Essi possono produrre:

- testo;
- immagini;
- codice sorgente;
- musica;
- video;
- modelli tridimensionali.

I moderni Large Language Models (LLM), come GPT, Claude, Gemini e Llama, appartengono a questa categoria.

---

# Confronto tra AI, ML e DL

| Caratteristica | AI | Machine Learning | Deep Learning |
|----------------|----|------------------|---------------|
| Ambito | Disciplina generale | Sottoinsieme dell'AI | Sottoinsieme del ML |
| Apprendimento dai dati | Non sempre | Sì | Sì |
| Utilizzo di regole | Possibile | Limitato | No |
| Necessità di grandi dataset | No | Media | Elevata |
| Interpretabilità | Elevata | Media | Ridotta |
| Potenza computazionale | Limitata | Media | Elevata |
| Esempi | Sistemi esperti | Random Forest, SVM | CNN, Transformer, LLM |

---

# Perché è importante per l'ingegnere

Per un professionista non è necessario conoscere in dettaglio gli algoritmi matematici alla base di ogni modello.

È invece fondamentale comprendere:

- quale tecnologia utilizzare;
- quali dati siano necessari;
- quali risultati ci si possa attendere;
- quali siano i limiti del modello;
- come validarne l'affidabilità.

La scelta tra AI simbolica, Machine Learning o Deep Learning dipende dal problema da risolvere, dalla disponibilità di dati, dai requisiti di spiegabilità e dal livello di rischio dell'applicazione.

---

## Concetti chiave

- L'Intelligenza Artificiale è la disciplina generale.
- Il Machine Learning è una tecnica che permette ai sistemi di apprendere dai dati.
- Il Deep Learning utilizza reti neurali profonde per affrontare problemi complessi.
- L'AI Generativa rappresenta una delle applicazioni più recenti del Deep Learning.
- La scelta della tecnologia deve sempre essere guidata dal problema ingegneristico e non dalla popolarità dello strumento.

---

## Bibliografia

1. ISO/IEC 22989:2022 – *Artificial Intelligence — Concepts and terminology*.
2. Russell S., Norvig P., *Artificial Intelligence: A Modern Approach*, 4th Edition, Pearson, 2021.
3. Mitchell T. M., *Machine Learning*, McGraw-Hill, 1997.
4. Goodfellow I., Bengio Y., Courville A., *Deep Learning*, MIT Press, 2016.
5. Bishop C. M., *Pattern Recognition and Machine Learning*, Springer, 2006.
6. Géron A., *Hands-On Machine Learning with Scikit-Learn, Keras & TensorFlow*, O'Reilly Media.
7. Regolamento (UE) 2024/1689 (AI Act).
