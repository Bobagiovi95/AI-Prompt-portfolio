# Analisi Chat: Student Habits vs Academic Performance

**Obiettivi**
- Scoprire cosa influenza il rendimento accademico
- Capire cosa può causare scarso rendimento
- Individuare casi anomali nel dataset

## Fasi dell'analisi

### 1. Esplorazione del dataset
Il dataset contiene 1000 studenti e 16 colonne. La variabile di output è `exam_score`.

### 2. Correlazioni numeriche
- `study_hours_per_day`: **+0.82**
- `mental_health_rating`: **+0.32**
- `social_media_hours`: **-0.17**
- `netflix_hours`: **-0.17**

### 3. Analisi categorica
Media dei voti suddivisi per categorie: qualità della dieta, livello di educazione dei genitori, ecc.

### 4. Outlier
8 studenti con valori anomali rilevati tramite z-score.

---

## Domande chiave definite e analizzate

1. **Ore di studio e rendimento** → forte correlazione positiva
2. **Sonno e salute mentale** → impatto positivo, soprattutto la salute mentale
3. **Social e Netflix** → correlazione negativa con i voti
4. **Attività extra ed esercizio fisico** → migliorano la performance
5. **Profili degli studenti migliori e peggiori** → differenze evidenti in abitudini e benessere

---

## Output

- [Relazione in PDF](Relazione_Student_Habits_Analysis.pdf)
