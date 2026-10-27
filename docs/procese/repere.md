---
title: Stratul de repere
description: Desenezi pe un strat reperele fixe ale sălii, ca să pui schița înapoi pe locul ei dacă s-a mutat între sesiuni.
tags:
  - rețetă
  - passthrough
  - straturi
  - ancorare
---

# Stratul de repere

Când lucrați într-un spațiu peste care vreți să suprapuneți desenul, pe un **strat separat** desenați schița spațiului din jur: reperele fixe ale sălii. Stratul acesta e un **ghidaj**. Dacă schița s-a mutat de la o sesiune la alta, o puneți înapoi aliniind reperele desenate cu cele reale.

!!! note "În proiect"
    Metoda se lucrează împreună în ateliere. Pagina descrie doar principiul și pașii din aplicație.

## Ce alegi ca repere

- **puncte fixe, clar recognoscibile**: un colț de perete, marginea unei ferestre, tocul unei uși, o coloană;
- **destul de depărtate** unele de altele;
- **pe planuri diferite**: de exemplu un colț de podea, o margine de fereastră pe alt perete, un punct de tavan;
- **nu** obiecte care se pot muta în timp: scaune, mese, ghiozdane, ghivece.

Cu repere apropiate sau pe același plan, o mică eroare de aliniere se vede mult la celălalt capăt al desenului.

## Desenează stratul de repere

1. Schiță nouă, scena **Passthrough** (vezi [Passthrough](../open-brush/spatiu.md#passthrough)).
2. Modul **Advanced** → *Extras* → **Layers** → **Add Layer**. Numește stratul, de exemplu `repere` (vezi [Straturi](../open-brush/straturi.md)).
3. Pe stratul `repere`, conturează reperele alese, cu o pensulă subțire și ușor de văzut. Pentru muchii drepte folosește [linia dreaptă](../open-brush/unelte/linie-dreapta.md).
4. Fă activ alt strat înainte să desenezi lucrarea propriu-zisă, ca reperele să rămână separate.
5. Salvează.

## Pune schița înapoi pe locul ei

Dacă la redeschidere desenul nu mai stă pe sală:

1. Fă vizibil stratul `repere`.
2. Încearcă întâi *Environment* → **Reset Scene Transform**.
3. Dacă nu ajunge: *Environment* → dezactivează **Lock Scene Transform**, ca să poți muta lumea.
4. Apucă lumea cu butoanele laterale și mut-o până când reperele desenate se suprapun peste cele reale. Verifică pe toate reperele, nu doar pe unul.
5. Reactivează **Lock Scene Transform** și salvează.

## Rolul reperelor în lucrare

În cererea de finanțare, reperele transpuse din sală au un rol triplu: sunt **amprenta spațiului din școală**, purtată de operă oriunde e deschisă; sunt **repere de siguranță** care mențin vizitatorul orientat atunci când lucrarea acoperă vizibilitatea realității; și sunt **metoda prin care o lucrare poate fi reancorată** corect dacă se încarcă decuplată de spațiul real.

!!! video "Clip: stratul de repere (în pregătire)"
    Desenarea reperelor pe un strat separat și realinierea schiței după ele.
