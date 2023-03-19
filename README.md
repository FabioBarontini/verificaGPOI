# Verifica di laboratorio Git

## Esercizio 1 (2pt)
1. Creare un repository Git in locale.
1. Effettuare le seguenti **modifiche** (in più commit):
    1. Aggiungere un nuovo file,
    1. Modificare il contenuto del file.
1. Creare un repository su GitHub e collegarlo a quello locale.
1. Allineare il repository remoto su GitHub con le modifiche effettuate.
1. **Consegnare su Classroom uno screenshot con i comandi eseguiti dalla bash e il repository locale.**

## Esercizio 2 (4 pt)
1. Creare una **copia locale** di questo repository .
1. Creare un nuovo **branch** di lavoro ed effettuare le seguenti **modifiche** al file *.css* (in più commit):
    1. Modificare il colore di sfondo,
    1. Modificare la dimensione del paragrafo,
    1. Modificare l'allineamento del tag *H1*.
1. Riportare sul main solo la modifica ii. e iii.
1. Allineare il repository remoto su GitHub con le modifiche effettuate.
1. Risolvere eventuali conflitti.
1. **Consegnare su Classroom uno screenshot con i comandi eseguiti dalla bash.**

## Esercizio 3 (2pt)
1. Creare una **copia locale** di questo repository .
1. Effettuare le seguenti **modifiche** (in più commit):
    1. aggiungere una riga al file es3 con il proprio nome
    2. Aggiungere una riga al file es3 con nome e cognome
1. Prima di eseguire la commit AVVERIRE il docente
1. Eseguire la commit
1. Eseguire la Pull del repository
1. Risolvere eventuali conflitti accettando solo l'ultima operazione
1. **Consegnare su Classroom uno screenshot con i comandi eseguiti dalla bash e il repository locale.**

## Esercizio 4 (10pt)
In questo esercizio dovrete simulare di avere il dono dell’ubiquità e essere contemporaneamente membri sia del gruppo A e dovrete simulare la seguente vita dello sviluppo di un programma
## Regole:
•	A ogni fine mese viene rilasciato al cliente l’attuale versione in beta.
•	Il rilascio viene fatto compilando direttamente dal branch main/master
•	Dopo il rilascio viene creato un Tag relativo alla versione rilasciata
## Facilitazione:
•	Creare una cartella in locale gestita con git (non è richiesta l’allineamento verso una versione su github)
•	In caso di conflitto accettare entrambe le modifiche che hann ogenerato il conflitto
## Calendario:
1.	## Primo mese:
    a.	GruppoA: Esegue le modifiche creando un branch. Le modifiche consistono in 3 commit
    b.	Al termine verrà rilasciata la versione 100p1
2.	## Secondo mese:
    a.	GruppoA: Esegue le modifiche creando un nuovo branch. Le modifiche consistono in 2 commit
    b.	GruppoB: Esegue le modifiche creando un nuovo branch. Le modifiche consistono in 3commit (portando solo la prima e terza modifica, la seconda non verrà mai utilizzata)
    c.	Al termine verrà rilasciata la versione 100p2
3.	## Terzo mese:
    a.	GruppoA: deve lavorare su un problema individuato dal cliente sulla 100p1. Appena risolto viene rilasciata una versione 100p1d1 e creato tag. A fine mese viene riportata la modifica sul main insieme al lavoro del gruppo B
    b.	GruppoB: Esegue le modifiche creando un nuovo branch. Le modifiche consistono in 2 commit
    c.	Al termine verrà rilascita la verisone 100p3
4.	## Quarto mese
    a.	Gruppo A: lavora su un branch per una versione innovativa. Due commit e rilasciata versione 200b1 direttamente su branch
    b.	Gruppo B: lavora su main branch, fa due commit e viene rilasciataversione 100p3
5.	## Quinto mese
    a.	Viene deciso di rendere principale la verisone 200 e lasciare la verisone 100px in un branch separato
    b.	GruppoA: creerà un branch chiamato 100px dove sarà presente l’attuale codice della 100p3 e porterà il codice del branch 200 sul main branch riportando tutte le commit contenute nel branch
    •	Consegnare su Classroom uno screenshot con i comandi eseguiti dalla bash e il repository locale.

