---
title: Salvare și export
description: Salvarea schițelor, caietul de schițe, salvările automate, exportul 3D, publicarea.
tags:
  - salvare
  - export
---

# Salvare și export

## Salvează schița

**Admin Panel → Save Sketch.** La salvare, aplicația îți cere o fotografie a lucrării, care devine **miniatura** schiței din caietul de schițe.

- Prima salvare creează un fișier nou. Salvările următoare îl actualizează.
- Fișierele au extensia `.tilt` și stau în cască, în `Open Brush/Sketches`.

!!! protocol "Când salvezi"
    La finalul lucrului sau **înainte să scoți casca**.

## Miniatura { #miniatura }

Fotografia făcută la salvare e imaginea după care elevul își găsește lucrarea data viitoare. Alege fie o **imagine de ansamblu**, fie un **detaliu pe care elevul îl recunoaște**, ca schița să fie ușor de găsit pentru continuare.

## Redenumește o schiță nouă { #redenumeste }

O schiță salvată prima dată primește un nume automat. Ca s-o redenumești:

1. Deschide caietul de schițe (*Sketchbook*), butonul mare din mijlocul *Admin Panel*.
2. Găsește schița în lista de schițe locale.
3. Apasă pe **meniul cu trei puncte** (⋯) al schiței.
4. Apasă pe **iconița „abc”** și scrie numele nou cu tastatura virtuală: numele real al elevului și o dată simplă, de exemplu `Ana Popescu 3.11` (vezi [Regula de nume](../protocoale/arhivare.md#regula-de-nume)).

## Caietul de schițe (*Sketchbook*)

Butonul mare din mijlocul *Admin Panel*. Are file pentru:

- **schițele locale**, salvate în cască;
- schițe din **Icosa Gallery** (galeria online a comunității), dacă există conexiune la internet.

Acolo deschizi o schiță existentă sau o [redenumești](#redenumeste).

## Salvări automate

Open Brush salvează automat, în `Open Brush/Sketches/Autosave`, ultimele cinci schițe la care s-a lucrat. Dacă ai pierdut o lucrare, uită-te acolo: muți fișierul în `Sketches` (de pe calculator) și apare în caietul de schițe. Salvările automate sunt o plasă de siguranță, **nu înlocuiesc salvarea manuală**.

## Combină două schițe

Open Brush poate aduce o schiță în alta (*Merge*), de exemplu ca să reuniți spațiile mai multor grupe. Detalii în [documentația oficială](https://docs.openbrush.app/user-guide/merging-sketches).

## Imagini și GIF-uri

Cu [camera foto](unelte/camera.md) faci fotografii, GIF-uri și imagini 360°. Cum le scoți din cască: [Copiez lucrările pe calculator](../procese/transfer.md).

## Export 3D

**Admin Panel → ⋯ → Labs → Export** creează un dosar în `Open Brush/Exports`, cu câte un subdosar pentru fiecare format 3D disponibil (de exemplu GLB). Le folosești în Blender, pe web sau pentru printare 3D. Unele pensule animate nu arată identic în afara Open Brush.

## Publicare online (*Upload*)

Din **Admin Panel → Upload** poți publica schița în Icosa Gallery, Sketchfab sau Viverse. Pentru asta e nevoie de un cont.

!!! protocol "Publicarea lucrărilor elevilor"
    Lucrările elevilor **nu se publică** online din cască fără acordul echipei de proiect și fără acordurile semnate de elevi și părinți. Publicarea se face centralizat, de către echipă.
