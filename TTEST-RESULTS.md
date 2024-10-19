TEST-RESULTS

Defect 1:
- Input: 4+5
- Rezultatul așteptat: 9
- Rezultatul obținut: 0
- Observație: Calculatorul nu procesează corect adunările simple. În loc să returneze suma corectă, returnează 0.

Defect 2:
- Input: 4/0
- Rezultatul așteptat: Infinity sau un mesaj de eroare specific
- Rezultatul obținut: ERROR
- Observație: Împărțirea la zero nu este gestionată corect. Programul returnează un mesaj generic de eroare în loc să gestioneze cazul cu Infinity sau un avertisment specific.

Defect 3:
- Input: 2+3*4
- Rezultatul așteptat: 14 (înmulțirea are prioritate)
- Rezultatul obținut: 20
- Observație: Calculatorul nu respectă ordinea corectă a operațiilor. Se pare că face adunarea înainte de înmulțire.

Defect 4:
- Input: -5+2
- Rezultatul așteptat: -3
- Rezultatul obținut: 7
- Observație: Programul nu procesează corect numerele negative. În loc să adauge 2 la -5, programul ignoră semnul negativ și face calculul ca și cum toate numerele ar fi pozitive.

Defect 5:
- Input: 3*4
- Rezultatul așteptat: 12
- Rezultatul obținut: 0
- Observație: Calculatorul nu efectuează corect înmulțirea simplă. Returnează 0 în loc de rezultatul corect, 12.
