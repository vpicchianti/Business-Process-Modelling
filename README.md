Questo progetto si propone di **progettare e analizzare opportuni processi che rispettino fedelmente 
lo scenario descritto sotto.**
Inizialmente i processi vengono modellati utilizzando la notazione [BPMN](https://www.bpmn.org/), che consente 
di ottenere una visualizzazione efficace e standardizzata delle attività; la successiva 
traduzione di tali processi in reti di Petri e in Workflow nets permette poi
di condurre un'analisi semantica, che mira a individuare eventuali problemi, ambiguità 
e/o punti critici del processo. 
Le analisi sono svolte utilizzando i software [Woped](https://woped.dhbw-karlsruhe.de/) e [Woflan](https://www.win.tue.nl/woflan/). 

### P56: Scuola di ballo
Si consideri lo scenario di una scuola di ballo che debba gestire le richieste
degli allievi. L’allievo contatta la scuola e riceve una lista dei corsi disponibili.
L’allievo sceglie il corso e viene messo in contatto con un maestro. Il maestro
propone una data e luogo per la prima lezione e l’allievo può accettare, o
proporre data e luogo diversi e così via fino a quando l’appuntamento viene
fissato. Prima di ogni incontro l’allievo riceve un video di preparazione da
guardare. Durante l’incontro l’allievo esegue una serie di prove col maestro
e ogni prova non eseguita correttamente viene ripetuta. Al termine di ogni
incontro, dopo aver effettuato il pagamento elettronico alla scuola, l’allievo e
il maestro possono accordarsi per un nuovo appuntamento (col procedimento
descritto sopra), oppure l’allievo può decidere di concludere il corso. Se il
corso viene terminato, il cliente informa la scuola e il processo si conclude.
Modificare i processi in modo che al termine del corso l’allievo possa
scegliere se iniziare un nuovo percorso di apprendimento.
</br>
</br>
</br>

Questa repository contiene:
- Il file `.bpmn` con la modellazione dello scenario
- I file `.pnml` che contengono le reti di Petri dei processi 
- Il file `.pdf` contenente il report, il quale si propone di riassumere le strategie usate per la modellazione e per le analisi
- Altri file contenenti snippet di analisi semantiche
