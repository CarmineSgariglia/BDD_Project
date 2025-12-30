# Sistema di Gestione Aeroportuale — Progetto Basi di Dati

Progetto di gruppo realizzato per l’esame di **Basi di Dati**  
Corso di Laurea in Informatica — Università degli Studi di Napoli Federico II  
Anno Accademico 2024/2025

Il repository contiene la progettazione e l’implementazione di una base di dati
relazionale per la gestione delle principali attività aeroportuali.

---

## Obiettivo del Progetto

Il sistema supporta la gestione di:
- voli
- prenotazioni
- passeggeri
- bagagli
- gate aeroportuali

con distinzione tra utenti generici e amministratori.

L’obiettivo principale è garantire **coerenza, integrità e correttezza dei dati**
attraverso vincoli, trigger e logica implementata direttamente nel database.

---

## Tecnologie Utilizzate

- PostgreSQL
- PL/pgSQL
- UML (modellazione concettuale e logica)
- LaTeX (documentazione)

---

## Caratteristiche Principali

- Progettazione concettuale tramite diagrammi UML
- Vincoli di integrità (CHECK, UNIQUE, ENUM)
- Trigger per la gestione automatica delle regole di business
- Funzioni e procedure per operazioni complesse
- Gestione concorrente delle prenotazioni

---

## Documentazione

La documentazione completa (in lingua italiana) include:
- progettazione concettuale
- progettazione logica
- progettazione fisica
- descrizione dettagliata di vincoli, trigger e funzioni

📄 File: `BDD_Documentation.pdf`

---

## Contesto Accademico

- Insegnamento: Basi di Dati
- Università: Università degli Studi di Napoli Federico II
- Tipologia: Progetto di gruppo

---
## Integrazione con l’Applicazione

Il database progettato in questo progetto è utilizzato come livello di persistenza
da un’applicazione desktop Java sviluppata per il corso di Programmazione a Oggetti.

Repository dell’applicazione:
https://github.com/Massimo127r/Applicativo_Aeroporto

## Autori

- Carmine Sgariglia  
- Mattia Lemma  
- Massimo Russo
