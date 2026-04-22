# Claude Code — 57 Tecniche

Questo repository contiene la risorsa ufficiale del corso **"Claude Code — 57 Tecniche"**. 
Si tratta di una guida completa formatta in HTML che raccoglie procedure rodate, prompt avanzati, meccaniche nascoste e best practices (il famoso "l'altro 80% che la maggior parte non conosce") per padroneggiare Claude Code.

## 📚 Struttura della Guida

Il file principale `claude-code-99-tecniche.html` contiene 57 tecniche suddivise strategicamente in 8 categorie essenziali per ogni moderno sviluppatore:

1. ⌨️ **Comandi Essenziali**: pianificazione (`/compact`, `/clear`, `/init`), budgeting term e profilazione (`/cost`, `/memory`).
2. ⚡ **Tecniche di Produttività**: code review, workflow test-first, revisione integrata e commit checkpointing via git.
3. 🏗️ **Tecniche di Architettura**: audit strutturali, enforce di pattern via `CLAUDE.md`, migrazioni dati, e profiler di perfomance.
4. 🤖 **Automazione del Workflow**: CI Pipeline Builder, script pre-commit, setup ambienti.
5. 🔧 **Debug e Recupero**: blame git automatici e risoluzione di dipendenze incrociate.
6. 🚀 **Tecniche Avanzate**: L'uso estensivo dei marker più aggressivi (`autopilot:`, `ralph:`, `ulw` e Team Mode).
7. ⚙️ **Workflow Profondi**: Skip permissions, `git worktrees`, `HANDOFF.md`, e i container docker.
8. 💎 **Potenza Nascosta**: Operatività non-interattiva, workflow invisibili al terminale.

## 🚀 Come visualizzare i contenuti

La guida è stata volutamente ottimizzata come *"Zero-Dependencies Single-Page Application"*.
Tutto il CSS, il DOM management e i font web (Google Fonts) sono incorporati e ottimizzati per l'usabilità.

Hai due opzioni per iniziare:

### Metodo 1: Browser Diretto (Consigliato)
Fai doppio click su `claude-code-99-tecniche.html` in Esplora Risorse, oppure trascinalo all'interno di un qualsiasi browser (Chrome, Edge, Safari).

### Metodo 2: Web Server Locale
Se desideri visualizzare la guida da localhost (specialmente se intendi integrarla su altre app), avviala da terminale:

**Se usi Python:**
```bash
python -m http.server 8080
```
Visita `http://localhost:8080/claude-code-99-tecniche.html`
