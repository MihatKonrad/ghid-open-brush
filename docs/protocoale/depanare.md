---
title: Când ceva nu merge
description: Probleme frecvente cu casca și cu Open Brush, și ce faci.
tags:
  - depanare
---

# Când ceva nu merge

Caută problema în tabel (sau cu bara de căutare). Încearcă soluțiile în ordine.

## Casca și controlerele

| Problemă | Ce faci |
| --- | --- |
| imaginea e încețoșată | mută ușor casca în sus/jos pe față; verifică distanța dintre lentile; șterge lentilele cu microfibra |
| imaginea „a fugit” într-o parte | ține apăsat butonul **Meta** pe controlerul drept ca să recentrezi |
| un controler nu apare sau „zboară” | verifică bateria AA; mută-te într-o zonă mai luminată, fără soare direct; mișcă controlerul în fața căștii |
| apare mesajul de pierdere a urmăririi (*tracking lost*) | lumina e prea slabă sau prea puternică; aprinde lumina, trage jaluzelele; acoperă oglinzile mari |
| zona de siguranță a dispărut sau e greșită | retrasează zona (meniul Meta → setări → zona de siguranță) |
| casca nu pornește | pune-o la încărcat 15 minute, apoi ține butonul de pornire apăsat |
| bateria curelei nu încarcă casca | verifică cablul scurt dintre curea și cască; verifică procentul bateriei B100; repune bateria în locaș |
| transmiterea pe ecran nu merge | casca și dispozitivul în aceeași rețea Wi-Fi; încearcă un hotspot de pe telefon |

## Open Brush

| Problemă | Ce faci |
| --- | --- |
| panourile au dispărut sau sunt în locuri ciudate | **Admin Panel → ⋯ → Reset Panels**; uită-te și în spate sau la picioare |
| nu găsesc o unealtă (pipetă, selecție, straturi) | treci în modul **Advanced** |
| desenul sacadează, aplicația merge greu | salvează imediat; evită particulele și pensulele animate; verifică **Settings → Current Sketch Cost**; închide și redeschide schița |
| aplicația s-a închis singură | redeschide-o; deschide schița din caietul de schițe; dacă lipsesc părți, caută în `Sketches/Autosave` |
| nu găsesc schița salvată | caietul de schițe → schițele locale; verifică pe ce cască s-a lucrat; caută în `Sketches/Autosave` |
| o imagine importată nu apare | verifică dosarul (`Media Library/Images`) și formatul (JPEG/PNG); redimensionează sub 2048 px |
| desenul nu mai stă pe locul lui din sală | *Environment* → **Reset Scene Transform**; sau **Select All** și mutați selecția la loc (vezi [Passthrough](../open-brush/spatiu.md#passthrough)) |
| liniile desenate nu apar unde mă aștept | verifică dacă e activ stratul potrivit și dacă stratul nu e ascuns |
| am șters sau am mutat ceva din greșeală | ++x++ (anulează), ținut apăsat pentru mai mulți pași |
| tot ce desenez apare dublat | oglinda e pornită: apasă din nou pe **Mirror** |
| desenez linii drepte în loc de libere | unealta *Straight Edge* e activă: apasă din nou pe ea |
| butoanele sunt inversate | s-au schimbat mâinile (bazele controlerelor s-au lovit): lovește-le din nou ușor |

## Dacă nimic nu ajută

1. Salvează (dacă se mai poate).
2. Închide Open Brush din meniul Meta.
3. Repornește casca (ține butonul de pornire → *Restart*).
4. Anunță echipa de proiect.

Pentru probleme mai rare, vezi [secțiunea de depanare a documentației oficiale](https://docs.openbrush.app/user-guide/troubleshooting-issues-with-open-brush).
