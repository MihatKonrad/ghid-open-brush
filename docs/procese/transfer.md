---
title: Copiez lucrările pe calculator
description: Transfer prin cablu USB-C între casca Quest 3S și calculator, în ambele sensuri.
tags:
  - rețetă
  - transfer
  - arhivare
---

# Copiez lucrările pe calculator

Schițele, fotografiile și GIF-urile stau în memoria căștii. Le copiezi pe calculator cu un **cablu USB-C** de date (nu orice cablu de încărcare transferă date).

## Conectează casca

1. Pornește casca și pune-o pe cap sau ține-o în mână, cu ecranul vizibil.
2. Conectează cablul USB-C între cască și calculator.
3. În cască apare un mesaj care cere acces la date (*Allow access to data*). Alege **Allow** (permite).
4. Pe calculator:
    - **Windows**: în *File Explorer* apare dispozitivul **Quest 3S**. Deschide **Internal shared storage**.
    - **macOS**: e nevoie de un program pentru dispozitive Android, de exemplu [OpenMTP](https://openmtp.ganeshrvel.com/) (gratuit).

!!! info "Setare făcută de echipă"
    Căștile sunt setate din Meta Horizon managed services ca să apară pe calculator prin USB. Dacă nu apare casca, scoate cablul, pune casca pe cap și conectează din nou: mesajul de acces apare doar când casca e activă.

## Copiază din cască pe calculator

Pe cască, în **Internal shared storage → Open Brush**:

| Ce | Dosar |
| --- | --- |
| schițe (`.tilt`) | `Sketches` |
| salvări automate | `Sketches/Autosave` |
| fotografii, panorame | `Snapshots` |
| GIF-uri | `Videos` |
| exporturi 3D | `Exports` |

Copiază (nu muta) fișierele într-un dosar al proiectului pe calculator. Vezi regula de arhivare din [Salvare și arhivare](../protocoale/arhivare.md).

## Copiază fișiere în cască { #copiaza-fisiere-in-casca }

Pentru imagini de referință, panorame sau o schiță adusă de pe altă cască:

| Ce | Unde pui fișierul în cască |
| --- | --- |
| imagini | `Open Brush/Media Library/Images` |
| panorame 360° | `Open Brush/Media Library/BackgroundImages` |
| video | `Open Brush/Media Library/Videos` |
| modele 3D | `Open Brush/Media Library/Models` |
| o schiță de pe altă cască | `Open Brush/Sketches` |

Dacă aplicația era deschisă, reîncarcă biblioteca media sau caietul de schițe ca să apară fișierele noi.

!!! warning "Nu deconecta în timpul copierii"
    Așteaptă să se termine transferul înainte să scoți cablul. O schiță copiată pe jumătate nu se mai deschide.
