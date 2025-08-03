# 📘 Progetto Basi di Dati — Federico II (A.A. 2024/2025)

Questo repository contiene il progetto realizzato per l’esame di **Basi di Dati** presso l’Università degli Studi di Napoli Federico II nell’anno accademico 2024/2025.

## 📁 Contenuto

- `schema.sql` – Script per la creazione dello schema del database
- `data.sql` – Script per il popolamento del database con dati di esempio
- `funzioni_trigger/` – Script con trigger e funzioni in PL/pgSQL
- `documentazione/` – Documentazione del progetto in LaTeX
- `diagrammi/` – Diagrammi ER e relazionali del database

## 🧰 Tecnologie utilizzate

- PostgreSQL
- PL/pgSQL
- LaTeX (per la documentazione)
- dbdiagram.io / Lucidchart (per la modellazione)

## 🚀 Come eseguire il progetto

1. Clona il repository:
   ```bash
   git clone https://github.com/tuo-username/nome-repo.git
   cd nome-repo
   ```

2. Avvia PostgreSQL e crea un nuovo database:
   ```sql
   CREATE DATABASE progetto_basi_dati;
   ```

3. Esegui gli script SQL:
   ```bash
   psql -U tuo_utente -d progetto_basi_dati -f schema.sql
   psql -U tuo_utente -d progetto_basi_dati -f data.sql
   ```

4. (Facoltativo) Aggiungi le funzioni e i trigger:
   ```bash
   psql -U tuo_utente -d progetto_basi_dati -f funzioni_trigger/trigger_e_funzioni.sql
   ```

## 📄 Documentazione

La documentazione completa è disponibile nella cartella [`documentazione/`](./documentazione/). Include:

- Introduzione al progetto
- Analisi dei requisiti
- Diagrammi concettuali e logici
- Esempi di query SQL
- Spiegazione dei trigger e delle funzioni

## 📚 Autori

- Carmine Sgariglia – *Studente di Informatica presso Federico II*
- Mattia Lemma – *Studente di Informatica presso Federico II*
- Massimo Russo – *Studente di Informatica presso Federico II*


