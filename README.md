# Global Happiness & Development – Data Analysis

Dieses Projekt untersucht globale Muster im Wohlbefinden und deren Zusammenhang mit wirtschaftlichen, sozialen und gesellschaftlichen Faktoren.  
Die Analyse kombiniert Python‑basierte Datenaufbereitung mit interaktiven Visualisierungen in Tableau.

---

## Projektübersicht

**Ziel**  
Untersuchung zentraler Einflussfaktoren auf das subjektive Wohlbefinden weltweit sowie Identifikation von Mustern, Trends und Ländergruppen.

**Tools**  
Python (Pandas, NumPy, Seaborn), Tableau, Excel

---

## Analyseschritte

### 1. Datenaufbereitung (Python)
- Zusammenführung mehrerer internationaler Datensätze  
- Vereinheitlichung von über 200 Ländernamen (Mapping, Entfernen von Sonderzeichen, Varianten)  
- Bereinigung fehlender Werte und Duplikate  
- Erstellung finaler Variablen:  
  'happiness_final', 'gdp_final', 'health_final', 'freedom_final', 'social_support_final'  
- Export des bereinigten Datensatzes für Tableau

### 2. Explorative Analyse
- Scatterplots zur Mustererkennung  
- Korrelationsanalyse  
- Lineare Regression  
- K‑Means‑Clusteranalyse  
- Zeitreihenanalyse

### 3. Tableau Story
- Scatterplot (GDP vs Happiness)  
- Regression  
- Clusteranalyse (kombiniertes Dashboard)  
- Zeitreihe  

---

## Ergebnisse

- Positive Korrelation zwischen GDP und Happiness
- Positive Beziehung zwischen GDP und Social Support (Regression)
- Klar abgegrenzte Ländergruppen in der Clusteranalyse
- Zusammenhang von Gesundheit, Freiheit und sozialer Unterstützung mit höherem Wohlbefinden
- Stabile oder leicht steigende Trends in den Zeitreihen, jedoch regionale Unterschiede

---

## Einschränkungen

- Unterschiedliche Datenqualität und fehlende Werte  
- Politisch variierende Ländernamen  
- Keine kausalen Aussagen möglich  
- Zeitreihen nicht für alle Länder vollständig verfügbar  

---

##  Dokumente

- Python Notebook (Cleaning & EDA)  
- Bereinigter Datensatz  
- Tableau Story  
- Storyboard‑Plan (Outline, Hypothese, Zusammenfassung, Einschränkungen)

---

## Sicherheit

API‑Keys und sensible Dateien werden **nicht** im Repository gespeichert.  
Siehe '.gitignore' für Details.




