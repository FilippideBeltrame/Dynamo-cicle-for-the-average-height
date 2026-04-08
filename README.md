# 📐 Dynamo — Average Room Height Calculator (Altezza Media Locali)

> **🇮🇹** Ciclo Dynamo che calcola automaticamente l'altezza media di tutti i locali del modello BIM secondo la normativa italiana.
>
> **🇬🇧** Dynamo script that automatically calculates the average height of all rooms in the BIM model according to Italian building standards.

---

## 🇮🇹 Il problema / The Problem 🇬🇧

**IT:** Il calcolo dell'altezza media dei locali è richiesto dalla normativa italiana per verificare l'abitabilità. Su modelli complessi con soffitti a falda o non piani, il calcolo manuale è lungo e impreciso.

**EN:** Average room height calculation is required by Italian regulations to verify habitability. On complex models with sloped or non-flat ceilings, manual calculation is slow and inaccurate.

---

## ✅ La soluzione / The Solution

**IT:** Il ciclo Dynamo calcola automaticamente il volume di ogni locale e lo divide per la sua superficie, ottenendo l'altezza media reale anche in presenza di geometrie complesse, e segnala i locali sotto soglia.

**EN:** The Dynamo script automatically calculates each room's volume and divides it by its floor area, obtaining the real average height even with complex geometries, and flags rooms below the minimum threshold.

---

## ⚙️ Come funziona / How It Works
Modello Revit / Revit model
 ->
Dynamo legge volume e superficie per ogni locale
Dynamo reads volume and floor area for each room
 ->
Calcolo: volume / superficie = altezza media
Calculation: volume / area = average height
 ->
Output: locali conformi / non conformi
Output: compliant / non-compliant rooms
---

## 🛠️ Tecnologie / Tech Stack

- **Dynamo for Revit**
- **Python** (nodi custom / custom nodes)

---

## 📌 Normativa di riferimento / Reference Standard

🇮🇹 D.M. 5 luglio 1975 — altezza minima 2,70m locali abitabili (2,40m corridoi e bagni)
🇬🇧 Italian habitability regulations — minimum 2.70m for habitable rooms (2.40m for corridors and bathrooms)
