---
title: "Telly, una delle mie tante idee nel cassetto"
summary: Libcurl, rust e 15 minuti liberi per trasformare una mia esigenza in un command line tool.
date: 2022-04-11
aliases: ["/telly-client-telegram-rust"]
tags: ["Stories", "Tools", "Rust"]
author: ["Andrea Raponi"]
draft: false
aliases: [/stories/telly-client-telegram-rust]
weight: 1
---


## **Le Migliori Idee Nascono in Movimento**
Sono arrivato alla conclusione che le idee più interessanti mi sono venute mentre praticavo sport. Forse dovrei vivere in bici o addirittura correndo!

![Corri Andrea!](https://i.imgur.com/cM3Uclp.png#center)

L’idea di **Telly** è nata proprio mentre correvo, sommerso da quei fastidiosi “tlin” di notifiche, spesso provenienti da email.

---

## **Una Riflessione sulle Email**
Per diverso tempo ho utilizzato con grande soddisfazione [iRedMail](https://www.iredmail.org/) per gestire il mio ex server di posta.  
Ma siamo davvero sommersi da **processi in background**! 😱

---

## **Perché Monitorare i Processi è Cruciale?**
Nel nostro mondo iperconnesso, monitorare processi come:
- **Rsync**
- **Backup in cloud**
- **Restore di container**  
e qualsiasi altra automazione è di vitale importanza.  

Nel mio caso, questi processi giravano come **task crontab**, con notifiche inviate da un SMTP server. Tuttavia, questo approccio mi ha spesso lasciato sommerso da email inutili, che a volte ho ignorato o perso.

---

## **E Quindi, Perché Telly?** 😱
![Hello Telly!](https://i.imgur.com/y0qZ823.png)

**Telegram e i bot** sono la soluzione perfetta: uniscono l’immediatezza delle notifiche alla semplicità di un’app di messaggistica.

Utilizzando le [API di Telegram](https://core.telegram.org/bots/api) e un semplice bot creato con **BotFather**, ho sviluppato un **command line tool** basato su [curl-rust](https://crates.io/crates/curl) per inviare messaggi via bot direttamente dalla riga di comando.

---

## **I Vantaggi di Telly**
Grazie a Telly, ho sostituito tutte le email di monitoraggio per i miei servizi. Ora, con un colpo d’occhio su Telegram, riesco a leggere istantaneamente ogni notifica.

---

## **Perché Non Usare Direttamente `curl`?** 😅
Utilizzare un’implementazione **type safe** di `curl` è una buona idea:  
- Si evita la **verbosità negli script**.
- Un **semplice file di configurazione** aggiunge un valore tangibile.

---

## **Cosa Aspettarsi dal Futuro di Telly**
Sto già lavorando a una versione evoluta con nuove funzionalità. Questo è solo l’inizio!  
Se volete soppiantare le vecchie email di monitoraggio, trovate il codice su [GitHub](https://github.com/andrearaponi/Telly). 😊
