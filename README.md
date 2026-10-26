# Ghid Open Brush, în română

Ghid practic pentru desenul 3D în realitate virtuală cu [Open Brush](https://openbrush.app), pentru profesori și elevi, pe Meta Quest 3S cu cureaua BoboVR S3 Pro.

Realizat de coVR în proiectul *Spații pentru sine*, în parteneriat cu Liceul de Arte Plastice Timișoara, în programul *Școli creative 2026-2027*.
Finanțat de Municipiul Timișoara prin Centrul de Proiecte și Administrația pentru Sănătate și Educație.

## Structura

```
docs/
├── index.md, start-rapid.md
├── open-brush/      ← ghidul aplicației: interfață, desen, pensule, unelte, spațiu, straturi, import, salvare
├── procese/         ← rețete pas cu pas
├── echipament/      ← Quest 3S, BoboVR S3 Pro, controlere
├── protocoale/      ← înainte / în timpul / după sesiune, igienă, arhivare, depanare
├── practica/        ← exerciții și plan pe săptămâni
├── resurse/         ← glosar EN–RO, linkuri, despre
└── assets/          ← CSS, logo-uri, (video/ și img/ pentru capturi)
mkdocs.yml           ← configurare și meniul site-ului
```

## Cum editezi

Fiecare pagină e un fișier Markdown în `docs/`. Poți edita direct pe GitHub (creionul de pe fișier): la salvare (*commit* pe `main`), site-ul se reconstruiește și se publică singur în 1–2 minute.

O pagină nouă trebuie adăugată și în secțiunea `nav:` din `mkdocs.yml`.

### Casete speciale

```markdown
!!! protocol "Titlu"
    Pas obligatoriu, regulă de sală.

!!! video "Clip: … (în pregătire)"
    Ce trebuie filmat.

!!! verifica "De verificat"
    Detaliu de confirmat pe echipament.

!!! tip "Sfat"
!!! warning "Atenție"
```

### Video

Clip de pe YouTube (nelistat) sau Vimeo, încorporat:

```html
<div class="video-16x9"><iframe src="https://www.youtube-nocookie.com/embed/ID_CLIP" title="Descriere" loading="lazy" allowfullscreen></iframe></div>
```

Clip scurt găzduit direct în depozit (MP4 sub ~10 MB, în `docs/assets/video/`):

```html
<div class="video-16x9"><video src="../assets/video/nume.mp4" controls muted playsinline preload="metadata"></video></div>
```

Calea relativă depinde de nivelul paginii (`../` pentru paginile din subdosare, `../../` pentru `open-brush/unelte/`).

### Butoane de controler

`++x++`, `++a++`, `++b++` se afișează ca taste.

## Local

```bash
pip install -r requirements.txt
mkdocs serve        # previzualizare la http://127.0.0.1:8000
mkdocs build --strict
```

## Publicare (prima dată)

1. Pe GitHub: **Settings → Pages → Build and deployment → Source: GitHub Actions**.
2. În `mkdocs.yml`, completează `site_url` și `repo_url` cu adresa reală.
3. Fă push pe `main`. Adresa site-ului: https://mihatkonrad.github.io/ghid-open-brush/

## Licență

Textul: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Siglele coVR, Centrul de Proiecte și ASEMT nu intră sub această licență. Codul de configurare: MIT.
