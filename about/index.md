---
layout: page
title: Riguardo Trovaparadigmi
date: 2021-07-31
---

Hai un noioso compito di scrivere tutti i paradigmi presenti in una versione? Questo è lo script che fa per te! Trova tutti i paradigmi di una versione, togli loro gli accenti e salvali in una pratica lista in un batter d' occhio!



## L'intenzione

Fornire a tutti un'opzione più o meno precisa per **trovare rapidamente i paradigmi di un'intera versione in latino**, e salvarli in un documento di testo. 

Sostanzialmente, **risparmiare tempo** alle persone che in ogni caso copierebbero i paradigmi dal Dizionario Online Olivetti.



## L'idea

> Vi avviso. State per fronteggiare un muro di testo

In prima liceo, la nostra professoressa, per ogni versione, ci assegnava il compito di trascriverne i paradigmi. Ogni compito andava consegnato sottoforma di documento di testo, in formato Word oppure OpenDocument. Notai che la maggior parte dei miei compagni, persino i più bravi, copiavano i paradigmi dal Dizionario Online Olivetti, il cui uso era stato suggerito dalla stessa prof, infatti si vedevano anche gli accenti, spesso, nei loro documenti. 

Nel 2020 ero alle prese con Python, stavo scrivendo i miei primi programmi, scraper di siti web con Selenium. 

Dunque sviluppai una semplice interfaccia grafica con AppJar e la usai per tutti i compiti successivi. Purtroppo tale interfaccia permetteva di visualizzare e copiare solo un paradigma alla volta, allora riscrissi tutto il codice, senza interfaccia grafica, per separare le parole di una versione e cercare i paradigmi per ognuna fra queste, riconoscendo se si tratta di verbi.


Verso la seconda parte del 2020, notai che il mio programma era sostanzialmente una disordinata pila di merda, quindi lo riscrissi interamente. Una cosa interessante aggiunta fu lo scaricamento delle pagine web in asincrono, con la libreria async, che ventuplicò la velocità di download di molte pagine, come 100. 

**Aggiornamento (31 Luglio 2021)** La (terza) riscrittura del codice è completa ed adesso c'è sia un' interfaccia grafica sia un installer per Windows, quindi se volete risparmiare tempo trovando i paradigmi potete installare questa app usando il pulsante download nella pagina principale, oppure <a href="/images/myw3schoolsimage.jpg" download>cliccando qui </a>.

## Il codice

Se volete contribuire oppure visualizzare il codice della GUI[^1], con cui potete **trovare** i paradigmi di un'**intera versione**, potete farlo cliccando sul logo di GitHub nella pagina principale, oppure [direttamente cliccando su questo testo](https://github.com/bortox/Trovaparadigmi).

[^1]: Graphical User Interface, interfaccia grafica.