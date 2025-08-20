# Progetto Basi di Dati — Federico II (A.A. 2024/2025)

Questo repository contiene il progetto realizzato per l’esame di **Basi di Dati** presso l’Università degli Studi di Napoli Federico II nell’anno accademico 2024/2025.

## Tecnologie utilizzate

- PostgreSQL
- PL/pgSQL
- LaTeX (per la documentazione)
- draw.io (per la modellazione)

## Come eseguire il progetto

1. Clona il repository:
   ```bash
   git clone https://github.com/CarmineSgariglia/BDD_Project.git
   cd BDD_Project
   ```

2. Apri il terminale e crea un nuovo database:
   ```bash
   createdb -U postgres progettoBDD
   ```

3. Esegui lo script:
   ```bash
   pg_restore -U postgres -d progettoBDD -f BasiDati.sql
  
   ```

## Documentazione

La documentazione completa in linguaggio LaTeX Include:

- Introduzione al progetto
- Progettazione concettuale
- Progettazione logica
- Progettazione fisica
- Funzioni, procedure e altre automazioni

## Autori

- Carmine Sgariglia 
- Mattia Lemma 
- Massimo Russo 


