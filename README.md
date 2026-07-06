# Sistemi Operativi Real-Time, con un'analisi delle caratteristiche e delle performance di VxWorks

Tesi di Laurea — Corso di Laurea in Informatica
Scuola di Scienze Matematiche, Fisiche e Naturali, Università degli Studi di Firenze
**Autore:** Federico Lombardi · **Relatore:** Prof. Rosario Pugliese · A.A. 2024-2025

## Descrizione

Tesi su sistemi operativi real-time (RTOS), con analisi approfondita di **VxWorks** (Wind River Systems), RTOS proprietario usato in settori critici (spazio, difesa, automotive, motorsport).

## Contenuti

1. **Introduzione** — obiettivi e struttura tesi.
2. **Sistemi real-time** — differenze soft/firm/hard real-time, caratteristiche, concezioni errate, classificazione algoritmi di scheduling.
3. **Scheduling task aperiodici** — algoritmi Jackson, Horn, Bratley, Spring, Latest Deadline First, EDF con vincoli di precedenza.
4. **Scheduling task periodici** — Rate Monotonic, Earliest Deadline First, Deadline Monotonic, confronto RM vs EDF.
5. **Real-Time Operating Systems** — organizzazione RTOS, gestione memoria (reale/virtuale, allocazione dinamica, overflow dello stack), gestione interrupt, task deadline, inversione delle priorità (priority ceiling, priority inheritance).
6. **VxWorks** — caratteristiche (task/scheduling, sincronizzazione, IPC, ambiente cross-compiled, file system), design e risultati test delle performance (task switching, preemption, latenza interrupt, comunicazione messaggi, semaphore shuffling), confronto con altri RTOS, casi d'uso reali:
   - NASA Mars Rover Curiosity
   - Leonardo S.p.A. (difesa)
   - Telemetria in Formula 1 (Magneti Marelli)
7. **Conclusioni e sviluppi futuri** — RTOS multi-core, standard di certificazione (ARINC653, AUTOSAR), sicurezza dei RTOS (SCADA, vulnerabilità note), integrazione con intelligenza artificiale.

## File

`LombardiFederico.pdf` — testo completo (48 pagine).
