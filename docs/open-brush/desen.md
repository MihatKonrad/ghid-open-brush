---
title: Desenul de bază
description: Trasare, grosime, anulare, mutarea desenului, netezire, forme perfecte.
tags:
  - desen
  - începători
---

# Desenul de bază

## Trasează o linie

Ține apăsat **trăgaciul** mâinii-pensulă și mișcă mâna. Când îl eliberezi, linia (în engleză *stroke*) se termină. Fiecare linie e un obiect separat: o poți șterge, colora sau muta mai târziu.

!!! tip "Viteza contează"
    Majoritatea pensulelor reacționează la viteza mâinii și la cât de tare apeși trăgaciul. O mișcare lentă dă o linie mai controlată, una rapidă dă o linie mai energică. Încearcă ambele.

## Grosimea liniei

Împinge **joystick-ul mâinii-pensulă** spre stânga (mai subțire) sau spre dreapta (mai gros). Vârful pointerului își schimbă mărimea și îți arată grosimea înainte să desenezi.

## Anulează și refă

| Acțiune | Buton (dreptaci) | Buton (stângaci) |
| --- | --- | --- |
| Anulează (*Undo*) | ++x++ pe mâna-paletă | ++a++ |
| Refă (*Redo*) | ++y++ pe mâna-paletă | ++b++ |

Ține butonul apăsat ca să anulezi sau să refaci repede mai mulți pași. Anularea merge și pentru ștergeri, mutări sau schimbări de culoare, nu doar pentru linii.

## Mută, rotește și scalează desenul

!!! warning "În passthrough, mutarea lumii e blocată implicit"
    În proiect lucrăm în mediul **Passthrough**, unde Open Brush blochează implicit mutarea lumii cu butoanele laterale, ca desenul să rămână pe locul lui din sală. Ca să vezi desenul din altă parte, mergi în jurul lui. Ca să muți tot desenul: **Select All** și muți selecția, sau deblochezi din *Environment* → **Lock Scene Transform**. **Reset Scene Transform** readuce desenul la locul inițial (vezi [Passthrough](spatiu.md#passthrough)).

În mediile virtuale, ține apăsate **ambele butoane laterale** (*grip*), câte unul în fiecare mână, ca și cum ai apuca desenul cu două mâini:

- mișcă mâinile împreună: **muți** desenul;
- rotește-le una în jurul celeilalte: **rotești** desenul;
- depărtează-le sau apropie-le: **mărești** sau **micșorezi** desenul.

Cu **un singur** buton lateral, apăsat în spațiul gol, poți trage desenul mai aproape sau mai departe.

!!! info "Desenul nu se modifică"
    Când „apuci lumea”, schimbi doar poziția ta față de desen. Liniile rămân la fel. E ca și cum te-ai apropia de o sculptură sau ai privi-o prin lupă.

## Linii mai netede (Lazy Input)

Controlerele sunt foarte sensibile, iar curbele trase încet pot ieși tremurate. Funcția **Lazy Input** netezește linia: pointerul te urmează cu o mică întârziere, ca o pensulă trasă pe o sfoară.

Pornire și oprire: **ține apăsat trăgaciul mâinii-paletă** și **atinge butonul cu iepure/țestoasă** de pe controler.

<div class="video-16x9"><iframe src="https://www.youtube-nocookie.com/embed/2CEyUrv3IZk" title="Lazy Input în Open Brush" loading="lazy" allowfullscreen></iframe></div>

## Forme perfecte cu gestul de buclă

Cu [linia dreaptă](unelte/linie-dreapta.md) activă, poți obține și cercuri sau sfere. Ține trăgaciul și descrie o **buclă mare închisă** în aer. Aplicația recunoaște gestul și schimbă forma în ordinea: linie → cerc → sferă → linie. Repetă bucla până ajungi la forma dorită, apoi desenează.

## Unde se află pointerul

Linia iese din **vârful** controlerului, nu din mână. Dacă ți se pare incomod unghiul, schimbă-l din **Settings → Pointer Angle**.

## Rezumat gesturi

| Vreau să… | Fac |
| --- | --- |
| desenez | țin trăgaciul mâinii-pensulă |
| schimb grosimea | joystick mâna-pensulă stânga/dreapta |
| rotesc paleta | joystick mâna-paletă stânga/dreapta |
| anulez / refac | ++x++ / ++y++ |
| mut lumea (blocat implicit în passthrough) | un buton lateral |
| rotesc și scalez lumea (blocat implicit în passthrough) | ambele butoane laterale |
| mut tot desenul în passthrough | **Select All**, apoi apuc selecția |
| deschid meniul rapid | ++b++ |
| apuc un panou, o imagine, o selecție | butonul lateral al mâinii-pensulă |

!!! video "Clip: gesturile de bază (în pregătire)"
    Trasare, grosime, anulare, desenul văzut din mai multe părți în passthrough.
