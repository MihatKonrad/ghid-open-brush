---
title: Imagini și modele
description: Imagini de referință, modele 3D, linii salvate pentru refolosire, panorame 360°.
tags:
  - import
  - referință
---

# Imagini și modele

Poți aduce în desen **imagini de referință**, **video**, **modele 3D** și **panorame 360°** pentru cerul mediilor virtuale. Toate se încarcă din **biblioteca media**.

## Deschide biblioteca media

1. Treci în modul **Advanced**.
2. Deschide panoul **Extras**.
3. Alege **Local Media Library**.
4. Sus ai file: **Local Images** (imagini), **Local Videos** (video), **Local Models** (modele 3D), **Background Images** (panorame pentru cer), **Saved Strokes** (linii salvate).
5. Apasă pe o miniatură ca s-o aduci în scenă.

## Cum ajung fișierele în cască

Biblioteca arată doar fișierele copiate în dosarele aplicației, în memoria căștii:

| Tip | Dosar în cască |
| --- | --- |
| Imagini | `Open Brush/Media Library/Images` |
| Video | `Open Brush/Media Library/Videos` |
| Modele 3D | `Open Brush/Media Library/Models` |
| Panorame 360° | `Open Brush/Media Library/BackgroundImages` |

Le copiezi cu un cablu USB-C de pe calculator. Pașii: [Copiez lucrările pe calculator](../procese/transfer.md#copiaza-fisiere-in-casca). Poți face subdosare, de exemplu un dosar pentru fiecare grupă.

## Formate

| Tip | Formate |
| --- | --- |
| Imagini | PNG, JPEG (și SVG) |
| Video | MP4 |
| Modele 3D | GLB / GLTF, OBJ |
| Panorame | JPEG sau PNG, proporție 2:1 |

!!! warning "Imagini mici, casca mulțumită"
    Fiecare imagine ocupă memorie video. Imaginile mari sau prea multe pot face aplicația să se închidă. Recomandare: **maximum 2048 px pe latura lungă**, câteva imagini pe schiță. Redimensionează pozele de pe telefon înainte să le copiezi.

## Mută, mărește, fixează, șterge

| Vreau să… | Fac |
| --- | --- |
| mut imaginea sau modelul | îl apuc cu butonul lateral |
| măresc / micșorez | îl apuc cu ambele butoane laterale și depărtez sau apropii mâinile |
| îl fixez, ca să nu-l mișc din greșeală | în timp ce îl țin cu butonul lateral, apăs trăgaciul (*pin*) |
| îl șterg | îl apuc și îl arunc, sau îl ating cu radiera (întâi îl eliberez dacă e fixat) |

## Panoramă 360° ca cer

O fotografie panoramică 360° (proporție 2:1) poate înlocui cerul unui mediu virtual. Se copiază în dosarul `BackgroundImages` și se alege din fila **Background Images**.

!!! note "În proiect"
    Nu o folosim: elevii lucrează în passthrough, unde fundalul este sala reală.

## Refolosește linii salvate { #refoloseste-linii-salvate }

Poți păstra un grup de linii (un copac, un obiect, un motiv) și să-l aduci în alte schițe, editabil:

1. Selectează liniile cu [Selecția](unelte/selectie.md).
2. Deschide **Admin Panel → ⋯ → Labs** și alege **Save Selected Strokes**.
3. În orice schiță: **Extras → Local Media Library → Saved Strokes** și alege elementul. Apare grupat și selectat, gata de așezat.

## Modele 3D

Modelele 3D (de exemplu din Blender sau scanări) se pot folosi ca reper sau ca parte a scenei. Pe Quest e posibil să trebuiască pornită importarea modelelor din **Settings**, la opțiunile experimentale. Modelele mari se încarcă greu și încarcă desenul. Pentru atelierele cu elevii ne limităm de regulă la imagini și panorame.
