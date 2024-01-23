# DB University

##
Modellizzare la struttura delle entità di un database per memorizzare tutti i dati riguardanti una università:
- sono presenti diversi Dipartimenti (es.: Lettere e Filosofia, Matematica, Ingegneria ecc.);
- ogni Dipartimento offre più Corsi di Laurea (es.: Civiltà e Letterature Classiche, Informatica, Ingegneria Elettronica ecc..)
- ogni Corso di Laurea prevede diversi Corsi (es.: Letteratura Latina, Sistemi Operativi 1, Analisi Matematica 2 ecc.);
- ogni Corso può essere tenuto da diversi Insegnanti;
- ogni Corso prevede più appelli d’Esame;
- ogni Studente è iscritto ad un solo Corso di Laurea;
- ogni Studente può iscriversi a più appelli di Esame;
- per ogni appello d’Esame a cui lo Studente ha partecipato, è necessario memorizzare il voto ottenuto, anche se non sufficiente.
- Pensiamo a quali entità (tabelle) creare per il nostro database e cerchiamo poi di stabilirne le relazioni.
Infine, andiamo a definire le colonne e i tipi di dato di ogni tabella.


# DB University 22-01-2024

Dopo aver creato un nuovo database nel vostro phpMyAdmin eseguite le query del file allegato:

1.	Selezionare tutti gli studenti nati nel 1990 (ottenere 160 risultati)
![query1](/PHPMYADMIN/query1.JPG)
2.	Selezionare tutti i corsi che valgono più di 10 crediti (ottenere 479 risultati)
![query2](/PHPMYADMIN/query2.JPG)
3.	Selezionare tutti gli studenti che hanno più di 30 anni
![query3](/PHPMYADMIN/query3.JPG)
4.	Selezionare tutti i corsi del primo semestre del primo anno di un qualsiasi corso di laurea (ottenere 286 risultati)
![query4](/PHPMYADMIN/query4.JPG)
5.	Selezionare tutti gli appelli d'esame che avvengono nel pomeriggio (dopo le 14) del 20/06/2020 (ottenere 21 risultati)
![query5](/PHPMYADMIN/query5.JPG)
6.	Selezionare tutti i corsi di laurea magistrale (ottenere 38 risultati)
![query6](/PHPMYADMIN/query6.JPG)
7.	Da quanti dipartimenti è composta l'università? (ottenere 12 risultati)
![query7](/PHPMYADMIN/query7.JPG)
8.	Quanti sono gli insegnanti che non hanno un numero di telefono?
![query8](/PHPMYADMIN/query8.JPG)


# DB University 23-01-2024

### QUERY GROUPBY

1.  Contare quanti iscritti ci sono stati ogni anno
![querygroupby1](/QUERYGROUPBY/querygroupby1.JPG)
2.  Contare gli insegnanti che hanno l'ufficio nello stesso edificio
![querygroupby2](/QUERYGROUPBY/querygroupby2.JPG)
3.  Calcolare la media dei voti di ogni appello d'esame
![querygroupby3](/QUERYGROUPBY/querygroupby3.JPG)
4.  Contare quanti corsi di laurea ci sono per ogni dipartimento
![querygroupby4](/QUERYGROUPBY/querygroupby4.JPG)


### QUERY JOIN

1.  Selezionare tutti gli studenti iscritti al Corso di Laurea in Economia
![queryjoin1](/QUERYJOIN/queryjoin1.JPG)
2.  Selezionare tutti i Corsi di Laurea Magistrale del Dipartimento di
Neuroscienze
![queryjoin2](/QUERYJOIN/queryjoin2.JPG)
3.  Selezionare tutti i corsi in cui insegna Fulvio Amato (id=44)
![queryjoin3](/QUERYJOIN/queryjoin3.JPG)
4.  Selezionare tutti gli studenti con i dati relativi al corso di laurea a cui
sono iscritti e il relativo dipartimento, in ordine alfabetico per cognome e
nome
![queryjoin4](/QUERYJOIN/queryjoin4.JPG)
5.  Selezionare tutti i corsi di laurea con i relativi corsi e insegnanti
![queryjoin5](/QUERYJOIN/queryjoin5.JPG)
6.  Selezionare tutti i docenti che insegnano nel Dipartimento di
Matematica
![queryjoin6](/QUERYJOIN/queryjoin6.JPG)
7.  BONUS: Selezionare per ogni studente il numero di tentativi sostenuti
per ogni esame, stampando anche il voto massimo. Successivamente,
filtrare i tentativi con voto minimo 18.
![queryjoin7bonus](/QUERYJOIN/queryjoin7bonus.JPG)
