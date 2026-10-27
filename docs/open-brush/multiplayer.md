---
title: Multiplayer
description: Mai mulți elevi desenează în același timp, în aceeași schiță, fiecare cu casca lui.
tags:
  - multiplayer
  - grup
---

# Multiplayer

<div class="pe-scurt" markdown>**Pe scurt:** 2–12 persoane desenează **în același timp**, în aceeași schiță, fiecare cu casca lui. · **Unde:** *Admin Panel → Multiplayer* · **Mod:** doar Beginner · **Necesită:** internet pe toate căștile, aceeași versiune Open Brush</div>

## Ce câștigi și ce pierzi

| Avantaje | Limitări |
| --- | --- |
| toți lucrează deodată, nu pe rând | **merge doar în modul Beginner**, fără uneltele din Advanced |
| fiecare îi vede pe ceilalți desenând, în timp real | e nevoie de internet stabil pe toate căștile |
| vorbesc între ei prin voce spațială | liniile celorlalți apar cu o mică întârziere |
| cu colocarea, spațiul virtual se suprapune peste sala reală | doi elevi nu trebuie să editeze același obiect în același moment |

!!! warning "Multiplayer funcționează doar în modul Beginner"
    În versiunea actuală, multiplayer nu merge cu modul **Advanced**. Ai pensulele, culorile, radiera, linia dreaptă, oglinda, mediul, camera și teleportul, dar **nu** ai pipeta, repictarea, selecția, zborul, tăierea și unirea, nici panoul *Extras* (straturi, lumini, ghidaje, import de imagini). Verificați din nou după fiecare actualizare a aplicației.

!!! tip "Când îl alegi"
    Multiplayer e bun pentru **schițe comune rapide, explorare și discuție în interiorul spațiului**. Pentru construcția atentă, cu uneltele din Advanced (straturi, selecție, imagini de referință, lumini), lucrați **pe rând pe o singură cască** (vezi [Lucrez în grup](../procese/lucru-in-grup.md)). Cele două se pot combina: schițați împreună în multiplayer, apoi rafinați pe rând.

## Creează sau intră într-o cameră

1. **Admin Panel → Multiplayer.**
2. Scrie un **pseudonim** (*nickname*). Pentru elevi: prenumele sau un cod de grupă, nu numele complet.
3. Scrie un **nume de cameră** sau păstrează numele generat.
4. Alege numărul maxim de participanți (implicit 4, maximum 12).
5. **Join.** Dacă numele nu există, se creează camera și tu devii **proprietarul** ei.
6. Ceilalți scriu **același nume de cameră** și intră.

Numele camerei și pseudonimul sunt ținute minte pentru data viitoare.

!!! protocol "Camere private"
    Folosiți un nume de cameră greu de ghicit (de exemplu `lap-g1-x7k2`), nu „test” sau „clasa”. Oricine știe numele poate intra. Profesorul creează camera și rămâne proprietar.

## Administrează camera (proprietarul)

Din **Multiplayer → Manage Room**, proprietarul vede lista participanților și poate:

- **Mute for me**: nu mai aude un participant (doar pentru sine);
- **Mute for everyone**: oprește vocea unui participant pentru toți;
- **View only**: participantul vede, dar nu poate desena;
- **Kick User**: scoate un participant din cameră;
- **Transfer room ownership**: dă controlul altcuiva.

Setările de voce și *View only* se pot aplica și întregii camere. *View only* e util când un elev prezintă spațiul și ceilalți doar privesc.

## Voce

Vocea e **spațială**: îl auzi pe celălalt din direcția în care se află în scenă. Open Brush cere permisiunea de microfon. Dacă sunteți toți în aceeași sală, vă auziți oricum direct, așa că e bine să **opriți vocea pentru toată camera**, ca să nu apară ecou.

## În aceeași sală: passthrough și colocare

Multiplayer funcționează acum și în passthrough: elevii pot lucra **în același spațiu real**, fiecare cu casca lui, pe aceeași lucrare. Când toți elevii sunt în aceeași încăpere:

1. **Passthrough:** alegeți un mediu *passthrough*. Fiecare vede sala reală prin camerele căștii, cu desenul comun suprapus. Imaginea din camere **nu se transmite** celorlalți. Ieșiți din cameră înainte să reveniți la un mediu obișnuit.
2. **Colocare manuală:** ca desenul să stea pentru toți **în același loc din sală**, căștile se aliniază după un reper comun:
    1. alegeți un reper **fix** al sălii, la îndemână și cât mai orizontal, de exemplu marginea unui pervaz, și două puncte clare pe el: **A** și **B** (nu un obiect care se poate muta, ca o masă sau un scaun; vezi [Stratul de repere](../procese/repere.md));
    2. proprietarul: **Multiplayer → Set Shared Alignment**, pune vârful controlerului pe A și apasă trăgaciul, apoi pe B și apasă trăgaciul. Verifică săgeata de la A spre B și confirmă cu trăgaciul. Panoul arată *Shared alignment ready*;
    3. fiecare participant: **Align Play Space**, aceleași colțuri, **în aceeași ordine A → B**. Panoul arată *Play space aligned*.

Dacă scena se decalează, alegeți **Realign Play Space**. Mutarea sau scalarea lumii strică alinierea; atunci proprietarul o reface.

!!! warning "Siguranță în multiplayer în aceeași sală"
    Cu mai mulți elevi cu cască în aceeași încăpere, riscul de ciocnire crește. Zonele de siguranță ale căștilor **nu știu unele de altele**, iar în passthrough Open Brush nu le afișează. Lăsați spațiu mare între elevi; în passthrough se văd între ei.

## Participant de la distanță { #participant-de-la-distanta }

Un participant care nu e în sală (de exemplu facilitatorul, la întâlnirile online de ghidaj) intră în aceeași cameră multiplayer de oriunde:

- în passthrough, el vede desenul comun **suprapus peste propria lui cameră**, nu peste sala din școală;
- colocarea nu se aplică pentru el, pentru că nu e în aceeași încăpere;
- ca să vadă cum stă desenul față de sala reală, se uită la **transmiterea din căștile elevilor** (vezi [Facilitator Suite](../echipament/horizon-managed-services.md) și [Arăt pe ecran ce vede elevul](../procese/proiectare.md)).

## Salvare

!!! verifica "De verificat pe căștile noastre"
    Cine salvează schița comună și pe ce cască ajunge fișierul. Recomandare până la verificare: proprietarul camerei salvează, iar ceilalți salvează și ei o copie, înainte să iasă din cameră.

## Limitări cunoscute

- Liniile și obiectele mutate de alții apar cu o mică întârziere.
- Doi elevi nu trebuie să editeze **același obiect în același timp**.
- Toți trebuie să aibă **aceeași versiune** de Open Brush. Actualizați căștile împreună.
- Rețeaua școlii poate bloca conexiunea. Testați înainte, iar la nevoie folosiți un hotspot.

Detalii în documentația oficială: [Multiplayer](https://docs.openbrush.app/user-guide/multiplayer) și [Manual Colocation](https://docs.openbrush.app/user-guide/manual-colocation).
