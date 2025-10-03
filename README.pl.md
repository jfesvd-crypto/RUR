<p align="center">
  <img src="https://img.shields.io/badge/DOI-10.5281/zenodo.XXXXXXX-blue?style=for-the-badge" alt="DOI">
  <img src="https://img.shields.io/badge/Wersja-v1.0.0-green?style=for-the-badge" alt="Wersja">
  <img src="https://img.shields.io/badge/Licencja-MIT-yellow?style=for-the-badge" alt="Licencja">
</p>

<h1 align="center">RUR — Ramy Uczciwej Rekrutacji</h1>

### [Przeczytaj pełny dokument (PDF)](https://ifess-krypto.github.io/RUR/RUR_Project_Book_v1.pdf) ## Przegląd (Overview)

**RUR (Ramy Uczciwej Rekrutacji)** to otwarty protokół, którego celem jest przywrócenie symetrii i sprawiedliwości w procesach rekrutacyjnych ery agentów AI. Adresuje problem chaosu związanego ze spamem aplikacyjnym generowanym przez AI ("Wojna Botów") oraz wrodzonej niesprawiedliwości tradycyjnej rekrutacji ("Niesprawiedliwy Teatr"). Naszym celem nie jest eliminacja performansu, ale zmiana bodźców tak, aby **opłacało się performować uczciwość**.

## Główne Założenia (Highlights)

* **Symetryczne Ujawnienie**: Obowiązkowy `Org Truth Packet` od pracodawców i `Needs Capsule` od kandydatów tworzą świadomy, symetryczny punkt wyjścia.
* **Sprawiedliwa Alokacja**: 3-pasowy, częściowo losowy proces selekcji z użyciem Weryfikowalnej Funkcji Losowej (VRF) zastępuje nieprzejrzysty model "kto pierwszy, ten lepszy".
* **Wzajemna Sprawczość**: `Raport Kompatybilności` oraz równe, wolne od konsekwencji reputacyjnych prawo do `Wzajemnego Weta` wzmacniają pozycję obu stron.
* **Proces Refleksyjny**: `Rytuały Powolności` są celowo wprowadzone, aby zachęcić do przemyślanej interakcji, a nie do stronniczych, reaktywnych decyzji.
* **Audytowalność i Transparentność**: Cały protokół jest zbudowany na weryfikowalnych mechanizmach, od paragonów z losowania po publiczny Protokół Falsyfikacji.

## Geneza Projektu

Projekt ten jest wynikiem unikalnej, intensywnej współpracy pomiędzy ludzkim orkiestratorem a wieloma zaawansowanymi systemami AI (w tym Gemini od Google i Claude od Anthropic). Jest to dowód koncepcji dla "Symfonii Agentów", gdzie ludzka intencja kieruje wieloagentową deliberacją w celu projektowania złożonych systemów socjotechnicznych. Ewolucja projektu, od technicznego pytania do kompletnych ram filozoficznych i operacyjnych, dokonała się w ciągu kilkudziesięciu godzin iteracyjnego dialogu. Inspiracją były koncepcje takie jak Ontologiczny Realizm Strukturalny (C0), zdecentralizowane obliczenia (COsystem) oraz krytyczna analiza przyszłości agentów AI.

## Status Projektu

To repozytorium zawiera kompletny pakiet teoretyczny dla protokołu RUR 1.0, włączając w to manifest, specyfikacje techniczne oraz metodologię testowania. Projekt jest obecnie w fazie koncepcyjnej, gotowy do pilotażowego wdrożenia (`Latarnia-EC01`).

## Jak cytować (BibTeX)

Jeśli wykorzystujesz tę pracę w swoich badaniach, prosimy o cytowanie jej w następujący sposób:

```bibtex
@misc{RUR2025Framework,
  author       = {Feszter, Janusz (ifess-krypto)},
  title        = {RUR — Ramy Uczciwej Rekrutacji: Protokół Przywracania Symetrii w Rekrutacji Ery AI},
  year         = {2025},
  publisher    = {Zenodo},
  version      = {v1.0.0},
  doi          = {10.5281/zenodo.XXXXXXX},
  howpublished = {\url{[https://github.com/ifess-krypto/RUR](https://github.com/ifess-krypto/RUR)}}
}
```

## Samodzielne generowanie PDF

Aby wygenerować kompletną "Księgę Projektu" w formacie PDF z plików markdown w tym repozytorium, potrzebujesz zainstalowanego narzędzia `pandoc` oraz dystrybucji LaTeX. Uruchom następujące polecenie z głównego katalogu repozytorium:

```bash
pandoc spec/pl/*.md philosophy/pl/*.md -o RUR_Project_Book_v1_pl.pdf --toc --pdf-engine=xelatex
```

## Jak wnieść wkład?

To jest projekt otwarty. Zapraszamy do dyskusji, krytyki i współpracy. Prosimy zacząć od lektury **[Manifestu](https://github.com/ifess-krypto/RUR/blob/main/spec/pl/01_manifest.md)** oraz **[Pełnej Specyfikacji Protokołu](https://github.com/ifess-krypto/RUR/blob/main/spec/pl/05_spec_rur_v1.md)**.