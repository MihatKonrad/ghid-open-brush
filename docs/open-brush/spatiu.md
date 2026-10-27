---
title: Spațiul de lucru
description: Passthrough (lucrul în sala reală), mediu, lumini, fundal, ghidaje, aliniere.
tags:
  - spațiu
  - passthrough
---

# Spațiul de lucru

## Passthrough: desenul în sala reală { #passthrough }

În proiect lucrăm **în general în passthrough**: elevii văd sala reală prin camerele căștii și desenează direct în ea. Desenul stă în spațiul real al școlii, nu într-o lume virtuală. Rămânem în passthrough până la momentul în care lucrarea e transpusă ca scenografie într-o altă sală.

!!! protocol "Primul pas la orice schiță nouă"
    Setează scena **Passthrough**: alegi mediul *Passthrough* din panoul *Environment* (în Beginner, pe fața *Tools*; în Advanced, în *Extras*).

Ce se schimbă în passthrough:

- **Mutarea lumii cu butoanele laterale e blocată implicit**, ca desenul să nu se decaleze față de sala reală dintr-o apucare accidentală. Desenul se poate muta totuși: selectezi tot (**Select All**, vezi [Selecție](unelte/selectie.md)) și muți selecția, sau deblochezi mutarea lumii (mai jos).
- **Comenzile scenei** sunt în fereastra mediului Passthrough (deschizi *Environment* cât timp e selectat Passthrough):
    - **Lock Scene Transform** blochează sau permite mutarea lumii;
    - **Reset Scene Transform** readuce desenul în poziția, orientarea și mărimea inițiale.
- **Zona de siguranță a căștii nu se mai afișează** cât timp mediul Passthrough e activ. Elevii văd sala, dar zona fizică trebuie să rămână liberă (vezi [În timpul sesiunii](../protocoale/in-timpul.md#siguranta-fizica)).

!!! info "Desenul rămâne legat de locul real"
    Blocarea împiedică doar mutarea din Open Brush. Cât de bine stă desenul pe locul lui depinde de urmărirea căștii și de configurarea sălii. Ca desenul să se deschidă de fiecare dată cam în același loc, folosiți un [punct fix de pornire](../procese/repere.md#punct-fix-de-pornire). Dacă s-a mutat totuși de la o sesiune la alta, îl puneți înapoi cu ajutorul [stratului de repere](../procese/repere.md).

În [multiplayer](multiplayer.md#in-aceeasi-sala-passthrough-si-colocare), fiecare elev vede sala prin casca lui, iar desenul comun e aliniat prin colocare.

## Mediu (*Environment*) { #mediu }

Pe lângă Passthrough, Open Brush are medii virtuale: un studio, un cer de noapte, spațiul cosmic și altele. Lumina mediului schimbă felul în care arată culorile, dar nu modifică liniile deja trase. Mediul se salvează odată cu schița.

În proiect le folosim doar ca să înțelegem ce face un mediu. Lucrul propriu-zis se face în Passthrough.

## Lumini (*Lights*) { #lumini }

Scena are trei lumini, pe care le poți colora și orienta:

| Lumină | Rol |
| --- | --- |
| **Soarele** | lumina principală, cea mai puternică, **face umbre** |
| **Luna** | lumina secundară, nu face umbre |
| **Lumina de umplere** (*fill*) | luminează uniform toată scena; se vede mai ales în culoarea umbrelor |

- Muți soarele și luna apucându-le cu trăgaciul pe sfera mică din panou.
- Luminile se salvează cu schița.
- Pensulele care luminează singure nu sunt afectate de lumini (vezi [Pensule](pensule.md#pensule-care-lumineaza-singure)).

!!! verifica "De verificat în passthrough"
    Cum se văd luminile scenei pe liniile desenate în mediul Passthrough.

## Fundal: cer și ceață (*Backdrop*) { #cer-si-ceata }

Panoul *Backdrop* schimbă **cerul** unui mediu virtual (un gradient între două culori) și **ceața**:

- alegi culorile de sus și de jos ale cerului;
- cursorul de ceață stabilește cât de densă e; dreptunghiul de lângă el îi schimbă culoarea;
- ca să revii la cerul inițial, reîncarci mediul din panoul *Environment*.

!!! note "În proiect"
    Explicăm ce face *Backdrop*, dar elevii lucrează în passthrough, unde fundalul este sala reală.

## Ghidaje (*Guides*) { #ghidaje }

Ghidajele sunt forme transparente pe care desenul „se lipește”. Te ajută să desenezi suprafețe perfecte.

| Ghidaj | Pentru |
| --- | --- |
| **Plan** | suprafețe plane, desen 2D în spațiu |
| **Sferă** | forme rotunde |
| **Cub** | muchii și fețe drepte |
| **Capsulă** | cilindri cu capete rotunjite |

Ghidajele se mută și se scalează ca orice obiect, cu butoanele laterale.

## Aliniere și transformări { #aliniere-si-transformari }

Pentru lucru precis există două panouri, în *Extras*:

- **Snap Settings** (alinierea): pozițiile se rotunjesc la o grilă, iar rotațiile la unghiuri fixe. Poți alinia doar pe unele axe și poți alinia la ghidaje.
- **Transform**: blochezi anumite axe ca să muți un obiect doar pe orizontală, doar pe verticală etc., și ai unelte de aliniere.

!!! video "Clip: passthrough (în pregătire)"
    Alegerea mediului Passthrough, desen în sală, Lock și Reset Scene Transform.
