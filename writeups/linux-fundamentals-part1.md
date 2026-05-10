# 🐧 Linux Fundamentals Part 1

**Piattaforma:** TryHackMe  
**Categoria:** Linux  
**Difficoltà:** Facile  
**Data completamento:** Maggio 2026  
**Badge ottenuti:** `cat linux.txt` · `First Four`  

---

## 🎯 Obiettivo della room

Imparare i comandi fondamentali di Linux interagendo con un terminale reale. La room copre la struttura del filesystem, la navigazione da riga di comando e i comandi essenziali per leggere e gestire file.

---

## 📝 Concetti chiave appresi

### Storia di Linux
- Il kernel Linux fu rilasciato per la prima volta da **Linus Torvalds nel 1991**
- Annunciato con un messaggio su Usenet, originariamente descritto come "just a hobby"
- Oggi è alla base di server, sistemi embedded, Android e ambienti cloud

### Comandi fondamentali

| Comando | Funzione |
|---------|----------|
| `echo` | Stampa testo a schermo |
| `whoami` | Mostra l'utente corrente |
| `ls` | Elenca file e directory |
| `cd` | Naviga tra directory |
| `cat` | Legge e mostra il contenuto di un file |
| `pwd` | Mostra il percorso della directory corrente |

### Struttura del filesystem Linux

```
/
├── home/       # Directory degli utenti
├── etc/        # File di configurazione di sistema
├── var/        # File variabili (log, database)
├── tmp/        # File temporanei
└── root/       # Home dell'utente root
```

---

## 🔍 Note personali

Avendo già lavorato con Linux in produzione (CentOS, cPanel, SSH), molti comandi erano familiari. L'approccio della room è utile per **sistematizzare** conoscenze acquisite sul campo e vederle in una prospettiva orientata alla sicurezza.

La differenza rispetto all'uso operativo quotidiano: in un contesto di security ogni comando lascia tracce nei log — consapevolezza importante per chi lavora in ambito SOC.

---

## 🏅 Badge

- **cat linux.txt** — completato l'uso del comando `cat` per leggere file
- **First Four** — prime 4 room completate su TryHackMe

---

## 🔗 Link utili

- [Room su TryHackMe](https://tryhackme.com/room/linuxfundamentalspart1)
- [Linux Command Line Cheatsheet](https://cheatography.com/davechild/cheat-sheets/linux-command-line/)
