# Tema3_IA_SimionescuAlexia
Titlu: Analiza algoritmilor pentru descoperirea regulilor de asociere și aplicarea lor pe seturi de date FAO privind consumul alimentar

## Descriere
Acest proiect are ca scop identificarea regulilor de asociere în consumul alimentar pentru România și Italia, utilizând algoritmul FP-Growth și compararea acestuia cu algoritmul Apriori. Analiza este realizată pe baza seturilor de date FAO (Global Individual Food Consumption Data Tool).

Proiectul include etapele de:
- curățare și preprocesare a datelor;
- transformare în bază de date tranzacțională;
- extragere de itemset-uri frecvente;
- generare și analiză a regulilor de asociere;
- comparație între FP-Growth și Apriori din punct de vedere conceptual și computațional.

## Structura repository-ului
- `Tema3_IA.ipynb` – notebook Google Colab care conține întregul cod sursă;
- `README.md` – descrierea proiectului.

## Rulare
Codul a fost dezvoltat și rulat în **Google Colab**.  
Pentru rulare:
1. Deschideți notebook-ul `Tema3_IA.ipynb` în Google Colab;
2. Asigurați accesul la seturile de date FAO (încărcate din Google Drive);
3. Rulați celulele în ordine.

## Seturi de date
Seturile de date utilizate provin de la:
FAO / WHO – Global Individual Food Consumption Data Tool (GIFT)  
https://www.fao.org/gift-individual-food-consumption/data/en
