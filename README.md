# NaukaGithub — warsztat Git & GitHub 🛠️

> Repozytorium treningowe **Optimal Design of Structures (ODS)** — sandbox do nauki
> operacji na Git i GitHub oraz pracy z systemami agentycznymi.

---

## 🏗️ O ODS — Optimal Design of Structures

**Optimal Design of Structures** to zespół budujący nowoczesne narzędzia dla
inżynierii konstrukcyjnej — od przeglądarek modeli BIM/IFC, przez automatyzację
obliczeń, po integracje z asystentami AI. Łączymy **inżynierię konstrukcji** z
**inżynierią oprogramowania**: solidne fundamenty, mierzalne wyniki, żadnych tez
bez dowodu.

## 🎯 Po co to repo?

To repozytorium powstało **na żywo na streamie** jako przestrzeń do ćwiczeń:

- podstawy Git: `add` → `commit` → `push`, `status`, `log`,
- praca na gałęziach (branch) i Pull Requesty,
- współpraca człowieka z **systemami agentycznymi** na wspólnym repozytorium.

## 📂 Zawartość

| Plik | Opis |
|------|------|
| `nowyplik.txt` | plik demo utworzony podczas warsztatu |
| `pliktestowy.txt` | plik demo z ćwiczeń commit/push |
| `README.md` | ten dokument |

## ⚡ Szybki reset komend (ściąga z warsztatu)

```bash
git status                 # co się zmieniło
git add <plik>             # dodaj konkretny plik do commitu
git commit -m "opis"       # zapisz zmiany
git push                   # wyślij na GitHub
git pull                   # pobierz zmiany innych

git switch -c feature/x    # nowa gałąź
git switch main            # powrót na main
```

**Złota reguła:** przed pracą `pull`, potem `status → add → commit → push`.
Sekretów (`.env`, hasła, klucze) **nigdy** nie commitujemy — nawet w repo prywatnym.

## 🤖 Następny krok: Git + agenci AI

Kolejna część warsztatu pokazuje, jak agentowy system może **czytać, planować i
wprowadzać zmiany** w repozytorium GitHub obok człowieka — z zachowaniem czystej
historii, gałęzi i Pull Requestów.

---

<sub>© Optimal Design of Structures · repo warsztatowe · 2026-08-13</sub>
