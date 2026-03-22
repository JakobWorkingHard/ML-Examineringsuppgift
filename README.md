# Machine-learning projekt om husvärderingar i Kalifornien

Vi har fått ett dataset med bostäder och en rad olika variabler som hör till dessa bostäder. Vår uppgift är att se om vi kan skapa en Machine-Learning modell som förutsäger bostäders pris baserat på dessa variabler. Vår slutsats är att ifall vi tränar modellen Random Forest, så kan vi förvänta oss att förutsäga en bostads värde med 15% felmarginal.

## Kom igång

Följ stegen nedan för att sätta upp projektet och köra det lokalt på din dator.

### 1. Klona repot (valfritt)
Börja med att ladda ner koden till din dator:
```bash
git clone [https://github.com/JakobWorkingHard/ML-Examineringsuppgift.git](https://github.com/JakobWorkingHard/ML-Examineringsuppgift.git)
cd ML-Examineringsuppgift
```

### 2. Skapa en virtuell miljö
För att hålla projektets beroenden isolerade, skapa en virtuell miljö (kallad `.venv`):
```bash
python -m venv .venv
```

### 3. Aktivera den virtuella miljön
Du måste aktivera miljön innan du installerar paketen. 

**På Windows:**
```bash
.venv\Scripts\activate
```

**På macOS och Linux:**
```bash
source .venv/bin/activate
```
*(När miljön är aktiverad bör du se `(.venv)` i början av din kommandorad.)*

### 4. Installera beroenden
Installera alla paket som krävs för att projektet ska fungera via `requirements.txt`:
```bash
pip install -r requirements.txt
```

### 5. Kör projektet!
Nu är allting uppsatt och du är redo att köra koden. 

