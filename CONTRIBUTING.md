# [Contribuire all' openAPS](https://github.com/openaps/openaps/blob/master/CONTRIBUTING.md)
(traduzione)
Grazie per essere una parte di OpenAPS.

OpenAPS è una serie di strumenti per supportare una bricolage semovente
implementazione in base ai OpenAPS Progetto di riferimento. Gli strumenti possono essere
classificato come *Monitor* (raccolta di dati sull'ambiente, e
stato operativo dei dispositivi e/o aggregando i dati che è
rilevanti in un unico luogo), *predict* (fare previsioni su ciò che dovrebbe
succedere dopo), o *control* (promulgare cambiamenti, e l'alimentazione più dati indietro
nel *monitor*).

Procedendo uso di questi strumenti o qualsiasi pezzo all'interno, l'utente accetta la
diritto d'autore (vedi LICENSE.txt per maggiori informazioni) e rilasciare qualsiasi
contributi da responsabilità.

*Nota:* Questo è destinato ad essere un insieme di strumenti per sostenere un fai da te auto-driven
implementazione e qualsiasi persona la scelta di utilizzare questi strumenti è esclusivamente
responsabile della prova e implementare questi strumenti indipendentemente o
insieme come un sistema. La [parte fai da te di OpenAPS è importante](Http://bit.ly/1NBbZtO). Mentre la formazione formale o esperienza come
ingegnere o uno sviluppatore non è richiesto, cosa *è* necessario è una crescita
mentalità per imparare che cosa sono essenzialmente "mattoni" per l'attuazione di un
OpenAPS esempio. Questo non è un sistema di "impostare e dimenticare"; richiede
test e monitoraggio diligente e costante per garantire che ogni pezzo di
il sistema sta monitorando, la previsione e l'esecuzione, se lo desideri. Il
le prestazioni e la qualità del sistema risiede esclusivamente con voi.

Inoltre, questa comunità di contributori crede in "pagandola
Forward", e le persone che stanno attuando questi strumenti sono invitati a
contribuire facendo domande, contribuendo a migliorare la documentazione, e
contribuire in altri modi.

Si prega di inviare i problemi e tirare le richieste in modo che tutti gli utenti possono condividere
conoscenza. Se si ha familiarità con GitHub e/o codifica, [prova anche questi modi per essere coinvolti con OpenAPS.](https://openaps.gitbooks.io/building-an-open-artificial-pancreas-system/content/docs/Overview/contribute.html)

Per l'hacking su openaps, ecco alcuni consigli per aiutare le patch raggiungere
più persone più rapidamente. Il ramo `master` è speciale, dovrebbe
essere "produzione" codice pronto, testato e verificato, e deve corrispondere al
contenuti disponibili in PyPI. In pratica questo significa che il ramo `master`
non è mai toccati direttamente, ma piuttosto si usa una varietà di altri
rami per fare le cose, e quindi unire il lavoro nel `master`
ramo. Talvolta questo è chiamato
[Flusso git](http://nvie.com/posts/a-successful-git-branching-model/).
Ecco alcune linee guida che possono aiutare:
  
  *Indirizzare un ramo `dev` per le richieste di trazione. L'ultimo aggiornamento
    ramo, in particolare qualsiasi filiale recentemente aggiornato con `dev` nel
    Nome.
  * Evitare la modifica `ramo master`.
  *cambiamenti di prova

per lo sfondo sul movimento OpenAPS e progetto Vedere [OpenAPS.org](http://OpenAPS.org/).
Tradotto con Google.
