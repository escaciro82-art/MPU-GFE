Ecco il testo del README. Copialo e incollalo nell'editor di GitHub:

# Tudor / MPU GFE-03 — Architettura Computazionale Adattiva 4D

## Panoramica del Progetto

Tudor / MPU GFE-03 è un'architettura di elaborazione parallela non convenzionale basata su una matrice toroidale di 30x30 Processing Elements, coordinata dal supervisore GFE-HOST. Supera i paradigmi bidimensionali introducendo una topologia 4D, autoregolazione omeostatica dinamica e risonanza di fase su unità poliedriche (rombi 3D).

## Caratteristiche Principali

* Topologia Iper-spaziale 4D: Assi X e Y per connessioni planari, Asse Z per traslazioni diagonali con shift logici, Asse W per iper-connessioni con inversione bitwise. Riduce il diametro topologico a O(log N).
* Topologia Toroidale Continua: Chiusura ad anello Modulo 30 per eliminare gli effetti di bordo.
* Autoregolazione Omeostatica: Monitoraggio del target del 50% di nodi attivi tramite controllore a isteresi (soglia superiore > 480, inferiore < 420).
* Risonanza di Fase (Rombi 3D): Oscillatori di fase guidano la convergenza verso strutture poliedriche stabili orientate sui tre assi.

## Roadmap e Stato di Avanzamento

1. [Completato] Definizione specifica architetturale 4D (Baseline v2).
2. [Completato] Formalizzazione geometria romboedro 3D e protocollo.
3. [In corso — v3] Collaudo funzionale in simulazione del singolo nodo (tb_single_node_gfe03_v3.sv).
4. [Sospeso] Sblocco e validazione array toroidale 30x30.
5. Aggiornata la documentazione del progetto con la panoramica dell'architettura  4D e l'avanzamento della roadmap<img width="1024" height="559" alt="WhatsApp Image 2026-11-18 at 19 43 29" src="https://github.com/user-attachments/assets/52189608-2fa4-4144-b764-20b256764932" />
