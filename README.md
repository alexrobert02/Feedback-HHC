# FeedbackHHC

* Analiza opiniilor pacienților cu privire la tratamentul acordat de către agenția de furnizare a serviciilor de asistență medicală la domiciliu. 
* Setul de date este disponibil la adresa https://data.cms.gov/provider-data/dataset/6jpm-sxkc. Setul de date conține informații referitoare la agenția care oferă servicii de asistență la domiciliu iar variabila target este calitatea îngrijirii pacientului. O analiză similară se găsește la adresa https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9407698/.
* Utilizarea altor variabile pentru predicție: spre exemplu, utilizarea notelor clinice pentru a prezice spitalizarea pacientului https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7606545/.

**Tema 1**: Selecția celor mai influente atribute
1. Preprocesarea datelor
2. Analiza exploratorie a setului de date: valorile medii și mediane, vizualizarea datelor sub forma unor histograme/ barplot-uri, etc.
3. Selecția atributelor (utilizați spre exemplu PCA, Correlation-based Feature Selection, etc.)

**Tema 2**: predicția feedbackului pacienților privind calitatea serviciilor oferite de agenție\
Problema considerată este o problemă de clasificare multi-clasă. 
1. Antrenați cel puțin 2 algoritmi de clasificare (spre exemplu, rețele neuronale, Random forest https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html, etc.)
2. Testați algoritmii antrenați și afișați metricile de performanță
3. Realizați o analiză comparativă a algoritmilor testați (spre exemplu utilizând ROC (receiver operating characteristic curve)

### Echipa:
- Burghelea Daria E2
- Pește Ioana E2
- Manoliu Ana-Delia B4
- Constantin Ana-Maria B4
- Zaharia Robert-Alexandru B4
