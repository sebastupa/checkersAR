# AR Checkers – Joc de Dame în Realitate Augmentată

Această aplicație reprezintă un joc de dame implementat în **Realitate Augmentată (AR)**, care rulează direct în browserul mobil folosind tehnologii Web AR. Tabla de joc și piesele sunt afișate tridimensional pe baza markerului **HIRO**, iar utilizatorul poate interacționa prin atingerea ecranului (tap).

Aplicația a fost realizată ca proiect pentru activitățile practice de laborator, având ca scop explorarea conceptelor de bază din domeniul realității augmentate și al interacțiunii 3D.

---

## 🔧 Tehnologii utilizate

- **A-Frame** – framework Web pentru scene 3D și VR/AR
- **AR.js** – bibliotecă pentru Realitate Augmentată marker-based
- **HTML5 & JavaScript** – structură, logică și interacțiune
- **Web AR (browser mobil)** – nu necesită instalarea unei aplicații native
- **GitHub Pages** – pentru găzduire și rulare prin HTTPS

---

## 📱 Cum se rulează aplicația

1. Deschide aplicația pe un **telefon mobil** (Android sau iOS) folosind linkul:
https://sebastupa.github.io/checkersAR/
2. Permite accesul la cameră.
3. Scanează markerul **HIRO** (printat sau afișat pe un ecran).
4. Tabla de dame și piesele vor apărea în mediul real.
Marker HIRO:
https://upload.wikimedia.org/wikipedia/commons/4/48/Hiro_marker_ARjs.png

---

## 🎮 Funcționalități implementate

- Afișarea unei **table de dame 8×8** în Realitate Augmentată
- **Piese 3D** poziționate corect pe tabla de joc
- **Selectarea pieselor prin tap**
- **Evidențierea mutărilor posibile**
- Verde – mutare simplă
- Galben – captură
- **Reguli de bază ale jocului de dame**:
- mutare diagonală înainte
- captură obligatorie dacă este disponibilă
- captură multiplă cu aceeași piesă
- **Alternarea turelor** (ALB / NEGRU)
- Afișarea turei curente (overlay + text AR)
- **Buton INFO** cu explicații și reguli

---

## 📏 Reguli implementate (variantă simplificată)

- Jocul începe cu jucătorul **ALB**
- Piesele ALBE se deplasează în jos, piesele NEGRE în sus
- Captura este obligatorie dacă există o mutare de captură
- După o captură, dacă este posibilă o nouă captură, jucătorul continuă
- Nu sunt implementate piese de tip „damă” (king)

