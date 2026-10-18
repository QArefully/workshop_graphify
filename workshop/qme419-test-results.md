# QME-419 — wyniki porównania pięciu planów

Test przeprowadzono 16 października 2026 r. Pięć niezależnych agentów Luna (high) przygotowało po jednym `workshop/e2e-plan.md` na osobnych worktree. Każdy plan oceniło niezależnie dwóch recenzentów Sol (high) według `C:\Users\iwano\Desktop\repos\tgc-workshop-evaluate-plan\plan-grading-template.md`. Każdy raport przeszedł kontrolę `tools/grading.py` (21 pozycji i poprawna suma punktów).

## Oceny

| Worktree | Recenzent A | Recenzent B | Średnia |
|---|---:|---:|---:|
| `qme419-plan-1` | 89 | 79 | 84 |
| `qme419-plan-2` | 61 | 58 | 59,5 |
| `qme419-plan-3` | 43 | 37 | 40 |
| `qme419-plan-4` | 55 | 55 | 55 |
| `qme419-plan-5` | 48 | 41 | 44,5 |

**Średnia ze wszystkich 10 ocen: 56,6/100. Mediana: 55/100.** Rozbieżności między recenzentami pozostawiono bez rozstrzygania, zgodnie z zasadą niezależnej oceny.

### Szczegóły punktacji

Kategorie: koszyk /30, ceny /30, wersja robocza i opóźnione odpowiedzi /25, wykonalność /10, istniejące pokrycie i ryzyka /5. „Braki” to identyfikatory ocenione `not_met`.

| Plan | Recenzent | Koszyk | Ceny | Wersja robocza | Wykonalność | Pokrycie | Razem | Braki |
|---|---|---:|---:|---:|---:|---:|---:|---|
| 1 | A | 30 | 30 | 18 | 8 | 3 | 89 | D02, F02, R02 |
| 1 | B | 20 | 30 | 18 | 8 | 3 | 79 | C05, C08, D02, F02, R02 |
| 2 | A | 22 | 13 | 18 | 5 | 3 | 61 | C02, C07, D02, F01, P03, P04, R02 |
| 2 | B | 22 | 13 | 18 | 5 | 0 | 58 | C02, C07, D02, F01, P03, P04, R01, R02 |
| 3 | A | 26 | 0 | 13 | 2 | 2 | 43 | C05, D02, D03, F01, F03, P01, P02, P03, P04, R01 |
| 3 | B | 20 | 0 | 13 | 2 | 2 | 37 | C05, C08, D02, D03, F01, F03, P01, P02, P03, P04, R01 |
| 4 | A | 17 | 10 | 20 | 5 | 3 | 55 | C05, C06, C08, D04, F01, P02, P03, R02 |
| 4 | B | 17 | 10 | 20 | 5 | 3 | 55 | C05, C06, C08, D04, F01, P02, P03, R02 |
| 5 | A | 15 | 5 | 18 | 5 | 5 | 48 | C05, C07, C08, D02, F01, P02, P03, P04 |
| 5 | B | 15 | 5 | 13 | 5 | 3 | 41 | C05, C07, C08, D02, D03, F01, P01, P02, P03, R02 |

## Tokeny agentów wykonujących plany

Wartość „wejście” to wszystkie tokeny wejściowe minus tokeny wejściowe z cache. „Wyjście” obejmuje tokeny rozumowania. Recenzenci nie są uwzględnieni.

| Plan | Wejście bez cache | Wyjście | Razem |
|---|---:|---:|---:|
| 1 | 87 377 | 5 100 | 92 477 |
| 2 | 40 567 | 6 103 | 46 670 |
| 3 | 52 453 | 4 644 | 57 097 |
| 4 | 86 429 | 6 064 | 92 493 |
| 5 | 76 982 | 8 739 | 85 721 |
| **Suma** | **343 808** | **30 650** | **374 458** |
| **Średnia** | **68 761,6** | **6 130** | **74 891,6** |
| **Mediana** | **76 982** | **6 064** | **85 721** |

## Dostępność artefaktów

W chwili zapisu tego podsumowania oryginalne `C:\wt\qme419-plan-1`–`qme419-plan-5` i `C:\wt\qme419-reviews` nie były już dostępne. Dlatego ten plik zachowuje zweryfikowane wyniki i identyfikatory braków, ale nie zawiera treści pięciu planów ani dziesięciu raportów recenzentów.
