---
title: 'Astro Framework Setup Tutorial'
date: 2022-10-06T20:19:50+02:00
tags: ['👨‍💻 Echo 404', '👨‍💻 Web development', '👨‍💻 AstroJS']
ShowWordCount: false
hideAuthor: true
ShowPostNavLinks: false
description: "Come installare il framework Astro all'interno del tuo sito web"
layout: 'article'
ShowShareButtons: true
---

Piccola guida sul come preparare il setup per realizzare il tuo sito web con il framework [Astro](https://astro.build/).

**Premessa**

Per utilizzare questo Framework, sarà necessario installare [Node.js](https://nodejs.org/en/). Cliccando su [questo link](https://nodejs.org/en/)</a> sarai renderizzato al sito ufficiali di Node.Js dove, cliccando sul pulsante con la versione LTS, scaricherai l'eseguibile per installarlo.

Dopo aver cliccato sull'eseguibile scaricato e aver completato l'installazione di Node.JS, ti appariranno questi programmi:

![](../../posts/node1.png)

Quello che è stato installato è Node.JS e, insiseme, è stato installato _Node.Js command prompt_, quello che ci servirà in questo tutorial.

Aprilo e appena ti appare il prompt, digita _node-v_ e, il numero che ti apparirà, rappresenta la versione che hai appena installato di Node.JS.


## Parte 1: Crea il progetto

Bene, ora che Node è installato, possiamo partire con il set up di Astro.

Come prima cosa, tenendo aprto il prompt, creiamo la cartella dove verrà creato il nostro sito web. Per comodità, ti consiglio di possizionare questa cartella nella direcotry Documents (in particolare creiamo una cartella dentro Documents dove tenere tutti i nostri lavori) quindi, tramite prompt di Node, andiamo a crearla.

Come prima cosa digita il comdando _cd Documenti/_ (o Documents se hai l'OS in inglese), poi tramite il comando _mkdir developer_ creiamo una cartella chiamata developer, entriamoci dentro tramite il comando _cd developer/_.

**P.S.**

mi raccomando nei nomi delle directory, dette anche cartelle, e dei file non dovrebbero andare gli spazi, al posto di quelli usa o un - o un _).
Ora, se andari dentro _Documenti_, troverai tutte le cartelle che hai creato:

![](/posts/node2.png)

Ora, come ultimissima cosa prima di cominciare seriamente, ti faccio scaricare un Package Manager che può tornarti utile durante il lavoro, [Yarn](https://yarnpkg.com/). Quindi, sempre dal tuo prompt di Node, digita _npm i -g corepack_ e aspetta che venga installato.

Ora possiamo veramente cominciare

## Parte 2: Installa Astro

Ora che abbiamo la base su cui cominciare, è ora di far entrare in scena il protagonista di questa guida, Astro. Come si può vedere dal sito ufficiale di Astro per installare Astro avremo bisogno di nuovo del prompt di Node. A questo punto digita _npm create astro@latest_.

A questo punto sarai dentro il “processo di installazione di Astro” (facciamo che chiamarlo così). La prima cosa che ti uscirà è mettere il nome del sito

```
 Welcome to Astro! (create-astro v1.1.0)
 Lets walk through setting up your new Astro project.
 ? Where would you like to create your new project? >> nomeDelSito

```

Dopo il nome, ti verrà chiesto che template vorresti usare (se vuoi creare qualcosa da zero basterà cliccare su _Empty Project_). Per questo esempio useremo un template _Portfolio_, quindi va su e giù con le frecciete e premi invio per scegliere. Dopo aver copiato il Template nel progetto, Astro ti chiederà se vuoi utilizzare i pacchetti di npm; Non mi metterò qua a spiegarti [cosa sono](https://it.wikipedia.org/wiki/Npm_(software)), a te basta digitare Y. La stessa cosa la fai per Git. Infine ti chiederà che vuoi settare TypeScript, io ti consiglio Strict.

Bene, a questo punto hai installato Astro dentro il tuo sito, veloce no come procedimento 😀

Se sei ancora incerto che abbia installato qualcosa, vai dentro la cartella developer e guarda se ti ha creato una cartella con il nome che hai inserito; Altrimenti digita _cd nomeDelSito_ e digita _yarn start_, ti è uscito una cosa del genere?

```
 yarn run v1.22.19
 $ astro dev
    astro  v1.4.2 started in 49ms
   ┃ Local    http://127.0.0.1:3000/
   ┃ Network  use --host to expose

```

Se non ti è uscito... controlla cosa ti è uscito, perché di solito ti dice cosa c'è che non va (poi al massimo copia su Google l'errore che ti esce).
Se ti è uscito, bene! Ora apri il tuo browser e digita http://127.0.0.1:3000/ e Tac, ecco il tuo sito con il template di default.

**BUON DIVERTIMENTO!**